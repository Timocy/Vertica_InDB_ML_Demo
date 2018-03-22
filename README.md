# Vertica In-DB ML Demo

## 용도
분석용 RDBMS Vertica에서 ANSI-SQL을 활용해 Machine Learning 모델 개발에 필요한 일련의 과정을 수행하는 데모

## 개괄
Jupyter Notebook을 활용해 Python과 SQL을 조합함. Python 코드는 데이터 시각화에 활용하고 그 외 모든 작업은 Vertica에서 제공하는 SQL기반 in-DB ML기능을 활용함.

## Data dictionary and source information
Smart Meter 데이터는 Irish Energy 에서 공개한 데이터셋으로 15분 간격으로 24시간 동안 15분 간격으로 측정한 전력 사용량 (kw) 데이터가 저장되어 있다. http://www.ucd.ie/issda/data/commissionforenergyregulationcer/
전력 사용량과 연계하기 위해 날씨 데이터 역시 30분 간격으로 별도로 측정되었다.
