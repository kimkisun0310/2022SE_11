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

## Use Case Diagram

<img width="452" alt="image" src="https://user-images.githubusercontent.com/62105312/166081465-8d8d068e-fb0c-4cdd-b994-ccaed515949e.png">

## UI Screen Design

<img width="452" alt="image" src="https://user-images.githubusercontent.com/62105312/166081484-6b4fd6c3-cc99-434b-ad3c-4471e7dd2106.jpg">

## Use Case Descriptions

2. 회원 탈퇴
   | 회원 | 쇼핑몰 |
   | --- | --- |
   | 1. 회원 탈퇴를 진행한다. | |
   | | 2. 해당 회원에게 상품이 하나도 없는지 확인한다.|
   | | 3. 상품이 없을 경우 회원 탈퇴 완료 메시지를 출력한다. |

## Use Case Diagram

<img width="452" alt="image" src="https://user-images.githubusercontent.com/62105312/166082590-d50d3876-bad5-4177-9f4a-ccd43955ba4d.png">

## UI Screen Design

<img width="452" alt="image" src="https://user-images.githubusercontent.com/62105312/166083118-e56acb67-691b-4727-8331-8d86507498ed.jpg">

## Use Case Descriptions

3. 로그인/로그아웃 기능
   | 회원 | 쇼핑몰 |
   | --- | --- |
   | 1. 등록한 ID와 Password로 로그인을 한다. | |

   | 회원             | 쇼핑몰                           |
   | ---------------- | -------------------------------- |
   | 1. 로그아웃한다. |                                  |
   |                  | 2. 프로그램이 자동으로 종료된다. |

## Use Case Diagram

<img width="452" alt="image" src="https://user-images.githubusercontent.com/62105312/166127569-e60c6af4-b10c-4e6c-9e6b-c7d8d71e4a0d.png">

## UI Screen Design

<img width="452" alt="image" src="https://user-images.githubusercontent.com/62105312/166127996-bbaa987c-6667-46b9-92dc-4819b10e62f9.jpg">

## Use Case Descriptions

3. 판매 의류 등록 및 조회/수정 기능
   | 회원 | 쇼핑몰 |
   | ---------------- | -------------------------------- |
   | 1. 상품명, 제작회사명, 가격, 수량, 추가상품, 추가상품가격, 판매 종료일 등의 정보를 입력하여 상품을 등록한다. | |

   | 회원                                                       | 쇼핑몰                            |
   | ---------------------------------------------------------- | --------------------------------- |
   | 1. 자신이 등록한 판매 중인 의류 상품을 조회한다.           | 2. 상품 리스트 페이지를 제공한다. |
   | 3. 리스트에서 특정 상품을 선택하여 상품의 정보를 수정한다. |                                   |

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
