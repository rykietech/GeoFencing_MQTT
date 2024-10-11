GeoFencing Using MQTT  broker
--------------------------------
A flutter app, using MQTT to send location data to a subscriber server hosted on my windows pc, meant to show an IOT use case for geofencing

In order to run these scripts, the following are required:

Android Phone, Windows machine.

**For the android phone scripts, flutter is required. Please refer to the following link in order to install flutter.**
>https://docs.flutter.dev/get-started/install/windows
>$ flutter doctor

**from there you may see that you need to unstall android sdk. to do so, please follow this link**
>__https://docs.flutter.dev/get-started/install/windows#install-android-studio__

**Once you have all of this set up you will need to copy the presented scripts into your lib folder**
>__\flutter_projects\myFlutterApp\lib (main.dart and home_page.dart located in the flutter_scripts folder).__


**In the terminal please run the following package retreivals.**
>$ flutter pub add geolocator $ flutter pub add geocoding

**You will then need to add the following to your AndroidManifest.xml located at android>app>src>main**
>__Add it above the line, directly below the package line.__

**if you have any further issues installing geolocator packages, please refer to this link https://pub.dev/packages/geolocator/install**
>$ flutter pub add mqtt_client if you have any further issues installing mqtt packages, __**please refer**__ to this link https://pub.dev/packages/mqtt_client/install

**From there, please choose to run the app on a compatible android device as I do not think it will work using the chrome emulator.**
**It should also work using the regular android emulators but.. whats the point? you can't move around with that.**
>To run the mqtt_subscribe scripts, you will need python3 installed.
>**please refer** to the following link to download and install python 3 if needed __https://www.python.org/downloads/__

**The geolocator packages are required $ pip install geopandas or $ py -m pip install geopandas**
>**please refer** to this link if needed https://geopandas.org/en/stable/getting_started/install.html
>The broker used is the open test broker located at https://test.mosquitto.org/

**Below shows a screenshot of the results**
>![image](https://github.com/user-attachments/assets/50966c63-ecf9-4f89-9c5b-75813e471d68)
