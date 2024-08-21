# EX.NO.1-PIOT
# SOURCE CODE
```
const int ledPin = 12;   
const int buttonPin = 13;

void setup() {
  pinMode(ledPin, OUTPUT);    
  pinMode(buttonPin, INPUT_PULLUP); 
}

void loop() {
  int buttonState = digitalRead(buttonPin); 
  
  if (buttonState == LOW) { 
    digitalWrite(ledPin, LOW);
  } else { 
    digitalWrite(ledPin, HIGH);
  }
}
```
# OUTPUT:
![Screenshot 2024-08-21 093738](https://github.com/user-attachments/assets/d7902e4c-fc65-454a-b2aa-dbee4eb7134a)
![Screenshot 2024-08-21 093725](https://github.com/user-attachments/assets/81bd9c3c-9bd2-4a42-8b24-20c7dcdc9452)

