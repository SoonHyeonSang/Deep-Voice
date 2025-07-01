# Deep-Voice
음성 특징 분석 기반 딥보이스 탐지 시스템

![그림3](https://github.com/user-attachments/assets/ade0963b-21fc-4bf7-9795-357ac4de9b70)
![그림4](https://github.com/user-attachments/assets/5e0d27fe-ad35-4210-ba95-6de5d2078c6c)

📌 **프로젝트 소개**

음성 파일로부터 MFCC, Chroma 등 다양한 음향 특성을 추출하여, 딥보이스 여부를 판단하는 딥러닝 분류 모델을 설계했습니다.

Flask를 통해 REST API 형태로 배포하고, 클라이언트에서 음성파일 업로드 시 탐지 결과를 실시간으로 반환합니다.

---

🛠 **주요 기능**

- **음향 특징 추출**: Librosa 기반 MFCC, Chroma, Spectral features 등 전처리
- **AI 분류 모델**: 음성 특성 데이터를 이용한 딥보이스 판단 모델 학습
- **서버 구축 및 통신**: Flask 기반 RESTful API 구축
- **모바일 연동 (예정)**: 추후 React Native 혹은 Flutter 기반 모바일 연동 고려

![그림](https://github.com/user-attachments/assets/ecde4f99-a449-473f-8491-794eb43dcc33) 

딥러닝 모델 생성 흐름도

![그림2](https://github.com/user-attachments/assets/e3e0a767-54d3-4bcb-bce2-fb7d1c7eeb87)

서버, 애플리케이션 동작 흐름도

---

🧑‍💻 **본인 역할**

- 음성 특징 분석을 위한 데이터 수집 및 전처리 파이프라인 구축
- TensorFlow 기반 분류 모델 학습 및 성능 튜닝
- Flask API 서버 구현 및 모델 배포 환경 구축
- API 테스트 및 후처리 로직 설계 (확신도 기준 분류 등)
    
![그림6](https://github.com/user-attachments/assets/97e3a319-5088-4c9d-bc6c-d244395179e7)
    
Flutter 사용 패키지

![그림5](https://github.com/user-attachments/assets/b4e80c62-3e40-4103-8252-c7e3ad6ac7cf)

flask 서버에서의 정상 동작

