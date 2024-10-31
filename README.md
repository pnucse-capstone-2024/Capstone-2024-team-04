# 수어비전(Sign Language Vision)

<div align="center">
  <img src="https://github.com/user-attachments/assets/e12f8c73-d145-4a19-946e-774414f3a974" alt="수어비전">
</div>


## 1. 프로젝트 소개

### 1.1. 배경 및 필요성

‘부산광역시 농아인 협회’의 자문 결과에 따르면, 청각장애인이 한글 독해 능력이 부족하여 수어에 의존하는 의사소통 방식을 사용하고 있습니다. 이는 청각장애인이 비장애인과 의사소통을 할 때 많은 장벽을 느끼고 있음을 의미합니다. 또한, 길 찾기, 관공서 방문, 의료기관 이용 등 대중교통을 이용해야 하는 상황에서 특히 많은 불편함을 호소하는 것으로 나타났습니다.


 이러한 문제를 해결하기 위해 저희 수어비전 팀에서는, 비전 인식 기술을 활용한 수어 번역 애플리케이션 개발에 나섰습니다. 많은 교통 상황 중에서도 버스, 지하철, 비행기 등과 달리 노선이 정해지지 않은 택시 이용 상황에 초점을 맞추었으며, 청각장애인도 쉽게 사용할 수 있도록 직관적인 애플리케이션을 개발하기 위에 노력했습니다.

### 1.2. 목표 및 주요 내용

- 택시 이용 시 농인들의 원활한 의사소통을 지원하는 수어 인식 애플리케이션 개발
- 실시간 수어 동작 인식 및 텍스트 변환 서비스 제공
- 택시 기사와의 원활한 의사소통을 위해 음성 출력 기능을 탑재
- [AI Hub의 수어 영상 데이터셋](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=data&dataSetSn=103)을 활용한 정확하고 신뢰성 있는 번역 시스템 구현


## 2. 팀 소개

| 이름 | 역할 | 담당 업무 |
|------|------|-----------|
|   허재성   |   팀장   |   AI 모델 학습   |
|   한지석   |   팀원   |   AI 모델 학습   |
|   김민혁   |   팀원   |   애플리케이션 제작   |


## 3. 상세설계

### 3.1. 시스템 구성도

<p align="center">
  <img src="https://github.com/user-attachments/assets/f44e1988-88b9-48c1-8fd7-6e81b3496773" alt="시스템구성도 drawio">
</p>


### 3.2. 사용 기술

#### Backend & AI
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)

#### Frontend
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

#### 개발 도구
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Android Studio](https://img.shields.io/badge/android%20studio-346ac1?style=for-the-badge&logo=android%20studio&logoColor=white)


## 4. 설치 및 사용 방법

#### 설치 방법
### 레포지토리 클론
```bash
# 앱 레포지토리 클론
git clone https://github.com/kyleidea1/sign-language-translator-app.git

# 서버 레포지토리 클론
git clone https://github.com/kyleidea1/sign-language-translator-server.git
```

### 앱 빌드
- Android Studio에서 `sign-language-translator-app` 프로젝트를 빌드합니다.

### 서버 애플리케이션 실행
```bash
# 서버 디렉토리로 이동
cd sign-language-translator-server
# Docker 컨테이너 실행
sudo docker-compose up
```

### 앱 카메라 권한 확인
- 앱 최초 실행 시 카메라 접근 권한을 요청합니다.
- 권한이 거부된 경우, 브라우저 설정에서 카메라 권한을 허용해주시기 바랍니다.

### 수어 영상 녹화 및 번역 결과 확인
- 녹화 버튼을 눌러 수어 동작을 녹화합니다.
- 녹화 완료 후 자동으로 번역이 시작되며 결과가 화면에 표시됩니다.


## 5. 시연 영상

<p align="center">
  <a href="https://www.youtube.com/watch?v=jNpjqRoLIwE">
    <img src="http://img.youtube.com/vi/jNpjqRoLIwE/0.jpg" alt="2024년 전기 졸업과제 04 수어비전">
  </a>
</p>
