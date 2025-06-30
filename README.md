# Week 1 - LED Blink with ESP32 (Wokwi)

This is my first embedded systems project using **ESP32** on **Wokwi Simulator**.  
It blinks an LED connected to GPIO pin 2 of the ESP32.

---

## 🔧 Components Used
- ESP32 Dev Module
- Onboard LED (or external via GPIO)
- Wokwi Simulator

---

## 🧠 Skills Practiced
- Digital Output using `digitalWrite()`
- GPIO Configuration
- `delay()` usage for timing

---

## 📷 Circuit Simulation
![Wokwi Circuit Screenshot](link-to-image-if-uploaded)

---

## 🚀 Code Snippet (Main logic)
```cpp
void setup() {
  pinMode(2, OUTPUT);
}

void loop() {
  digitalWrite(2, HIGH); // Turn LED ON
  delay(1000);           // Wait 1 second
  digitalWrite(2, LOW);  // Turn LED OFF
  delay(1000);           // Wait 1 second
}



