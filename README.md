# basic-Arduino-2

## Hello Arduino


### Description

### Code
/*

*/
 
void setup() {
  Serial.begin(9600); 
}
void loop() {
  Serial.println("Hello World");
  delay(9600);
}
### Wirring 
### Reflection





# basic-Arduino-2

## button-Activaded LED


### Description
Prees the button to turn the LED on.

### Code





/*
  Enayatulllah
  button LED assignmennt
  push the button LED turns on
*/
int LEDpinBLUE = 12;
int buttonpin1 = 2;
int LEDpinRED = 13;
int buttonpin2 = 4;
int buttonstate = 0;

void setup() {
  pinMode(LEDpinBLUE, OUTPUT);
  pinMode(buttonpin1, INPUT); 
  pinMode(LEDpinRED, OUTPUT);
  pinMode(buttonpin2, INPUT);
  Serial.begin(9600);


}

void loop() {
  buttonstate = digitalRead(buttonpin1);
  Serial.println(buttonstate);
  if (buttonstate == 1) {
    digitalWrite(LEDpinBLUE, HIGH);
  }
  else {
    digitalWrite(LEDpinBLUE, LOW);
  }
  
  buttonstate = digitalRead(buttonpin2);
  Serial.println(buttonstate);
  if (buttonstate == 1) {
    digitalWrite(LEDpinRED, HIGH);
  }
  else {
    digitalWrite(LEDpinRED, LOW);
  }
}
/*
/*
  Enayatulllah
  button LED assignmennt
  push the button LED turns on
*/
int LEDpin = 12;
int buttonpin = 2;
int buttonstate = 0;

void setup() {
  pinMode(LEDpin, OUTPUT);
  pinMode(buttonpin, INPUT);
  Serial.begin(9600);


}

void loop() {
  buttonstate = digitalRead(buttonpin);
  Serial.println(buttonstate);
  if (buttonstate == 1) {
    digitalWrite(LEDpin, HIGH);
  }
  else {
    digitalWrite(LEDpin, LOW);
  }


### Wirring 


### Reflection

### Imige: https://scontent.xx.fbcdn.net/v/t1.15752-9/138463745_1974246226049844_3320621944882217791_n.jpg?_nc_cat=104&ccb=2&_nc_sid=58c789&_nc_ohc=UwVo7Sqh0HQAX9Aoy2U&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=414583b0cb83c13fdd10a720bd3df1ab&oe=6027DEFD

https://scontent.xx.fbcdn.net/v/t1.15752-9/139786470_884136242353543_5462664106954042176_n.jpg?_nc_cat=103&ccb=2&_nc_sid=58c789&_nc_ohc=HmEKVOfjdIkAX-oI0fo&_nc_ht=scontent.xx&oh=e0fe11be4f4464262acc1ca7d7fdf1df&oe=602C76B8



