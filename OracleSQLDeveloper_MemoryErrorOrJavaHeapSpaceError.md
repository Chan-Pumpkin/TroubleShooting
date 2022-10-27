## 에러 메시지
![에러메시지](https://user-images.githubusercontent.com/62877858/198315513-fb27cbc5-d2cd-4e16-a706-659654e3f4cb.PNG)

위와 같이 **메모리 부족하다**는 에러메시지 혹은 **Java heap space** 에러메시지가 뜨는 상황이 발생할 수도 있다.

## 방법
![경로](https://user-images.githubusercontent.com/62877858/198315485-ee9c840f-226d-4e34-bcd5-d3dc5bf9ffcd.PNG)

위와 같은 경로에 들어가서(중간 가려진 경로는 내 컴퓨터 네임) product.conf에서 

AddVMOption -Xmx(여기 내용 수정)M

XMx 용량을 늘려주면 된다.
