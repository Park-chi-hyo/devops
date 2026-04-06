##  DevOps & CI/CD Environment
이 프로젝트는 효율적인 개발 운영을 위해 다음과 같은 **DevOps 환경**을 구축하여 관리하고 있습니다.

*   **Version Control**: GitHub (Git-Flow 전략 적용)
*   **IDE**: Eclipse (STS) 연동 및 EGit 활용
*   **Build Tool**: Maven / Gradle (Spring Boot 환경)
*   **Automated Workflow**: 
    *   **GitHub Actions**: 코드 Push 시 자동 빌드 및 테스트 수행
    *   **Dependency Management**: Toptal 기반의 최적화된 `.gitignore` 적용
*   **Cost Management**: AWS Budgets를 통한 실시간 비용 모니터링 및 임계값 초과 시 자동 제어(IAM Policy/Action) 설정

###  Workflow Strategy
1. **Main Branch**: 제품 배포를 위한 안정적인 소스 관리
2. **Develop Branch**: 기능 통합 및 사전 테스트 수행
3. **Feature Branch**: 단위 기능 개발 및 Pull Request를 통한 코드 리뷰 진행

