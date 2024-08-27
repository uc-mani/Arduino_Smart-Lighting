## Smart Home Automation using Arduino

Sensing The Surrounding’s Light using LDR 
:(value 0 -1023):
- 0 -------------Light Intensity Lower
- 1023 --------Light Intensity Higher
- High Intensity outside (~1023) -----Bulb with low intensity (~0)
- Low Intensity Outside (~0)-----Bulb with high intensity (~255)
- PWM Signal to LED (Bulb) (Value 0-255)

# Schematics:

![Schematics](https://github.com/user-attachments/assets/ffe2e2ea-38e1-4d07-8f70-4efca1179d70)

  

# Setup:
![6](https://github.com/user-attachments/assets/09e6c47e-5e42-49d5-ad19-3310f9928191)

  

# Testing:
https://github.com/user-attachments/assets/02fbd36d-9469-4ec4-8f5e-8e307bbb95e6

  

- When LDR has low intensity(dark), LED Bulb fully lights up!
![5](https://github.com/user-attachments/assets/1243089b-05bb-4280-af79-666974c068aa)
![2](https://github.com/user-attachments/assets/a9fb29d3-dd49-4801-ac96-64b2d20335a5)

  

- When LDR receive high intensity Light(sun), the LED bulb dims down!
![4](https://github.com/user-attachments/assets/63decb7f-6a37-407b-a3d2-0a1146a8d108)
![1](https://github.com/user-attachments/assets/0d90d11b-4029-44ed-9ba8-4dae5c8bc7ea)
