# USB_TO_LORA_DONGLE

USB to LoRa is a robust and versatile USB to LoRa that allows you to connect without limits. Its excellent range and simple connection allow you to converse with devices up to 5 kilometres distant. LoRa Dongle is the appropriate answer for anybody wishing to develop long-range wireless communication in a number of applications.

<img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/lora_usb.png"/>

## How To use
To begin, you must configure the LoRa in transceiver mode by selecting the jumpers shown in the image below:

<img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img.jpg"/>

 You can download the XCTU from below :
 
 * [Dodnload XCTU](https://hub.digi.com/support/products/xctu/)
 
You can use XCTU or Tera Term for Windows to transmit and transfer data, as well as other related software. Among all, XCTU is effective and simple to use. follow the steps below

<img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img4.png"/>
<img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img5.png"/>
<img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img6.png"/>
<img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img7.png"/>
<img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img10.png"/>
<img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img11.png"/>

It receive data from other LoRa Dongle, as you see in below image

<img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img12.png"/>

### Operating Mode
There are four operating modes, which are set by M1 and M0, the details are as follows:
 * Normal Mode(M1=0,M0=0) 
   <img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img.jpg"/>
 * WOR Mode(M1=0,M0=1)
   <img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img1.jpg"/>
 * Configuration Mode(M1=1,M0=0)
   <img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img2.jpg"/>
 * Deep sleep Mode(M1=1,M0=1)
   <img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img3.jpg"/>
   
### Use LoRa USB As Breakout
You may use this device as a breakout, which means you can link it to any microcontroller or CPU by configuring the UART jumper wires as shown in the image below.

<img src = "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img14.jpg"/>

### Lora GUI For Configuration (run with the help of GUI)

 Follow the steps to configure the Lora module:-

 #### Step 1: Setup lora in configuration mode, for this you need to short M0 and open M1 as shown in figure. In case of LoRa Dongle find the mode selection jumper in that board and remove M1 jumper for config mode.
 
  <img src= "https://github.com/sbcshop/Usb_To_LoRa_Dongle_Software/blob/main/Images/img2.jpg" />
 
#### Step 2: Open lora GUI 
 <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_1.png" />

#### Step 3: set the COM Port and Baudrate
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_2.png" />
 
#### Step 4: For COM Port go to Device Manager, before this first you need to connect the Lora module via USB cable 
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_7.png" />
 
#### Step 5: Write the right COM Port in the GUI,then press connect button
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_8.png" />
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_9.png" />

#### Step 6: Press read button to see the device configuration which lora already have
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img__10.png" />
 
#### Step 7: Write the values which you need to configure, for eg: i configure channel and baudrate, after that press write button
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_13.png" />
 
#### Step 8: Restart the GUI, set baudrate and port, then connect and press read button 
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_14.png" />
  <img src= "https://github.com/sbcshop/Lora-HAT-for-Raspberry-Pi/blob/main/images/img_15.png" />
  
## Documentation
* [USB LoRa Dongle Hardware](https://github.com/sbcshop/Usb_To_LoRa_Dongle_Hardware)
* [USB LoRa Dongle Schematic](https://github.com/sbcshop/Usb_To_LoRa_Dongle_Hardware/blob/main/Documents/sch%20USB%20LoRa%20Dongle.pdf)
* [USB LoRa Dongle User Manual](https://github.com/sbcshop/Usb_To_LoRa_Dongle_Hardware/tree/main/Documents)

 ## Related Products

* [LoRa HAT For Raspberry Pi](https://shop.sb-components.co.uk/products/lora-hat-433mhz-868mhz) 

 ![LoRa HAT For Raspberry Pi](https://cdn.shopify.com/s/files/1/1217/2104/products/lora.jpg?v=1670911119&width=300)
 
 * [RangePi](https://shop.sb-components.co.uk/products/range-pi)
 
 ![RangePi](https://cdn.shopify.com/s/files/1/1217/2104/products/1_54b19023-5d19-4f55-acea-af894f2d00c6.png?v=1646815358&width=300)

## Product License

This is ***open source*** product. Kindly check LICENSE.md file for more information.

Please contact support@sb-components.co.uk for technical support.
<p align="center">
  <img width="360" height="100" src="https://cdn.shopify.com/s/files/1/1217/2104/files/Logo_sb_component_3.png?v=1666086771&width=300">
</p>

