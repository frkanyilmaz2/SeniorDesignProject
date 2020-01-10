# SeniorDesignProject
E-Attendance using Bluetooth Beacon Technology

# Introduction

  Bluetooth beacons are hardware transmitters - a class of Bluetooth low energy (LE) devices that broadcast their identifier to nearby portable electronic devices. The technology enables smartphones, tablets and other devices to perform actions when in close proximity to a beacon. Bluetooth beacons use Bluetooth low energy proximity sensing to transmit a universally unique identifier picked up by a compatible app or operating system. The identifier and several bytes sent with it can be used to determine the device's physical location, track customers or trigger a location-based action on the device such as a check-in on social media or a push notification. 
  
  Bluetooth beacons differ from some other location-based technologies as the broadcasting device (beacon) is only a 1-way transmitter to the receiving smartphone or receiving device, and necessitates a specific app installed on the device to interact with the beacons. This ensures that only the installed app (not the Bluetooth beacon transmitter) can track users, potentially against their will, as they passively walk around the transmitters.

# Motivation

The motivation of this project is keeping track of the attendance of a class by using Bluetooth beacons. Without this technology, lecturers have to keep track of the attendance either on paper or by using student ID card system. The problem with the said solutions is that, students can sign other students name who are not present at the lecture time or use their cards to sign in. My project offers a solution to this problem.

Nowadays smartphones are pretty common. Every student has a smartphone that supports Bluetooth. The students will install The Scanner App on their phone which supports BLE. And every classroom will get a beacon device installed. These devices advertise the name of the classroom they located in with a low signal range. In order to sign in, the students will have to be present close to the beacon device. The Lecturers then, will be able to see who is in the class on their phone by using the Displayer app.


The Advertiser app: https://github.com/frkanyilmaz2/Advertiser

The Scanner app: https://github.com/frkanyilmaz2/Discovery

The Displayer app: https://github.com/frkanyilmaz2/Displayer
