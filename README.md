# USB_TO_LORA_DONGLE

USB to LoRa is a robust and versatile USB to LoRa that allows you to connect without limits. Its excellent range and simple connection allow you to converse with devices up to 5 kilometres distant. LoRa Dongle is the appropriate answer for anybody wishing to develop long-range wireless communication in a number of applications.

<img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/lora_usb.png"/>


## Lora GUI For Configuration (run with the help of GUI)
 For this, you need to use Lora onboard USB 
 <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_18.jpg" />
 
 Go to the Lora GUI folder, and run the LORA_GUI.py file. from this file, you can configure the Lora and you are able to transmit, receive the data  (eg: baud rate, channel etc)
 Follow the steps to configure the Lora module:-

 ### Step 1: Setup lora in configuration mode, for this you need to short M0 and open M1 as shown in figure. In case of PICO LoRa Expansion find the mode selection jumper in that board and remove M1 jumper for config mode.
 
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_16.jpg" />
 
### Step 2: Open lora GUI 
 <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_1.png" />

### Step 3: set the COM Port and Baudrate
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_2.png" />
 
### Step 4: For COM Port go to Device Manager, before this first you need to connect the Lora module via USB cable 
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_7.png" />
 
### Step 5: Write the right COM Port in the GUI,then press connect button
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_8.png" />
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_9.png" />

### Step 6: Press read button to see the device configuration which lora already have
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img__10.png" />
 
### Step 7: Write the values which you need to configure, for eg: i configure channel and baudrate, after that press write button
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_13.png" />
 
### Step 8: Restart the GUI, set baudrate and port, then connect and press read button 
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_14.png" />
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_15.png" />
 
