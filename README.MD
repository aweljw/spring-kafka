## SPRING-KAFKA

### kafka 설치
- brew install kafka
- brew install zookeeper

### kafka, zookeeper 실행
- `brew services start kafka` or `zkServer start`
- brew services start zookeeper

### kafka 용어 (draft)

- Producer 
    - 카프카에게 데이터를 보내는 어플리케이션
- Consumer
    - 카프카에서 데이터를 받는 어플리케이션
- Broker
    - 카프카 서버
- Cluster
    - 카프카 클러스터
- Topic
    - 카프카 스트림을 식별하기 위한 이름
- Partitions
    - Topic을 분산 저장하는데 분산 저장되는 단위
- Offset Partition
    - 안에서 데이터의 위치를 찾기 위한 offset
- Consumer group
    - 같은 일을 처리하는 Consumer 들의 논리적 집합이 덕분에 Consumer의 Scalable이 가능하다.