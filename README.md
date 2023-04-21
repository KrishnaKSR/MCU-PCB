![Powerful Kasi](https://user-images.githubusercontent.com/131287772/233634466-f5d9399b-fecb-48e5-87be-6c9bcff3d3ce.png)
![Super Jaagub-Snicket](https://user-images.githubusercontent.com/131287772/233634527-46b58f0c-2da5-4c7e-8113-e14e64dbf6d1.png)
# MCU-PCB
![Incredible Krunk](https://user-images.githubusercontent.com/131287772/233719177-16710aa9-d477-4b5d-b674-f8624b058721.png)

//Code for servo 
#include <Servo.h>

Servo s;

void setup()
{
  s.attach(10);
}

void loop()
{
  s.write(0);
  delay(1000);
  s.write(180);
  delay(1000);
}
