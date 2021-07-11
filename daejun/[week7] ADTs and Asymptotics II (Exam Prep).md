## ADTs and Asymptotics II (Exam Prep)

### 1

a)
- g(N, 1): Θ(N)
- g(N, 2): Θ(N^2)

b)
- g(N, 2): Ω(N), O(2^N)
- g(N, N): Ω(N), O(N^N)

### 2



### 3

- Best Case: Θ(logN), Worst Case: Θ(루트 N)

### 4

1. 알파벳 순서로 List에 저장한다.
2. Map<Section, List<Student>>
3. 중복을 제외하기 위해 Set에 저장한다.
4. ADT 두 개 준비. 1번 ADT에 존재하지 않으면 1번에 저장, 존재하면 2번 ADT에 저장 (답지 보니까 Set 이용. 꼭 Set이어야 하는 이유가 있는지?)  
5. Map<sid, Student>
6.  
7. LinkedList 이용해서 head node를 tail node로 변경
