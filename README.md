# Automation-SMART-SECURITY-SYSTEM
<h1>Failed RDP to IP Geolocation Information</h1>

<h2>Demostration:</h2>
 https://1drv.ms/v/c/ff8a77a3d328bef4/EefZiUFL02tIruTAIfDynUsBq6eOeY0gjOtfzLOSpDKdrA?e=nw5gEE


<h2>Description:</h2>
<b>The Smart Security System is design to Assist in Helping Security Profession in protecting builings or apertments.
<h2>HARDWARE:</h2> An LDR sensor, or Light Dependent Resistor, is a passive electronic component whose resistance changes with light intensity, decreasing in bright light and increasing in darkness,
  a phenomenon known as photoconductivity. Made from a high-resistance semiconductor material, 
  its resistance can vary dramatically from megaohms in the dark to just a few hundred ohms in bright light, 
  making it useful for detecting light levels in applications like automatic streetlights, night lamps, and light meters. 
  Ultrasonic sensors detect a multitude of objects contactless and wear-free with ultrasonic waves. It does not matter whether 
  the object is transparent or opaque, metallic or non-metallic, firm, liquid or powdery. Our ultrasonic sensors are available in many different designs, ranges, cone angles and output types.
  BUZZER used as arlam sound emmiter is Arlam system is triggered when both sensors detect an intruder, LCD is included for dispaly, Sevor Moter is used to create rotation of the Front sensor.
  LEDs are included as Lights and Buttons to manually control lights and arlam triggered.
  
</b>
<br />
<p align="center">
<img src="https://content.instructables.com/FHC/5HJU/HC9MI6WA/FHC5HJUHC9MI6WA.jpg?auto=webp&fit=bounds&frame=1&height=1024&width=1024" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
<br />
HARDWARE CONNECTION OF THE SMART SECURITY SYSTEM
<br />
<br />

<p align="center">
<img src="https://hackster.imgix.net/uploads/attachments/1467120/_RwXwGn0V9P.blob?auto=compress&w=900&h=675&fit=min&fm=jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
<h1> Software of the Smart Security System</h1>

<b>This project is a Smart Security System built with Arduino that combines two functions:
Intruder Detection – An ultrasonic sensor (HC-SR04) measures the distance of objects in front of it. If an intruder comes closer than a set distance (e.g., 50 cm),
 the system activates a buzzer to sound an alarm.
Automatic Light Control – An LDR (Light Dependent Resistor) monitors the surrounding light intensity. If it is dark, the system automatically
 switches on a light (LED or relay-controlled bulb). If it’s bright, the light turns off.
This makes the system useful for home and office security, especially at night.</b>
<p align="center">
<img src="<p align="center">
<img src="https://i.imgur.com/vEZRa0x.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h1>Use Database to Control and Store data on site and control system using IP address create using the Firebase database
</h1>
<b> Firebase Realtime Database is a cloud-hosted NoSQL database provided by Google.
Data is stored in JSON format and updates in real-time across all connected devices.
Example: If your Arduino sends “Intruder Detected” to Firebase, you can instantly see it on a mobile app or web dashboard.
So in this project:
When an intruder is detected, Arduino (ESP32/NodeMCU) sends this event to Firebase.
When it is dark/light, the LDR readings are also sent to Firebase.
You can check the security status remotely on your phone.
</b>
<p align="center">
<img src="<p align="center">
<img src="https://i.imgur.com/tmezNTO.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
