NAME: ASHIT BAPURAO CHOUDANTE
COMPANY: CODETECH IT SOLUTION
INTERN ID: CT0806HS
DURATION: 20 DEC 2024 TO 20 MARCH 2025

QUESTION: LED BLINKINDG WITH ARDUINO

#include<Arduino.h>
#include<Wire.h>
const int ledPin = 13; //Define led pin
void setup() {
  pinMode(ledPin, OUTPUT); //set the led pin as output
}

void loop() {
(ledPin, HIGH);//Turn on led on digital write
 delay(1000);//delay 1 sec
  
  
 (ledPin, LOW);//Turn off led
  
  delay(1000);//delay 1 sec
}
