1. 동시성 제어를 하지않고, 다수의 트랜잭션을 동시에 수행할 때 생길수있는 문제
- 갱신 손실(lost update): 수행중인 트랜잭션이 갱신한 내용을 다른 트랜잭션이 엎어씀으로써 갱신이 무효가 되는것
- 오손 데이터 읽기(dirty read): 완료되지않은 트랜잭션이 갱신한 데이터를읽는것
- 반복할 수 없는 읽기(unreapeatable read): 한 트랜잭션이 동일한 데이터를 두번읽을때 서로 다른 값을 읽는것


2. 락킹