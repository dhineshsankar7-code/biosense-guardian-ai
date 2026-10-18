# Firmware integration placeholder

The current repository's web dashboard is a browser-only demo and does not receive data from an ESP32. Firmware should be added after the team selects and wires its sensor modules.

Before implementing firmware, document:
- ESP32 board model and pin map
- Exact heart-rate/SpO₂ sensor module and supported library
- Temperature sensor type and measurement location
- Sampling rate, calibration procedure, and known limitations
- Data transport protocol and API schema
- Wi-Fi credentials stored outside source control

Do not label readings as accurate until they have been tested against appropriate reference equipment. Never hard-code Wi-Fi passwords, API keys, or real patient details in public code.
