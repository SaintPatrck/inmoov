Here is a BOM Updated 04/05/2016
Of course you need to have a 3d printer.

2x arduino Mega=80 euros ebay.(The default is 1xUno and 1x Mega, but the legs and waist are yet to come )

Screw Allen countersunk:

M3x20MM about 50.
M4x20MM about 50
M8x100MM about 15

Phillips Flat-Head Wood Screws:

M3x12MM, about 100 for small servos.
M4x20MM, about 50 for big servos.
Plus some small screws for the eye mechanism, the jaw machanism and to fix the pistons on the small servos. But I used the screws that were delivered with the servos.
 

 Hands and forarms(Left, right):
10x servos HK15298B=180 euros Hobbyking
2x servos MG996r=22 euros ebay for the rotational wrist
0,8mm braided /fishing line. 200LB= 10 euros ebay
Miscealenous Bolts= 10 euros hardware store
1500gr natural ABS= 70 euros orbi-tech get 4kg if you start printing
10x extension spring 0.51mm diameter, 1cm length(13/64″x13/16″)
Arms and shoulders(Left, right):
8 Hitec HS805BB=240 euros ebay (better get even stronger in torque and faster)
Miscealenous Bolts= 10 euros hardware store
1500gr black, yellow, natural ABS= 56 euros orbi-tech
Head and torso:
2x Hitec HS805BB HEAD (up/down, right/left)
1x servos HK15298B JAW MECHANISM
2x servos HK15298B NECK TILTING(1 Master, 1 slave)
2x Servo DS929hvCorona or similar EYE MECHANISM
1X Camera Hercules HD (dismantled for this purpose)
or 1X LifeCam3000 Microsoft
1X kinect xbox 360  (not dismantled or see tutorial below)
About 4kg natural ABS
0,8mm braided thread/fishing line 200LB= 5 euros hardware store or ebay
Miscealenous Bolts= 10 euros hardware store
1500gr natural ABS= 70 euros orbi-tech
1x Battery 6V12AH  + battery charger 6V1.5A:  35 euros (The robot requires only one battery to work, and the charger should keep the battery topped up during use.) Alternatively when running the whole day, I used a eFuel switch Power supply 6V-15V Output 20Amps but it is not really enough for the full robot. So I’m currently using a 6V 60Amps Switching Power Supply. Here is a link for a 6V 50Amps:  http://www.ebay.ca/itm/New-6V-Power-Supply-300W-6V-50A-Switching-Power-Supply-WITH-CE-/182703380182?hash=item2a89f856d6:g:dJ4AAOxyXHpSTJZ-
2x Mini PC speaker 8Ohm 10W
Mini amplifier 6V
1xPIR sensor retriggered
Cables and wires
Speaker_size1

Stomach:
High stomach: 2x Hitec HS805BB
Mid stomach: 2x Hitec HS805BB  or HK15338
Ribbon cable length:
Nervo board to neck——————————— ribbon length10cm
Nervo board to head (Eyes/Jaw)—————- ribbon length55cm
Nervo board to shoulder 3xribbon————– ribbon length35cm
Shoulder to Arm————————————– ribbon length 30cm
Shoulder to hand————————————- ribbon length30cm
shoulder to fingersensors————————- ribbon length30cm
Nervo board to stomach————————— ribbon length30cm
Latest Configuration with NUC:
CPU: 8th Gen Intel i7 8550 Quad Core 4,0ghz
SSD: 256GB (OS + Myrobotlab)
HDD:500GB ( just because I had a spare hard drive)
RAM: 32GB
Graphic: Intel UHD Graphics 620
Connectivity: HDMI, Mini-DP, Gigabit Lan, 2*USB3.0, 2*USB2.0,
WIFI & Bluetooth: 2.4G/5G Wifi B/G/N/AC+bluetooth
Size: 113mmx108mmx30mm
OS installed: Windows 10 pro and Linux Ubuntu
Tablet Lenovo connected as screen via hotspot to control wirelessly the PC (Tablet model Thinkpad8 2GB RAM, 128GB ssd, Processor 1,46Ghz)
Connected devices controled by MRL:
1x USB3.0 Hub 8 ports
1x Kinect ONE or Orbbec Astra (i can switch between, I do not recommend the kinect ONE)
2x Arduino Mega
2x Nervo Boards
1x Arduino Nano
3x NeoPixel
2x HC-SRC04 sensors
1x PIR sensor
10x finger pressure sensors
2x Hercules webcam
1x USB sound card
1x Logitech H600 headset wireless
2x loud speaker 10watt
1x power supply 6V 60Amps which can be replaced by a 6V12AH battery pack
 

Older configuration:
Using a Lenovo Touchpad 8″ tablet with a 8port Hub powered by a Powerbank 10000mAh 5V. The Tablet runs either under Windows8 or 10, and can be configured to run with Linux. It is a true mini PC. You will need a OTG+Charging special cable for this Lenovo Tablet. I had a hard time to find it, which is very strange. Carefull other similar Tablet brands cable will not work.

