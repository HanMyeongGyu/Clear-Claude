# Clear-Claude

1. 프로젝트 개요 (Overview)
이 프로젝트는 Claude 웹 인터페이스에 사용자 편의 기능을 추가하고, 개발자 도구(F12)를 거치지 않고도 웹사이트의 문서 구조와 코드를 즉시 복사하여 Claude에게 전달할 수 있는 내장 툴을 포함한 UI 개선 프로젝트입니다.

2. 주요 기능 (Key Features)
One-Click Code Extractor: 웹페이지의 특정 요소나 전체 소스 코드를 클릭 한 번으로 복사하여 Claude 입력창에 자동 삽입.

Developer-Friendly UI: 긴 코드 블록을 관리하기 편한 확장형 레이아웃 및 다크 모드 최적화.

Custom Prompt Presets: 자주 사용하는 분석 프롬프트를 버튼 형태로 내장.

3. 설치 및 설정 (Setup & Installation)
Step 1: 환경 구축
본 도구는 Chrome 확장 프로그램 형태 또는 Tampermonkey 스크립트로 구동됩니다.

저장소를 클론합니다: git clone https://github.com/your-repo/claude-ui-plus.git

브라우저의 확장 프로그램 관리 페이지로 이동합니다.

개발자 모드를 활성화합니다.

압축해제된 확장 프로그램을 로드합니다를 클릭하여 폴더를 선택합니다.

Step 2: 권한 설정
Claude.ai 및 소스 코드를 가져올 대상 웹사이트에 대한 스크립트 실행 권한을 허용해야 합니다.

4. 핵심 기능 구현: 내장 코드 복사 (Built-in F12 Function)
이 기능은 사용자가 일일이 개발자 도구(F12)를 열어 코드를 복사하는 번거로움을 해결합니다.
