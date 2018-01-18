---
layout: project
type: project
image: images/Arduino-300x300.png
title: Tamagotchi
permalink: projects/tamagotchi
# All dates must be YYYY-MM-DD format!
date: 2016-10-12
labels:
  - Arduino
  - MIT APP Inventor
  - Android
summary: A sub-project that I completed for my EE296 sophomore project. 
---

<img class="ui image" src="{{ site.baseurl }}/images/tamagotchi.jpg">

Tamagotchi is a handheld digital pet that kids can interact with as raise. It goes through many different life cycles depending on how you interact with it. 

We created a simple app using the MIT App Inventor which is the Tamagotchi itself. The app connects via Bluetooth to our circuit which mainly consists of a photoresistor, thermistor, moisture sensor, and Bluetooth transceiver. Using the photoresistor, the app says if it is too dark when it gets dark. Using the thermistor, the app says if it is too hot. The moisture sensor is used when the app feels it is thirsty or drowning. If all conditions are good, the app will say it is happy.

In conlusion, the app and circuit worked perfectly together only giving us errors that pertained to the Bluetooth transceiver. The Bluetooth transceiver was definitely the most annoying component to work with because of how it performs when it is connected wrong or differently. Sometimes the Android device wouldn't even show the Bluetooth transceiver.