This is the keyboard I bought:
https://www.amazon.com/Keyboard-TOUCHPAD-EXECUTIVE-Bluetooth-Detachable/dp/B017HLXESO
I was expecting to be able to use the case for travelling but unfortunately there is a serious issue with the size. Although the seller pretends to sale cases that fit 8″ tablet it is truly impossible to fit the tablet.

So you are advised about the issue…

Beside that the keyboard works fine, with sometimes a loss of connection but it automatically reconnects anyway.

 

The PowerBank+8 port HUB USB3.0 powers through USB:

the tablet Lenovo
the Arduinos
the cameras
the sound amplifier
Kinect
I purchased a 8 port HUB USB3.0 to have extra ports and it works fine with the OTG cable and the Lenovo Tablet. If you do not use the powerbank, it’s important for to power the hub to have a supply that can deliver at least 5v4Amps, because we hook many USB devices that require each 500mAh.

 Substitute possible tablets but not tested:
Venue 8 Pro 5000 (5855) (Should fit according to the specs size, the OTG cable(Charge+Data transfer) is not possible to find according to some users)
Jumper EZpad Mini3 Windows 10 8.0 inch 2GB/32GB (no need for otg+charge because of seperate charge and USB3.0) Should fit in the back of the robot.
Insignia™ – 8″ – Tablet – 32GB (Some builders reported this tablet to be junk)
KOCASO 8 Inch Windows 10 HD Tablet PC Computer (Too small, will need a printed adapter)
Chuwi Hi8 Pro 8″IPS Windows10 (Should fit according to the specs size)
NUVISION, Full HD 1920X1200 IPS Signature Edition tablet. 8″(Too small, will need a printed adapter)
Kinect 360 battery powered with  10 AA rechargeable batteries of 1,2v 2500mAh.

image

#############################################################################

After many tests with the OdroidU3 and the Raspi2, I came to the conclusion that the Arm processor were too slow to obtain a correct FPS value from the cameras, which lead me to go for another option.

This is abandoned:

1x Mini Touchscreen display :    (Displays/7_17_78_cm_Display_Set_mit_Touchscreen_LS_7T_HDMI_DVI_VGA_CVBS)
1x Odroid U3:  (ODROID_U3_Einplatinen_Computer_Cortex_A9_QuadCore_2_GB.html)
Installing Ubuntu on SD card for Odroid: procedure to flash s/w release
1x Odroid U3 batteries: (ODROID_U3_ODROID_UPS_USV_LiIon_3_Ah.html)re
1x Mini bluetouth keyboard: (Mini_Bluetooth_Keyboard_mit_Touchpad_DAYCOM_BTK_260T)
1x emmc or mini SD card class10
1x Odroid Batterie 3v Bios saver.
1x Fan Odroid processor cooler
1x Wireless dongle
1x Bluetooth dongle
1x HDMI cable to mini HDMI
############################################################################

 

Servos in order of my preferences for the hand:
HK15298B  (Strong torque 20kg , no noise, never burned, 90degree)
HK15298    (Strong Torque 15kg, noisy, never burned, 90degree)
MG996R    (Low Torque 10kg, a bit noisy, burn sometimes, 180degree)
MG946R    (Middle Torque 12kg, a bit noisy, burn sometimes,180degree)
MG995      (Low Torque 10kg, a bit noisy, burn very easily, 180degree)
These are servos I have tried. There is other servos that can fit the required size specifications. All these servos need to be set with a Min, Max within the software because their rotation in degree varies. Each finger of the InMoov hand has a different extension, retraction length.

 

Alternative Servos  that maybe can fit:
For the hand:
TGY-5521MDHV (24kg torque, should fit)
JX PDI-6221MG(20-36kg torque, fit, only 60° of rotation??)
RS-550MGC-HV (11.2kg torque, should fit)
HS-311  (3.5kg torque, should fit)
XQ-S4020D  (21.5kg torque, should fit)
For bicep, shoulder and torso:
Savöx SV-0235MG (35kg torque, fit)
TS-80 Tower Hobbies giant scale(24kg torque, identical to HS805BB)
CYS model S8218  (40kg torque, does not fit, needs adjustment, issue software with attach/detach)
HK15338 (25kg torque, fit perfectly, needs resistors, reversed polarity)
HS5805MG(27,5kg torque, should fit)
PDI-HV2060MG jx (60kg torque, fit good, reversed polarity)
FS6535M (33 kg torque, fit good)
For the eyes:
Towerpro SG91
TowerPro SG92R
For stomach:
Savöx SV-0235MG (35kg torque, do not fit needs modifications)
TS-80 Tower Hobbies giant scale(24kg torque, identical to HS805BB)
CYS model S8218  (40kg torque, does not fit, needs adjustment, issue software with attach/detach)
HK15338 (25kg torque, fit perfectly, needs resistors, reversed polarity)
HS5805MG(27,5kg torque, should fit)
PDI-HV2060MG jx (60kg torque, should fit)
