# 1895-assignment-15
Repository for the first github assignment in 1895
Owen is out of twon at a wedding so this asignemnt will be just me and Richard

# Dave Jones

# Source code
// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
  pinMode(2, INPUT);
}

// the loop function runs over and over again forever
void loop() {
  if(digitalRead(2 == HIGH)){
    digitalWrite(13, HIGH);   // turn the LED on (HIGH is the voltage level)
    delay(500);                       // wait for a second
    digitalWrite(13, LOW);    // turn the LED off by making the voltage LOW
    delay(500);                       // wait for a second
    digitalWrite(12, HIGH);   // turn the LED on (HIGH is the voltage level)
    delay(500);                       // wait for a second
    digitalWrite(12, LOW);    // turn the LED off by making the voltage LOW
    delay(500);                       // wait for a second
    digitalWrite(11, HIGH);   // turn the LED on (HIGH is the voltage level)
    delay(500);                       // wait for a second
    digitalWrite(11, LOW);    // turn the LED off by making the voltage LOW
    delay(500);                       // wait for a second
  }
  else{
    digitalWrite(13,LOW);
    digitalWrite(12,LOW);
    digitalWrite(11,LOW);
  }
}
