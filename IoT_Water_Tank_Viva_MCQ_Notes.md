---
title: "IoT Viva MCQ Notes"
subtitle: "Case Study 3: Smart Water Tank Level Monitoring System"
author: "AquaWatch Project"
---

# How to remember

Read the question, answer it aloud, then use the memory line. These MCQs cover the water-tank case study and the related IoT syllabus.

# A. Case Study: Smart Water Tank

1. **What is the main problem in the case study?**
   - A. Tanks have no water pipes
   - B. Manual checking causes overflow and water shortage
   - C. Wi‑Fi is not available anywhere
   - D. Tanks cannot store water
   - **Answer: B.** *Manual visits are late; IoT shows the level before trouble happens.*

2. **What does the Smart Water Tank system monitor?**
   - A. Water colour only
   - B. Quantity/level of water in a tank
   - C. Building paint
   - D. Electricity bill
   - **Answer: B.**

3. **Which reading means low water level in the case study?**
   - A. 15%
   - B. 50%
   - C. 80%
   - D. 95%
   - **Answer: A.**

4. **Which reading means a partially filled tank?**
   - A. 0%
   - B. 15%
   - C. 50%
   - D. 95%
   - **Answer: C.**

5. **Which reading indicates an almost full tank?**
   - A. 15%
   - B. 50%
   - C. 80%
   - D. 95%
   - **Answer: D.** *95% = stop filling to avoid overflow.*

6. **What is IoT?**
   - A. Internet of Things
   - B. Internal Online Tank
   - C. Input of Temperature
   - D. Internet of Tables
   - **Answer: A.**

7. **Which is the basic IoT flow for this system?**
   - A. Sensor → IoT device → internet/cloud → dashboard
   - B. Dashboard → pen drive → sensor
   - C. Pump → keyboard → cloud
   - D. Sensor → paper register only
   - **Answer: A.**

8. **Why is IoT monitoring better than manual checking?**
   - A. It provides 24/7 remote readings and early alerts
   - B. It removes all water pipes
   - C. It makes sensors unnecessary
   - D. It works only when a person visits
   - **Answer: A.**

9. **What is a water-level sensor used for?**
   - A. To measure available water quantity
   - B. To print reports
   - C. To connect Wi‑Fi alone
   - D. To store data in a database
   - **Answer: A.**

10. **Which sensor can measure level without touching water?**
    - A. Ultrasonic sensor
    - B. DHT11 temperature sensor
    - C. Buzzer
    - D. Breadboard
    - **Answer: A.** *It measures distance to the water surface using sound waves.*

11. **How does an ultrasonic water-level sensor estimate level?**
    - A. Measures distance from sensor to water surface
    - B. Reads Wi‑Fi password
    - C. Measures room temperature
    - D. Counts users
    - **Answer: A.**

12. **What happens when level is below the low threshold?**
    - A. Low-water alert is generated
    - B. Files are deleted
    - C. Wi‑Fi permanently stops
    - D. Tank becomes full
    - **Answer: A.**

13. **What happens when level reaches overflow threshold?**
    - A. Overflow alert is generated; pump can be stopped
    - B. The sensor is removed
    - C. The dashboard is deleted
    - D. Water level becomes 0%
    - **Answer: A.**

14. **What is an actuator in this water-tank system?**
    - A. Relay-controlled water pump
    - B. Dashboard gauge
    - C. Sensor reading
    - D. Wi‑Fi SSID
    - **Answer: A.**

15. **Why is a relay used with a pump?**
    - A. It lets the low-voltage controller safely switch a higher-power load
    - B. It measures water level
    - C. It stores cloud data
    - D. It replaces Wi‑Fi
    - **Answer: A.**

# B. IoT Hardware and Connections

16. **What is NodeMCU?**
    - A. Node Microcontroller Unit
    - B. Network Memory Control Unit
    - C. New Mobile Cloud Unit
    - D. No Microcontroller Used
    - **Answer: A.**

17. **Why is ESP8266/NodeMCU useful for IoT projects?**
    - A. It has built-in Wi‑Fi
    - B. It needs no electricity
    - C. It is a water sensor
    - D. It stores unlimited cloud files
    - **Answer: A.**

18. **ESP stands for:**
    - A. Espressif Systems Processor
    - B. Electronic Storage Platform
    - C. External Sensor Pin
    - D. Embedded Signal Power
    - **Answer: A.**

