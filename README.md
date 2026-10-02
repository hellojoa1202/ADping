<h3><strong>ADping</strong></h3>

<p><sub>분야: 자율주행 · 차선 인식 · 차량 제어</sub></p>
<p><sub>기간: 2024-2 TAVE 14기</sub></p>

<h4><strong>구조</strong></h4>

<pre><code>ADping/
├── data/
│   └── data.py                  # 데이터 처리
├── models/
│   └── lane_navigation_final.h5 # 최종 차선 인식 모델
├── notebooks/
│   └── lane_navigation.ipynb    # 차선 인식 학습·추론
├── scripts/
│   └── autonomous_driving.py    # 자율주행 실행
└── vehicle_control/
    ├── AI_CAR/                  # 차량 제어 코드
    └── AI_CAR.zip              # 차량 제어 실험 자료</code></pre>

<h4><strong>구성</strong></h4>

<p><sub>최종 모델: <code>models/lane_navigation_final.h5</code></sub></p>
<p><sub>중간 모델·실험용 모델: 제외</sub></p>

<p><sub>2025 한이음 자율주행 경량화 → <a href="https://github.com/hellojoa1202/ADS_lightweight">ADS_lightweight</a></sub></p>