void setup() {
  // put your setup code here, to run once:
  pinMode(7, OUTPUT);
  digitalWrite(7, 0);
  delay(1000);
}

void loop() {
  // put your main code here, to run repeatedly:
  int count = 0;

  while(1) {
    digitalWrite(7, 0);
    delay(100);
    digitalWrite(7, 1);
    delay(100);

    count++;

    if(count == 6) {
      while(1);
    }
  }
}
