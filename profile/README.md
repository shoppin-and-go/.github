## [서비스 체험해보기 (클릭)](https://shoppin-and-go.github.io/frontend/)

<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://github.com/user-attachments/assets/a78e132b-0885-4907-8872-00a145ff9528" alt="demo_cart" width="200"/>
    <div style="margin-left: 20px;">
        데모의 카트 화면예시입니다.<br/>
        사물 인식을 대신 하여, 우측 상단 버튼을 통해 가상의 카트에 상품을 추가/삭제해볼 수 있습니다.
    </div>
</div>

<div style="display: flex; align-items: center;">
    <img src="https://github.com/user-attachments/assets/8bd70a54-12bd-4a98-9e8f-e4345404581b" alt="demo_buttons" width="200"/>
    <div style="margin-left: 20px;">
        좌측 버튼을 누르면, 가상 카트의 카메라 앞에서 무작위의 물품을 추가합니다.<br/>
        우측 버튼을 누르면, 가상 카트의 카메라 앞에서 무작위의 물품을 제거합니다.
    </div>
</div>

# Shoppin&Go: AI 기반 실시간 쇼핑 추적 서비스
카메라를 이용한 실시간 물체 인식을 통해 잠바구니의 상품을 추적하고 관리하는 서비스입니다.

https://github.com/user-attachments/assets/ae3d5e78-9622-41d3-86f2-4c3297ed8c65

## Features
### QR코드 스캔을 통한 카트 연동
- 앱을 이용하여 카트에 부착된 QR코드를 스캔하여 카트 정보를 연동할 수 있습니다.
### 카메라를 통한 쇼핑 재고 추적
- 카트에 부착되어 있는 카메라로 상품을 넣고 빼는 행동을 감지하고 캡쳐합니다.
- 캡처한 이미지를 바탕으로 상품의 종류를 분류합니다.
### 앱을 통한 실시간 재고 관리 및 동기화
- 카트에 상품이 추가되었을 때, DB에 재고를 반영하고 웹소켓을 통해 앱으로 변경 내역을 전송합니다.
- 앱에서 실시간으로 변경되는 재고의 정보과 가격을 확인할 수 있습니다.

## Architecture

![architecture](https://github.com/user-attachments/assets/d1dabbb5-0dbf-4761-8c0c-8bf6d0117ae0)


## User Flow Diagram

![image](https://github.com/user-attachments/assets/61fda617-7326-49c4-a309-132adf24eb2a)
