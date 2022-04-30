## UI Screen Design
<img width="452" alt="image" src="https://user-images.githubusercontent.com/87361140/165644879-4a4ee1ba-87de-41bb-b800-7d533c0b5f4d.png">

<img width="300" height="200" alt="image" src="https://user-images.githubusercontent.com/87361140/165760963-fa11b7f7-1ba2-4fbb-88f6-d74c0e219be3.png">

<img width="452" alt="image" src="https://user-images.githubusercontent.com/87361140/165777754-fc644418-c3d4-4ca1-a6bb-05ac608100dc.png">


## Use Case Descriptions

1)상품 검색, 검색 결과 상품 리스트 정렬 기준  '평균 구매만족도'로 변경
|Actor Action|System Response|
|---|---|
||1. 검색 화면을 출력한다.|
|2. 회원이 검색어를 입력한다.|3. 검색어에 해당하는 상품 리스트를 상품명의 오름차순으로 출력한다.|
|4. 검색 조건을 '평균 구매 만족도'로 변경한다.|5. 상품 리스트를 평균 구매 만족도가 높은 순서로 출력한다.|
|Alternative Cources
Step4-5는 검색 조건이 '상품명'이길 원하는 경우 생략할 수 있다.|

2)상품 상세 정보 조회
|Actor Action|System Response|
|---|---|
||1. 상품 리스트를 출력한다.|
|2. 상세 정보가 보고싶은 상품을 선택한다.|3. 선택한 상품의 상세 정보를 출력한다.|

3)상품 구매, 추가 상품 구매, 포인트 사용
|Actor Action|System Response|
|---|---|
||1. 상품 리스트를 출력한다.|
|2. 회원이 구매를 원하는 상품을 선택한다.|3. 선택한 상품의 상세한 정보를 출력한다.|
|5. 추가 상품으로 등록한 물품도 같이 선택한다.|6. 추가 상품 금액만큼 증가된 총 구매금액을 출력한다.|
|7. '즉시 결제'버튼을 클릭한다.|8. 결제 화면으로 이동한다.|
|9. 사용할 포인트를 입력한다.|10. 회원이 입력한 포인트를 뺀 최종 결제 금액을 보여준다.|
|11. 결제를 진행한다.|
|Alternative Cources
Step5-6은 추가 상품을 구매할 필요가 없다면 생략할 수 있다.|
|Step9-10은 포인트가 3000점이 넘지 않거나 포인트를 사용하지 않을 경우 생략할 수 있다.|

4) 포인트 적립 기능

4-1) 포인트 적립
|Actor Action|System Response|
|---|---|
|1. 회원이 상품을 구매하는 Event가 발생한다.|2. 구매가 완료되었다는 메세지를 띄우면서 적립된 포인트도 함께 출력한다.|

4-2) 포인트 반환
|Actor Action|System Response|
|---|---|
|1. 회원이 신청한 환불이 완료된다.| |
|2. 환불한 내역을 확인한다.|3. 반환된 포인트가 포함된 환불 내역을 출력한다.|
