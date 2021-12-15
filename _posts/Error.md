# Error

## No serializer found for class org.hibernate.proxy.pojo.bytebuddy.ByteBuddyInterceptor and no properties discovered to create BeanSerializer

### 원인

```java
package com.hologachi.backend.model;

import javax.persistence.Column;
import javax.persistence.Entity;
import javax.persistence.FetchType;
import javax.persistence.GeneratedValue;
import javax.persistence.GenerationType;
import javax.persistence.Id;
import javax.persistence.JoinColumn;
import javax.persistence.JoinTable;
import javax.persistence.ManyToOne;
import javax.persistence.Table;

import lombok.AccessLevel;
import lombok.Getter;
import lombok.NoArgsConstructor;

@NoArgsConstructor(access = AccessLevel.PROTECTED)
@Getter
@Entity
@Table(name="TBL_CATEGORY2")
public class Category2 {

	@Id @GeneratedValue(strategy = GenerationType.IDENTITY)
	@Column(name = "CATEGORY2_ID")
	private int id2;
	
	@Column(name = "NAME")
	private String cat2;
	
	@ManyToOne(fetch = FetchType.LAZY)
	@JoinColumn(name = "CATEGORY1_ID")
	private Category1 category1;
	
	public Category2(String cat1, String cat2) { // 대분류 이름, 소분류 이름 
		this.category1 = new Category1(cat1);
		this.cat2 = cat2;
	}
	
}
```



### 해결방안

1. ```(fetch = FetchType.LAZY)``` 삭제





## org.apache.catalina.connector.ClientAbortException: java.io.IOException: Broken pipe 

