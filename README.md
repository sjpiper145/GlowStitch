# GLOWSTITCH LEDS 
Open Source Hardware – [CC BY-SA 4.0 Licence](https://creativecommons.org/licenses/by-sa/4.0/)

# What are GlowStitch LEDs?
GlowStitch LEDs are flexible, paintable, machine sewable, hand sewable, and colorful LED lights. Perfect for hobbyists, makers, cosplayers, and teachers, they are the ultimate all-in-one crafting product for soft circuits, paper circuits, and so much more. Made from flexible PCBs, they are the most versatile way to get started with electronics and crafting projects.  All you need is some conductive fabric tape and a battery holder to make a circuit.
These will be launched as a project with [Crowd Supply](https://www.crowdsupply.com/makerqueenau/glowstitch-leds) very soon, where you can read full details on the project.  
The build process has been documented on the [Hackaday Project page](https://hackaday.io/project/186907-machine-sewable-led-strips).

# Why Open Source? 
The aim of this project is to make electronics easier and strip away the things that make it hard.  Releasing the circuit board designs makes it easier for others to get involved and design their own compatible modules, building up a larger variety of GlowStitch parts.  The faster we can work, the more things we’ll build and the better we’ll get at things like innovating in wearable tech and edutech spaces.  
I encourage you to download these blueprints and design your own modules for custom projects, interesting applications, and commercial products.  This will enable the creation of much larger custom projects where you might require more specific LED colours for group projects, art installations, conference badges and much more.  By doing this I will be delighted to know that you are inspiring and educating others and maybe even learning some circuit board design skills yourself.  

# What’s included
Included in these files are the following types of GlowStitch LEDs, which all include editable KiCAD files, and renders. To make these, you'll need to export them as a gerber in KiCAD and send to a PCB manufacturer.

##	x1 LED Strips
- Panel size: 100 x 100 mm
- Strip size: 22 x 6 mm
- Panel includes 40 LED Strips
- Requires a total of 40 0807 size LEDs to assemble

![x1 LED Strips Panelised Front Render](https://user-images.githubusercontent.com/7828884/192925136-33a7f0f9-4989-4f67-bec8-f4ff0f6b66d9.jpg)

##	x5 LED Strips
- Panel size: 90 x 80 mm
- Strip size: 32 x 6 mm
- Panel includes 20 LED Strips
- Requires a total of 100 0807 size LEDs to assemble

![x5 LED Strips Panelised Front Render](https://user-images.githubusercontent.com/7828884/192925227-6b5b798c-6f26-4996-93d8-5ae677a26db2.jpg)


## x12 LED Ring  
-	Panel Size: 70 x 54 mm 
-	LED Ring Size: 60 x 44 mm
-	Panel includes 1 LED Ring
-	Requires a total of 12 0807 size LEDs to assemble

![Glowstitch LED Ring Front Render](https://user-images.githubusercontent.com/7828884/192925258-824bff5c-9bab-4c85-b85d-7ccb6652d5a5.jpg)

##	Coin cell battery holder
-	Battery Holder Size: 37 x 38 mm
-	Requires x1 Coin Cell Battery Holder
	https://www.aliexpress.com/item/33038214773.html
-	Requires x1 SMD Slide Switch:
	https://www.aliexpress.com/item/32885421103.html
- M3 x 2mm Screws

![GlowStitch Coin Cell Holder Front Render](https://user-images.githubusercontent.com/7828884/192925295-fda27ba8-d813-43d7-964c-d65ad5e09edb.jpg)

##	AAA Battery Holder
-	Battery Holder Size: 70 x 36 mm
-	Requires x1 AAA Battery Holder
	https://www.aliexpress.com/item/1005002935544616.html
-	Requires x1 SMD Slide Switch:
	https://www.aliexpress.com/item/32885421103.html

![AAA Battery Holder Front Render](https://user-images.githubusercontent.com/7828884/192925377-833fd824-058e-48f6-8e6e-7a2e9ef7e3f0.jpg)

# How to use these files

Whatever you make, I’d prefer if you labelled it with the project name ‘GlowStitch’ as attribution to the project.  Please note the variety sheets with space artwork showcased on the Crowd Supply campaign will not be available here.  I've included the editable KiCAD files in the folders above, to have these made you'll need to export the gerber files and send to your manufacturer.  After the crowdfunding campaign is complete they will also be available through PCBWay’s module store if you’d prefer to just click the purchase button.   

# Tech Specs 
All the LEDs used are 0807 size, about half the size of a grain of rice.  You can make these up with any colour of LED you like, but make sure to choose the same LED colour in a single strip otherwise your LEDs will not be uniformly bright. If you are planning to hand-solder these in your own run of LED strips, make sure to get yourself some proper SMD (surface mount) soldering equipment rather than using a large soldering iron. This includes a reflow plate, reflow oven or hot air reflow station, plus solder paste and a good pair of tweezers. The tabs on the LED strips are designed for 8mm size fabric conductive tape. 

# Design
This design is optimised for flexible PCB manufacture, including wavy traces and teardrop ends to reduce the potential of traces snapping from metal fatigue.  There is also a silkscreen ‘swoosh’ on the positive side of the strips to make it easy to identify which side is which when the ends are covered with tape.  
These designs are arranged in a square frame already, which is called ‘panelising’ the design.  This makes it easier for the factory to manufacture.  
![x5 LED Strips close up](https://user-images.githubusercontent.com/7828884/192927069-e23c2f7d-71bc-4c4c-94ea-7088fc57df42.jpg)

While coin cell battery holders are the smaller source of power, they also present a swallowing hazard for young children.  I have added a small screw hole to add an M3 size screw below the battery to make it harder for a child to remove. I strongly recommend using the AAA battery holder instead if you are in an edutech space or have young children around your house.  

These designs may change as I update them with improvements. 

# Manufacturing Specs
To get the flexible gerber files manufactured, you’ll also need to specify these manufacturing details as well as the panel size detailed in the file descriptions. 
- 1 Layer
- Black Soldermask / Coverlay
- White Silkscreen
- ENIG finish
- Polymide Flex material, 0.1mm thickness
- No stiffener

The battery holders can just be made from a standard manufacturing process, default settings are generally fine. 

# Did you make some? 
I’d love to see and share your project if you end up making something with these.  You can tag me on twitter using [@sjpiper145](https://twitter.com/sjpiper145), use the hashtag #GlowStitch and/or send me an email at steph@piper3dp.com.  


