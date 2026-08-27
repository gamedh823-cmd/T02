[SYSTEM_VERIFICATION_LOG] YU JIWON - MINI_GAME_GOGOGO & EVIDENCE
> System Message: 본 문서는 유지원(숭실대학교 전자정보공학부 IT융합전공)의 웹 미니게임 프로젝트 검증 안내 및 성과 내역서입니다.

> 검증안내서 링크 [https://github.com/gamedh823-cmd/T02/blob/main/README.md]

> 플레이 링크 [https://www.google.com/search?q=https://gamedh823-cmd.github.io/T02/]

1. 검증 안내서 (GUIDE FOR EVALUATOR)
본 미니게임 웹사이트는 원활한 검증을 위해 다음 절차를 따릅니다.

2.	어디로 가나요? (접속 경로)

> 웹 링크 접속: [https://www.google.com/search?q=https://gamedh823-cmd.github.io/T02/]

3.	무엇을 하나요? (검증 절차)

> 1) 접속 후 닉네임을 입력하고 [확인] 버튼을 눌러 메인 로비에 진입합니다.
> 2) 5개의 미니게임 중 원하는 게임을 선택해 마우스 좌클릭, 방향키 또는 스페이스바를 사용하여 정확히 30초 동안 플레이합니다.
> 3) 하단의 '음소거' 및 '흔들림 끄기' 옵션을 토글하여 상태 제어가 정상 작동하는지 확인합니다.
> 4) 브라우저 창을 최소화하거나 다른 탭으로 이동하여 일시정지 오버레이가 자동으로 실행되는지 테스트합니다.
> 5) 게임 오버 후 로비로 돌아가 코인, 장착한 스킨, 닉네임, 최고 기록이 localStorage에 영구 보존되는지 확인합니다.

4.	무엇이 보이면 통과인가요? (성공 기준)

> 제한 시간 준수: 모든 미니게임은 시간 연장 버프 없이 정확히 30초 뒤에 결과 화면(게임 종료)으로 전환됩니다.
> 데이터 연동 및 보존: 게임 종료 후 로비 복귀 시 현재 판의 점수와 목숨은 초기화되나, 누적 코인 및 상점 스킨 등은 안전하게 유지됩니다.
>	상태 제어: 포커스 이탈 시 즉시 일시정지가 작동하며, 렌더링 및 사운드 제어가 에러 없이 수행됩니다.

5.	안 될 때 (Troubleshooting)

> 404 에러 발생: 'Ctrl + F5'(강력 새로고침)를 실행하거나, 시크릿 모드(Ctrl + Shift + N) 창에서 다시 접속하십시오.
> 최신 내용 미반영: 깃허브 서버의 배포 반영까지 1~2분 소요될 수 있으므로 잠시 대기 후 새로고침하십시오.

6. VERIFIED EVIDENCE LOGS (프로젝트 검증 내역)
> MINI_GAME_GOGOGO

> 프로젝트명: 웹 기반 종합 미니게임 아케이드 시스템 (Mini GAME GoGoGo)
> 사용 기술: HTML5, CSS3, Vanilla JavaScript, Web Audio API, LocalStorage
> 최종 성과: 5종의 인터랙티브 미니게임 구현, 영구 데이터 저장 및 예외 처리 시스템 완성
> 상세 요약: 순수 자바스크립트와 HTML5 Canvas/DOM을 활용하여 색깔 맞추기, 먹구름 피하기, 별자리 찰칵, 기억력 테스트, 타이머 맞추기 등 총 5종의 아케이드 미니게임을 구축했습니다. Web Audio API를 통한 레트로 사운드 모듈, 콤보 및 피버타임 시스템, LocalStorage 기반의 데이터 영구 보존 및 예외 복구(try-catch) 로직을 직접 설계하여 완성도를 높였습니다.

> 미니게임 소스코드 바로가기 [GitHub Project Access] [https://github.com/gamedh823-cmd/T02/blob/main/index.html]
