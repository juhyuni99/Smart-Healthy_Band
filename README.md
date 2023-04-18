# IoT Smart_Healthy Band & Monitoring System

> 🏡MQTT통신, Node-Red 환경을 이용한 IoT 스마트 홈 제작🏡
* 프로젝트 기간 : 2022.05 ~ 2022.06

* 기획 의도 : 주택에 거주하는 1인 가구를 대상으로 보다 편리하고 안전하게 생활할 수 있도록 다양한 기능을 갖춘 스마트 홈을 제작함. 자동제어, 관리 시스템, 편의 시스템에 초점을 맞춤.

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
