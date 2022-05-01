# 2022SE_11

## 요구사항

회원이 판매한 상품에 대한 총액 및 평균 구매만족도와 구매한 상품에 대한
총액 및 평균 구매만족도를 출력한다. 이때, 삭제된 구매 내역은 통계에서 제외한
다. 또한 매월 말일에 모든 회원들에게 그 달에 대한 판매 및 구매 통계 정보를
이메일로 공지된다.

## Use case diagram

![Untitled](https://user-images.githubusercontent.com/58579386/166129160-074a1139-ce35-45ff-bb87-b5006b32ed29.png)

![Untitled](https://user-images.githubusercontent.com/58579386/166129163-f00ac9c3-3d4f-432a-99f7-225a354c6b36.png)

## UI screen design & use case description

![Untitled](https://user-images.githubusercontent.com/58579386/166129164-e4f5d8d4-bb12-4130-8f82-f4a9ad6a4900.jpg)

| 유저 | 쇼핑몰 |
| --- | --- |
| 1. 상단에서 '구매 통계내역' 클릭한다. |  |
|  | 2. 해당 회원의 구매 상품 통계 내역(상품 명, 제작 회사 명, 평균 구매 만족도, 총액) 출력한다. |
| 3. 산단에서 '판매 통계내역' 클릭한다. |  |
|  | 4. 해당 회원의 판매 상품 통계 내역(상품 명, 제작 회사 명, 평균 구매 만족도, 총액) 출력한다. |

| 쇼핑몰 |
| --- |
| 1. 매월 말일 모든 회원에게 통계 정보 등록된 이메일로 전송한다. |
