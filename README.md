# [CICD for ECS Hands On LAB](title)

> **본 Hands on Lab은 oregon region을 기준으로 작성되었습니다. 실습을 하실 때 반드시 리전을 확인하기 바랍니다.**

## Prerequisites

1. [IAM 유저 생성하기](./doc/create-iam-user)

2. [워크스페이스 생성하기](./doc/create-a-workspace)

3. (선택사항) [워크스페이스를 위한 IAM 역활 생성하기](./doc/create-an-iam-role-for-your-workspace)

4. (선택사항) [워크스페이스에 IAM 역활 추가하기](./doc/attach-the-iam-role-to-your-workspace)

## ECR repository 등록 및 ECS 클러스터 생성 Task Definition 등록하기

1. [ECR 에 도커 이미지를 위한 리포지토리 생성하기](./doc/create-ecr-repository)

2. [ECR 클러스터를 위한 VPC 생성하기](./doc/create-vpc)

3. [ECR 클러스터 생성하기](./doc/create-ecr-cluster)

4. [Task Definition 작성하기](./doc/create-task-definition)

5. [Service에서 사용할 Application Load Balancer 생성하기](./doc/create-alb)

6. [Service 작성하여 서비스 배포하기](./doc/create-service)

## Code Commit, Code Build, Code Pipeline으로 CI/CD 파이프라인 구성하기

1. [Code Commit에 Git Repository 생성하고 Cloud9에 형상 clone 하기](./doc/create-codecommit-repo)

2. [Code Commit Repository에 Dockefile 및 buildspec.yaml 추가하기](./doc/create-resource-for-build)

3. [Cope Pipeline을 생성하여 ECS에 지속적인 배포하기](./doc/create-pipeline)

## 실습후 리소스 삭제하기

1. Code Pipeline 삭제
2. Code commit 리포지토리 삭제
3. Code build 프로젝트 삭제
4. ECS 서비스 삭제
5. ECS Task Definition 삭제
6. ECS 클러스터 삭제
7. ECR 리포지트리 삭제
8. Cloud9 워크스페이스 삭제
9. ALB 삭제
10. VPC 삭제