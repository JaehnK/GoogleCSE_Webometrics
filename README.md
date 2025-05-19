# Google Custom Search Engine (CSE) 도메인 분석 도구

이 프로젝트는 Google Custom Search API를 활용하여 검색 결과의 도메인 분포를 분석하는 도구입니다. 검색 결과에서 URL을 수집하여 최상위 도메인(TLD), 2단계 최상위 도메인(STLD), 그리고 전체 도메인 이름을 추출하고 시각화합니다.

### 기능

Google Custom Search API를 통한 검색 결과 수집

수집된 URL에서 TLD, STLD 및 도메인 추출

도메인 분포 시각화

분석 결과 CSV 파일로 저장

### 설치 및 사용법

Google API 키 및 검색 엔진 ID 설정
이 도구를 사용하기 위해서는 Google Cloud Platform에서 API 키와 Custom Search Engine ID가 필요합니다.

#### Google Cloud Platform API 키 발급:

- [Google Cloud Console](https://console.cloud.google.com/)에 접속하여 계정 로그인

- 새 프로젝트 생성 또는 기존 프로젝트 선택

- 왼쪽 메뉴에서 'API 및 서비스' > '라이브러리' 선택

- "Custom Search API" 검색 후 활성화

- '사용자 인증 정보' 페이지에서 'API 키 만들기' 클릭

- 생성된 API 키 복사 (제한 설정 권장)


#### Google Custom Search Engine ID 설정:

- [Google Programmable Search Engine](https://programmablesearchengine.google.com/about/)에 접속

- '새 검색 엔진 만들기' 클릭

- 검색할 사이트 설정 (전체 웹 검색은 '검색 전체 웹' 옵션 선택)

- 생성 후 검색 엔진 ID(cx) 복사

#### Google Colab에서 실행하기

googleCSE.ipynb 클릭 후, Open in Colab 버튼 클릭
