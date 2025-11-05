```mermaid
mindmap
  root((**IaC 기반 클라우드 구축** (총 32시간)))
    1. IaC 개요 및 기본 (4시간)
      필요성 및 장점
      CM vs Provisioning
      핵심 도구 비교
    2. Terraform 기본 및 구조 (10시간)
      **설치 및 HCL 문법**
      Provider 및 Resource 정의
      Data Source 활용
      Module을 사용한 재사용성
      **[핵심]** State 파일 관리 및 보안
    3. 클라우드 인프라 프로비저닝 (10시간)
      **클라우드 Provider 설정** (AWS/Azure/GCP)
      네트워크 (VPC, Subnet, Routing)
      컴퓨팅 (EC2/VM, Security Group)
      데이터베이스 및 스토리지 (RDS/S3)
      **[실습]** 종속성 문제 해결
    4. 환경 관리 및 CI/CD 파이프라인 (8시간)
      **Workspace**를 이용한 환경 분리 (Dev/Prod)
      Terraform Cloud/Backend (원격 State)
      CI/CD 파이프라인 통합
        GitHub Actions 연동
        Plan-Apply 자동화
      **[심화]** Taint, Import, Destroy
```
