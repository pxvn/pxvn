<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=200&color=gradient&text=PAVAN%20K.&textBg=false&animation=fadeIn&fontColor=fff&fontSize=50&desc=&descAlignY=65"/>
</div>

<p align="center">
  <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="15px"> 
  Building Robots & IoT Solutions
  <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="15px">
</p>

## <p align="center">  IoT Development | Robotics Projects | Embedded Systems | Maker </p>


## 👨‍💻 About Me

```cpp
// profile.ino
#include <Arduino.h>

class Student {
private:
    String name = "Pavan Kalsariya";
    String university = "Parul University";
    String focus = "Computer Engineering";
    
public:
    void setup() {
        Serial.begin(115200);
        Serial.println("Student profile initialized...");
        printCurrentWork();
    }
    
    void printCurrentWork() {
        Serial.println("Currently building:");
        Serial.println("- Underwater navigation robot");
        Serial.println("- Energy management systems");
        Serial.println("- Agricultural monitoring rover");
        Serial.println("- Desktop companion bot (CAKE)");
    }
    
    void loop() {
        Serial.println("Learning, building, growing...");
        delay(1000);
    }
};

Student me;
