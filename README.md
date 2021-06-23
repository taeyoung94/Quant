# Quant

## 1. Portfolio Optimization

1) ✍ Summary
- **활용DB**: Financial product index (80년도부터 현재까지)
- **분석목표**: 포트폴리오 비중 모델링
- **성과**: 위험을 줄이는 포트폴리오인것을 도출, 최대의 return 값을 위해 Maximize Sharpe Ratio 적용
- **역할**: **End to End 분석, EDA부터 발표까지 진행**
2) 접근방향
> - 머신러닝 EDA를 통해 각 인덱스별 기본 자산 배분 적용
> - Transaction을 적용시켜 시간이 지나면서 비중을 변화, 최적의 비중 확인
> - 비중을 LSTM을 통해 예측 및 예측 성공률 도출
> - Backtesting과 결과값들을 시각화
3) 모델링 기준
>     1) 횡적 리스크 모델링 (MVO 사용)
>     2) 종적 리스크 모델링 (포트폴리오 모든 자산 사용)
>     3) Deep-learning과 Backtesting 활용하여 예측 및 최소 Drawdown 값 도출
4) 결론
> Link: [프로젝트PPT](https://github.com/taeyoung94/Quant/blob/main/Presentation.pdf)/ [프로젝트코드](https://nbviewer.jupyter.org/github/taeyoung94/Quant/blob/main/Portfolio_Rebalancing_final.ipynb)/ [프로젝트 시각화](https://nbviewer.jupyter.org/github/taeyoung94/Quant/blob/main/Result.ipynb)
