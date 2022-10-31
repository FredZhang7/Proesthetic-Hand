# Prosthetic Hand

#### Challenges
1. No alchohol nor cotton sticks available at home to clean my skin for accurate electromyography readings
2. Muscle sensors bought from Amazon sometimes give off abnormal spikes in the voltage outputs & the prosthetic hand user may use different batteries
3. No multimeter available to detect any potential short circuits or leakage current
4. Little to no Serial data support on Raspberry Pi

#### Solutions
1. Used tape to remove oil, dust, and other dirty particles from my forearm before testing
2. Read the voltage outputs in intervals and curl the prosthetic fingers only if consecutive intervals produce consistent results
3. Always left a 220Ω resistor in the circuit before completing any circuits & used LED lights to test if a circuit works as intended
4. Switched to Arduino Uno Rev3

#### Detection V1
- 
- See [detection_v1.ino](https://github.com/FredZhang7/Proesthetic-Hand/detection_v1.ino]
