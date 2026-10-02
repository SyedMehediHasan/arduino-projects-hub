# LED Blink Control

This is a beginner Arduino project that makes an LED blink on and off repeatedly.

## Components
- Arduino Uno
- 1 LED
- 1 x 220Ω resistor
- Jumper wires

## Wiring
- LED anode (+) -> Digital Pin 13
- LED cathode (-) -> 220Ω resistor -> GND

## Code
```cpp
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(500);
  digitalWrite(13, LOW);
  delay(500);
}
```

## Notes
This project helps beginners understand:
- `pinMode()`
- `digitalWrite()`
- `delay()`
