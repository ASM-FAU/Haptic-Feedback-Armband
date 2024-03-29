# Haptic Feedback Armband

The haptic feedback armband was mainly designed for prosthesis appliacations. It contains 5 vibration motors, of which each can correspond to one finger. The device is completely wireless and contains a custom designed PCB, 1800 mAh lithium polymer battery, 5 vibration motors, an IMU to gather motion data and an FSR to measure armband tightness. All code and hardware models are provided in this repository to replicate the device.

## Software
The software is split into two parts for the client device (the haptic feedback armband) and a master PC that it communicates with. The architecture is shown in the follong Figure.
![Ros_overview](https://github.com/ASM-FAU/Haptic-Feedback-Armband/assets/141027919/b78747be-4555-4fe0-9160-5b28fc6a3a56)


## Hardware
The armband consists of 5 modules in total. A main module, containing the PCB, battery and senors as well as a vibration motor and smaller modules containing a vibration motor only. The casing was 3D printed using FDM and PLA filament. The flexible links were printed with TPU filament. This is how the armband looks like:
![Armband_3D_View](https://github.com/ASM-FAU/Haptic-Feedback-Armband/assets/141027919/1785485f-5e78-4347-92ee-84d4b8889d9c)
![main_module](https://github.com/ASM-FAU/Haptic-Feedback-Armband/assets/141027919/88b7e59b-bf38-4f70-b87f-b88ff5b84325)
![sub_module](https://github.com/ASM-FAU/Haptic-Feedback-Armband/assets/141027919/8aa3fcda-d4c6-4201-bdf7-a9fc979093d3)
