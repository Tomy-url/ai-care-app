요양원 AI 관리 시스템 최종 배포 패키지

구성 파일
- index.html : 메인 웹앱
- manifest.json : 모바일 홈화면 설치 설정
- sw.js : 오프라인 캐시용 서비스워커
- icon-192.png / icon-512.png : 앱 아이콘

설명
이 패키지는 Netlify에 업로드하기 좋은 다중 파일 구조입니다.
이전 ZIP처럼 index.html 하나만 있는 구조가 아니라,
배포용으로 필요한 기본 파일을 함께 포함합니다.

사용 방법
1. 압축 해제
2. Netlify 로그인
3. Add new site → Deploy manually
4. 압축 해제한 파일 전체 업로드
