## THE MACHINE PARADOX

17.10-27.10

### **Forensic Questions**

**What does it do?**‍

A 3D printer is a device that creates three-dimensional objects by layering material based on a digital design. Using a computer-aided design (CAD) model as a blueprint, the printer adds material layer by layer, whether it's thermoplastic, resin, or metal, to form a solid object. Different printing technologies, such as Fused Deposition Modeling (FDM), Stereolithography (SLA), or Selective Laser Sintering (SLS), dictate the type of material and the layering process, resulting in a tangible product that mirrors the digital design.

‍

**How does it work?**

The 3D printer works by interpreting a digital 3D model, slicing it into thin horizontal layers using specialized software, and then building the object layer by layer through additive manufacturing. Depending on the technology used, the printer deposits material, such as thermoplastic filament, liquid resin, or metal powder, layer by layer, with each layer fusing to the one below. The material is solidified using various methods like heating, UV curing, or laser sintering, resulting in a three-dimensional object that matches the digital design.

‍

**How is it built?**

The 3D printer is constructed using a combination of mechanical, electronic, and software components. Mechanically, it features a frame that houses the moving parts, including the print head or extruder, and a build platform. These components are driven by motors, guided by linear rails or rods, ensuring precise movements on the X, Y, and Z axes. Electronically, a main control board processes digital instructions from the slicing software, directing the motors and regulating the temperature of the print head or curing source. Additionally, various sensors monitor conditions like temperature and filament presence, while the software interface allows users to configure settings, load models, and initiate the printing process.

‍

**Why it failed, or it wasn’t used anymore?**

The 3D printer still functions, but it's an older, unstable model with low accuracy and print quality.

![Alt text](../images/TMPFOTO1.png)

## **Powering things up**

‍
After the disassembly process, we meticulously examined each individual component. Utilizing a precision lab power supply and a high-resolution multimeter, we conducted comprehensive tests to determine the optimal voltage required for each component's functionality.

‍


DC Lab Power Supply - How we brought individual 3D Printer components back to life



The supply powering the printer hot plate



We monitored the temperature of the hot plate while gradually increasing the voltage

‍

Connecting the power-supply to the extruder



The printer monitor displaying again after a very long rest



Powering the printer nozzle



Extruder melting filament

### **Results**

**How many motors did we find inside?**

Five motors - they are used to move the extruder in the three axis to permit drawing in 3D space.

‍

**Does it contain a computer or microcontroller?**

Yes, an Arduino board and a RAMPS.

‍



**Did you found any sensors?**

Yes, temperature sensors.

### **Conclusions**

**What did you learn?**

- How a 3D printer is assembled
- How a 3D printer works
- How to power up each component individually
- Fundamental electronics
- How a step motor works

‍

**What surprised you?**

- The number of components, screws and pieces the printer had
- The fact that we can make the extruder work with just 3 components
- How easy and repareable it is
- How much the 3D technology has improved since 2015