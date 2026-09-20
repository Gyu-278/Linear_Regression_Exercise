# Linear_Regression_Exercise

## Concrete Compressive Strength Prediction (Linear Regression)

콘크리트 배합 데이터(시멘트, 물, 재령 등)를 활용하여 **압축강도(MPa)**를 예측하는 선형 회귀(Linear Regression) 모델을 구현

---

## 프로젝트
Google Colab 환경에서 예제 및 실습을 수행.

1. **정규 방정식 (Normal Equation):** 무어-펜로즈 의사역행렬(`np.linalg.pinv`)을 이용한 해석적 학습법 구현 (`pinv` vs `inv` 수치적 안정성 비교)
2. **경사하강법 (Gradient Descent):** 벡터화된 배치 경사하강법 구현 및 특성 스케일링(Standardization)과 학습률($\alpha$)의 중요성 검증
3. **특성 공학 (Feature Engineering):** 콘크리트 공학 도메인 지식을 반영한 $\ln(\text{age})$ 및 물-결합재 비($w/b$) 변수 추가를 통한 예측 오차(RMSE) 개선
4. **다항 회귀 및 과적합 (Polynomial Regression & Overfitting):** 다항식 차수($d$) 증가에 따른 훈련/테스트 오차 변화 관찰 및 Overfitting 진단

---

## 기술 Stack
- **Language:** Python 3
- **Libraries:** NumPy, Pandas, Matplotlib, Scikit-learn
- **Dataset:** UCI Machine Learning Repository - Concrete Compressive Strength
