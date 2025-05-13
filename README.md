# Kinetic-Remote
Imagine a remote that never needs batteries. This innovative design uses a simple coil and magnet to generate power whenever you press a button. The energy is converted into usable electricity, making the remote both reliable and eco-friendly. Say goodbye to dead batteries and hello to a smarter, greener way to control your devices!

The system consists of 4 main components:
1. Infrared remote control device
2. Faraday voltage generator
3. Charge storage component
4. Voltage regulator

      ![image](https://github.com/user-attachments/assets/a5e51a96-2431-4be0-a34c-e0a1113335cd)


 Working of the Remote
 
 The Batteryless Remote is designed to function without traditional batteries by generating its own power through electromagnetic induction. This is achieved using a 6- inch tube wrapped with a 2000-turn coil, inside which three small magnets move freely.


The voltage required by the remote control device is generated using a DIY kinetic generator that converts mechanical power to electrical power, based on Faraday’s principle. The device consists of a hollow acrylic tube, with a cylindrical magnet sealed inside the tube, and 2000 turns of enameled copper wire (38 SWG) wound around the outer surface of the tube. When the tube is shaken, the magnet travels the length of the tube back and forth. This leads to a change of magnetic field as seen by the wire, and generates an EMF (electromagnetic force) that is proportional to the number of turns and the rate at which the magnetic field is changed. Thus, if you shake vigorously rather than gently, a larger EMF is generated. The AC EMF generated is passed through a Full Wave Bridge Rectifier made using Schottky diodes (1N5819) and converted to DC output voltage. This DC voltage is maintained at a constant 3V output using a Low Dropout Voltage Regulator (LP2950-3.3V). 

2 capacitors (4700uF/25V) are connected in parallel which store the charge coming from LDO which makes the output voltage efficient and sustainable.

Circuit Schematic Made on Fritzing:
![WhatsApp Image 2024-11-13 at 19 45 44_6a01a6bc](https://github.com/user-attachments/assets/b03302be-840b-4b23-9019-c4573395abb7)



This is how the final assembly of Remote looks like:
						![WhatsApp Image 2025-05-13 at 23 18 22_0d1f11d8](https://github.com/user-attachments/assets/14dbf8b6-53f4-4fbf-90c3-471a95b283e7)


                        
