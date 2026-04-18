# transformer_basic
[Project] Transformer Basic Implementation
이 프로젝트는 딥러닝의 혁신을 이끈 Transformer(Attention Is All You Need) 모델의 핵심 구조를 이해하고, Python과 PyTorch/Keras를 사용하여 직접 구현해 보는 실습 프로젝트입니다.

🚀 프로젝트 개요
목표: Transformer의 셀프 어텐션(Self-Attention) 메커니즘 이해 및 인코더-디코더 구조 구현

주요 학습 내용:

Positional Encoding

Multi-Head Attention

Masked Multi-Head Attention

Feed Forward Network

Residual Connection & Layer Normalization

🛠 기술 스택
Language: Python 3.x

Environment: Jupyter Notebook (.ipynb)

Libraries: PyTorch (또는 TensorFlow/Keras), NumPy, Matplotlib

📂 파일 구조
transformer_implementation.ipynb: Transformer 전체 구조 구현 및 학습 코드가 포함된 메인 파일

data/: 실습에 사용된 샘플 데이터셋 (필요 시 추가)

images/: 모델 구조도 및 학습 결과 그래프

📖 주요 구현 내용
Scaled Dot-Product Attention: 쿼리(Query), 키(Key), 값(Value) 간의 관계 점수를 계산

Multi-Head Attention: 여러 개의 헤드가 서로 다른 특징을 병렬적으로 학습하도록 구현

Position-wise Feed-Forward Networks: 각 포지션에서 독립적으로 적용되는 완전 연결 층

Encoder & Decoder Stacking: 위 모듈들을 쌓아 올려 전체 모델 완성

💻 실행 방법
저장소를 클론합니다.

Bash
git clone https://github.com/fsaisoft/transformer_basic.git
필요한 라이브러리를 설치합니다.

Bash
pip install torch numpy matplotlib
Jupyter Notebook을 실행하여 transformer_implementation.ipynb 파일을 엽니다.

📊 학습 결과
(여기에 학습 과정에서의 Loss 그래프나 간단한 번역/예측 결과 예시를 스크린샷으로 첨부하면 더욱 좋습니다!)
