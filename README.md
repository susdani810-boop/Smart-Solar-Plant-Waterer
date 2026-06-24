# My ESP32 Smart Solar Irrigator (with some budget maker hacks!) 🌿☀️

I wanted to share my latest DIY project: a fully automated, solar-powered dual-pump irrigation system built to keep my plants alive and well! 

Everything is controlled by an **ESP32**, an **RTC (DS3231)** module for precise timing, and a **dual-channel relay module** to trigger the pumps. 

Since I'm still waiting for a few components, I had to come up with some pretty cool "hacks" along the way to test everything:
1. **The "No-Battery" Test:** I don't have my lithium batteries yet, but I couldn't wait to test the hardware. I hooked everything up to an UPS module powered by a powerbank. All the LEDs lit up perfectly on the first try!
2. **Serial Monitor Control:** To test the dual-pump setup without changing the schedule in my main code, I built an interactive serial test. Typing `i` in the Arduino IDE triggers Pump 1 for a crisp 10-second run. To test Pump 2 without code edits, I just swapped the terminal wires and triggered it through the same command. Both pumps are working flawlessly!

**Next steps:** Testing the solar panel out in the sun (using the UPS module as a 5V regulator to see if it charges a phone first) and dropping the lithium cells in to make it 100% off-grid.

Let me know what you think or if you have any tips for solar power optimization! 🚀

Ecco la lista dei componenti pronta da copiare e incollare direttamente su GitHub o dove preferisci, configurata con le parole chiave esatte per la ricerca su AliExpress e un calcolo che rientra perfettamente nel budget che hai chiesto!

🛒 Components List & AliExpress Search Terms
Here is the complete part list for this project. If you want to replicate it, you can find every component on AliExpress using the exact search terms provided in the parentheses:

-Microcontroller: ESP32 Development Board - 30 or 38 pins (ESP32 NodeMCU ESP-WROOM-32) — ~€4.00

-Real-Time Clock: DS3231 RTC Module with battery (DS3231 RTC module High Precision) — ~€2.50

-Relay Module: 2-Channel Relay Module 5V with Optocoupler (2 channel relay module 5v) — ~€2.00

-Water Pumps: 2x 5V/6V Mini Submersible Water Pumps (5v mini submersible water pump) — ~€4.50 total (€2.25 each)

-Power / Battery Management: 18650 Battery UPS Charging Board v3 (18650 UPS shield V3 ESP32 5V) — ~€4.50

-Power Source: 2x 18650 Rechargeable Lithium Batteries 3.7V (18650 battery rechargeable 3.7v) — ~€8.00 total

-Solar Panel: 5V 5W or 6V 6W Monocrystalline Solar Panel with bare wires (5v 5w solar panel mini) — ~€6.00

-Water Hoses: 2-3 meters of 7mm Silicone/PVC Hose (7mm water pump hose silicone) — ~€3.00

-Project Box: Waterproof Plastic Enclosure Box (waterproof plastic project box enclosure) — ~€5.00

-Cables & Accessories: Breadboard jumper wires, terminal blocks, and small hardware (jumper wires male to male female) — ~€3.50

💰 Estimated Total Budget
Total Estimated Cost: ~€43.00 – €48.00 (with free or budget shipping options on AliExpress)
