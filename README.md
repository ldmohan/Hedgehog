# Hedgehog
Hedgehog: Detecting Drink Spiking on Wearables

We introduce "Hedgehog," a pervasive sensing approach that utilizes optical sensors in everyday wearables to identify spiked drinks. The technology analyzes variations in light reflectivity caused by small particles in the drink. We present a wearable prototype resembling a smart ring and report rigorous experiments demonstrating Hedgehog's effectiveness, with up to 89.71% accuracy in detecting tampered drinks. This innovation showcases the potential of wearables to provide a safety measure against a prevalent social issue.

### Smart Ring Prototype ###
The prototype uses a M5StickC PLUS ESP32 development board that controls the sampling frequency of the light sensor and uploads the samples to a server in real-time. It is also possible to use a smartphone for analyzing the measurements. A light sensor is integrated through a separate wire attached to a plastic ring. The ring is made from an elastic wire, making it easy to adjust to different fingers. Our prototype takes light measurements using a red laser diode (650 nm, 5 mW, 3-5V) and a photoresistor (5 M ohm). The photoresistor measures the intensity of light reflected back from the beam produced by the laser diode. The photoresistor captures analog voltage measurements converted to digital voltage representations in the microcontroller. Then, the data is sent to the mobile phone to detect the spiked drink.
![Figure 1:](https://github.com/ldmohan/Hedgehog/blob/main/fig1.png)
### Arduino code for the M5Stick ###
Upload the [code ](https://github.com/ldmohan/Hedgehog/blob/main/M5cPlusRedLaserHedgehog.rar/" Code") to the M5StickC. Change your  mobile phone hotspot details in the code to send data to the phone 
