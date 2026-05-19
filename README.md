# JScript Auto-Translator

한국어 자막 CSV를 영어·러시아어·베트남어로 일괄 번역하는 정적 웹 도구. Claude / ChatGPT / Gemini API 중 선택해 사용합니다.

## 사용 방법

1. 우상단 `⬇ CSV 양식 다운로드` 로 템플릿 받기
2. `순서`, `페이지`, `Korean` 컬럼을 채워 업로드
3. 설정 탭에서 API 키 입력 (브라우저 localStorage에만 저장됨)
4. `전체 번역 시작` → 완료 후 결과 CSV 다운로드

## 보안

- API 키는 **사용자 브라우저의 localStorage 또는 메모리**에만 저장되며 HTML 파일·서버 어디에도 포함되지 않습니다.
- 세션 전용 모드를 켜면 키가 메모리에만 머물러 탭을 닫는 즉시 사라집니다.
- 키 백업/복원은 설정 탭의 내보내기/불러오기(JSON) 기능 사용.

## 배포

순수 정적 HTML 한 파일이므로 Vercel · GitHub Pages · Netlify 등 어디든 zero-config 배포 가능합니다.
