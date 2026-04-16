# 🤖REMOTE CONTROL ROBOT USING ESP8266 WITH L298N🚚
>> # INTRODUCTION

 An RC (remote-controlled) robot is a simple robotic system that can be controlled wirelessly from a distance using a remote device such as a smartphone, joystick, or web interface. Instead of manual operation, it receives commands through a wireless communication module like the ESP8266, which processes the signals and controls the movement of the robot.

 The robot typically uses a motor driver such as the L298N to control DC motors that drive the wheels, allowing it to move forward, backward, and turn left or right. This setup makes it a practical project for learning basic robotics concepts such as motor control, wireless communication, and embedded programming.
 __________________________________________________________________________________________________________________________________________________________________

 ># 🖋️ESP8266 MODULE

 The ESP8266 is a low-cost WiFi microcontroller that acts as the “brain” of an RC robot. It receives commands wirelessly from a phone or controller and processes them to control the robot’s movements. By sending signals to a motor driver like the L298N, it manages the speed and direction of the DC motors, allowing the robot to move forward, backward, and turn. Its built-in WiFi makes it ideal for building simple and efficient wireless control systems for robotics projects.


## 👉SPECIFICATION

➥ 1. Microcontroller: 32-bit Tensilica L106

➥ 2. Operating Voltage: 3.3V (NOT 5V tolerant)

➥ 3. Input Voltage (NodeMCU board): 5V via USB (regulated to 3.3V)

➥ 4. Clock Speed: 80 MHz (can go up to 160 MHz)

➥ 5. WiFi Standard: IEEE 802.11 b/g/n (2.4 GHz)

➥ 6. GPIO Pins: Around 11 usable digital I/O pins (varies by board)

➥ 7. ADC: 1 analog input (0–1V range)

➥ 8. Flash Memory: Typically 4MB (varies by module)

➥ 9. Communication Protocols: UART, SPI, I2C, PWM


 ## 👉CHARACTERISTICS


➥ 1. Built-in WiFi: Allows direct wireless communication without extra modules

➥ 2. Low Cost: Very affordable, ideal for student and hobby projects

➥ 3. Low Power Consumption: Efficient for small IoT and robotics systems

➥ 4. Compact Size: Small and easy to integrate into circuits

➥ 5. Programmable with Arduino IDE: Easy for beginners to use

➥ 6. Suitable for IoT: Commonly used in smart devices and wireless control systems

➥ 7. Limited GPIO Voltage (3.3V): Requires caution when connecting to 5V components


># 🖋️L298N Motor Driver

 The L298N Motor Driver Module is a dual H-bridge motor driver commonly used in RC robots and other mobile robotics projects to control DC motors. It serves as an interface between a low-power microcontroller such as an ESP8266 or Arduino and high-power motors, allowing the robot to move without damaging the controller. In an RC robot system, its main function is to control both the direction and speed of the motors, enabling movements such as forward, backward, left turn, right turn, and stop. It achieves this by receiving digital signals from the microcontroller and then switching the motor voltage polarity internally to control rotation direction. Additionally, it supports PWM (Pulse Width Modulation), which allows smooth speed control by adjusting the power delivered to the motors. The L298N is also responsible for handling higher voltage and current from an external power supply, protecting the microcontroller from electrical damage while ensuring stable motor operation.

 The L298N is widely used in 2-wheel RC robots because it can independently drive two DC motors, making it ideal for differential steering systems. It is designed to work with motor supply voltages ranging from 7V to 35V and can typically handle up to 2A continuous current per channel, depending on cooling conditions. The module includes built-in protection features such as flyback diodes to prevent voltage spikes caused by motor operation, as well as a heat sink to manage thermal dissipation. Because of its simplicity, affordability, and compatibility with many microcontrollers, the L298N remains one of the most popular motor drivers in beginner to intermediate robotics projects, especially in educational RC robot designs.


## 👉SPECIFICATION


