# 2022SE_11


## 요구사항

회원은 구매 내역(상품명, 제작회사명, 판매자, 가격, 평균 구매만족도, 구매일)을
조회할 수 있다. 이때 상품명의 오름차순으로 정렬해서 출력한다. 조회된 구매 내
역 중에서 하나의 상품을 선택하여 구매만족도를 평가하거나 구입 후 4주가 지나지
않은 상품의 경우 환불을 신청할 수 있다. 환불을 신청하는 경우 택배사에 자동으로
물품 수거 신청이 요청된다.

## Use case diagram

![Untitled](https://user-images.githubusercontent.com/58579386/166129191-46249e8e-3b26-434f-af9d-1173ac33fcda.png)


## UI screen design & Use case Description

![Untitled](https://user-images.githubusercontent.com/58579386/166129192-44361f80-8f87-43fb-a73e-be58e9330cbb.png)

### 구매내역 조회

| 유저 | 쇼핑몰 |
| --- | --- |
| 1. 구매내역 조회 요청한다. |  |
|  | 2. 구매내역 리스트 출력한다. |

![Untitled](https://user-images.githubusercontent.com/58579386/166129194-ca448ff5-8479-4f3f-a5d9-59de35877f33.png)

### 평가

| 유저 | 쇼핑몰 |
| --- | --- |
| 1. 구매 내역에서 ‘구매 만족도 평가’ 클릭한다. |  |
|  | 2. 평가 폼 출력한다. |
| 3. 작성 및 제출한다. |  |
|  | 4. 평가 반영 후 출력한다.  |

![Untitled](https://user-images.githubusercontent.com/58579386/166129195-c35a4038-38c8-43de-b58e-18b6d15d5fba.png)

### 환불

| 유저 | 쇼핑몰 |
| --- | --- |
| 1. 구매 내역에서 ‘환불’ 클릭한다. |  |
|  | 2. 환불 폼 출력한다. |
| 3. 환불 폼 작성 후 신청서 제출한다.  |  |
|  | 4. 환불 진행, 택배사 물품 수거 신청한다. |
