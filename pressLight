/*
 * date:29.09.2020
 * author: ibrahim cansun
 * purpose: if i am pressing button, led is lighting
 */
const int LedPin = 12;
const int butonPin = 13;
int butonDurumu = 0;

void setup() {
  pinMode(butonPin, INPUT);
  digitalWrite(butonPin, HIGH);
  pinMode(Ledpin, OUTPUT);
}

void loop() {
  butonDurumu = digitalRead(butonPin);
  if(butonDurumu == HIGH){
    digitalWrite(Ledpin, HIGH);//lighting
  }
  else{
    digitalWrite(Ledpin, LOW);
  }
}
