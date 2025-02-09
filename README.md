# IntelliScout Ver.2


## 🚀 Project Overview
IntelliScout Ver.2 is an advanced Spybot Monitoring System designed for real-time surveillance and feedback transmission. This system operates in both manual and automatic hybrid modes, offering enhanced flexibility and control. It is capable of detecting obstacles using a radar system and provides visual feedback with color indicators:
- **Red Signal:** Indicates the presence of an obstacle, displaying distance and angle information.
- **Green Signal:** Indicates a clear path with no obstacles detected.

The system is connected via a static IP, transmitting real-time data to tablets and laptops. IntelliScout Ver.2 is highly versatile, suitable for applications in non-human intervention areas such as borewells, pipeline monitoring, coal mines, and gold mines.

Live streaming method used in camera for the visibility of the area required using the internet.
App or Browser for viewing live area view of the required area where the internet is available for the device and the controlling system, so that it can be connected and the information will be telecasted from the device to the required monitor or screen.
Esp-32 for controlling the device this is the heart of the device where the whole information will be send and received and this will be sending to which sensor the information is to be send.
Servo motor to close and open the door of the storage area whenever required to the delivery to the desired person.

<hr>

## 👥 Team Name
<h1>CYBER GEEKS</h1>
<h2>"We do do Just Do It!"</h2>

## 📛 Project Name
IntelliScout Ver.2 (SpyBot) Monitor the Ativity on Remote Places Where Non-Human Intervention is not Possible (Millitary, FireFighter, Rescue Borewells, Space Missions, etc).

## 🗓️ Version
2.0

## 🎓 Mentored By
Dr. Manzoor Sir Ansari (IOT & Robotics)

## 📊 Model Used
Agile Model (Develope Based on Proper Planning and the Methodologies we used in 4 Months)

(Planning, Skectching, Discussion, Budget Checking, Developing, Testing, Validation, Training , Again Testing , Send it to the Final) Booked!

## 🌟 Novelty
IntelliScout Ver.2 introduces a hybrid operational mode, combining manual and automatic functionalities for enhanced adaptability. Its real-time feedback system, integrated with radar-based obstacle detection, provides precise distance and angle measurements, improving safety and efficiency in hazardous environments. The use of static IP for secure, stable communication further elevates its reliability.

## 🌟 Design and Implementation
This System of the security surveillance robot can be operated in two ways i.e. the robot can be used in automatic mode or it can also be controlled manually through the web. This facility helps the user to get a video – feed at all times which can be seen live or through recording. Both the operations are implemented using separate circuits, the manual operation is done using a circuit that uses ESP-32 as its core and the automatic operation is done by using ESP-32 as its core. But both modes cannot be used simultaneously they have to be preset do work in a particular operating mode. The circuits are constructed considering the drawback, each circuit has its own drawbacks if taken individually but if used together they eliminate most of the drawbacks.
<br>
<div align="center">
  <img src="https://github.com/user-attachments/assets/b1db662e-d888-4815-98c8-342e48796624" alt="Centered Image" width="400"/>
</div>
<hr>

## 🌟 Block Diagram
<br>
<div align="center">
  <img src="https://github.com/user-attachments/assets/843c3ff6-6790-40aa-979b-2dba178b4ca8" alt="Centered Image" width="400"/>
</div>

<br><br>
<center><h1>Fig1: Block Diagram of Surveillance Robot</h1></center>

## 📚 Introduction
IntelliScout Ver.2 was developed to address the growing need for efficient, real-time monitoring systems in areas that are hazardous or inaccessible to humans. By leveraging advanced robotics and communication technologies, IntelliScout offers a comprehensive solution for surveillance, inspection, and monitoring tasks.

## ⚙️ Working
- **Control Modes:** Operates in manual and automatic hybrid modes.
- **Communication:** Connected via static IP for real-time data transmission.
- **Obstacle Detection:** Utilizes a radar system to identify obstacles, displaying alerts with color codes (red for detected obstacles with distance and angle info, green for clear paths).
- **Feedback Mechanism:** Sends real-time feedback to tablets and laptops for continuous monitoring.
<hr>

## 📚 Components Used
The hardware is comprised of the following components:
 ESP-32 Camera Module
 L293N Motor Driver IC
 SG-90 Servo Motor
 Micro SD card
 Antenna
 Rechargeable Batteries (12V)
 100Rpm Motors
 Mountain Wheels
 Switch
 Jumper wire and connecting wire
<hr>

