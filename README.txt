돈통 - 비 PWA / 마리화나 아이콘 버전

이 버전은 PWA 설치 기능을 제거한 버전입니다.
- manifest.webmanifest 없음
- sw.js 없음
- service worker 등록 코드 없음

아이콘은 '마리/화나' 글자 아이콘으로 새로 생성했습니다.
- favicon-32.png: 브라우저 탭 / 북마크바
- icon-180.png: iPhone/iPad 홈 화면에 추가
- icon-192.png, icon-512.png: Android/고해상도용 보조 아이콘

중요:
브라우저 favicon 캐시가 매우 질기기 때문에 index.html의 아이콘 경로에 ?v=marijuana3 캐시 방지 값을 붙여두었습니다.
그래도 안 바뀌면 아래를 해보세요.
1. Ctrl + Shift + R
2. 주소 뒤에 ?v=3 붙여 접속
3. F12 > Application > Storage > Clear site data
4. 기존 홈화면 아이콘은 삭제 후 다시 추가
