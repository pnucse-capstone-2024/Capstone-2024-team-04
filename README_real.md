# 부산대학교 정보컴퓨터공학부 23학년도 전기 졸업과제

## 팀명: 팀 수어비전

### 주제: 수어 영상 데이터셋을 이용하여 농인들을 도와주는 배리어프리 애플리케이션 제작

[수어 영상 데이터셋](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=data&dataSetSn=103)


농인들에게 직접 설문조사를 한 결과, 일상생활 중 가장 힘든 상황은 교통 수단을 이용해야 할 때인 것으로 나타났습니다. 특히, 버스와 지하철 등 대중교통보다 택시를 이용하는 상황에서 더욱 어려움을 겪고 있습니다. 이를 돕기 위해 택시에서 농인들이 사용할 수 있는 비전 인식 프로그램을 제작합니다.

## 사용자 요구사항

### 수어 인식

- 사용자가 손동작을 카메라를 통해 입력하면, 시스템은 이를 실시간으로 수어로 인식해야 합니다.
- 다양한 수어 동작을 인식할 수 있어야 하며, 정확도와 신속성이 보장되어야 합니다.

### 텍스트 번역

- 수어로 인식된 동작은 텍스트로 번역되어야 하며, 사용자가 쉽게 이해할 수 있는 언어로 번역되어야 합니다.
- 번역된 텍스트는 실시간으로 제공되어야 하며, 빠른 응답 속도가 필요합니다.

## 시스템 요구사항

### 실시간 처리

- 카메라 입력을 실시간으로 처리하고, 수어 인식 및 텍스트 번역이 실시간으로 이루어져야 합니다.
- 응답 시간이 최소화되어야 하며, 시스템이 지연 없이 동작해야 합니다.

### 정확성

- 수어 인식 및 텍스트 번역의 정확성이 보장되어야 합니다. 오분류나 오역을 최소화해야 합니다.

## 개발 환경

- **개발 언어**
    - Python ![PythonAnywhere](https://img.shields.io/badge/pythonanywhere-%232F9FD7.svg?style=for-the-badge&logo=pythonanywhere&logoColor=151515)
    - Kotlin ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
- **개발 도구 및 실행 환경**
    - Visual Studio Code ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
    - Android Studio ![Android Studio](https://img.shields.io/badge/android%20studio-346ac1?style=for-the-badge&logo=android%20studio&logoColor=white)
    - TensorFlow ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