## 🏗️ Architecture
1. **Robotic Spybot Car:** Equipped with sensors and cameras for data collection.
2. **Radar System:** Detects obstacles, measuring distance and angle.
3. **Static IP Communication:** Ensures stable, secure data transmission.
4. **Control Interface:** Tablets and laptops receive and display real-time feedback.
<br><br>
## 🖼️ Gallery

<div align="center">
  <img src="https://github.com/user-attachments/assets/9574bb6e-87fb-4d77-a671-19ce20eb6c22" alt="Centered Image" width="400"/>
</div>

<hr>

## 🛠️ Connections
<h1><center>Pin Connections:</center></h1>.
<h2><center>From ESP-32 to L293N Motor Driver</center></h2>
<ul type="I">
  <li>Pin 14 – R1</li>
<li>Pin 15 – R2</li>
<li>Pin 13 – L1</li>
<li>Pin 12 – L2</li>
<li>5V -- 5V</li>
<li>Grd -- Grd</li>
</ul>

<h2><center>From L293N Motor Driver to Motors</center></h2>
<ul type="I">
  <li>O1 – Motor 1(side 1)</li>
 <li>O2 – Motor 1(side 2)</li>
 <li>O3 – Motor 2(side 1)</li>
 <li>O4 – Motor 2(side 2)</li>
</ul>
<br>
<b><u><center>Fig: 1.1</center></u></b>

Connections of Surveillance Robot
From ESP-32 to Other Components:
 Pin

<div align="center">
  <img src="https://github.com/user-attachments/assets/51471fcd-93c5-4572-b12a-62c796e92887" alt="Image 1" width="300" style="margin-right: 10px;"/>
  <img src="https://github.com/user-attachments/assets/590243e9-2cab-4f75-90fa-8c3fbca3641e" alt="Image 2" width="300"/>
</div>

<hr>

## 🚖_Working Methods_
The robot is switched on by using 12V DC batteries as the power supply from external source, then the ESP-32 and L293N Motor driver shield gets power to get started. With this the robot gets moving.
2. The Camera starts viewing and will be used for live viewing on the desired device on which you are given with the IP address or on an application that are built for it.
3. The motors are used for the movement of the robot by taking the instruction given by us.
4. The ESP-32 will be taking all the information from us and giving commands to all the robot and this is also called heart of the robot and this will be connecting to the internet where communication between the devices will be taken here from monitor to the device.
5. The controlling can be done by the IP entered device browser or the application built for it.
6. The controls will be forward, backward, right, left, stop, flash, servo and speed of motor.
7. The device can be controlled from anywhere in the world with any internet enabled device.
8. The live viewing can be seen in the monitor of the controlling device.
<hr>

## 🛠️ Applications
- **Non-Human Intervention Areas:** Ensures safety in hazardous environments.
- **Borewells:** Inspects deep and narrow spaces.
- **Pipeline Monitoring:** Detects leaks and structural issues.
- **Coal and Gold Mines:** Enhances safety by monitoring dangerous underground areas.

## 🚩 Problems Solved
- Eliminates the need for human presence in hazardous environments.
- Provides real-time data for quick decision-making.
- Enhances safety with precise obstacle detection.
- Offers flexible control with hybrid manual-automatic operation.

## ❗ Problems Faced
- **Connectivity Issues:** Initial challenges with stable static IP setup.
- **Obstacle Detection Accuracy:** Fine-tuning radar sensitivity for varying environments.
- **Power Management:** Optimizing battery life for prolonged operations.

## 🖼️ Gallery

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1BgycYz_Y-RsCUGoMiMVxPy2b0Y7DPQ6G" alt="Image 1" width="200" style="margin: 10px;"/>
  <img src="https://drive.google.com/uc?export=view&id=1Wj3YJmR5ZdNBK-ohh3R9zZHg_WyCZjL9" alt="Image 2" width="200" style="margin: 10px;"/>

  <img src="https://drive.google.com/uc?export=view&id=1Yi2zJmHQlnRpX0IEi7aZ4yUVczPN3XL9" alt="Image 3" width="200" style="margin: 10px;"/>
  <img src="https://drive.google.com/uc?export=view&id=1kjXi-yy5yWlR4ffghXnXkxeMmC6YICIK" alt="Image 4" width="200" style="margin: 10px;"/>

  <img src="https://drive.google.com/uc?export=view&id=1UlIIZBXPKV5qBPmylzIJbZ5QS9PnmKxx" alt="Image 5" width="200" style="margin: 10px;"/>
  <img src="https://drive.google.com/uc?export=view&id=11dlM0JQJzkm1Sr59dwlq-GU2PF7YjsHY" alt="Image 6" width="200" style="margin: 10px;"/>

  <img src="https://drive.google.com/uc?export=view&id=1QsFAtFufDagzluAyueFj7YhRfZ7ZatG2" alt="Image 7" width="200" style="margin: 10px;"/>
  <img src="https://drive.google.com/uc?export=view&id=1znQ3aJeiKRylbU9drUbn0zmOdg4cMrCr" alt="Image 8" width="200" style="margin: 10px;"/>
