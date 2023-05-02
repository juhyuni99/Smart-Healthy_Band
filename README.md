# IoT Smart_Healthy Band & Monitoring System

> 🖥️MQTT 통신, Web을 이용한 IoT Healthy_band & Monitoring System🖥️
* 프로젝트 기간 : 2020.10 ~ 2020.12

## 👋개발 배경
* 바쁜 현대사회에서 자신의 건강을 미처 챙기지 못하는 사람들이 증가, 사회적으로 미세먼지의 농도가 높아지고, 코로나 전염도 심각해지고 있습니다. 
* 이에 여러 센서가 장착된 mini IoT healthy band를 통해 자신의 건강과 외부환경을 확인할 수 있도록 제작하였습니다.

## 📚얻은 역량
 * AWS EC2 (Linux) 활용 능력
 * Web과 board 연동 능력
 * Docker Container에 대한 이해와 활용
 * MQTT, InfluxDB, Grafana에 대한 이해
 * Web에 대한 이해 (HTML, HTTP - GET, POST)
 * Config mode에 대한 이
 * 팀원과의 소통을 통한 협업 능력

## 📌기대효과
 * 간편한 날씨와 대기상태 파악 가능 
 * 운동시, 자신의 몸 상태를 한눈에 볼 수 있어 적절한 운동을 즐길 수 있다.
 * 체온, 미세먼지 평균값 -> 사용자는 모니터링 시스템을 통해 자신의 건강 상태와 외부 환경 정보를 실시간으로 확인할 수 있습니다
 
## 🔨사용 보드
 * Esp8266

## ⚡사용 기술
 * Docker : MQTT, Influxdb, Grafana 서버 제작
 * HTTP : Web 통신 프로토콜
 * WIFI : 센서 원격 제어

## 📝사용언어
 * HTML
 * C : MQTT 통신, HTTP 통신, 센서 제어

## 🔆개발환경
 * Linux(AWS EC2)
 * Visual Studio Code
 
## 💡기능
* 기능 : 만보기, 기상청 날씨정보 실시간 DATA 출력, 체온 측정, 미세먼지 측정
<img width="416" alt="image" src="https://user-images.githubusercontent.com/102004234/232667637-f064386f-93fd-4854-a356-f93458b0af86.png">


* 기능 소개 

  * 만보기: 구글어시스턴트를 이용하여 음성인식 음악 스피커 구현
  * 기상청 날씨정보 실시간 DATA 출력 : 구글어시스턴트 서비스에 mqtt통신을 추가시켜 edge와 cloud node-red에서 LED 제어(이 외에 센서 추가하여 간편하게 등록 가능 )
  * 스마트 가로등 : 주택 집 외부 벽=>Lux센서를 이용하여 가로등(NeoPixel) edge NodeRed로 제어 구현
  * 미세먼지 알라미: 기상청 정보와 날씨 api 크롤링하여 Node-Red UI에 시각화 
  * 홈 관리 시스템: Node-Red UI를 이용한 홈 관리 시스템
  * 침입자 감지 메시지: 초음파 센서를 통해 침입자 감지 후 이메일로 메시지 전송



 ### Could server
>>뮤직 셀렉터, 미세먼지 알라미, 침입자 감지 시스템, 미니 IoT Controler-LED 제어

 ### Edge server
>>미니 IoT Controler-google assistant mqtt publish, 스마트 가로등

## 1) 주택 집 외부 벽 가로등 구현
