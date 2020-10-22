# rape-mugging-alarm-raspberrypi
I am making a low-cost safety alarm from a Raspberry Pi Zero.

This is inspired by a recent interest in Raspberry Pis and ring wearables, such as the beautiful yet exorbitantly priced Siren.

## Materials List
From Adafruit:
- 1 x Adafruit MiniBoost 5V @ 1A - TPS61023[ID:4654] = $3.56
- 1 x Raspberry Pi Zero W[ID:3400] = $10.00
- 1 x 16mm Illuminated Pushbutton - Yellow Momentary[ID:1441] = $1.50
- 1 x 16mm Illuminated Pushbutton - Red Momentary[ID:1439] = $1.50
- 1 x 16mm Illuminated Pushbutton - Blue Momentary[ID:1477] = $1.95
- 1 x CR2032 Lithium Coin Cell Battery[ID:654] = $0.95

This would have qualified for free shipping, but the lithium coin cell battery can't be sent through USPS so I paid $10.55 in shipping (whoops).
You can separate the order into lithium battery and everything else to get the free shipping and bring down that cost.

From Amazon:

- UST JetScream Floating Whistle, 122dB, Orange
Sold by: Amazon.com Services LLC
$6.99
- Micro Center 32GB Class 10 SDHC Flash Memory Card SD Card (2 Pack)
Sold by: Micro Center
$10.49
- GPS Module GPS NEO-6M(Ar duino GPS, Drone Microcontroller GPS Receiver) Compatible with 51 Microcontroller STM32 Ar duino UNO R3 with IPEX Antenna High Sensitivity for Navigation Satellite Positioning
Sold by: MakerFocus
$11.99
- Shapenty Black Plastic Shell Dip Type CR2032 Vertical Coin Button Cell Battery Sockets 3 Pin Holder Case, Pack of 20
Sold by: Shapenty
$6.49

I could've gotten a GPS module for $3.95 from AdaFruit (Passive GPS Antenna uFL - 15mm x 15mm 1 dBi gain), so that bites.
I'm not sure if GPS is necessary with the Raspberry Pi Zero W's built-in wifi.

I am going to borrow solder, solder iron and station, and wire from a friend.
I will update with what the casing costs once I'm done putting this together.

Overall, if the purchases are done optimally and the purchaser lives in the U.S., I estimate the total investment in this system to be $47.38 with some leftover parts.
Doing a price comparison, unfortunately my system does not hold muster compared to a flood of car keychains with sirens on them retailing for $15-20. However, I will still finish the project and see how it goes. My system does have the advantages of being highly customizable, having a warm yellow alarm option of silently texting friends/family/or police, and being in my humble opinion way better looking than most of those keychains.

## Current planned functionalities
- Silent Alarm to discreetly text family, friends, and/or local police. 
  There will be multiple levels to this, like a yellow alarm "I feel nervous, this is my location."
  or "I feel nervous, call me." and a red alarm "Call the police, I'm in danger" with a location sent.
- Very loud whistle sound.

## Things I'm thinking through
- I want to make this system easy to carry around and hide on someone's person. 
I think this will change depending on who's using it e.g. a man, a woman, an elderly person, a child, a middle of the road aged person,
a person of color who might get trigger shot if they reach into their clothes.
- I want to make this system self-sustaining or low maintenance power wise.
- I may want to integrate the Raspberry Pi into a wearable.

## Advantages of this type of system:
- It is less steps than navigating through a smart phone - this saved time can be life saving.
- It should be low cost.
- It's fun to make and share if you are an open source/DIY enthusiast. It is made for minorities especially in mind, so there's an added bonus of 
  supporting diversity in the maker community.
- It does not stop working if your phone is taken or has run out of charge.
- It is not tied to an app store or phone functionalities.
