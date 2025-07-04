---

title: "rc\_speedway"
author: "Kiyan Kesheh"
description: "50 mph rc speedster!"
created\_at: "2025-03-14"
---

## Day 1 (03/14/2025)

Spent the whole day researching what components would be best for a high-speed 1/10 scale RC car. My main goal was to build something that could reach 50+ mph without breaking the bank. I compared a ton of different motors based on torque curves, RPM limits, and KV ratings. After some digging, I decided on the **Surpass Hobby Rocket 3650 3900KV motor**. It had solid reviews and a proven track record in lightweight RC speed builds. For the ESC, I went with a **60A unit** that could handle high amp draw under full throttle without thermal shutdowns.

To power the whole setup, I picked **HOOVO 4S 5200mAh 100C LiPo batteries**—plenty of discharge capacity to handle speed pulls without sag. For control, I selected the **Flysky FS-iA6B 2.4GHz receiver**, mostly because it’s affordable and works with my existing transmitter.

I also looked into tire options. I learned that regular rubber tires tend to balloon at high speed, which messes with handling. Belted slicks or foam tires are the way to go if I want straight-line stability. I’ll hold off on tires until I figure out my gearing.

Finally, I made a full BOM (Bill of Materials) on AliExpress. I calculated everything including shipping and taxes. The total cost at this stage was **\$129.49**, which leaves plenty of room in my \$400 budget.

---

## Day 2 (03/25/2025)

Started sketching the layout of the electronics and components. Since I don’t have a specific chassis yet (intentionally keeping it open-ended), I focused on a modular layout that could work with multiple 1/10 scale frames. I drew rough diagrams of motor placement, ESC position, and battery tray.

One thing I made sure of was to plan cable routing paths early. I want the build to look clean, so I decided to run ESC wires under the battery tray using printed channels. For the receiver, I planned to mount it vertically to keep the antennae free of signal obstructions.

Also spent time looking at pinion and spur gear combos. To hit 50+ mph, I’ll need aggressive gearing, but I also don’t want to overheat the motor. I started looking at aluminum spur gears for durability under load. No purchases yet, just window shopping and taking notes.

---

## Day 3 (04/10/2025)

Took the sketches from Day 2 and turned them into a Fusion 360 model. I made a prototype electronics tray that can be mounted to most chassis using zip ties or screws. Included slots for zip ties and wire guides to avoid messy wiring later on.

Also created a battery tray that would work with my 5200mAh LiPo. Printed it in **PETG** to withstand heat and flexing. Used the following print settings:

* Nozzle Temp: 230°C
* Bed Temp: 80°C
* Infill: 50% Gyroid
* Layer Height: 0.2 mm
* Print Speed: 75%
* Slicer: Cura

The tray came out clean and fit the battery well. This gave me confidence to move forward with more printed parts. I also added all part numbers and links into an Excel sheet and uploaded it to the GitHub repo I started for this build.

---

## Day 4 (05/03/2025)

Finally started installing components. Mounted the 3650 motor using a basic **540-size aluminum motor mount**. Fit was snug, and I aligned it properly to avoid mesh issues later. ESC was mounted just behind the battery tray, and I gave it airflow clearance to help with cooling.

Had to reprint one of the wire channels after realizing the insulation on my **12 AWG** wires was thicker than I expected. Cut the channel deeper and used a soldering iron to smooth it out.

I also printed a custom receiver mount and installed it near the servo bay. Tucked in the wires and added foam padding for shock absorption. Tried to paint the battery cover with acrylics, but it instantly peeled off the PETG. Forgot to sand and prep—classic mistake.

---

## Day 5 (06/30/2025)

Today was the big soldering day. Got up early and knocked it all out in one go. Soldered motor wires to the ESC, and the joints turned out clean. Connected power leads and verified voltage with a multimeter. Receiver powered on instantly, and it **bound to my transmitter on the first try**, which was a nice surprise.

Throttle and steering channels both worked perfectly. Servo centered without any twitching or calibration issues. Zip-tied the wiring and used heat shrink tubing wherever possible to protect joints. The whole layout is compact and solid.

Weighed the final build with batteries. It’s not ultra-light, but that’s good—it should give me enough traction at launch. Took the car out for a quick spin down the alley, and even with 20% throttle, it took off fast. Didn’t push it yet. Next test will involve GPS speed tracking to see how close I am to the 50 mph goal.

I’m super happy with the progress so far. Project is nearly done unless I decide to upgrade the tires, body shell, or fine-tune gearing later. This was a huge learning experience, and I’m hyped to see how it performs on a full throttle pass.
