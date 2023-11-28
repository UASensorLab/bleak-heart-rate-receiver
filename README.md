# bleak-heart-rate-receiver
Bleak code that connects to any commercial sensor that streams heart rate over GATT according to bluetooth specifications and parses data.
If the sensor also sends sensor contact detection bit, energy expended, or RR intervals, it will also parse them.

---
Known to work with:
- EliteHRV CorSense
- Polar H9
- Polar H10
- Polar OH1+
- Polar Verity Sense

---
Usage:
1. Scan for all BLE devices by running bleak_scanner.py.
2. Find the name/address of your device from the output.
1. Open bleak_heart_rate_receiver.py, put in the unique name of your device, and run.
