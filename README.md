<div align="center">

# DevOps & Cloud Engineer

### Kubernetes · CI/CD · GitOps · Observability · Cloud Migration

애플리케이션의 빌드부터 배포, 모니터링, 장애 대응까지  
안정적이고 반복 가능한 운영 환경을 만드는 DevOps 엔지니어입니다.

</div>

---

## 👋 About Me

Kubernetes 기반 애플리케이션 배포 환경과 CI/CD 파이프라인을 구축하고,  
클라우드 및 IDC 환경의 인프라 설계와 마이그레이션을 수행해 왔습니다.

단순한 배포 자동화를 넘어 헬스체크, 롤백, 아티팩트 관리, 보안,
로그·메트릭·트레이스 통합 수집까지 운영 전체 과정의 안정성과 효율성을
높이는 데 집중하고 있습니다.

### Core Competencies

- Kubernetes 및 Helm 기반 배포 환경 구축
- Jenkins와 Gitea 기반 CI/CD 및 GitOps 파이프라인 설계
- 순차·교차 배포, 헬스체크, 재배포 및 롤백 체계 구축
- Nexus 기반 빌드 아티팩트와 컨테이너 이미지 버전 관리
- Loki, Mimir, Tempo 기반 Observability 파이프라인 구축
- AWS 및 Naver Cloud 인프라 설계와 마이그레이션
- 클라우드와 IDC Kubernetes 환경 간 서비스 이관
- Credentials, Secret, ConfigMap 기반 보안 및 환경설정 관리

---

## 🛠 Tech Stack

