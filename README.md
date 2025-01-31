# Eagle's Road " 새로운 길 , 독수리처럼 힘차게~!! "
## Team

| ![박패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![이패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![최패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![김패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![오패캠](https://avatars.githubusercontent.com/u/156163982?v=4) |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: |
|            [최진호](https://github.com/UpstageAILab)             |            [김태환](https://github.com/UpstageAILab)             |            [김현진](https://github.com/UpstageAILab)             |            [유영신](https://github.com/UpstageAILab)             |            [김예승](https://github.com/UpstageAILab)             |
|                            팀장, 모델테스트                             |                            모델테스트                             |                            모델테스트                             |                            데이터분석                             |                            데이터분석                             |

## 0. Overview
### Environment

AMD Ryzen Threadripper 3960X-Core Processor
NVIDAIA Gefoece RTX 3090
CUDA Version 12.2

### Requirements

matplotlib==3.10.0
numpy==2.2.0
pandas==2.2.3
scikit-learn==1.6.0

## 1. Competiton Info

### Overview

Dialogue Summarization 경진대회는 주어진 데이터를 활용하여 일상 대화에 대한 요약을 효과적으로 생성하는 모델을 개발하는 대회입니다. 

일상생활에서 대화는 항상 이루어지고 있습니다. 회의나 토의는 물론이고, 사소한 일상 대화 중에도 서로 다양한 주제와 입장들을 주고 받습니다. 나누는 대화를 녹음해두더라도 대화 전체를 항상 다시 들을 수는 없기 때문에 요약이 필요하고, 이를 위한 통화 비서와 같은 서비스들도 등장하고 있습니다.

그러나 하나의 대화에서도 관점, 주제별로 정리하면 수 많은 요약을 만들 수 있습니다. 대화를 하는 도중에 이를 요약하게 되면 대화에 집중할 수 없으며, 대화 이후에 기억에 의존해 요약하게 되면 오해나 누락이 추가되어 주관이 많이 개입되게 됩니다.

이를 돕기 위해, 우리는 이번 대회에서 일상 대화를 바탕으로 요약문을 생성하는 모델을 구축합니다!

![Image](https://github.com/user-attachments/assets/6780fd7e-54ad-40cc-af0b-10d411121a6f)

참가자들은 대회에서 제공된 데이터셋을 기반으로 모델을 학습하고, 대화의 요약문을 생성하는데 중점을 둡니다. 이를 위해 다양한 구조의 자연어 모델을 구축할 수 있습니다.

제공되는 데이터셋은 오직 "대화문과 요약문"입니다. 회의, 일상 대화 등 다양한 주제를 가진 대화문과, 이에 대한 요약문을 포함하고 있습니다.

참가자들은 이러한 비정형 텍스트 데이터를 고려하여 모델을 훈련하고, 요약문의 생성 성능을 높이기 위한 최적의 방법을 찾아야 합니다.

경진대회의 목표는 정확하고 일반화된 모델을 개발하여 요약문을 생성하는 것입니다. 나누는 많은 대화에서 핵심적인 부분만 모델이 요약해주니, 업무 효율은 물론이고 관계도 개선될 수 있습니다. 또한, 참가자들은 모델의 성능을 평가하고 대화문과 요약문의 관계를 심층적으로 이해함으로써 자연어 딥러닝 모델링 분야에서의 실전 경험을 쌓을 수 있습니다.

본 대회는 결과물 csv 확장자 파일을 제출하게 됩니다.

input : 249개의 대화문

output : 249개의 대화 요약문

### Evaluation Metric

<img width="800" alt="Image" src="https://github.com/user-attachments/assets/80a8290a-b471-436e-b187-09e555956f84" />

### Timeline

<img width="630" alt="Image" src="https://github.com/user-attachments/assets/d004282b-41b4-4b04-946a-72750380d73e" />


## 2. Components

### Directory

![image](https://github.com/user-attachments/assets/3f5616da-c6bd-4226-98aa-16a00c136673)

## 3. Data descrption

### Dataset overview

<img width="800" alt="Image" src="https://github.com/user-attachments/assets/beacc2c4-e6ad-4681-844b-e3b41957dda9" />

### EDA & Data Processing

<img width="613" alt="Image" src="https://github.com/user-attachments/assets/8f71602b-5dc0-412a-b5b4-80eecc57f971" />

<img width="862" alt="Image" src="https://github.com/user-attachments/assets/51180682-f990-461f-a11d-f4ce2ba5ceeb" />

<img width="862" alt="Image" src="https://github.com/user-attachments/assets/2057817a-554b-44a9-b8ce-39a9a791ca26" />

<img width="858" alt="Image" src="https://github.com/user-attachments/assets/38dbbeeb-0da5-4f71-b7c9-2f445050353f" />

## 4. Modeling

### Model descrition & Modeling Process

<img width="946" alt="Image" src="https://github.com/user-attachments/assets/6203790f-3f74-4fe8-bd6e-dc77b1216ee6" />

![Image](https://github.com/user-attachments/assets/8b089e43-4bbf-4ebb-a156-dd4be8d18217)

## 5. Result

### Leader Board

![Image](https://github.com/user-attachments/assets/0f8ce7a8-25ce-4938-bc82-3a19e5397ae7)

### Presentation

https://docs.google.com/presentation/d/16C3gxiuxN2i_rtIF9Rn5Xo6NONPxuNICbAryDjqDSNE/edit#slide=id.g32e225d9c1d_2_75

## etc

### Meeting Log

- Notion : https://www.notion.so/3-Eagle-s-Road-5fb1a904b18240bb9fb6f0791d3f3ee0?pvs=4
- Google Docs (Mentoring) : https://docs.google.com/document/d/1d92dD-P3A1gI9VX8rh676Ti01jyVend46uXls8Cv2QQ/edit?tab=t.0

### Reference
-
