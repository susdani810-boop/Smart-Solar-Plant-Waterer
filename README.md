# My ESP32 Smart Solar Irrigator (with some budget maker hacks!) 🌿☀️

I wanted to share my latest DIY project: a fully automated, solar-powered dual-pump irrigation system built to keep my plants alive and well! 

Everything is controlled by an **ESP32**, an **RTC (DS3231)** module for precise timing, and a **dual-channel relay module** to trigger the pumps. 

Since I'm still waiting for a few components, I had to come up with some pretty cool "hacks" along the way to test everything:
1. **The "No-Battery" Test:** I don't have my lithium batteries yet, but I couldn't wait to test the hardware. I hooked everything up to an UPS module powered by a powerbank. All the LEDs lit up perfectly on the first try!
2. **Serial Monitor Control:** To test the dual-pump setup without changing the schedule in my main code, I built an interactive serial test. Typing `i` in the Arduino IDE triggers Pump 1 for a crisp 10-second run. To test Pump 2 without code edits, I just swapped the terminal wires and triggered it through the same command. Both pumps are working flawlessly!

**Next steps:** Testing the solar panel out in the sun (using the UPS module as a 5V regulator to see if it charges a phone first) and dropping the lithium cells in to make it 100% off-grid.

Let me know what you think or if you have any tips for solar power optimization! 🚀
