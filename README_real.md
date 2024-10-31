![시스템구성도 drawio](https://github.com/user-attachments/assets/d1e93042-a5f8-4f36-b381-5391f0a5f0d4)# 수어비전(Sign Language Vision)

<div align="center">
  <img src="/api/placeholder/800/200" alt="프로젝트 배너 이미지" />
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

## 2. 상세설계

### 2.1. 시스템 구성도

<div align="center">
  <img src="/api/placeholder/800/400" alt="시스템 구성도" />
  <p><em>시스템 구성도</em></p>
</div>

### 2.2. 사용 기술

#### Backend & AI
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)

#### Frontend
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

#### 개발 도구
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Android Studio](https://img.shields.io/badge/android%20studio-346ac1?style=for-the-badge&logo=android%20studio&logoColor=white)

## 3. 설치 및 사용 방법

### 요구사항

```bash
# 필요한 환경
- Python 3.8+
- Android Studio
- Visual Studio Code
```

### 설치 방법

```bash
# 레포지토리 클론
git clone [repository URL]

# 필요한 패키지 설치
pip install -r requirements.txt
```

## 4. 소개 및 시연 영상

<div align="center">
  <img src="/api/placeholder/800/400" alt="시연 영상 썸네일" />
  <p><em>프로젝트 시연 영상</em></p>
</div>

## 주요 기능

### 수어 인식
- 실시간 카메라 입력을 통한 수어 동작 인식
- 높은 정확도와 신속한 인식 처리
- 다양한 수어 동작에 대한 인식 지원

### 텍스트 변환
- 인식된 수어의 실시간 텍스트 변환
- 사용자 친화적인 텍스트 출력
- 신속한 응답 시간

### 시스템 성능
- 실시간 처리 및 최소화된 지연 시간
- 높은 인식 정확도
- 안정적인 시스템 운영

## 5. 팀 소개

### 팀명: 팀 수어비전 (Team Sign Language Vision)

| 이름 | 역할 | 담당 업무 | 연락처 |
|------|------|-----------|---------|
|      |      |           |         |
|      |      |           |         |
|      |      |           |         |

## 라이센스

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
