## UI Screen Design
<img width="452" alt="image" src="https://user-images.githubusercontent.com/87361140/165644879-4a4ee1ba-87de-41bb-b800-7d533c0b5f4d.png">

<img width="452" alt="image" src="https://user-images.githubusercontent.com/87361140/165760963-fa11b7f7-1ba2-4fbb-88f6-d74c0e219be3.png">


## Use Case Descriptions

1)상품 정보 조회 및 상품 구매 기능

|Actor Action|System Response|
|---|---|
|1. 회원이 검색 조건 중 ‘상품명’을 선택한 후 검색어를 입력한다.|2. 검색어에 해당하는 상품 리스트를 상품명의 오름차순으로 보여준다.|
|3. 구매를 원하는 상품을 선택한다.|4. 선택한 상품의 상세한 정보를 보여준다.|
|5. 즉시 결제한다.|6. 구매가 완료되었다는 메세지를 띄운다.|
|Alternative Cources
Step1-2에서 정렬 기준을 ‘평균 구매 만족도’로 바꿔 상품 리스트를 확인할 수 있다.|

2) 결제 기능

|Actor Action|System Response|
|---|---|
| |1. 구매 상품 목록과 총 구매금액을 포함하는 결제 화면을 보여준다.|
|2. 사용할 포인트를 입력한다.|3. 회원이 입력한 포인트를 뺀 최종 결제 금액을 보여준다.|
|4. 결제를 진행한다.||
|Alternative Cources
Step2-3은 포인트를 사용하지 않을 경우 생략할 수 있다.|
