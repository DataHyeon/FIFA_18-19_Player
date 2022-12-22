## Title : Who do you need for Manchester United?

<br>

### Author : DataHyeon

<br>

### Date : 22.12.22

<br>

### Language : Jupyter

<br>

### Dec

- EPL 18/19시즌 MU의 감독인 솔샤르는 팀 성적을 위해서 2명의 선수를 영입하려고 했다.

- 내가 그 때의 MU의 감독이라면 과연 누구를 영입했을 것인가에 대한 데이터 분석

<br>

### Progress

- EDA를 통한 데이터 전처리 : FIFA 전체 데이터에서 MU 선수의 자료 추출

- 비교를 위해서 각 지표(몸값, 스탯 등) 지역 라이벌 팀인 MC 팀의 자료 추출

- 각 데이터들의 결측치를 확인하고 특이값(골키퍼의 타 포지션 스탯)등을 0값으로 대체

- 상대적으로 라이벌팀과 미드필더와 수비수에서 전체적 스탯과 몸값이 낮음

- 영입 포지션을 미드필더 1명과 수비수 1명으로 결정

- 영입 기준을 나이와 전체적 스탯, 잠재력, 약발의 정도로 정하고 영입대상 고려

- 수비수에서는 S.Umtiti, 미드필더에서는 K.Mbappe를 영입대상으로 결정

<br>

### Module

- 전처리 : pandas
 
- 시각화 : matplotlib, seaborn

<br>

### File

- Main : FIFA_main.ipynb

- Input : FIFA_data.csv

- Ouput : output.png

<br>

### Conclusion

- 기본적으로 어느정도 정리가 잘 되어있는 데이터셋으로 구성이 되어있었지만 단순 포지션별로 비교하기 위한 전처리 작업이 까다로웠다

- 분석의 결과를 가지고 상대방(파트너, 상사 등)을 설득하기 위해서는 시각화 측면에서 직관적으로 데이터가 나타날 수 있도록 해야한다는 것을 배웠다
