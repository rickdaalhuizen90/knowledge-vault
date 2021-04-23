## Components
- Arduino Uno
- Breadboard
- USB Cable
- 220 Ohm Resistors
- Jumper Wire
- RGB LED

## Create a common ground
1. Use a jumper wire to connect the ground pin on the Arduino to a negative rail on the breadboard. This allow all the LED's to use the ground pin on the Arduino

2. Insert the resistors on the breadboard. Space the resistors with one leg to the negative rail.

3. The long lead of the 2 leads on the LED is the positive lead. Connecting it the wrong way will make the circuit not work.

4. Connect the negative lead on the horizontal rail in which the resistor is connected.

5. Complete the circuit


Program

```c
/* A simple program to sequentially turn on and turn off 3 LEDs */ 

int LED1 = 13;
int LED2 = 12;
int LED3 = 11;

void setup() {
   pinMode(LED1, OUTPUT);
   pinMode(LED2, OUTPUT);
   pinMode(LED3, OUTPUT);
}


void loop() {
  digitalWrite(LED1, HIGH);    // turn on LED1 
  delay(200);                  // wait for 200ms
  digitalWrite(LED2, HIGH);    // turn on LED2
  delay(200);                  // wait for 200ms       
  digitalWrite(LED3, HIGH);    // turn on LED3 
  delay(200);                  // wait for 200ms
  digitalWrite(LED1, LOW);     // turn off LED1
  delay(300);                  // wait for 300ms
  digitalWrite(LED2, LOW);     // turn off LED2
  delay(300);                  // wait for 300ms
  digitalWrite(LED3, LOW);     // turn off LED3
  delay(300);                  // wait for 300ms before running program all over again
}
```