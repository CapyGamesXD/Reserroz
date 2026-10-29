---
title: "Reserroz"
github: "https://github.com/CapyGamesXD/Reserroz"
description: "An inexpensive Flipper Zero Wi-Fi Devboard! The original dev board costs £35 (39 euros!!!)! When I saw this, I thought it was a lot! For fun, I plugged an ESP32 into my Flipper and flashed the firmware, and it did everything the official one does with a £2 product! The main thing lacking from the ESP32 alone is the convenience! Having to plug in 4 cables and carry around a thick (several mm thick!) and kinda ugly ESP32 with you! I wanted something in-between, hence, Reserroz! I decided on the name by using Google Translate (English to Latin). The name comes from the Latin verb for opening or making accessible (resera), which reflects the nature of this project! :D"
created_at: "2026-10-29"
total_time: "9h"
---

# October 29, 2026: I designed the PCB!
<!-- fabricate:entry 1537 -->

Being my first devboard PCB, I referenced a few sources to make sure I didn't do anything too wrong. It took a LONG time! I am using the AMS1117 voltage regulator with an ESP32 S3 Mini 1 (similar to the chip used on the official devboard, but smaller) which goes for £3-5 apiece - likely the most expensive part of the project, similarly, not one you'd want to cheap out on!

Additionally, I designed a cute logo for it (visible on the board image below!)
Routing was a challenge! I tried to put the main smaller components close together to minimise resistance (important for certain components) and make it look cooler XD 
I decided on USB-C, because it's the best port for compatibility and ease-of use. I also added diodes on the 5V inputs to prevent someone plugging the cable in while it's on the Flipper from damaging either device. I took extra care to make sure the antenna was clear of anything that could affect its performance, since this is a WiFi board!

Really excited to have my first log on Fabricate done! Thanks for reading!

![](https://fabricate.hackclub-assets.com/936db6a17c84a0719431f3306ec346b05f2f5007df58cca92d0499eb0cf6ab99/image-png/Screenshot%202026-10-29%20at%2016.45.53.png)

**Total time spent: 6h**

# October 29, 2026 (entry 2): Updated the PCB!
<!-- fabricate:entry 1549 -->

I added an LED and passthrough for some essential Flipper pins! I also improved the schematic, reducing the number of messy links, replacing them with nets! I'm now going to check how much the PCB costs to manufacture (this is the scary part :O)
Thanks for reading!

![](https://fabricate.hackclub-assets.com/a57a62bb21b95f9ee294d26c8a8c6a94a6cb0e80f58321e5af903980a991b326/image-png/Screenshot%202026-10-29%20at%2019.01.53.png)
![](https://fabricate.hackclub-assets.com/7cee8d9d1ea157b6e33ee9dc1e6d7c655774869a63d748514273dc174a149105/image-png/Screenshot%202026-10-29%20at%2019.03.20.png)

**Total time spent: 1h 30m**

# October 29, 2026 (entry 3): PCB Exporting and cost comparison
<!-- fabricate:entry 1551 -->

I exported using a plugin, (had to do it a few times), then found that the PCB in its current state was very expensive. I changed up some settings and evaluated costs to reduce the price and find a good configuration.

![](https://fabricate.hackclub-assets.com/6e29a6f5c0022d996882f2625ea9bb1e3fdd1ed00c1bed3adea943ba45889937/image-png/Screenshot%202026-10-29%20at%2020.08.57.png)

**Total time spent: 1h**

# October 29, 2026 (entry 4): Finishing up!
<!-- fabricate:entry 1553 -->

Finishing up the project, preparing to submit!
I made a GitHub repository, exported all the files and set them out properly!
I'm currently adding the journal.md file and filling in the other requirements.

![](https://fabricate.hackclub-assets.com/577ba2956fed9cb64f68860e43399d28abef74fa9f513add7a3b6805223d5d48/image-png/Screenshot%202026-10-29%20at%2020.42.52.png)

**Total time spent: 30m**
