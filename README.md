# Micro-bit Projects  
  
## Summary

Project collection built as part of the **SFI WEAVE 2022** outreach programme (Science Foundation Ireland). I served as **Showcase Station Coordinator (May 2022)** for a micro:bit station that introduced primary school students and teachers to coding, electronics, and computational thinking through hands-on projects.
                                                                                                                                                      The collection covers input (buttons, accelerometer, microphone, light sensor, compass), output (LED display, sound), and inter-device messaging (radio groups), packaged as small self-contained programs suitable for live demonstration with children.
                                                                                                                                                      Stack: micro:bit (v1 and v2), MakeCode / JavaScript, embedded sensors and radio.                                                                                                                                   
  
## Projects                                                                                                                                                                                                        
                  
  | Project | What it does |                                                                                                                                                                                         
  |---|---|
  | **Paper Scissors Rock** | Classic game logic, randomised choice on shake |                                                                                                                                       
  | **Graphical Dice** | Shows a random number 1–6 on shake, animated like a real die |                                                                                                                              
  | **Clap Smile** *(v2+)* | Detects claps via microphone — happy face on clap, sad face in silence (threshold 200 Hz) |                                                                                             
  | **Sound Logger** | Live bar-chart display of ambient sound level |                                                                                                                                               
  | **Compass** | Shows direction and angle on Button A; sounds when facing East. First run requires tilting to fill the screen |                                                                                    
  | **Square of a Number** | Button A increments the number (1–25), Button B shows its square, A+B resets to 1 |                                                                                                     
  | **Thermometer** | Button A shows temperature in Celsius; Button B converts to Fahrenheit |                                                                                                                       
  | **Stopwatch** | Lap timer with sound on logo touch *(v2 only)*; alternate version uses A+B button |                                                                                                              
  | **Emoji Sender** | Button A picks a random emoji; shake broadcasts it to group ID 105 |                                                                                                                          
  | **Happy Check** | A+B shows "HAPPY?", shake sends the question to group ID 110, Button A replies YES, Button B replies NO |                                                                                      
  | **Light Sensor Alarm** | Triggers an alarm and angry face when light > 50; Button A shows the live reading. Group ID 115 |                                                                                       
                                                                                                                                                                                                                     
## Context                                                                                                                                                                                                         
                                                                                                                                                                                                                     
The SFI WEAVE programme supports public engagement with science. This station was designed for primary-school showcase events — projects had to be **immediately understandable to a 9-year-old**, **resilient under demo conditions**, and **demonstrate one concept at a time** (sound, light, motion, messaging).