19. **What operating voltage does ESP8266 NodeMCU use?**
    - A. 3.3V
    - B. 12V only
    - C. 220V
    - D. 24V only
    - **Answer: A.**

20. **Why must sensors share ground with NodeMCU?**
    - A. To provide a common electrical reference and complete the circuit
    - B. To increase cloud storage
    - C. To make Wi‑Fi faster
    - D. To change tank capacity
    - **Answer: A.**

21. **What is GPIO?**
    - A. General Purpose Input/Output pin
    - B. Global Pump Internet Output
    - C. Gauge Pin Internal Operation
    - D. Ground Power Input Output
    - **Answer: A.**

22. **What is GPIO input used for in this project?**
    - A. Receiving the sensor signal
    - B. Switching the pump directly at mains voltage
    - C. Storing Blynk data
    - D. Creating a PDF
    - **Answer: A.**

23. **What is GPIO output used for?**
    - A. Controlling an LED, buzzer, or relay signal
    - B. Measuring cloud storage
    - C. Naming a dashboard
    - D. Replacing a sensor
    - **Answer: A.**

**GPIO–A. How many commonly usable digital GPIO pins does a NodeMCU ESP8266 development board expose?**
    - A. About 11: D0–D8 plus RX and TX
    - B. 1 only
    - C. 50 only
    - D. No digital pins
    - **Answer: A.** *Say “about 11 usable digital GPIOs” in viva. RX/TX are normally used for serial communication, so they may not be free in every project.*

**GPIO–B. How many analogue input pins does a usual NodeMCU ESP8266 board have?**
    - A. One: A0 / ADC0
    - B. Eleven
    - C. Zero
    - D. Twenty
    - **Answer: A.** *A0 reads an analogue voltage; ordinary GPIO pins read/write digital HIGH or LOW.*

**GPIO–C. Are GPIO input and output separate physical groups of pins?**
    - A. No. A GPIO is general-purpose and is configured in software as input or output
    - B. Yes. Inputs can never become outputs
    - C. Yes. Outputs can never read a signal
    - D. GPIO works only as output
    - **Answer: A.**

**GPIO–D. Why should GPIO0, GPIO2 and GPIO15 be used carefully?**
    - A. They affect the ESP8266 boot mode; wrong external wiring can stop it from starting
    - B. They contain extra water
    - C. They are cloud-only pins
    - D. They are the analogue input
    - **Answer: A.**

**GPIO–E. Why should GPIO6–GPIO11 normally not be used in a NodeMCU project?**
    - A. They are connected internally to flash memory
    - B. They are water-level probes
    - C. They are all analogue pins
    - D. They are Wi-Fi antennas
    - **Answer: A.**

24. **What does a breadboard provide?**
    - A. Solderless temporary circuit connections
    - B. Cloud hosting
    - C. Water storage
    - D. Wi‑Fi service
    - **Answer: A.**

25. **What is the role of jumper wires?**
    - A. Connect circuit components on a breadboard
    - B. Measure water level
    - C. Send notifications directly
    - D. Store data
    - **Answer: A.**

26. **Why must a 5V signal not be sent directly to a 3.3V ESP8266 GPIO pin?**
    - A. It may damage the ESP8266
    - B. It improves Wi‑Fi
    - C. It fills the tank faster
    - D. It creates a virtual pin
    - **Answer: A.**

# C. Blynk, Cloud and Dashboard

27. **What is Blynk IoT in this project?**
    - A. Cloud platform/dashboard for IoT data and alerts
    - B. A physical water tank
    - C. A jumper wire type
    - D. A relay only
    - **Answer: A.**

28. **What is a Blynk authentication token?**
    - A. Unique key linking the device code to a Blynk project
    - B. The tank capacity
    - C. The sensor distance
    - D. A GPIO pin
    - **Answer: A.**

29. **What is a Blynk virtual pin?**
    - A. Software data channel between device and dashboard
    - B. Physical metal pin on NodeMCU
    - C. Pump wire
    - D. Wi‑Fi router antenna
    - **Answer: A.**

30. **What does `Blynk.virtualWrite(V1, value)` do?**
    - A. Sends a value to virtual pin V1 on Blynk
    - B. Writes to physical GPIO V1
    - C. Turns off Wi‑Fi
    - D. Deletes sensor data
    - **Answer: A.**

31. **Which Blynk dashboard widget suits water percentage?**
    - A. Gauge or chart
    - B. Text editor only
    - C. Keyboard
    - D. Compiler
    - **Answer: A.**

