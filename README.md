![Ultrasonic Sensor Circuit](ultrasonic_circuit.png)

This electronic circuit uses an **ultrasonic sensor** (with Trig and Echo pins) to measure the distance between the sensor and an object. The sensor sends sound waves, and the Echo pin detects the time it takes for the waves to bounce back. The Arduino calculates the distance based on this time.

If the measured distance is less than 70 cm, the built-in **LED** on the Arduino board turns ON. Otherwise, the LED remains OFF. This can be useful for applications like proximity detection or obstacle avoidance. The circuit is simple, requiring only the ultrasonic sensor and the Arduino board, and it displays the distance in real time through the Serial Monitor.

Here’s the Tinkercad link to test it: [https://www.tinkercad.com/things/5iTgPs71th6-led-and-ultrasonic?sharecode=4ULStZLw5jrlYa394ur7zPk_JiDww6piXZtdbG6WqMA].
