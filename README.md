# 종합일람표점검기 Windows 다운로드

현재 정식 버전은 **2.0.2**입니다. Windows 10·11 64비트용이며 Python이 포함되어 있습니다.

[최신 설치 파일 다운로드](https://github.com/moonsugugu/jonghabchecker-download/releases/latest/download/JonghabChecker_Setup.exe) · [2.0.2 릴리스](https://github.com/moonsugugu/jonghabchecker-download/releases/tag/v2.0.2)

설치 후 시작 메뉴에서 실행합니다. 제어판 또는 Windows 설정의 설치된 앱에서 삭제할 수 있습니다. 설치 파일을 다시 실행하면 삭제·업데이트/다시 설치·취소를 선택합니다.

기존 1.2는 위 설치 파일로 처음 한 번 업데이트하세요. 2.0부터 앱 왼쪽의 **프로그램 업데이트 → 새 버전 확인**에서 새 정식 버전을 확인하고 업데이트 설치를 시작할 수 있습니다. 보고서를 먼저 저장하세요. 공식 설치 파일의 크기와 SHA-256 검증을 통과한 뒤 현재 앱을 종료하고 설치 프로그램을 실행합니다.

[사용법·소스·변경 이력](https://github.com/moonsugugu/jonghabchecker) · [2.0.2 소스 커밋](https://github.com/moonsugugu/jonghabchecker/commit/fea152f27285df1952caf2679384b7425709124c)

학생 자료는 로컬에서만 처리하며 설치 파일에 포함하지 않습니다. 릴리스의 build-info.json에서 소스 커밋과 실행 환경, SHA256SUMS.txt에서 설치 파일의 검증값을 확인할 수 있습니다. 이전 1.2 릴리스와 다운로드 주소는 유지합니다.

2.0.1은 이어지는 행의 출결 값이 달라 HWP 읽기가 중단되던 문제를 수정합니다. 같은 정수 표기 차이는 정상 처리하고 실제 충돌은 후보·원문 위치를 보존해 확인 필요·판정 보류로 표시합니다. 충돌한 값으로 개근을 판단하지 않습니다.

2.0.2는 점검 기능 변화가 없습니다. 설치 파일의 게시자·저작권·버전 정보를 채우고, 백신이 잘못 잡기 쉬운 쓰지 않는 실행 파일을 뺐습니다.
