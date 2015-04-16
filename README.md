# iot-arduino
This repository contains sample(s) for connecting Arduino devices to the IBM Internet of Things Foundation with a DHT22 sensor.
I include all the libraries needed to run out of the box this sketch.
Just connect the DHT22 to digital pin 2.


##### MUST MODIFY:

firstly you must know that this code just works with devices that they already registered in the bluemix platform with a specific MAC address, Device type, organization and password.

Just you need to modify the code:

CLIENT_ID "d:YOUR_BLUEMIX_ORGANIZATION:YOUR_DEVICE_HERE:MAC_HERE"
MS_PROXY "YOUR_BLUEMIX_ORGANIZATION.messaging.internetofthings.ibmcloud.com"
AUTHTOKEN "BLUEMIX PASSWORD OF THE DEVICES HERE"

an example of mac addres: 

byte mac[] = { 0xAD, 0x00, 0x11, 0x22, 0x11, 0xDA };
MAC FORMAT IN CLIENT_ID: AD00112211DA
 
