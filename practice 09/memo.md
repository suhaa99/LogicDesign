# Lab 09
## 실습 내용
### **리모콘 송신 신호**

#### **Submodule 1(nco)** : 주파수를 조절해서 CLK 설정

#### **Submodule 2(fnd_dec)** :  0에서9, 그리고 A에서F를 나타내는 4bit 입력 신호를 받아 7bit FND  segment  값 출력

#### **Submodule 3(led_disp)**: 각 seg 값을 LED화면에 출력

#### **Submodule 4(ir_rx)**: 리모콘 송신 신호를 받아 NEC 적외선 통신 규약에 맞는 data값 출력

#### **Top Module** : 리모콘의 송신 신호를 받아 FPGA의 디스플레이에 각 값 출력

### FPGA 실습 (팀) : 리모콘 송신신호의 수신값 Display


 ### **Top Module 의 DUT/TestBench Code 및 Waveform 검증**
 
![](https://github.com/suhaa99/LogicDesign/blob/master/practice%2009/capture/wave_total.PNG)

![](https://github.com/suhaa99/LogicDesign/blob/master/practice%2009/capture/%EC%BA%A1%EC%B2%98.PNG)