</div>

<!-- Add more images following the same format -->


## 🔗 Links
- **Video Demonstration:** [https://drive.google.com/file/d/1IzkPWICe1Skf9n4ZQYZvPlphjJqqmYI4/view?usp=sharing]
- **Project Presentation (PPT):** [https://drive.google.com/file/d/1c6ADDGAFiS-kNQgDVOwNIlyKjZxur9Pz/view?usp=sharing]
- **Canva (Public-Link):** [https://drive.google.com/file/d/1IzkPWICe1Skf9n4ZQYZvPlphjJqqmYI4/view?usp=sharing]
- **Project Documentation:** [https://drive.google.com/file/d/1iMnpbvhqf9GxEDpckzevKNTRLOb6rxXe/view?usp=sharing]

## 📞 Contact
- **Dhruv Dhayal** - [dhayaldhruv271@gmail.com](mailto:dhayaldhruv271@gmail.com)
- **Pratham Aggarwal** -[aggarwalpratham2602@gmail.com](mailto:aggarwalpratham2602@gmail.com)
- **Linkdin** - [Join Our Community](https://www.linkedin.com/company/the-cyber-geeks/?viewAsMember=true)
- **Instagram** - [Follow & Support Us](https://www.instagram.com/cybergeeks.iitm/?hl=en)
- *(Hiring is Open For Marketing & Management)*

## 🖼️ Gallery Of TechnoSapiens (SDIC * AIEC) '2K25

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1j1iDx6Ct__BQF74X-5yF_2OBmmXipY_S" width="400" style="margin: 10px;">
  <img src="https://drive.google.com/uc?export=view&id=1vcF54q-XAeGAtlEnfcTmy5uqP_xjG0lq" width="400" style="margin: 10px;">

  <img src="https://drive.google.com/uc?export=view&id=1AcL3aCu6OwGBHrBkQWuD44HlQvs2ALhP" width="400" style="margin: 10px;">
  <img src="https://drive.google.com/uc?export=view&id=1ajR_8iOWnuxplOFnpzYv4KxzFagLrdUm" width="400" style="margin: 10px;">

  <img src="https://drive.google.com/uc?export=view&id=1UNxBxuocuS1leaW5xab3Ao0YnnG7X6gS" width="400" style="margin: 10px;">
  <img src="https://drive.google.com/uc?export=view&id=1g-kYKC9_I1TUjujrESzB9cb-KzUTUk0Z" width="400" style="margin: 10px;">

  <img src="https://drive.google.com/uc?export=view&id=1zrGCW-I8BK9kLmEvE1wZhzyEw30nUygm" width="400" style="margin: 10px;">
  <img src="https://drive.google.com/uc?export=view&id=1fs1KD6KtySsiuVMcfx9qIHzVuNf2Vc-_" width="400" style="margin: 10px;">

  <img src="https://drive.google.com/uc?export=view&id=1-Acd3E800xWjeLDJ9HmEc2UKBHDY6TJW" width="400" style="margin: 10px;">
  <img src="https://drive.google.com/uc?export=view&id=1r2yNcR4vgaF2W4mJ8pLuESonKhrXukLj" width="400" style="margin: 10px;">

  <img src="https://drive.google.com/uc?export=view&id=1p4ZTvfq1nbYGyOe2WT-3BRO1QRHaiyRv" width="400" style="margin: 10px;">
  <img src="https://drive.google.com/uc?export=view&id=1hAw9O8G_Q9jMIVq07uTpMNEFC-UKRz7N" width="400" style="margin: 10px;">

  <img src="https://drive.google.com/uc?export=view&id=1fxaFhqwWWOXDeJR8ipKedmiCpC3qTC7x" width="400" style="margin: 10px;">
  <img src="https://drive.google.com/uc?export=view&id=1ygrU8NZPSp6CHUatriAF-I_rWHGHYiOz" width="400" style="margin: 10px;">
</div>



---

*For any queries or collaboration opportunities, feel free to reach out to us!*

