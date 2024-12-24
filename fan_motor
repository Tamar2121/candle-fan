// Define L9110 control pins
const int motorIA = 3; // Connect to IA on L9110
const int motorIB = 5; // Connect to IB on L9110

void setup() {
  // Set motor control pins as outputs
  pinMode(motorIA, OUTPUT);
  pinMode(motorIB, OUTPUT); 
}

void run_fan(){
 // Set motor to rotate clockwise
  analogWrite(motorIA, 225); // Full speed
  digitalWrite(motorIB, LOW);
  //delay(5000); // Run for 5 seconds

  // Set motor to rotate anticlockwise
  //digitalWrite(motorIA, LOW);
 // analogWrite(motorIB, 255); // Full speed
 // delay(2000); // Run for 2 seconds

  // Stop the motor
  /*digitalWrite(motorIA, LOW);
  digitalWrite(motorIB, LOW);
  delay(1000); // Stop for 1 second*/

}        
void loop(){
  run_fan();
}
