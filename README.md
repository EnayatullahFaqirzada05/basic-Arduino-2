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
}
