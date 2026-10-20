# 물질 탐정 AI
초등학교 3학년 과학 물체와 물질 수업을 위한 3단계 웹앱입니다.

## 실행
`index.html`을 GitHub 저장소의 최상위에 업로드하고 Settings → Pages → Deploy from a branch → main / (root) → Save를 선택하세요.
배포 주소는 보통 `https://사용자이름.github.io/저장소이름/`입니다.

## AI 모델
https://teachablemachine.withgoogle.com/models/gWLQCybIp/

모델을 웹에서 불러옵니다. 모델이 공개되어 있고 정상적으로 접근 가능해야 합니다. 첫 접속 시 인터넷 연결이 필요합니다.

## 참고
- 카메라는 HTTPS인 GitHub Pages에서 작동하며 사용자 권한 허용이 필요합니다.
- AI 클래스 이름은 `plastic`, `metal`, `wood`, `glass` 또는 한국어 이름을 지원합니다. 다른 이름이면 index.html의 `norm()`을 수정하세요.
- 사진 파일은 브라우저에서 모델에 전달하며 별도 서버로 업로드하지 않습니다. 외부 CDN 및 모델 호스팅 서버에서 라이브러리와 모델을 불러옵니다.
- 실제 기기에서 카메라/모델 동작을 확인하세요.
