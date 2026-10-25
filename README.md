# 민원답변 도우미

Windows용 민원답변 도우미의 **배포 파일·한국어 안내서·자동 업데이트 전용 저장소**입니다. 소스 저장소는 비공개로 유지합니다.

[최신 릴리스](https://github.com/newskool4d-sketch/minwon-answer-releases/releases/latest) · [v0.6.1 EXE 내려받기](https://github.com/newskool4d-sketch/minwon-answer-releases/releases/download/v0.6.1/minwon-answer-0.6.1-win-x64.exe) · [한국어 안내서](https://github.com/newskool4d-sketch/minwon-answer-releases/releases/download/v0.6.1/minwon-answer-0.6.1-guide-ko.html)

## 기존 사용자는 한 번 직접 업데이트하세요

**v0.6.0 이하 사용자는 v0.6.1 EXE를 한 번 직접 내려받아 실행해야 합니다.** v0.5.3 이하에는 자동 업데이트 기능이 없고, v0.6.0의 업데이트 주소는 일반 사용자에게 열려 있지 않습니다.

1. 기존 앱에서 **작업 내보내기**로 작업을 보관하고 앱을 닫습니다.
2. v0.6.1 EXE를 내려받아 실행하고 필요하면 **작업 불러오기**로 JSON을 엽니다.
3. **저장 설정**에서 작업 폴더와 자동 저장을 지정합니다. 작업 저장 기본값은 꺼짐입니다.
4. **업데이트**의 자동 업데이트를 켜 두면 이후 정식 새 버전을 확인·다운로드하고 정상 종료 뒤 적용합니다. 기본값은 켜짐입니다.

## 사용 환경과 파일 확인

- Windows 10·11 x64. 앱 실행에 Node.js를 별도로 설치할 필요가 없습니다.
- Codex·Claude CLI와 본인 로그인, 또는 Gemini API Key는 별도로 준비합니다. 자세한 방법은 릴리스의 한국어 안내서를 참고하세요.
- EXE와 같은 릴리스의 `.sha256`을 대조하세요. 현재 EXE에는 코드 서명이 없으므로 기관 실행 정책을 따르세요.
- 프로그램은 로컬 PC에서 실행하며, 실제 민원·내부 자료의 외부 AI 전송은 차단합니다. 가상 예시로 먼저 확인하세요.
- 작업·설정·로그인 폴더는 업데이트 시 유지하며, API 키·로그인 토큰·전송 동의를 작업 파일에 저장하지 않습니다.

이 저장소의 Git 파일은 배포 안내만 포함합니다. 실행 파일과 안내서는 **Releases**에서 내려받으세요.
