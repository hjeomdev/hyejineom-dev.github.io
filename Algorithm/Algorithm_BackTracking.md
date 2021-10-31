# 알고리즘 이론 정리
# 백트래킹
- 조건이 만족하는(배제) 모든 조합의 수 확인
- 조건을 만족하지 못하면 그 노드의 부모노드로 **돌아가서** 다른 경우를 찾음
- 배제를 통해서 시간을 단축할 수 있다
- 가능한 모든 수를 상태공간트리에 표현하고 DFS 방식으로 확인, 조건에 부합하는지 확인(Promising) 부합하지 않으면 배제(Pruning)하고 부모노드로 돌아간다
- DFS + 조건문

## 1. 깊이 우선탐색 (Depth-First Search:DFS)
- 스택
- 레벨 단위로 이동하며 자식노드를 선택함

## 2. 너비 우선탐색 (Breadth-First Search:BFS)
- 큐