Hey everyone, wanted to share my new project with you: An Automatic Solar powered double pump watering system that I made so my plants won’t die while I forget about them! 
Microcontroller used in this project is an ESP32 with an RTC module(DS3231) for precise time keeping and a 2 Channel relay module to power on/off the pumps.
Still waiting on some components , so i had to improvise some " to validate if everything worked:
Battery-less test: I still didn’t receive my lithium cells, but I couldn’t wait any longer to test this! So I connected everything to a UPS module, powered for now with a powerbank. Plugged everything in and it worked
Serial Monitor controle: I needed a way to test pumping without having to change the timer everytime in my main program. So i created an interactive serial test. Send an "i" through the Arduino IDE, Pump 1 powers ON for 10 seconds. To check if Pump 2 worked, i just switched the wires on both terminals and send the command again. Both pumps worked flawlessly!
Next upgrade: outdoor testing with the solar panel! I thought about using the UPS module as a 5V regulator to power everything, just to check if it can charge a cellphone first before getting into trouble. Then insert the lithium batteries and goodbye dependence to wall plug!
Please let me know what you guys think!
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


<img width="1500" height="1500" alt="image" src="https://github.com/user-attachments/assets/4f5e9a35-c0aa-4362-9acb-fd1eb05454f2" />





-Cables & Accessories: Breadboard jumper wires                                                                                                                    
https://it.aliexpress.com/item/1005009071621102.html?spm=a2g0o.productlist.main.2.68c2OxUyOxUymf&algo_pvid=c15dc057-94f0-4e4a-b859-d0cea2fd2075&algo_exp_id=c15dc057-94f0-4e4a-b859-d0cea2fd2075-1&pdp_ext_f=%7B%22order%22%3A%2211020%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%214.53%214.53%21%21%2134.22%2134.22%21%40211b61bb17823019045871820eacd1%2112000047812726049%21sea%21IT%216257754572%21X%211%210%21n_tag%3A-29919%3Bd%3Aec81afa4%3Bm03_new_user%3A-29895&curPageLogUid=TNkOxUB4RMaa&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009071621102%7C_p_origin_prod%3A   



<img width="220" height="220" alt="image" src="https://github.com/user-attachments/assets/5525f0f8-2892-4551-9e02-1d8a74c1953f" />







 (TAKE THE KIT:15cm KIT)

                                                                                  
💰 Estimated Total Budget
Total Estimated Cost: ~€50.00 – €90.00 (with free or budget shipping options on AliExpress)


I ADDED A FILE THAT EXPLAINS YOU HOW TO CONNECT THE CABLES IN THE RIGHT WAY, IT'S CALLED: Wiring & Connection Guide

I ALSO ADDED A FILE WITH THE CODE YOU HAVE TO PUT INTO ARDUINO IDE, IT'S CALLED:sketch_jun20aCOMPLETOFINITO.ino

Before you buy the things if you want to try it first you can by using this link: https://wokwi.com/projects/467719133093636097
HERE THERE ARE SOME PHOTOES ABOUT THE WOKWI WEBSITE:

<img width="762" height="657" alt="image" src="https://github.com/user-attachments/assets/6f4ba85a-7ec5-4bc8-ae76-59e02aec5f0e" />





I HAVE ALSO ADDED A VIDEO FOR THE COMPONENTS, BUT IT ISN'T A GOOD QUALITY, IF YOU WANT TO SEE IT HERE IT IS:
https://www.youtube.com/watch?v=XXyBIEqruyQ
