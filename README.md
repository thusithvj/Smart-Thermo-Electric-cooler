# Smart-Thermo-Electric-cooler
Built a smart thermoelectric cooler that can precisely control and maintain temperature — all without relying on a traditional refrigeration cycle.

🔹 Project Highlights:
 • Designed a compact system that can achieve and maintain any target temperature with ±1°C accuracy
 • Used a Peltier module with CPU-grade fans for efficient thermoelectric cooling
 • Built a custom insulated enclosure using precisely laser-cut Rigifoam to ensure minimal heat exchange
 • Developed our own temperature sensor from scratch, alongside an LM35 to monitor ambient temperature
 • Added a magnetic door sensor that alerts the user if the cooler door is left open or not sealed properly — crucial for temperature stability

🔹 Control System:
 • Used a NI USB-6001 DAQ card to interface with sensors and control outputs
 • Programmed the system using LabVIEW, where we created a real-time closed-loop feedback system
 • LabVIEW provided live data visualization, adjustable setpoints, and control logic to dynamically regulate the Peltier’s power
 • The DAQ card handled analog inputs (temperature sensors) and digital outputs (for driving actuators and the alert system)

🔹 Key Learnings:
 • Gained hands-on experience in sensor design, feedback control, and thermal system integration
 • Applied instrumentation techniques to real-world engineering problems
 • Learned how to work with LabVIEW and NI hardware to create responsive, real-time systems
