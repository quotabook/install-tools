# install-tools
Install AWS CLI and jq

이 액션은 ARM64 아키텍처에서 AWS CLI와 jq를 사용자 디렉토리에 설치하는 기능을 제공합니다. GitHub Actions 워크플로우에서 AWS 서비스와 JSON 데이터 처리를 위한 필수 도구를 자동으로 설치하여, 배포 및 관리 작업을 원활하게 수행할 수 있도록 지원합니다.

주요 기능:
- AWS CLI: Amazon Web Services와의 상호작용을 위한 커맨드라인 도구 설치
- jq: JSON 데이터를 처리하고 변환하기 위한 경량화된 커맨드라인 도구 설치
- 설치 확인: 각 도구의 설치 여부를 확인하고, 이미 설치된 경우 중복 설치를 방지

사용법:
- GitHub Actions 워크플로우에서 `uses: ./.github/actions/install-tools`를 통해 호출하여 사용합니다.