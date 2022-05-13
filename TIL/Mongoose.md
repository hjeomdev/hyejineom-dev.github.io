[Mongoosejs virtual populate](https://stackoverflow.com/questions/43882577/mongoosejs-virtual-populate)

- Populate in nested array

  ```js
  Project.find(query)
    .populate({
      path: "pages",
      populate: {
        path: "components",
        model: "Component",
      },
    })
    .exec(function (err, docs) {});
  ```

- [find by \_id](https://masteringjs.io/tutorials/mongoose/find-by-id)
- [lean](https://velog.io/@modolee/mongodb-document-to-javascript-object)
- [field attribute: immutable](https://stackoverflow.com/questions/50544198/prevent-field-modification-with-mongoose-schema)
- [sort](https://mongoosejs.com/docs/api/query.html#query_Query-sort)

```js
static findManyByUserId(userId) {
    return BookmarkModel.find({ userId: userId }).sort({ createdAt: 'descending' }).populate({ path: 'talk_id'}).lean();
  }

```
- [몽고DB Compass는 여러 개 도큐먼트를 한번에 지우는 기능은 제공하지 않는다](https://www.mongodb.com/docs/compass/current/documents/delete/)