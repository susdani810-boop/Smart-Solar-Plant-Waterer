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

-Microcontroller: ESP32 Development Board - 30 or 38 pins (ESP32 NodeMCU ESP-WROOM-32)                              https://it.aliexpress.com/item/1005006763775106.html?spm=a2g0o.order_list.order_list_main.5.651e3696stFDGw&gatewayAdapt=glo2ita (TAKE IT THE ESP AND THE BREAKOUTBOARD) 

<img width="220" height="220" alt="image" src="https://github.com/user-attachments/assets/7150d87c-aa33-486f-a459-b55a8a2e276b" />
 




-Real-Time Clock: DS3231 RTC Module with battery (DS3231 RTC module High Precision)                                                                                https://it.aliexpress.com/item/1005007143596890.html?spm=a2g0o.order_list.order_list_main.29.651e3696stFDGw&gatewayAdapt=glo2ita


<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/98e19785-8760-4858-9036-cb0600805ce9" />




-Relay Module: 2-Channel Relay Module 5V with Optocoupler (2 channel relay module 5v)                                                                              https://it.aliexpress.com/item/1005007003070916.html?spm=a2g0o.order_list.order_list_main.40.651e3696stFDGw&gatewayAdapt=glo2ita  (HW-383A 5V) 


<img width="220" height="220" alt="image" src="https://github.com/user-attachments/assets/d3d58153-7205-4c24-9fed-1f37ce832b51" />




-Water Pumps: 2x 5V/6V Mini Submersible Water Pumps (5v mini submersible water pump)                                   https://it.aliexpress.com/item/1005006312871213.html?spm=a2g0o.order_list.order_list_main.11.651e3696stFDGw&gatewayAdapt=glo2ita




<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/a751ef22-924f-4f49-9961-01a1a4284a94" />





-Power / Battery Management: 18650 Battery UPS Charging Board v3 (18650 UPS shield V3 ESP32 5V)                                                                    https://it.aliexpress.com/item/1005007183936785.html?spm=a2g0o.order_list.order_list_main.41.651e3696stFDGw&gatewayAdapt=glo2ita        (HW-465A 5V)



<img width="220" height="220" alt="image" src="https://github.com/user-attachments/assets/78cd2c38-e661-48cd-b2cc-5649cc125e18" />





-Power Source: 2x 18650 Rechargeable Lithium Batteries 3.7V (18650 battery rechargeable 3.7v)                                                                      https://it.aliexpress.com/item/1005008078553867.html?spm=a2g0o.order_list.order_list_main.35.651e3696stFDGw&gatewayAdapt=glo2ita (2 PIECES)


<img width="220" height="220" alt="image" src="https://github.com/user-attachments/assets/caac236e-bcfe-43ec-ac93-3afb615df117" />





-Solar Panel: 5V 5W or 6V 6W Monocrystalline Solar Panel with bare wires (5v 5w solar panel mini)                                                     https://it.aliexpress.com/item/1005009517261067.html?spm=a2g0o.order_list.order_list_main.17.651e3696stFDGw&gatewayAdapt=glo2ita (I TOOK THE 35W)




<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/35b5367c-881f-4fc5-b5b5-3edb8f725f00" />






-Water Hoses: 2-3 meters of 7mm Silicone/PVC Hose (7mm water pump hose silicone) 
https://it.aliexpress.com/item/1005006190980723.html?spm=a2g0o.order_list.order_list_main.23.651e3696stFDGw&gatewayAdapt=glo2ita (YOU NEED 5 METER)



<img width="220" height="220" alt="image" src="https://github.com/user-attachments/assets/0671db32-ff2f-453b-9e27-2deebbc0579a" />






-Project Box: Waterproof Plastic Enclosure Box (waterproof plastic project box enclosure) 

-Cables & Accessories: Breadboard jumper wires                                                                                                                    
https://it.aliexpress.com/item/1005009071621102.html?spm=a2g0o.productlist.main.2.68c2OxUyOxUymf&algo_pvid=c15dc057-94f0-4e4a-b859-d0cea2fd2075&algo_exp_id=c15dc057-94f0-4e4a-b859-d0cea2fd2075-1&pdp_ext_f=%7B%22order%22%3A%2211020%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%214.53%214.53%21%21%2134.22%2134.22%21%40211b61bb17823019045871820eacd1%2112000047812726049%21sea%21IT%216257754572%21X%211%210%21n_tag%3A-29919%3Bd%3Aec81afa4%3Bm03_new_user%3A-29895&curPageLogUid=TNkOxUB4RMaa&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009071621102%7C_p_origin_prod%3A             
 (TAKE THE KIT:15cm KIT)

                                                                                  
💰 Estimated Total Budget
Total Estimated Cost: ~€50.00 – €90.00 (with free or budget shipping options on AliExpress)
I ADDED A FILE THAT EXPLAINS YOU HOW TO CONNECT THE CABLES IN THE RIGHT WAY
