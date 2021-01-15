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





