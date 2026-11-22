<p align="center"><img src="docs/logo.png" alt="hwp-assist" height="64"></p>

한글(.hwp/.hwpx) 문서에 달린 **메모(피드백)를 AI가 읽고 고칠 부분을 제안**하는 Windows 프로그램입니다.
제안을 하나씩 보고 받아들인 것만 새 파일로 저장합니다. **원본 파일은 바뀌지 않습니다.**

## 내려받기

**[최신 설치 파일 내려받기](https://github.com/StaticDuo/hwp-assist/releases/latest/download/hwp-assist-setup.exe)** — 이 링크는 늘 최신 버전을 내려받습니다. (지난 버전은 [Releases](https://github.com/StaticDuo/hwp-assist/releases))
관리자 권한 없이 설치됩니다. "Windows의 PC 보호" 창이 뜨면 **추가 정보 → 실행**을 누르세요(코드 서명을 하지 않은 시험판).

## 필요한 것

- Windows 10/11
- 한컴오피스 한글 (.hwp 결과 저장과 한글 자동화 점검에 필요)
- Claude 유료 구독(Pro 이상)과 [Claude Code](https://code.claude.com/docs/en/setup). 설치·로그인은 프로그램 첫 화면에서 안내합니다.

## 할 수 있는 일

- 메모 반영: 메모를 ‘글을 고쳐 반영 / 자료·문헌 필요 / 질문 / 조치 없음’으로 나누고, 고칠 수 있는 것만 수정안을 만듭니다.
- 맞춤법·띄어쓰기, 문장 다듬기
- 문단별 전·후 비교, 메모·문단 단위 수락·거절, 직접 고치기
- 변경 보고서(.html): 무엇을 왜 바꿨는지, 사람이 할 일, 메모 답변 초안

## 알아 둘 점

- 작업할 때 해당 문단의 글이 Anthropic(Claude)으로 전송되고, 사용량은 본인의 Claude 구독 한도에서 차감됩니다.
- 문헌·수치를 지어내지 않도록 했지만, ⚠ 표시가 붙은 수정은 반드시 원문과 대조하세요.
- 이상하거나 불편한 점은 프로그램 오른쪽 위 **‘💬 의견 남기기’**로 알려 주세요. 보내기 전에 담길 내용(의견·화면 캡처·사용 기록)을 보여 주며, 누를 때만 개발자에게 전송됩니다.
- .hwp 결과 저장은 준비 중입니다. 지금은 .hwp 문서의 검토와 변경 보고서, .hwpx 문서의 새 파일 저장까지 됩니다.

hwp-assist는 Claude Code로 동작합니다. Anthropic의 공식 제품이 아닙니다.
