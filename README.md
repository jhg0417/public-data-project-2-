1.MDIS에서 인구주택총조사자료를 통해 2%_가구주택사항(제공), 2%_인구사항(제공)을 CSV파일로 다운받음.
2.다운받은 CSV을 파이썬으로 부름
3.출생아수는 대부분 가구주와 배우자에 기록되어있으므로 가구주와 배우자의 데이터를 표본 추출함.
4.가구일련번호를 통해 2%_가구주택사항, 2%_인구사항의 항목을 merge()함수를 통해 결합함.
5.코드 매핑
6.연령대별 상이한 출산율을 고려해 20-50대까지의 연령대만 추출하고 나머지 연령대는 결측값 처리해서 notna()로 걸러냄.
7.data.info(), data.head() 함수를 통해 데이터에 대해 간략히 설명.
8.빈도표 나타내봄.
9.연령대별 주거형태에 대한 평균 자녀 수와 연령대별 주택종류(1-5번) 평균 자녀 수를 시각화함. 주택종류를 간략화한 이유는 시각화할 때 한눈에 들어오게 하기 위함.
