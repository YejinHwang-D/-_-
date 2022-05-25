## 인증서 발급 서비스 Capstone Credential

### 1. Intro
 #### 소액 거리나 간단한 구두 계약을 원하는 사용자들이 편리하고 빠르게 거래에 대한 인증을 받을 수 있도록 인증서를 발급하는 서비스.
 
 본 프로젝트는 Hyperledger Indy를 사용하여 제작되었으며, Docker Image를 통해 Faber(발행자), Alice(고객)를 나누어 인증서를 발급합니다.

Field | Tools
--- | ---
Client **(ME)** | Webix, Javascript
Server **(ME)** | Flask
Database | SQLAlchemy
DID | hyperledger indy
Co-work | Github


### 2. Main function
1) **인증서 발급**
* 여러 상황에 맞는 인증서 양식 제공
* 양식에 맞는 데이터만 입력하면 간편하게 인증서 발급 기능
2) **로그 추적**
* 회원은 마이페이지를 통해 자신이 발급한 인증서 확인 가능
* 마이페이지에서 인증서 클릭 시 해당 발급된 인증서 페이지로 이동 가능



### 3. Start
```shell
git clone https://github.com/YejinHwang-D/Credential-Capstone-Design2
cd Credential-Capstone-Design2
pip3 install flask requests flask_sqlalchemy
```
```shell
export FLASK_APP=app
export FLASK_ENV=development
flask run
```

### 4. More information
프로젝트에 대한 더 자세한 설명은 [여기]()를 참고해주세요!
