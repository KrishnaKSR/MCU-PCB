![Sizzling Wolt](https://user-images.githubusercontent.com/131287772/233764128-8afde8dd-0b67-48f6-9916-c7abcb09ec7b.png)
![Sizzling Gaaris-Gogo](https://user-images.githubusercontent.com/131287772/233758694-482f9f12-3b08-4eba-9352-755a0a754406.png)
![Powerful Kasi](https://user-images.githubusercontent.com/131287772/233634466-f5d9399b-fecb-48e5-87be-6c9bcff3d3ce.png)
![Super Jaagub-Snicket](https://user-images.githubusercontent.com/131287772/233634527-46b58f0c-2da5-4c7e-8113-e14e64dbf6d1.png)
# MCU-PCB
//NIGHT LED
int sensePin = 0 ;
int ledPin = 9 ;

void setup(){
  analogReference(DEFAULT); // not necessary
  pinMode(ledPin,OUTPUT);
}

void loop()
{
  int val = analogRead(sensePin);

  if (val < 800) digitalWrite(ledPin,HIGH);
  else digitalWrite(ledPin,LOW);

}
