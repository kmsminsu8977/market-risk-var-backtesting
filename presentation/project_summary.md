# 발표 초안

## 1. 문제 정의

과거 손익 분포로 추정한 VaR는 실제 손실 예외를 어느 정도 설명하는가?

## 2. 데이터와 가정

- 합성 샘플 데이터: `data/sample/portfolio_returns.csv`
- 재현 가능한 baseline 실행을 우선 구성

## 3. 방법

포트폴리오 수익률 표본에서 Historical VaR와 Expected Shortfall을 추정하고 예외 발생률을 확인한다.

## 4. 현재 산출물

- 실행 스크립트: `python -m src.run_baseline`
- 결과 표: `outputs/tables/baseline_results.csv`

## 5. 후속 작업

- 실제 데이터 연결
- 민감도 분석
- 차트/보고서 산출
- 프로젝트별 상세 검증
