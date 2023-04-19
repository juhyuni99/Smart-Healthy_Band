# IoT Smart_Healthy Band & Monitoring System

> 🖥️MQTT 통신, Web을 이용한 IoT Healthy_band & Monitoring System🖥️
* 프로젝트 기간 : 2020.10 ~ 2020.12

## 👋개발 배경 : 바쁜 현대사회에서 자신의 건강을 미처 챙기지 못하는 사람들이 증가, 사회적으로 미세먼지의 농도가 높아지고, 코로나 전염도 심각해지고 있습니다. 이에 여러 센서가 장착된 mini IoT healthy band를 통해 자신의 건강과 외부환경을 확인할 수 있도록 제작하였습니다.

## 📚얻은 역량
 * MQTT, Node-Red 활용 능력
 * Linux 환경에서의 프로그래밍 능력
 * IBM Cloud 활용 능력
 * Raspberry pi 활용 능력
 * Python virtual environment 활용 능력
 * Docker Container 활용
 * Google Assistant 활용
 * Cloud Server, Edge Server 에 대한 이해와 활용
 * 팀을 이끌어가는 능력
 * 팀원과의 소통을 통한 협업 능력

## 기대효과
 * 간편한 날씨와 대기상태 파악 가능
 * 운동시, 자신의 몸 상태를 한눈에 볼 수 있어 적절한 운동을 즐길 수 있다.
 
## 🔨사용 보드
 * Raspberry pi3 : 마이크 제어, 스피커 제어, MQTT 통신 서버 제어, Node-Red
 * Esp8266 : MQTT 통신, Neopixel

## ⚡사용 기술
 * Docker : MQTT 서버 구축
 * Google Assistant : 음성 인식
 * Bluetooth : Bluetooth 스피커 연결

## 📝사용언어
 * Python
 * C++

## 🔆개발환경
 * Raspbian
 * Visual Studio Code
 
## 💡기능
* 기능 : 미세먼지 알라미, 뮤직 셀렉터, 스마트 가로등, 침입자 감지 메시지, 홈 관리 시스템, 미니 IoT Controler
<img width="416" alt="image" src="https://user-images.githubusercontent.com/102004234/232667637-f064386f-93fd-4854-a356-f93458b0af86.png">


* 기능 소개 

  * 뮤직 셀렉터: 구글어시스턴트를 이용하여 음성인식 음악 스피커 구현
  * 미니 IoT Controler : 구글어시스턴트 서비스에 mqtt통신을 추가시켜 edge와 cloud node-red에서 LED 제어(이 외에 센서 추가하여 간편하게 등록 가능 )
  * 스마트 가로등 : 주택 집 외부 벽=>Lux센서를 이용하여 가로등(NeoPixel) edge NodeRed로 제어 구현
  * 미세먼지 알라미: 기상청 정보와 날씨 api 크롤링하여 Node-Red UI에 시각화 
  * 홈 관리 시스템: Node-Red UI를 이용한 홈 관리 시스템
  * 침입자 감지 메시지: 초음파 센서를 통해 침입자 감지 후 이메일로 메시지 전송



 ### Could server
>>뮤직 셀렉터, 미세먼지 알라미, 침입자 감지 시스템, 미니 IoT Controler-LED 제어

 ### Edge server
>>미니 IoT Controler-google assistant mqtt publish, 스마트 가로등

## 1) 주택 집 외부 벽 가로등 구현
