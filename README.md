# 🛠️ Workshop Ideas & Future Builds

This is my personal "backlog" of projects I’m currently itching to build. It’s a mix of solving workshop annoyances and experimenting with industrial tech in a hobby environment. 

---

### 📐 Digital Miter Saw Fence
Measuring twice and still cutting once (wrongly) is annoying. I want to build a motorized stop for my miter saw that I can control via a small touch display.

* **The Plan:** Use an ESP32 to drive a NEMA 23. Since I want the UI to stay responsive while the motor is moving, I’m focusing on a non-blocking multi-threaded setup (using both ESP32 cores).
* **Tech I'm playing with:** * Smooth acceleration ramps (FastAccelStepper).
    * Logic to subtract the saw blade thickness automatically.
    * Maybe a web interface to send cut lists directly from my PC.

### ♻️ Desktop Plastic Shredder
I have a growing pile of failed 3D prints. Instead of throwing them away, I want to turn them back into regrind for a future extruder project.

* **The Challenge:** Shredding ASA or PETG requires serious torque. I’m planning to use a NEMA 34 with a beefy worm gearbox. 
* **Smart Features:** To prevent the motor from burning out when a part gets stuck, I’ll implement an auto-reverse routine.
* **The "Industrial" Touch:** I’ve worked with **Modbus** before, so I’m thinking about using Modbus-capable sensors to monitor the load and system health in real-time.

---

## 🚀 Current Interests & Deep Dives
Aside from the builds, I’m currently spending my free time on:
* **Moving to STM32:** Exploring the ARM Cortex world for more "industrial-feeling" projects.
* **Qt/QML:** Trying to make my project displays look less like 1995 and more like modern HMIs.
* **PCB Design:** Moving my breadboard messes into clean, custom PCBs designed in Fusion 360.

---
**Got ideas or better ways to solve these?** Feel free to open an issue – I'm always down for a technical chat!
