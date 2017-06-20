# AWS Athena 실습 워크샵

본 워크샵 코스는 AWS Athena를 사용하여 데이터 수집, 분석, 변환 및 시각화에 대한 실전 기술 방식에 대한 실습 과정을 포함하고 있습니다. AWS의 다양한 데이터 분석 서비스를 활용하여 대용량 데이터 분석 및 시각화, 클라우드 기반 대형 데이터 솔루션 구현, 빅데이터 응용 프로그램의 공용 클라우드 배포 또는 마이그레이션, 대규모 데이터 저장 환경 구현 및 유지 관리, 데이터 관리 및 분석을 담당하는 데이터 엔지니어, 분석가 및 데이터 과학자를 대상으로 합니다.

## 필수 지식

이 과정에 참여하기 전에 참가자는 다음에 대한 기본 지식이 있어야 합니다.

- Parquet 및 ORC와 같은 파일 형식에 대한 일반적인 이해
- SQL과 유사한 쿼리 언어를 사용하여 데이터를 분석 한 경험

## 실습 목표

이 과정이 끝나면 참가자는 다음 작업을 수행 할 수 있습니다.

- Amazon Athena의 목적 및 사용 사례 이해, 아키텍처와 쿼리 처리 방법 이해, Quicksight를 통한 데이터 시각화
- 스키마 및 데이터 유형의 목적 및 구조 파악 및 웹 UI 및 JDBC 드라이버를 사용하여 Athena와 상호 작용
- EMR, Kinesis 같은 서비스 기반 데이터 변환 및 로드, 질의 및 결과 보기
- ELB, CloudFront 등과 같은 다른 AWS 서비스와 Athena의 통합

## 필수 준비

### AWS 계정

본 워크샵을 진행하려면 AWS 기본 계정을 준비해야 합니다. 본 워크샵의 일환으로 시작하는 모든 리소스는 AWS 계정이 12개월 미만인 경우, 제공하는 AWS 프리티어로 충분히 가능합니다. 프리티어를 넘어서는 경우, 과금일 될 수도 있습니다. 따라서, 새로운 실습용 계정을 만드시길 권장합니다. 자세한 내용은 [AWS 프리 티어 페이지](https://aws.amazon.com/free/)를 참조하십시오.

### 설치할 프로그램

**AWS CLI** PC에 AWS CLI (Command Line Interface)가 설치되어 있어야합니다. CLI를 사용하여 개체를 S3 웹 사이트 버킷에 복사합니다. [AWS CLI 시작하기](http://docs.aws.amazon.com/ko_kr/cli/latest/userguide/installing.html) 안내서에 따라 시스템에 CLI를 설치 및 구성하십시오. 

**SQL WorkBench** PC에 [SQL WorkBench](http://www.sql-workbench.net/downloads.html)를 설치하고, [Athena용 JDBC](https://s3.amazonaws.com/athena-downloads/drivers/AthenaJDBC41-1.0.0.jar)를 사용할 수 있어야 합니다.

## 실습 과정

- [Lab 1 Athena 사용해보기](labs/lab2.md) - Amazon Quicksight 활용
- [Lab 2 Athena 지원 형식 및 SerDes](labs/lab3.md)
- [Lab 3 데이터 파티셔닝](labs/lab4.md) - EMR Spark 활용
- [Lab 4 칼럼 형식으로 변환](labs/lab5.md) - Kinesis 및 EMR 활용
