Geofencing - Starter code
========================

Solution code for Advanced Android with Kotlin Codelab

Introduction
------------
A geofence is a virtual perimeter defined by GPS or RFID around a real world area. 
Geofences can be created with a radius around a point location. 

Geofencing has a lot of applications including:

- Reminder apps, such as reminding you to pick up a prescription when you get to a certain destination like your pharmacy.
- Child location services, where a parent can be notified if a child leaves an area designated by a geofence.
- Attendance, where an employer can know when their employees arrive by the time they enter a geofence.
- A treasure hunt app that uses geofences to mark the place where the treasure is hidden. When you enter that place, you will be notified that you have won! - This is what you will be making in this codelab!


Pre-requisites
--------------
- The latest version of Android Studio.
- A minimum of SDK API 29 on your device or emulator. (This should still work on lower API levels but may look differenti.)


Getting Started
---------------
1. Download and run the app.
2. If you are running API 29 or higher, grant the "Always allow" permission; otherwisa, grant "Allow" for location permissions.

Note: If you are running this app on an emulator, you will need to use another app to pull location data from.
This is because geofencing relies on device sensors to detect the location of the device, which the emulator cannot access.
