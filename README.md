# Prosthetic Hand

### Aesthetics

Inner Look
![Inner Look](https://github.com/FredZhang7/Proesthetic-Hand/blob/main/Prosthetic_Hand_Inner_Look.jpeg)

Outer Look
![Outer Look](https://github.com/FredZhang7/Proesthetic-Hand/blob/main/Prosthetic_Hand_Outer_Look.jpeg)

### Journal of Progress
1. Electromyogragy (EMG) Testing
![EMG Testing](https://drive.google.com/file/d/1xdGDu_gt9ZFMpc_6s7Qvo7Smc1eVCu5N/view?usp=sharing)
2. Mechanics Testing
![Beta Hand Testing](https://drive.google.com/file/d/1F7A8A4LyIdtMx8l9OecwImrnwCySaV7k/view?usp=sharing)
3. 

### Challenges
1. No alchohol nor cotton sticks available at home to clean my skin for accurate EMG readings
2. The prosthetic hand user may use different batteries
3. No multimeter available to detect any potential short circuits
4. Little to no Serial data support on Raspberry Pi

### Solutions
1. Used tape to remove oil, dust, and other dirty particles from my forearm before testing
2. Read the voltage outputs in intervals and curl the prosthetic fingers only if consecutive intervals produce consistent results
3. Always left a 220Ω resistor in the circuit before completing any circuits & used LED lights to test if a circuit works as intended
4. Switched to Arduino Uno Rev3

### Detection V1
- Assuming there're no abnormal spikes in voltage outputs, it's fairly accurate. However, muscle sensors bought from Amazon sometimes give off abnormal spikes in the voltage outputs

### Detection V2
- Only tested this twice. Detection V2 solved the abnormal spikes problem by tracking the lowest voltage reading and analyzing the history of 20 voltage readings
