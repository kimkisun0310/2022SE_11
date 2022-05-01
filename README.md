# 2022SE_11


## 요구사항

회원은 구매 내역(상품명, 제작회사명, 판매자, 가격, 평균 구매만족도, 구매일)을
조회할 수 있다. 이때 상품명의 오름차순으로 정렬해서 출력한다. 조회된 구매 내
역 중에서 하나의 상품을 선택하여 구매만족도를 평가하거나 구입 후 4주가 지나지
않은 상품의 경우 환불을 신청할 수 있다. 환불을 신청하는 경우 택배사에 자동으로
물품 수거 신청이 요청된다.

## Use case diagram

![Untitled](https://github.com/kimkisun0310/2022SE_11/blob/fbb447f94b63a5fb3f56076f3c5623d0c03bf023/delete.png)

![Untitled](https://github.com/kimkisun0310/2022SE_11/blob/854ea264c768629cec2dd5d0c6813d6b54f91988/%ED%99%98%EB%B6%88%20event.png)

## UI screen design & Use case Description

![Untitled](https://github.com/kimkisun0310/2022SE_11/blob/eef1fafe3db2e34afe7d919422e94707dbaecaf3/Untitled%202.png)

### 구매내역 조회

| 유저 | 쇼핑몰 |
| --- | --- |
| 1. 구매내역 조회 요청 |  |
|  | 2. 구매내역 리스트 출력 |

![Untitled](https://github.com/kimkisun0310/2022SE_11/blob/eef1fafe3db2e34afe7d919422e94707dbaecaf3/Untitled%203.png)

### 평가

| 유저 | 쇼핑몰 |
| --- | --- |
| 1. 구매 내역에서 ‘구매 만족도 평가’ 클릭 |  |
|  | 2. 평가 폼 출력 |
| 3. 작성 및 제출 |  |
|  | 4. 평가 반영 후 출력  |

![Untitled](https://github.com/kimkisun0310/2022SE_11/blob/eef1fafe3db2e34afe7d919422e94707dbaecaf3/Untitled%204.png)

### 환불

| 유저 | 쇼핑몰 |
| --- | --- |
| 1. 구매 내역에서 ‘환불’ 클릭 |  |
|  | 2. 환불 폼 출력 |
| 3. 환불 폼 작성 후 신청서 제출  |  |
|  | 4. 환불 진행, 택배사 물품 수거 신청 |
