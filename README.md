# 파이썬과 인공지능을 활용한 금융 자료 분석

![image](https://github.com/user-attachments/assets/aa306864-3862-4d6d-9980-f403eaf53797)

<br>

## 강의 후기

대학 시절 투자론을 접하면서 주식과 암호화폐에 관심을 가지게 되었고, 차트 분석과 기업 분석을 공부하며 실제 거래도 해왔습니다. 
처음에는 제 기술적 분석 실력만으로도 충분하다고 생각했지만, 바쁜 일상속에서 직접 매매를 하다보니 분석에 착오가있거나 매매에 감정이 실려 손해를 보고 기회비용이 발생할 때가 많았습니다.

개발자가 된 후에는 투자 경험을 살려 트레이딩 프로그램 '[AntBot](https://github.com/JJOK97/AntBot)'을 개발한 적이 있습니다. 
Java를 기반으로 Claude AI의 API를 활용해 자동으로 매매 전략을 실행하는 시스템을 만들었지만, AI가 전략을 제대로 이해하지 못했고, 백테스팅 결과도 일정하지 않아 신뢰할 수 없는 문제가 있었습니다. 
코드를 수정하고 모델을 개선해도 문제를 해결하기 어려웠고, 단순히 매매 전략을 잘 설계하는 것만으로는 생각했던 프로그램이 나오지 않는다는 것을 깨닫게 되었습니다.

그렇기에 이전의 분석 방법과 개발 스택으로는 한계가 있다고 느꼈으며, 보다 실전에 가까운 접근을 해보고자 파이썬과 데이터 분석, 머신러닝을 활용한 금융 분석을 학습하기 위해 이 강의를 수강하게 되었습니다.

이번 과정을 통해 데이터를 다루는 방식 자체가 바뀌었습니다. 
예전에는 직접 차트를 보며 분석하고 매매 결정을 내려야 했지만, 다양한 라이브러리를 조합하면 이 과정이 훨씬 더 효율적으로 이루어질 수 있음을 경험했습니다. 
Pandas, NumPy 같은 라이브러리로 데이터를 빠르게 전처리하고, LSTM을 활용한 시계열 예측을 적용하면서 분석 속도가 빨라졌을 뿐만 아니라, 매매 과정에서 사람의 감정이 개입될 여지를 최소화할 수 있었습니다.  
*( 직접 차트를 분석하고 매매할 때는 상승장에서 과감하게 진입하거나, 손실을 인정하지 못하는 등의 심리가 작용할 수밖에 없습니다. 하지만 자동화된 시스템은 감정에 흔들리지 않고 일정한 규칙을 기반으로 일관된 매매를 수행할 수 있도록 만들어 줍니다. )*

또한 LSTM을 활용한 주가 예측 과정에서도 기존의 기술적 분석과는 전혀 다른 접근법을 경험할 수 있었습니다. 단순한 차트 패턴 분석이 아니라, 데이터를 학습시키고 결과를 확인하면서 기존 방식으로는 발견하기 어려웠던 복잡한 연관성을 찾아낼 수 있었습니다. 
과거 데이터를 기반으로 다양한 구간에서 백테스팅 결과, 승률이 60% 이상 유지되고, 수익률도 10% 이상 나오는 안정적인 성과를 보이며 직접 매매하는것에 비해서 훨씬 안정적인 결과를 얻을 수 있었습니다.

현재 교육 내용을 바탕으로 '[AntBot 2.0](https://github.com/JJOK97/AntBot2.0)'을 개발 중이며, 곧 배포를 앞두고 있습니다. 
이번에는 교육내용에서 더 나아가 Grafana와 Prometheus를 활용해 실시간 모니터링을 통해서 실제 수익률을 관리하며 지속적으로 알고리즘을 향상시킬 계획입니다. 

<br>
<hr>
