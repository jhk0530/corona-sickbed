# corona-sickbed: sickbed status dashboard for corona

## 목표 

경기도 병원의 가용 음압병상 현황을 보여주는 대시보드를 개발, 중증환자 입원이 원활히 진행될 수 있도록 돕는다.  

## 필요 기능

1. ~~**로그인**: 관련자만 볼 수 있도록, [shinymanager](https://blog.zarathu.com/posts/2019-08-25-shinymanager/) 추천~~ 

2. ~~음압병상 갖춘 병원들이 표시된 **경기도 지도**.~~

3. 각 **병원의 가용/전체 음압병상 수**를 직관적으로 확인. 병실등급 A-E 단계 존재하며 **등급별** 확인 가능해야 함.
 - 예) 분당서울대병원: A등급 보유병상 7개, A등급 가용병상 0개
 - A-E 등급 외 기타도 있어 고민 필요.
 
4. 타 시도 확장 고려한 개발

## 기타
- Input Data Example: [download](https://github.com/YoungjunNa/corona-sickbed/raw/master/data-example/2020-02-23.xlsx)
- Test Server: https://youngjunna.shinyapps.io/corona-sickbed
- Deploy Server: http://app.zarathu.com/corona/corona-sickbed/
- Coding Style Rule: [Tidyverse style](https://style.tidyverse.org/)
