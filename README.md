# Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. Basically a fiber 
optic link contains three main elements, a transmitter, an optical fiber and a receiver. The transmitter 
module takes the input signal in electrical form and then transforms it into optical (light) energy 
containing the same information. The optical fiber is the medium which takes the energy to the receiver. 
At the receiver light is converted back into electrical form with the same pattern as originally fed to the 
transmitter.
- **Transmitter**:LED, digital DC coupled transmitters are one of the most popular varieties due to their ease of 
fabrication. We have used a standard TTL gate to drive a NPN transistor, which modulates the LED 
SFH450V or SFH 756V source. (Turns it on and off)
- **Receiver**: SFH-551V is a digital optodetector. It delivers a digital output, which can be processed directly 
with little additional external circuitry. The integrated circuit inside the SFH551V optodetector comprises 
the photodiode device, a transimpedance amplifier, a comparator and a level shifter.
The photodiode converts the detected light into a photocurrent. With the aid of an integrated lens 
the light emanating from the plastic Fiber is almost entirely focused on the surface of the diode. At the 
next stage the trans-impedance amplifier converts the photocurrent into a voltage. In the comparator, the 
voltage is compared to a reference voltage. In over to ensure good synchronism between the reference 
and the trans- impedance output voltage, the former is derived from a second circuit of a similar kind, 
which incorporates a “blind” photodiode. The comparator derives a level shifter with an open collector 
output stages. Here a catch diode (similar to Schottky-TTL) prevents the saturation of the output 
transistor, thus limiting the output voltage to the supply voltage.

---

## PROCEDURE

▪ Refer to the block diagram & carry out the following connections and settings. 

▪ Connect the power supply with proper polarity to the kit link-B and switch it on. 

▪ Keep all Switch Faults in OFF position. 

▪ Keep switch SW8 towards TX position. 

▪ Keep switch SW9 towards TX1 position. 



<img width="637" height="258" alt="image" src="https://github.com/user-attachments/assets/3a18e537-9248-47bd-ac87-3019d397500a" />



▪ Keep switch SW10 towards TTL position. 

▪ Keep Jumper JP5 towards +5V position. 

▪ Keep Jumpers JP6 shorted. 

▪ Keep Jumper JP8 towards Pulse position. 

▪ Feed TTL Square wave signal of 1KHz from the function generator to the IN post of 
Digital Buffer. 


<img width="642" height="217" alt="image" src="https://github.com/user-attachments/assets/9ef8cfa5-10e8-4136-b264-81f16f9eed2f" />



▪ Connect the output post OUT of Digital Buffer to the post TX IN of Transmitter. 

▪ Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. 
Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by 
screwing it back. 

▪ Connect the other end of the Fiber to detector SFH551V (Photo Transistor Detector) very 
carefully.

▪ Observe the detected signal at post TTL OUT on oscilloscope.

▪ To measure the digital bandwidth of the phototransistor vary the input signal frequency and observe 
the detected signal at various frequencies.

▪ Determine the frequency at which the detector stops recovering the signal. This determines the max. 
bit rate on the digital link.

▪ Keep switch SW9 towards TX2 position. 

▪ Keep Jumper JP7 towards +5V position. 

▪ Remove fiber cable from SFH756V (660nm) and slightly unscrew the cap of SFH450V (950nm). Do 
not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the 
cap. Now tighten the cap by screwing it back. 

▪ Observe the detected signal at post TTL OUT on oscilloscope. 


<img width="646" height="233" alt="image" src="https://github.com/user-attachments/assets/bf5c5d46-443b-495f-83bb-074ae1007865" />



---


## BLOCK DIAGRAM

<img width="504" height="208" alt="image" src="https://github.com/user-attachments/assets/f02bfbe5-4b51-4d63-b3ea-eca30e3d2b32" />

---



## TABULATION  
**Transmission through Digital Link**

![WhatsApp Image 2025-11-16 at 21 27 50_701a94da](https://github.com/user-attachments/assets/d04d40df-a289-4b9f-860b-da5da8693dae)

---

## MODEL GRAPH

![WhatsApp Image 2025-11-16 at 21 26 40_62cdddf2](https://github.com/user-attachments/assets/dd8eabfb-df2f-4fbb-a208-d911d1c2b3f1)


---

## RESULT

Thus the experimental verification of frequency response of digital fibre optic link was successfull
