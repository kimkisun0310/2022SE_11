# 2022SE_11 B811123 이다연

## Use Case Diagram

<img width="452" alt="image" src="https://user-images.githubusercontent.com/62105312/166070787-8690b977-3fdf-4eb1-867a-3014bfb2b6a9.png">

## UI Screen Design

<img width="452" alt="image" src="https://user-images.githubusercontent.com/62105312/166070232-20476181-36dc-4e5d-a883-4bfc760e23e8.jpg">

## Use Case Descriptions

1. 회원가입
   | 회원 | 쇼핑몰 |
   | --- | --- |
   | 1. 회원이 자신의 기본정보와 ID/Password를 입력하여 가입을 진행한다. | |
   | | 2. 회원 가입 완료 메시지가 출력된다. |

# 2022SE_11

## 요구사항

회원이 판매한 상품에 대한 총액 및 평균 구매만족도와 구매한 상품에 대한
총액 및 평균 구매만족도를 출력한다. 이때, 삭제된 구매 내역은 통계에서 제외한
다. 또한 매월 말일에 모든 회원들에게 그 달에 대한 판매 및 구매 통계 정보를
이메일로 공지된다.

## Use case diagram

![Untitled](https://github.com/kimkisun0310/2022SE_11/blob/5eaf066cedcdf27c9fe6ac068f1e2d20a2e925a9/%ED%86%B5%EA%B3%84%EC%A0%95%EB%B3%B4.png)

![Untitled](https://github.com/kimkisun0310/2022SE_11/blob/1e054dfd40bdcebd1d07d010c3db5387c9b9eb68/Untitled%201.png)

## UI screen design & use case description

![Untitled](https://github.com/kimkisun0310/2022SE_11/blob/08a15f9b3063c20417ef76de916b6cec3de1a6a1/%ED%86%B5%EA%B3%84%EB%82%B4%EC%97%ADUI.jpg)

| 유저                           | 쇼핑몰                                                                                 |
| ------------------------------ | -------------------------------------------------------------------------------------- |
| 1. 상단에서 구매 통계내역 클릭 |                                                                                        |
|                                | 2. 해당 회원의 구매 상품 통계 내역(상품 명, 제작 회사 명, 평균 구매 만족도, 총액) 출력 |
| 3. 산단에서 판매 통계내역 클릭 |                                                                                        |
|                                | 4. 해당 회원의 판매 상품 통계 내역(상품 명, 제작 회사 명, 평균 구매 만족도, 총액) 출력 |

| 쇼핑몰                                                    |
| --------------------------------------------------------- |
| 1. 매월 말일 모든 회원에게 통계 정보 등록된 이메일로 전송 |
