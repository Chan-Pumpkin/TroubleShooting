# 스프링 string으로 mapper.java->mapper_sql.xml(mybatis) 매개변수 넘겨주다가 생긴 에러 발생

## 개요
![2022-08-17-TroubleShooting](https://user-images.githubusercontent.com/62877858/185171384-989c14da-23f2-40b6-8702-8d716273c654.png)
에러 발생!!! console을 보아하니, 파라미터 'loginId2'의 값을 못 찾는다는 에러문구.   

## 해결
String의 매개변수 2개를 넘겼는데, 쿼리에서 순서대로 {param1}, {param2}로 넣어주었다.
