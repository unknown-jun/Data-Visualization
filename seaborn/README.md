# Seaborn

## Seaborn 특징
- 여러 변수 간의 관계를 검사하기 위한 데이터 집합 지향 API
- 범주형 변수를 사용하여 관측치 또는 집계 통계량을 표시하기 위한 전문적인 지원
- 일변량 또는 이변량 분포를 시각화하고 데이터의 부분 집합 간 비교하기 위한 옵션
- 서로 다른 종류의 종속 변수에 대한 선형 회귀 모형의 자동 추정 및 표시
- 복잡한 데이터셋의 전체구조에 대한 편리한 보기
- 복잡한 시각화를 쉽게 구축할 수 있는 다중 플롯 그리드 구조를 위한 높은 수준의 추상화
- 여러 테마가 내장된 matplotlib 그림 스타일링 제어
- 데이터의 패턴을 충실히 나타내는 색상 팔레트 선택 도구

## S01. 산점도(Scatter Plot)

## S02. 라인 그래프(Line Plot)
1. line plot 생성
2. ci: 신뢰구간 속성
3. estimator: 집계값 조정
4. style: dash나 marker를 통한 차원 표현
5. col: 특정값대로 그래프 분할
6. query문을 통한 데이터 크기 제한
7. sort
8. palette: 색상 조합 조정
9. row
10. col_wrap: 한 열에 들어갈 최대 그래프 조절하기
11. fig.autofmt_xdate

## S03. 범주형 데이터(Categorical Data)  
1. 범주형 산점도(Categorical Scatterplot)  
2. 범주형 분포도(Categorical Distribution)  
&nbsp;&nbsp;&nbsp;2-1. 박스플랏(Box plots)  
&nbsp;&nbsp;&nbsp;2-2. 박슨플랏(Boxen plots)  
&nbsp;&nbsp;&nbsp;2-3. 카운트플랏(Violin plots)  
3. 범주형 추정치 도표(Categorical estimate plots)  
&nbsp;&nbsp;&nbsp;3-1. 막대 플랏(Bar plots)  
&nbsp;&nbsp;&nbsp;3-2. 포인트 플랏(Point plots)  
&nbsp;&nbsp;&nbsp;3-3. 카운트 플랏(Counts plot)  