### Container & DevOps

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Gitea](https://img.shields.io/badge/Gitea-609926?style=flat-square&logo=gitea&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Nexus](https://img.shields.io/badge/Nexus-1B1C30?style=flat-square&logo=sonatype&logoColor=white)

### Observability

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F46800?style=flat-square&logo=grafana&logoColor=white)
![Tempo](https://img.shields.io/badge/Tempo-F46800?style=flat-square&logo=grafana&logoColor=white)

### Cloud & Infrastructure

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Naver Cloud](https://img.shields.io/badge/Naver_Cloud-03C75A?style=flat-square&logo=naver&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

# 🚀 Projects

## DevOps · Kubernetes Platform

### 01. 중소기업통합플랫폼 구축사업

> Kubernetes 기반 CI/CD, GitOps 및 통합 Observability 환경 구축

**주요 업무**

- Jenkins, Kubernetes, Helm, Gitea 기반 CI/CD 및 GitOps 환경 구축
- 서비스 특성을 고려한 순차 배포 및 교차 배포 프로세스 구성
- 배포 단계별 헬스체크와 Nexus 기반 재배포·롤백 체계 구축
- SonarQube 정적 분석을 파이프라인에 연계해 코드 품질 검증 자동화
- Jenkins Credentials와 Kubernetes Secret을 활용한 인증정보 보안 관리
- Grafana Alloy 기반 Kubernetes 및 애플리케이션 텔레메트리 통합 수집
- 로그, 메트릭, 트레이스를 Loki, Mimir, Tempo로 전송하는 관측성
  파이프라인 구성

**Tech Stack**

`Jenkins` `Kubernetes` `Helm` `Gitea` `Nexus` `SonarQube`  
`Grafana Alloy` `Loki` `Mimir` `Tempo`

---

### 02. 중소기업통합회원 시스템 구축

> 애플리케이션 빌드부터 Kubernetes 배포까지 이어지는 자동화 체계 구축

**주요 업무**

- Jenkins, Kubernetes, Helm, Gitea 기반 CI/CD 및 GitOps 환경 구축
- 애플리케이션 빌드, 아티팩트 생성, 서버 및 Kubernetes 배포 자동화
- Nexus 기반 빌드 아티팩트와 컨테이너 이미지 버전 관리
- 버전별 아티팩트를 활용한 안정적인 재배포 체계 구성
- 배포 단계별 헬스체크와 재배포·롤백 절차 적용
- Jenkins Credentials와 Kubernetes Secret을 활용한 인증정보 관리
- 환경별 설정을 ConfigMap으로 분리해 설정 변경과 운영 관리 효율 개선

**Tech Stack**

`Jenkins` `Kubernetes` `Helm` `Gitea` `Nexus`  
`Credentials` `Secret` `ConfigMap`

---

### 03. 사내 그룹웨어 클라우드 배포 및 IDC 이관

> 클라우드에서 운영하던 그룹웨어를 IDC Kubernetes 클러스터로 이관

**주요 업무**

- 그룹웨어 애플리케이션의 Naver Cloud Kubernetes 배포 체계 구축
- 애플리케이션과 인프라 리소스를 IDC Kubernetes 클러스터로 이관
- 환경별 설정, Secret 및 배포 리소스를 분리해 환경 간 구성 정합성 확보
- 서비스 중단과 배포 위험을 최소화하기 위한 사전 검증 수행
- 배포 헬스체크 및 단계별 이관 절차 수립·수행

**Tech Stack**

`Naver Cloud` `Kubernetes` `Helm` `Jenkins` `Secret` `ConfigMap`

---

### 04. 유큐브메디 글로벌 의료관광 통합 플랫폼 구축

> 글로벌 의료관광 플랫폼을 위한 Kubernetes 기반 클라우드 환경 구축

**주요 업무**

- 글로벌 의료관광 통합 플랫폼의 클라우드 Kubernetes 배포 환경 구축
- Jenkins와 Helm 기반 빌드·배포 자동화 파이프라인 구성
- 오픈소스 Supabase 설치 및 플랫폼 연동용 백엔드 인프라 구성
- DNS에 DKIM 레코드를 적용해 발신 도메인 인증과 메일 신뢰성 강화
- 환경별 설정과 Kubernetes Secret을 분리해 민감정보 관리
- 배포 후 헬스체크와 로그 점검 체계를 구성해 운영 안정성 확보

**Tech Stack**

`Kubernetes` `Jenkins` `Helm` `Supabase` `DNS` `DKIM`

---

## Cloud Infrastructure · Migration

<details>
<summary><strong>01. CJ프레시웨이 AWS 마이그레이션</strong></summary>

<br>

- 워크로드 요구사항을 고려한 AWS VPC 네트워크 설계
- CloudWatch와 Slack을 연계한 운영 알림 체계 구성
- DLM을 이용한 EBS 스냅샷 백업 정책 구성

**Tech Stack:** `AWS` `VPC` `CloudWatch` `Slack` `DLM`

</details>

<details>
<summary><strong>02. 아산병원 파일럿 사업</strong></summary>

<br>

- AWS Snowball Edge를 이용한 약 52TB 규모 데이터 이관
- VPC, RDS 등 AWS 주요 서비스 구성 및 기술 교육 수행

**Tech Stack:** `AWS` `Snowball Edge` `VPC` `RDS`

</details>

<details>
<summary><strong>03. KT Cloud 서비스 진단 프로젝트</strong></summary>

<br>

- 36개 클라우드 서비스의 구성 및 운영 현황 분석
- 서비스별 진단 결과 정리 및 개선 보고서 작성

**Tech Stack:** `KT Cloud` `Cloud Assessment` `Technical Documentation`

</details>

<details>
<summary><strong>04. SK시그넷 프로젝트</strong></summary>

<br>

- AWS Application Migration Service를 활용한 서버 마이그레이션
- Amazon EKS 기반 Kubernetes 클러스터 구축

**Tech Stack:** `AWS MGN` `Amazon EKS` `Kubernetes`

</details>

<details>
<summary><strong>05. KOTRA 프로젝트</strong></summary>

<br>

- Samsung Cloud Platform 기반 VPC 네트워크 환경 구축
- VPN 및 CDN 구성
- 프로젝트 산출물 작성 및 감리 대응

**Tech Stack:** `SCP` `VPC` `VPN` `CDN`

</details>

<details>
<summary><strong>06. 성남문화재단 마이그레이션</strong></summary>

<br>

- Naver Cloud Classic 환경을 VPC 환경으로 마이그레이션
- 설치형 Microsoft SQL Server를 관리형 Cloud DB for MSSQL로 이관
- 애플리케이션 및 데이터베이스 전환 과정 검증

**Tech Stack:** `Naver Cloud` `VPC` `MSSQL` `Cloud DB`

</details>

---

## 📫 Contact

- Email: `soup0818@gmail.com`
- Mobile: `010-7387-1587`