32. **What is the main use of cloud dashboard in this case?**
    - A. View tank level remotely through internet
    - B. Physically fill the tank
    - C. Replace sensors
    - D. Remove thresholds
    - **Answer: A.**

33. **Which needs internet to work?**
    - A. Blynk cloud dashboard notification
    - B. Local sensor measurement
    - C. Local buzzer alert
    - D. Breadboard connection
    - **Answer: A.**

34. **If Wi‑Fi fails, what can still work locally?**
    - A. Buzzer/local relay logic, if programmed
    - B. Cloud dashboard updates
    - C. Phone notification
    - D. Remote chart
    - **Answer: A.**

35. **What does HTTP status code 200 mean?**
    - A. Success
    - B. Sensor damage
    - C. Overflow
    - D. Invalid Wi‑Fi password
    - **Answer: A.**

# D. Code, Timers and Alerts

36. **What is `void setup()` used for?**
    - A. Runs once to initialize hardware and connections
    - B. Runs forever every second
    - C. Sends every alert
    - D. Stores the tank
    - **Answer: A.**

37. **What is `void loop()` used for?**
    - A. Runs repeatedly as the main program loop
    - B. Runs only once
    - C. Creates Wi‑Fi hardware
    - D. Calibrates a sensor automatically forever
    - **Answer: A.**

38. **Why call `Blynk.run()` in the loop?**
    - A. Keeps Blynk communication active
    - B. Measures distance itself
    - C. Turns every pump on
    - D. Creates a breadboard
    - **Answer: A.**

39. **Why use BlynkTimer instead of `delay()`?**
    - A. It is non-blocking, so cloud communication continues
    - B. It uses no code
    - C. It removes Wi‑Fi
    - D. It increases voltage
    - **Answer: A.**

40. **What does `millis()` return?**
    - A. Milliseconds since device startup
    - B. Tank water in litres
    - C. Wi‑Fi password
    - D. Cloud storage size
    - **Answer: A.**

41. **What does `60000UL` represent?**
    - A. 60,000 milliseconds = one minute
    - B. 60 volts
    - C. 60% water level
    - D. 60 sensor pins
    - **Answer: A.**

42. **Why use an alert cooldown?**
    - A. Prevent repeated notification spam
    - B. Make sensor inaccurate
    - C. Stop all monitoring
    - D. Empty the tank
    - **Answer: A.**

43. **What is a threshold?**
    - A. Limit value that triggers an action/alert
    - B. Device serial number
    - C. Cloud provider name
    - D. Cable type
    - **Answer: A.**

44. **What should happen for an invalid sensor reading?**
    - A. Reject it, show sensor issue, and avoid unsafe pump decision
    - B. Treat it as 100% full
    - C. Delete cloud project
    - D. Ignore all future readings forever
    - **Answer: A.**

# E. Accuracy, Safety and Viva Concepts

45. **How can an ultrasonic tank sensor be calibrated?**
    - A. Measure empty-tank distance and maximum-water distance
    - B. Change Wi‑Fi name
    - C. Increase pump voltage
    - D. Remove the sensor
    - **Answer: A.**

46. **Why should the sensor be mounted above maximum water level?**
    - A. It needs clear distance measurement and must avoid water damage
    - B. It must touch water directly
    - C. It makes Blynk faster
    - D. It stops the relay
    - **Answer: A.**

47. **What may reduce ultrasonic sensor accuracy?**
    - A. Foam, turbulence, wrong mounting, or poor calibration
    - B. A clean stable water surface
    - C. A valid threshold
    - D. A private Wi‑Fi password
    - **Answer: A.**

48. **Why verify IoT readings with manual checks initially?**
    - A. To validate calibration and confidence before automation
    - B. To avoid using sensors
    - C. To remove all alerts
    - D. To make cloud access local only
    - **Answer: A.**

49. **Why use a relay instead of connecting the pump directly to NodeMCU?**
    - A. Pump voltage/current is much higher than a GPIO can safely provide
    - B. NodeMCU stores more water
    - C. Wi‑Fi needs a relay
    - D. A relay reads ultrasonic distance
    - **Answer: A.**

50. **How does this system reduce water wastage?**
    - A. Detects near-overflow early and can stop pumping
    - B. Keeps pump on continuously
    - C. Hides water-level readings
    - D. Uses more pen drives
    - **Answer: A.**

