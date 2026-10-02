<p><sub>2024-2 TAVE 14기 자율주행 프로젝트</sub></p>

<p><sub>카메라 영상에서 차선을 인식하고, 인식 결과를 바탕으로 라즈베리파이 기반 차량의 주행을 제어하는 프로젝트입니다. 차선 인식 모델, 학습 결과, 차량 제어 실험 코드를 함께 보관합니다.</sub></p>

<p><sub>포함된 코드와 자료</sub></p>

<ul>
  <li><sub>루트 Python 파일: 데이터 처리와 자율주행 실행에 사용하는 코드</sub></li>
  <li><sub><code>code/</code>: 차선 인식 모델 관련 노트북, 모델 가중치, 주행 제어 코드</sub></li>
  <li><sub><code>code/AI_CAR/</code>: 차량 주행 실험에 사용한 단계별 Python 코드와 관련 압축 파일</sub></li>
  <li><sub><code>lane_navigation_final.h5</code>: 학습된 차선 인식 모델 가중치</sub></li>
</ul>

<p><sub>폴더 구조</sub></p>

<pre><code>2024-2-TAVE-14th-Autonomous-Driving/
├── README.md
├── data.py
├── 자율주행 실행 코드
└── code/
    ├── 차선 인식 모델 및 학습 자료
    ├── lane_navigation_final.h5
    └── AI_CAR/
        ├── 차량 제어 Python 코드
        └── AI_CAR.zip</code></pre>