➥ 1. Driver Type: Dual full H-Bridge motor driver

➥ 2. Motor Channels: 2 DC motors or 1 stepper motor

➥ 3. Operating Voltage (Logic): 5V

➥ 4. Motor Supply Voltage: 7V – 35V

➥ 5. Continuous Current per Channel: 2A

➥ 6. Peak Current per Channel: up to 3A (short bursts)

➥ 7. Logic Input Voltage: 5V TTL compatible

➥ 8. PWM Frequency Support: Yes (speed control)

➥ 9. Onboard Regulator: 5V regulator (some modules include jumper control)

➥ 10. Protection Features: Overheating protection (basic), voltage drop protection (diode-based)


 ## 👉CHARACTERISTICS


➥ 1. Based on dual H-bridge circuit design for full motor direction control

➥ 2. Can drive 2 DC motors independently or 1 stepper motor

➥ 3. Compatible with 5V TTL logic signals from microcontrollers like ESP8266 and Arduino

➥ 4. Supports motor supply voltage from 7V to 35V

➥ 5. Provides up to 2A continuous current per channel (with proper cooling)

➥ 6. Allows PWM control for adjustable motor speed

➥ 7. Includes built-in 5V regulator (on most modules) for logic power supply

➥ 8. Equipped with protection diodes against back EMF from motors

➥ 9. Uses a heatsink for thermal management during operation

➥ 10. Simple and widely used in RC robots and educational robotics projects

➥ 11. Low cost and easily available, making it ideal for beginners

➥ 12. Suitable for differential drive RC robot systems (left and right motor control)

 __________________________________________________________________________________________________________________________________________________________________


>> # ▶CONCEPTUAL FRAMEWORK

<img width="889" height="446" alt="image" src="https://github.com/user-attachments/assets/91a7ea2b-5c88-41be-857b-42b0850d9aea" />

 __________________________________________________________________________________________________________________________________________________________________


>> # ▶BLOCK DiAGRAM

<img width="1022" height="336" alt="image" src="https://github.com/user-attachments/assets/15929d39-d6b5-4de7-ac79-9658dc2fe1f6" />

 __________________________________________________________________________________________________________________________________________________________________


>> # 🛠️LIST OF COMPONENT


| QUANTITY | Component | Description | Amount |
|-----|-----------|-------------|-------------|
| 1 | ESP8266 NodeMCU | Main WiFi microcontroller | 135 |
| 1 | L298N Motor Driver | Controls direction and speed of motors | 75 |
| 2 | Wheel (65mm) | Robot movement support | 250 |
| 2 | DC Gear Motor (915 RPM) | Provides torque and motion | 600 |
| 1 | Metal Ball Caster | Front/Rear support wheel | 62 |
| 2 | Hexagonal Brass Copper (4mm) | Mechanical spacers/support | 98 |
| 3 | 18650 Lithium-ion Battery (3.7V 2200mAh) | Power supply | 300 |
| 1 | Battery Holder | Holds and connects battery cells | 70 |
| FEW | Jumper Wires | Electrical connections | 0.00 |
| FEW | Solid Wire Gauge 22 | Internal wiring | 0.00 |
| 1 | Acrylic (Chassis) | Robot body structure | 150 |

 __________________________________________________________________________________________________________________________________________________________________

>> # 🤖PROJECT PICTURE

## TOPVIEW

<img width="550" height="500" alt="image" src="https://github.com/user-attachments/assets/e99cf035-b42b-446a-b593-4cc54c20b482" />


## SIDE VIEW

<img width="550" height="500" alt="image" src="https://github.com/user-attachments/assets/dae0676a-c5bb-4a97-9dad-5ca6fb5aec85" />


## FRONT VIEW 

<img width="550" height="500" alt="image" src="https://github.com/user-attachments/assets/fecaa076-ea4e-4872-819a-c888a85e75e6" />


## ISOMETRIC 

<img width="550" height="500" alt="image" src="https://github.com/user-attachments/assets/b8137f50-26d4-4d96-a00c-d426005e7b5e" />