51. **How does this system prevent water shortage?**
    - A. Sends low-level alert before the tank is empty
    - B. Deletes readings below 20%
    - C. Disables the pump permanently
    - D. Removes Wi‑Fi
    - **Answer: A.**

52. **What is the real-world larger version of an IoT monitoring system?**
    - A. SCADA — Supervisory Control and Data Acquisition
    - B. PDF reader
    - C. Breadboard only
    - D. Local text file
    - **Answer: A.**

53. **What is the role of Wi‑Fi analogous to in the human body?**
    - A. Nervous system carrying signals from sensor to cloud/phone
    - B. Heart pumping water
    - C. Tank itself
    - D. Buzzer sound
    - **Answer: A.**

54. **What is the key conclusion for this case study?**
    - A. IoT gives continuous remote tank monitoring, early alerts, and possible safe pump automation
    - B. IoT makes sensors unnecessary
    - C. IoT works only with manual readings
    - D. IoT removes the need for water storage
    - **Answer: A.**

# Instrument Working and Fault Detection MCQs

55. **How does an ultrasonic water-level sensor measure level?**
    - A. Sends a sound pulse and calculates distance from the returning echo
    - B. Sees the water colour
    - C. Stores the water in memory
    - D. Uses the Wi-Fi password
    - **Answer: A.**

56. **When is a sensor reading considered healthy?**
    - A. It is recent, within the calibrated range, and changes logically with the tank level
    - B. It is always exactly 50%
    - C. It has no timestamp
    - D. It is copied manually
    - **Answer: A.**

57. **Which is a likely ultrasonic-sensor fault sign?**
    - A. No echo, impossible distance, or a sudden unexplained jump
    - B. A normal 50% reading
    - C. A fresh timestamp
    - D. Good Wi-Fi signal
    - **Answer: A.**

58. **What does NodeMCU do in this project?**
    - A. Reads the sensor, calculates percentage, and sends it to the cloud by Wi-Fi
    - B. Holds all the water
    - C. Replaces the tank
    - D. Measures the water by itself without a sensor
    - **Answer: A.**

59. **How can we know that the NodeMCU is working?**
    - A. Its heartbeat/timer runs, voltage is normal, and fresh readings are being sent
    - B. The tank is painted blue
    - C. The cloud page is closed
    - D. The pump is unplugged
    - **Answer: A.**

60. **Which sign suggests a NodeMCU problem?**
    - A. Heartbeat stops, device repeatedly resets, or readings stop updating
    - B. One normal sensor reading
    - C. A full water tank
    - D. A successful cloud write
    - **Answer: A.**

61. **Which checks show that Wi-Fi communication is healthy?**
    - A. Good signal strength, low delay, few retries, and successful cloud updates
    - B. High tank capacity only
    - C. A relay label only
    - D. An old reading on screen
    - **Answer: A.**

62. **How is the cloud/dashboard connection checked?**
    - A. Compare the latest virtual-pin timestamp with the device's sent reading
    - B. Check the water colour
    - C. Measure wire length only
    - D. Restart the building
    - **Answer: A.**

63. **How do we verify that a relay and pump really worked?**
    - A. Confirm command and feedback, then check whether water level changes as expected
    - B. Assume every ON command is successful
    - C. Check Wi-Fi name only
    - D. Hide the pump status
    - **Answer: A.**

64. **Why should an automatic pump not act on one invalid reading?**
    - A. It could start or stop wrongly; validate/retry readings first
    - B. It makes the sensor faster
    - C. It saves no electricity
    - D. It removes cloud storage
    - **Answer: A.**

65. **What does the deployed project’s health page demonstrate?**
    - A. Diagnostic rules; actual hardware must send live telemetry to prove real health
    - B. A physical sensor is already installed in every tank
    - C. The dashboard can repair a broken pump
    - D. The cloud does not require data
    - **Answer: A.**

# 10-Second Revision

```text
Sensor measures level → NodeMCU reads it → Wi‑Fi sends it → Blynk shows it.
15% = low; 50% = partial; 80% = normal; 95% = near overflow.
ESP8266 = 3.3V microcontroller with built-in Wi‑Fi.
Virtual pin = software channel between NodeMCU and Blynk.
BlynkTimer = non-blocking scheduled reading; delay() blocks.
Relay = safe interface between NodeMCU and pump.
Calibration + invalid-reading check = more accurate and safer automation.
```
