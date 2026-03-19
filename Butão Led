int bp = 10;
int lp= 9;
int eb = 0;

void setup() {
  pinMode(bp,INPUT);
  pinMode(lp,OUTPUT);


}

void loop() {
  eb = digitalRead(bp);
  if (eb == HIGH){
    digitalWrite(lp,HIGH);
    delay(100);
    digitalWrite(lp,LOW);
    delay(100);
  }
  else {
    digitalWrite(lp,LOW);
  }



}