## BACK VIEW

<img width="550" height="500" alt="image" src="https://github.com/user-attachments/assets/4946971f-b9b6-4200-9bf2-83fc459eada1" />

 __________________________________________________________________________________________________________________________________________________________________

>> # 👩🏻‍💻ARDUINO CODES


#define ENA   14                    
#define IN_1  15                 
#define IN_3  2           
         

#include <ESP8266WiFi.h>
#include <WiFiClient.h> 
#include <ESP8266WebServer.h>

String command;            
int speedCar = 915;         
int speed_Coeff = 3;

const char* ssid = "Wifi Car";
ESP8266WebServer server(80);

void setup() {
 
 pinMode(ENA, OUTPUT);  
 pinMode(IN_1, OUTPUT);
 pinMode(IN_3, OUTPUT);
  
  
  Serial.begin(115200);
  


  WiFi.mode(WIFI_AP);
  WiFi.softAP(ssid);

  IPAddress myIP = WiFi.softAPIP();
  Serial.print("AP IP address: ");
  Serial.println(myIP);
 

     server.on ( "/", HTTP_handleRoot );
     server.onNotFound ( HTTP_handleRoot );
     server.begin();    
}

void goAhead(){ 

      digitalWrite(IN_1, HIGH);
      digitalWrite(IN_3, HIGH);
      analogWrite(ENA, speedCar);

  }

void goBack(){ 

      digitalWrite(IN_1, LOW);
      digitalWrite(IN_3, LOW);
      analogWrite(ENA, speedCar);
  }

void goRight(){ 

      digitalWrite(IN_1, HIGH);
      digitalWrite(IN_3, LOW);
      analogWrite(ENA, speedCar);
  }

void goLeft(){

      digitalWrite(IN_1, LOW);
      digitalWrite(IN_3, HIGH);
      analogWrite(ENA, speedCar);
  }

void goAheadRight(){
      
      digitalWrite(IN_1, LOW);
      digitalWrite(IN_3, HIGH);
      analogWrite(ENA, speedCar/speed_Coeff);
   }

void goAheadLeft(){

      digitalWrite(IN_1, HIGH);
      digitalWrite(IN_3, LOW);
      analogWrite(ENA, speedCar/speed_Coeff);
  }

void goBackRight(){ 

      digitalWrite(IN_1, LOW);
      digitalWrite(IN_3, HIGH);
      analogWrite(ENA, speedCar/speed_Coeff);
  }

void goBackLeft(){ 

      digitalWrite(IN_1, HIGH);
      digitalWrite(IN_3, LOW);
      analogWrite(ENA, speedCar);
  }

void stopRobot(){  

      digitalWrite(IN_1, LOW);
      digitalWrite(IN_3, LOW);
      analogWrite(ENA, speedCar);
 }

void loop() {
    server.handleClient();
    
      command = server.arg("State");
      if (command == "F") goAhead();
      else if (command == "B") goBack();
      else if (command == "L") goLeft();
      else if (command == "R") goRight();
      else if (command == "I") goAheadRight();
      else if (command == "G") goAheadLeft();
      else if (command == "J") goBackRight();
      else if (command == "H") goBackLeft();
      else if (command == "0") speedCar = 400;
      else if (command == "1") speedCar = 470;
      else if (command == "2") speedCar = 540;
      else if (command == "3") speedCar = 610;
      else if (command == "4") speedCar = 680;
      else if (command == "5") speedCar = 750;
      else if (command == "6") speedCar = 820;
      else if (command == "7") speedCar = 890;
      else if (command == "8") speedCar = 960;
      else if (command == "9") speedCar = 1023;
      else if (command == "S") stopRobot();
}

void HTTP_handleRoot(void) {

if( server.hasArg("State") ){
       Serial.println(server.arg("State"));
  }
  server.send ( 200, "text/html", "" );
  delay(1);
}

