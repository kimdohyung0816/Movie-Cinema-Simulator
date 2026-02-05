\# 컴퓨터그래픽스 - 영화관 시뮬레이터 (final.html)



Three.js(WebGL) 기반으로 영화관(중강당) 환경을 구성한 시뮬레이터입니다.  

좌석/무대/벽/통로 등 공간 요소를 배치하고, 화면 UI(CSS3D)와 함께 시각적/인터랙션 요소를 구현했습니다.



\- 제작자: 김도형 (20205125)

\- 주요 파일: `final.html`



---



\## 실행 방법 (중요)

이 프로젝트는 Three.js 모듈을 CDN(importmap, unpkg)로 로딩합니다.  

따라서 `final.html`을 더블 클릭(file://)로 여는 것보다 \*\*로컬 서버로 실행\*\*하는 것을 권장합니다.



\### 방법 1) VSCode Live Server (추천)

1\. VSCode로 프로젝트 폴더 열기

2\. `final.html` 우클릭 → \*\*Open with Live Server\*\*



\### 방법 2) Python 로컬 서버

프로젝트 폴더에서 아래 실행:



```bash

python -m http.server 5500



