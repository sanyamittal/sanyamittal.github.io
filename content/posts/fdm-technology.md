---
title: FDM Technology
date: 2024-09-26
tags:
  - Metal Additive Manufacturing
  - 3D printing
  - FDM Technology
---

# Introduction #

AM technologies are now widely being integrated into manufacturing operations in many industries. Adoption is, however, limited by the performance capabilities of any given technology and the extent to which it can deliver dependable and repeatable performance. To this end, manufacturers seek to fully characterize the performance of their equipment, software, and material so that uncertainty and risk is removed. 

Fused Deposition Modeling (FDM) is one such AM technology that is finding swift adoption by manufacturers for its simple workflow and outstanding range of permissible materials, enabling the highest levels of mechanical performance. The process is inherently simple. Thermoplastic materials are melted and extruded into ‘beads’ along a toolpath defined by the part geometry, in a layer-by-layer fashion.

# Types of FDM Printer #

When we talk about FDM 3D Printers, most of the time we tend to talk about the Cartesian version of the 3D printer but rarely do users know that there are four types of FDM 3D printers, namely: Cartesian, Delta, Polar and SCARA. The four types of FDM 3D printers are effectively used as per their applications. While the Cartesian 3D printer remains the dominant type of FDM 3D printer, other types like Polar and SCARA are quickly gaining an audience and finding new applications. It seems all the types of FDM 3D printers will have their niche market and usage.

## Cartesian 3D Printers ##

### Overview ###

Cartesian 3D printers are the most popular type of FDM 3D printers across the world. This printer is based on the Cartesian co-ordinate system, which uses three numbers to define the position of a point in space represented by X, Y & Z. The X & Y-axis represents the lateral and longitudinal position of a point, while the Z-axis represents the elevation of the point.
A huge majority of 3D printer manufacturers use this Cartesian coordinate system because it is one of the most fundamental coordinate systems used in a wide range of industrial and academic applications.

### Benefits ###

From a user’s point of view, having a Cartesian 3D printer secures you of a lot of stress that 3D printer owners go through during their early learning phase.
1. Being the most popular type, Cartesian3D printer owners can easily find experts to learn more or get professional help or troubleshoot their 3D printers. 
2. It also becomes easy to find replacement parts or a relevant community that own a Cartesian 3D printer like the one the user owns to share resources.
3. For a learner, the Cartesian 3D printer is comparatively easy to learn and easy to build and the structure is quite easy to understand.

### Disadvantages ###

Cartesian 3D printers have applications in almost all types of product manufacturing barring applications that are long or tall in size.

### Vendors ###

Some popular examples of Cartesian 3D printers are those from Ultimaker, Zortrax, Roboze, BigRep, etc.

## Delta 3D Printers ##

### Overview ###

Delta 3D printers are the second most popular type of FDM 3D printer. They can be easily distinguished from a Cartesian 3D printer due to their tall appearance. The unique structure as well is quite intriguing to look at and it’s a joy to watch the Delta 3D printer in action.
The printhead is connected to the three arms of the printer and they all operate in sync to print the layer of the object. The delta 3D printer works in a triangulation configuration and since the three arms work simultaneously, the build volume of the printer is not a cube but a cylinder and the base is a circle.
Instead of positioning the print head according to x, y, and z positions, each of the three arms changes its angle to position the print head on the build platform according to the model. Hitting the precise location is done by a series of trigonometric functions that consider the angle of all positioning arms.

### Benefits ###

1. The biggest benefit of a Delta 3D printer is its speed. The high speeds are possible as the extruder does not carry the weight of the stepper motor, and this weight reduction is translated into increased speed.
2. Another advantage of the Delta 3D printer is its height. It is tailor-made for creating objects that are taller like columns in architecture models and so manufacturers rely on the delta coordinate system when they want to build a 3D printer for manufacturing objects that have a higher Z-axis.

### Disadvantages ###

However, delta 3D printers do have a lot of problems. 
1. They cannot be used with Bowden extruders and so it limits the use of flexible materials. 
2. They also have a smaller base limiting the lateral size of the object to be manufactured. 
3. Besides, due to their size, they tend to be delivered in kits and new users find it hard to assemble such kits thereby keeping them away from this type of 3D printer.

### Vendors ###

Some popular examples of Delta 3D printers are Kossel – RepRap, Anycubic Delta, DeltaWasp, etc.

## Polar 3D Printers ##

### Overview ###

Polar 3D printers are not popularly used but still, they offer quite an interesting design. In a Polar 3D printer, the position of a point is defined only by two numbers i.e., an angle in 3D space and the separation distance (or radius) from a pre-defined centre. As a result, they use a circular grid instead of a square in a Cartesian 3D printer. The build platform of a Polar 3D printer can move left to right – back and forth and can also rotate while the arm (printhead) only moves in the Z-direction.

### Benefits ###

This way, much larger objects can be made in a smaller space.
Polar 3D printers have applications in building tall products like columns in architecture models, etc.

### Vendors ###

Polar3D is a popular example of a Polar 3D printer.

## Scara 3D Printers ##

### Overview ###

SCARA or Selective Compliance Assembly Robot Arm is a popular coordinate system employed in industrial robots. A SCARA 3D printer resembles industrial robots and offers greater freedom and flexibility when printing as it is not limited to a build platform and can move in all possible directions making it easier to print geometrically complex parts. Scara 3D printers move in the most similar way to human hands and print faster than Cartesian printers.
Currently, they have applications in the construction of structures like bridges, buildings, and even large-scale industrial projects.

### Benefits ###
print geometrically complex parts.
print faster

### Vendors ###

Dobot M1 3D printer, Robots used by MX3D to build the steel bridge in the Netherlands are great examples of Scara 3D Printers.

# Printer Components #

FDM printing is one of the most popular 3D printing methods available that challenges and inspires millions of creative minds in producing captivating 3D models creating a revolution in many industries such as healthcare and aerospace. In this article, we will discuss different 3D printer parts and how they function. We will also break down how you can increase the functionality of your printer and optimize your 3D prints.
Here, we have separated 3D printer parts into four categories which we will discuss in length throughout the article.
## 1. Mainboard ##

The Mainboard is the core hub of a 3D printer. It is where all the important work is processed as it is connected to all the electric components of a 3D printer. A properly functioning mainboard ensures the right motor movements, proper implementation of G-code, and lower print failure while ensuring a safe environment for printing. It increases the quality of the print, incorporates safety features, and continues to update the firmware. Through this, the users can customize certain features and optimize settings allowing them to explore the full potential of the printer. Some motherboards are designed to consume less power and work effectively without making annoying noise such as Creality CR-200B Silent Motherboard. Some of the chief parts of the mainboard include:
1. **Processor:** It works to convert the codes of the software to a bunch of instructions that the printer can understand. These processors tend to be either 8 or 32 bits. Firmware is a part of the motherboard that oversees the operational part of a printer managing different components throughout the process. It is software working as an intermediary between the slicer software and the hardware of the printer sending G-codes from the former to the latter. Firmware manages the following critical functions:
    1. **Movements of stepper motor:** Firmware interprets the instructions provided through G-codes and manages the stepper motors movements of the X, Y, and Z-axis
    2. **Temperature regulation:** To get quality prints, you have to print at the right temperature. Firmware controls the temperature of the hotend and the heated plate. This way the extruder melts the filament properly.
    3. **Bed levelling:** For better filament adhesion you must make sure that the build plate is levelled correctly. Firmware also has a role in this respect as it enables both manual and auto-levelling features. But all 3D printers don’t come with the auto-levelling feature so many of us find it a bit troublesome. In that case, you can get an auto bed levelling kit to avoid certain issues.
    4. **Cooling fans:** It regulates the cooling fans so the print layers cool down evenly lowering the risk of warping.
    5. **Safety features:** Firmware also facilitates end-stop detection and thermal runaway protection.

2. **Connectors:** This is where all the electronic 3D printer parts are connected either in the form of DuPont connectors, terminal blocks, or USB.
3. **Driver boards:** The role of driver boards is to interpret motor signals and commands so they can be relayed to regulate the movements of the 3D printer parts or components. A regular 3D printer has four drivers - one for the filament extruder and the rest three for the x, y, and z axes. The interface of the driver boards takes in the G-code commands and transforms them into electrical signals that regulate the supply of power to different coils in the motors, thus, managing their position and rotation. They have limit switches, endstops, tandem, and encoders to micromanage the precise movement evading collisions.
4. **Communications:** Your commands need to transform into G-codes and then be fed to the printer so it can follow them. You can send this program via an SD card or over WIFI.

## 2. Axes ##

A 3D printer mainly works in X, Y, and Z  axes. As the three axis moves in different directions it prints different sides of the model bringing forth the shape you were looking for. Depending on the digital design of the print and the coded instruction the printer moves its X, Y, and Z axis while the nozzle extrudes melted filaments in precise layers to form the print model.

The X-axis works on the horizontal movements of the printer. If the print head moves to the right part of the model, it prints specifically that part and the same is done for the left side too. 

The Y-axis represents the back-and-forth movements of the print head. Thus, when the print head shifts in the front it prints the front part of the model and the same happens for the back part. 

The Z-axis enables the print head to move vertically thus controlling the height of the model as it regulates the up and downshifting of the print head or the build plate. Because of the vertical movement, the nozzle deposits layer after layer of molten filament to give the print the desired height.

It’s important to understand the operating mechanism of the axis to fully comprehend how the printer works. This would help to readjust your design, calibrate the set parameters and learn proper maintenance to optimize the print quality.

## 3. Extruder ##

An extruder has two units: one is for pushing and pulling of filament, and another is for melting and extruding this molten filament. Its assembly consists of multiple parts which work simultaneously to complete the job in a correct manner, so we achieve high-quality print. Manufacturers create multiple types of extruders some are standard, and some are OPEN Source or custom-made extruders. Some extruders are using Granule or Pellet instead of filament. Some extruders have different materials like chocolate and can be used for any kind of material with some changes, but they have melting point and solidification in a limited range.

Bowden Extruder and Direct Drive extruder are the two of the most common types of extruders in the 3D printing industry. Both extruders have different mechanisms for pushing and pulling the filament and have different positions of hot-ends. This provides different advantages and disadvantages.

### Types of extruders: ###
1. **Bowden Extruder:** The filament travels through a tube and is fed from a certain distance to the Hot End because the motor is separated from the hot-end. This mechanism reduces weight, allowing for faster movements and lesser vibrations. In theory, it should produce more accurate prints at higher speeds because there is less movement to overcome. However, it is harder to print certain filaments like flexible ones, as the distance causes more oozing due to less effective retraction. Bowden extruders require better extrusion and retraction calibration.
2. **Direct Drive Extruder:** When the filament is fed directly to the hot end from the motor spindle, the motor is mounted on top of the hot end. This setup allows finer control over extrusion and is easier to work with. As a single unit, this type of extruder is ideal for high-speed extrusion and retraction, although it adds more weight to the moving x-axis.

### Bowden Extruder Parts ###

The Bowden extruder has two main parts: Cold End and Hot End. The filament is feeded through the Cold End which is then carried to the Hot End for melting. These are the main parts of the extruder, and both are further divided into subparts which are discussed in detail in the post further. 

1. **Cold End:** It is also called filament feeder as the filament is feeded at this end and then it carries the filament to the hot end while keeping a consistent pressure on the filament for a smoother extrusion.
    1. ***Dual Flanged Bearing:*** It provides counterforce for extrusion gear to make a good contact area with the filament. Nowadays manufacturers provide dual gear extrusion in which the bearing is replaced with another extrusion gear that drives through the same motor so it will provide more force over filament.
    2. ***Spring Arm:*** It is a piece of aluminum but is necessary for the proper working of the extruder. It provides a platform to connect the bearing and transfer spring force to the bearing which pushes the filament toward extrusion gear for good contact.
    3. ***Extrusion Gear:*** It has an important role in smooth print. It is the part that pushes the filament in the hot end and provides enough force to extrude the material. If extrusion gear is damaged or does not fit well on the stepper motor shaft it slips from the filament and the print may get worse due to slip of gear on filament. Extrusion gears come in many different designs according to their use. Each design has pros and cons. In most desktop 3d printers 20 or 16 teeth extrusion gear is used.
    4. ***Bowden Tube:*** It is used for two main reasons which are that it provides a guideway for filament between cold-end and hot-end and another reason is that it does not allow the filament to move wherein the air except towards the hot end. Bowden Tube is also smooth, so the filament smoothly flows between cold end and hot end.
Note: Bowden Tube is mostly used in Bowden type extruder but if you want to directly use your filament from dry-box without opening it to protect it from moisture, you can connect Bowden tube between cold-end and dry-box because it also provides an airtight seal if you use correct Bowden connector.
2. **Hot End:** This is where the inserted filament melts and extrudes in layers to build an object. The heating element sets the Hot End temperature according to the filament’s melting point and the nozzle then extrudes this molten filament onto the print bed for building the print. 
Hot ends can be made up of different materials. While the old hot ends (PEEK based) were able to print only with one or two materials, the new ones today can be used with a variety of thermoplastics. The maximum temperature limit was about 230°C. Now the most strong and durable materials for 3D printing (like Nylon, PET and Polycarbonate) extrude at temperatures above 240°C so the hexagonal all metal hot ends are used nowadays as they can reach a maximum temperature of about 320°C. They have active cooling to isolate the melt zone. A smaller melt zone means more control, therefore, cleaner retraction and lesser oozing which results in better print quality overall. Also, fewer parts and smaller size make it almost jam free and easier to clean unlike the PEEK based hot ends which used to jam a lot if not maintained properly. Tips for selecting the right Hot End:
- Check if it is compatible with the printer you have.
- Check the temperature range of the Hot End to ensure that it can melt the filament you work with.
- Check the right size of the nozzle based on your print requirement
- Check the heat-up time of the Hot End since rapid heat-up supports efficiency.

    1. ***Heat Sink:*** The heat sink is the upper part of the hot end and the entry point of filament from into the hot end. It guides the filament towards the heat block through a heat brake pipe. It also has a fan which helps it remain cool during the operation of the machine.
    2. ***Heat Break:*** It is the outer threaded pipe that has a PEEK layer and PTFE Tube for guiding the filament toward heat block smoothly. Also, as the name suggests, this component stops the heat from breaking and entering into the heat sink, so it resides between the heat sink and the heat block to keep the Hot End separated from the Cold End. Because of this, the filament does not get clogged. Generally, the heat break pipe is made of non-heat conducting material but now some manufactures also provide bi-metallic heat break which increases the non-conductivity of the heat break.
    3. ***Heat Block:*** The heating element from the heat block properly melts the inserted filament.

        1. *Heat Cartridge:* It is a high-wattage heating 3D printer part that acts as a source of heat energy which melts filaments. It is made of Ceramic. In the cartridge heater, nickel-chrome resistance wire is wound around the magnesium oxide core which is in the cylindrical alloy case and case is filled with magnesium oxide for better heat transfer. Never use an exceeded power rating heater because it will cause damage to the printer or accident.

        2. *Nozzle:* It is the tip of the Hot End and a tiny opening from which the melted filament extrudes. The nozzles need to be replaced repeatedly as the filament sticks to it after cooling down and clogs the nozzle. These nozzles come in different shapes, sizes, internal geometry, and material type. The print resolution and speed vary depending upon the characteristics of the nozzle. For example:  
In abrasive type material, you had to use stainless steel nozzle or any other hardened metal nozzle but for normal print material, you use a copper nozzle or brass nozzle.
The nozzle size is also important as Smaller Nozzle Size provides Smoother finish and more rigid and accurate parts whereas the bigger nozzle size is used to get faster prints, lesser support structures and better reliability. Nozzle sizes vary from 0.25mm to 0.75mm. The most common size is 0.5mm. 


    4. ***Cooling Fan:*** It is used to cool down the newly extruded filament layers to ensure that the next layer deposits evenly and securely on the previous layer thus preventing warping. The cooling fan also improves overhanging features, crisps the sharp edges, and results in good bridging capabilities. Some machines use only one fan, whereas others can have up to 3.  Something important to understand here is that not all cooling fans are created equal. Some machines use 25mm while others would use a 40mm size. Some fans are designed to blow at the mid hot end area, some are focused on the tip of the nozzle, and some have different shaped ducts.


## 4. Thermistor ##
It is a temperature sensor which checks the temperature of the heat- block print surface temperature so you can adjust it if needed to control the process of the extrusion for even flow. Thermistor resistance changes with changes in temperature. This value may differ for different kinds of manufactures, but the working principle is the same.


## 5. Print Bed ##

Some of the best print bed materials tend to be PEI, borosilicate, carborundum glass, or magnetic flex plates for their better print removal and remarkable adhesion qualities. Also, the print bed can be covered with PEI, PET or Painters blue tape to which the material adheres. All this lowers the risk of the print coming off the bed or warping. 
Heating the print bed before printing is important for the first layer as the filament sticks to a heated surface better, thus creating a strong foundation for the print. A heated print bed, with temperatures ranging between 40°C to 110°C, is required for all high temperature extrusion filaments like ABS, HIPS, Polycarbonate, Nylon.

Further, maintaining a steady temperature throughout the whole printing process ensures one-layer sticks to another perfectly, i.e. better adhesion between the layers, which results in a better structural integrity of the printed parts.
The things you should consider when selecting a print bed are filament compatibility, durability, adhesiveness, build volume of the printer, and print removal ease.
 
## 6. LCD DISPLAY ##

The LCD Display controller allows you to 3D print without the need of a computer connected or using a software host such as Cura. It needs an SD card to read the G-code instructions. The display allows more efficient space usage and frees up your computer for other tasks. It is perfect for day-to-day printing and will be used in the majority of the printing jobs.

## 7. Additional Features ##

By making some upgrades and changes you can enhance the functionality of the 3D printer. For that, you must do the following:
1. To accelerate the performance of the printer, install high-grade stepper motors, print beds, and hotends.
2. Update the firmware of the printer when available to enjoy the new features.
3. Add extra features such as a filament sensor, auto bed levelling sensor, and dual extrusion.
4. Upgrade the printer’s cooling solution by adding more fans.
5. Make frequent calibration of the printer for better printing accuracy.
6. Attune the slicer settings to lower filament wastage and improve print quality and speed.
7. Using an enclosed print chamber maintains a consistent printing temperature and protects from dust and debris.
8. Wi-Fi connectivity and LCD Touchscreens have become a fairly common feature, allowing better control and an easier file-transferring experience.
9. Working with filaments such as ABS can be dangerous as it produces harmful fumes. HEPA filtration is a way to filter the harmful particles and fumes produced during printing. It can entrap even microparticles and erratic organic compounds. HEPA filtration can upgrade the air circulation of a printer reducing health risks.
10. Some printers can be upgraded from single to multiple extruders. With multiple extruders you can print in multiple colors or materials simultaneously by assigning each extruder a specific color or material. The biggest benefit of multiple extruders is when you print you can set your support structures with a different material that can be dissolved in water or some other type of solvent.


# Materials #

The most common materials used in desktop FDM 3D printing are PLA, ABS, HIPS and PVA on a spool in reel form. Other materials used by the industry are nylon, glass polyamis, stereolithography (epoxy resin), wax, ceramics, photopolymers, polycarbonate and metals such as silver, titanium and steel.
Most materials can be found from different manufacturers and vendors at different prices. Furthermore, the Quality and the Properties will vary from manufacturer to manufacturer. Finding a good filament is an essential part of the 3DP workflow. You will get what you have paid for. There are new materials hitting the market every day and you will always be abel to find the right material for your project. This is an overview of the materials we have worked with and tested, but the market nowadays is not limited to only those!

## 1. Beginners Use ##

1. **ABS:** ABS is a very durable, strong and slightly flexible material. It is suitable for a large variety of purposes. ABS is used in automotive components, electronics assemblies, musical instruments, toys, protective cases, kitchen appliances, and is most famous as the material of Lego® toys. The material requires a heated bed, and it can be easily post-processed after printing!

| PROS                           | CONS                                                                     |
|--------------------------------|--------------------------------------------------------------------------|
| Excellent plastic properties   | Heated bed and/or chamber required                                       |
| Durable                        | Slightly smelly                                                          |
| Excellent for mechanical parts | Toxic when melted                                                        |
| Heat resistant                 | Tends to warp and in tall objects a layer separation (cracks) can happen |
| Easy for post processing       |                                                                          |

2. **PLA:** PLA is currently the most environmentally friendly material used in desktop FDM 3D printing. It is made from renewable sources of plant starch. The material is used in food packaging, bags, disposable tableware, feminine hygiene products, and even in diapers. It doesn’t require a heated bed and is non-toxic. In addition, for beginners PLA is considered as the easiest material to print with and it’s available in almost any color. You can get a high definition prints, but they will not be as strong or as durable as ABS products. The filament is not good for prints that will be exposed to high heat. Moreover PLA can be used as a supportive material for ABS designs with a dual or printers with multiple extruders.

| PROS                                               | CONS                                          |
|----------------------------------------------------|-----------------------------------------------|
| Bio-plastic                                        | Slow cooling down                             |
| Good smell                                         | Low heat resistance                           |
| Non-toxic                                          | Easier to break                               |
| No heated bed required                             | Limited post processing – sanding, gluing etc |
| High print speed                                   |                                               |
| Less wrapping and shrinking                        |                                               |
| Excellent for small and tall high-resolution parts |                                               |
| Hard or flexible variants                          |                                               |
| Many colors available and easy to paint            |                                               |

3. **HIPS:** HIPS is used as an alternative to ABS. Similarly, it is relatively strong, but more unlikely to warp and crack like ABS. Thus, it is easier to print with. Also, the low cost makes it the best choice among all other materials used in desktop FDM 3D printing for rapid prototyping, early design testing and educational purposes. Furthermore, HIPS 3D printing filaments are used as support material in printers with dual or multiple extruders, in order to provide structure to object with complex geometry. HIPS is Limonene soluble and it’s ideal for support structures, for parts with a lot of overhangs, moving interlocking parts of great complexity and more.

| PROS                           | CONS                |
|--------------------------------|---------------------|
| Excellent plastic properties   | Heated bed required |
| Durable                        | Slightly smelly     |
| Excellent for mechanical parts |                     |
| Heat resistant                 |                     |
| Easy post processing           |                     |
| Wide range of colors           |                     |

4. **NGEN:** nGen is co-polyester filament specifically designed for Desktop FDM 3D printing. It has a superior melt strength and dimensional accuracy. This material offers good bridging capabilities. And it handles overhangs better than most filaments. Objects printed with nGen show sparkling clarity and gloss. The filament is great for complex functional prototypes and 3D printed productions. Still it’s easy to print with!

| PROS                            | CONS                                 |
|---------------------------------|--------------------------------------|
| Low odor                        | Expensive compare to other filaments |
| Low emissions                   | Fewer colors available               |
| Suitable for small office space | Only one manufacturer                |
| Styrene-free                    |                                      |

## 2. Intermediate Use ##

1. **MAGNETIC IRON, STEEL, WOODFILL, COFFEE, COOPERFILL, BRONZEFILL – PLA:** All those are PLA base filaments with add-on fibers or powders of other materials like wood, steel, magnetic iron etc. Their main purpose is surface finish. Those materials are great for arts, concept models and even for some consumer end-products. Moreover, some high-end post processing techniques are suitable for those filaments like rusting, staining, polishing and the results could be very impressive and misleading that is not plastic.

| PROS                                  | CONS                                          |
|---------------------------------------|-----------------------------------------------|
| Great look and texture finish         | Not so durable & strong                       |
| Variety of post-processing techniques | Require specific (abrasive resistant) hot end |

2. **T-GLASSE/PETT:** T-glasse which is short for “Tough Glass”. It’s stiff and clear filament. The material is a highly translucent. It can reflect and transmit light and provides a great surface finish! T-glasse is the first 3D printing material to be approved by FDA as Food Safe and it’s 100% Recyclable. 

| PROS                     | CONS                                                  |
|--------------------------|-------------------------------------------------------|
| Food safe (FDA Approved) | Requires Special storage (absorbs water from the air) |
| 100% recyclable          | Prints slow                                           |
| Low odor                 |                                                       |

3. **TPU – NINJAFLEX & SEMIFLEX:** This is a rubber like filament that that has wide range of applications. It’s highly flexible and has a soft feel. Different flex-properties can be achieved when varying the number of outlines – shells – parameters and the percentage of infill. TPU – NinjaFlex and SemiFlex are great for functional prototypes like phone cases, hinges, shoe soles, watch bands etc. 

| PROS                       | CONS                                          |
|----------------------------|-----------------------------------------------|
| Extremely strong & durable | Requires a 3D Printer upgrade (in most cases) |
| Doesn’t require heated bed | Prints slow                                   |

4. **ALLOY 910 BY TAULMAN:** This is one of the strongest materials you can 3D print with! The tensile strength of 8,100+ PSI makes Alloy 910 as strong as Polycarbonate, but way easier to print with, because it warps 5 times less than PC! You can use Alloy 910 for height strength and stiff parts. Also, the material like all other nylon filaments has a wide range of chemical resistance!
5. **BRIDGE NYLON BY TAULMAN:** Bridge combines the strength of nylon 645 with the price of ABS and PLA filaments. Offers a better adherence to the printing platform, reduced water up-take from local humidity and reduced shrinkage that makes it easy to print. Printed parts from that material are stronger and more resilient than 3D prints from common materials like ABS and PLA.

## 3. Expert Use ##

1. **PVA:** PVA in 3D printing is used as a support material in printers with dual or multiple extruders, in order to provide structure to an object with complex form. PVA is water soluble and is ideal for base support material in some complex designs. Parts with moving features and lots of overhangs, such as building models, are possible because the supporting structure can be easily removed after printing to deliver a finished look.

| PROS                 | CONS                                              |
|----------------------|---------------------------------------------------|
| Recyclable           | Special storage required, because of air moisture |
| Bio-grade            | Hard to 3D print with                             |
| Nontoxic             |                                                   |
| Dissolvable in water |                                                   |

2. **POLYCARBONATE (PC):** Polycarbonate is one of the strongest materials for FDM 3D printing at the moment. The material in general is used in number of industries like medical, food, automotive, aeronautics etc. It’s one of the most used thermoplastics for engineering purposes now days. Another upside is that PC is biocompatible and can be sterilized. Lastly 3D Printed parts with PC are strong, durable, accurate, with great mechanical properties and heat resistant.

| PROS                        | CONS                                    |
|-----------------------------|-----------------------------------------|
| strong and durable          | high printing temperature (about 300ºC) |
| stiff and rigid             | expensive compared to other materials   |
| great mechanical properties | tend to warp a lot                      |
| biocompatible               | requires a heating chamber              |
 
3. **618 NYLON:** This material is recommended to experience users. It can be challenging to 3D Printing Print with, due to the warping and bed adherence. 618 Nylon is stronger than ABS and PLA, and more chemically resistant with lower coefficient of friction. 3D printed parts offer flexibility and strength.
4. **645 NYLON:** 3D Printed parts are strong still flexible. Suited for general industrial grade parts. Not easy to 3D print with due to warping and platform adhesion. 645 doesn’t emit any fumes when printed. Nylon 645 has the highest chemical resistance of all Nylons for 3D printing and is highly compatible where Nylon 6,6 is required!
5. **680 NYLON:** The 680 Nylon is pure polymer and it is FDA approved. This 3D Printing filament is great for clinical, food and medical industries. The filament itself is still not certified for those uses but it is in the process of! Testing is performed in compliance with US FDA manufacturing practice (GMP) regulations 21 CFR Parts, 210,211 and 820.

**PROS**

- When you need to make a print with extreme strength, durability and flexibility
- For end-use prototype that needs to be used and abused a lot, to test for optimal design
- For a replacement part that would coast a lot to buy otherwise
- Nylon offers a large variety of uses and has the most versatile list of properties
- You can dye nylon with interesting results. You can add variety of color effects, just make sure to dry your filament very well before use
- Suited for industrial grade parts
- High chemical resistance
- Lower coefficient of friction compared to other 3DP materials

## 3D Printing Materials Comparison ##

|                          |   ABS                                                                                                        |   PLA                                                                                                                                                                                    |   PVA                                                    |   HIPS                                                                                                       |
|--------------------------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
|   PRODUCED FROM          |   Petroleum                                                                                                  |   Plant starch                                                                                                                                                                           |   Petroleum                                              |   Petroleum                                                                                                  |
|   ECOLOGICALLY FRIENDLY  |   No                                                                                                         |   Yes                                                                                                                                                                                    |   No                                                     |   No                                                                                                         |
|   NOZZLE TEMPERATURE     |   210-250°C                                                                                                  |   170-220°C                                                                                                                                                                              |   190-220°C                                              |   220-250°C                                                                                                  |
|   BED TEMPERATURE        |   80-120°C                                                                                                   |   50-60°C                                                                                                                                                                                |   50°C                                                   |   80-120°C                                                                                                   |
|   HEATED BED             |   Required                                                                                                   |   Not required/Beneficial                                                                                                                                                                |   Not required                                           |   Required                                                                                                   |
|   PRINT SURFACE          |   PEI tape, PET tape, Kapton take                                                                            |   Blue tape/ PEI tape, PET tape, Kapton take                                                                                                                                             |   Blue tape/ PEI tape, PET tape, Kapton take             |   PEI tape, PET tape, Kapton take                                                                            |
|   ADDITIONAL COOLING     |   Not required/Beneficial                                                                                    |   Required                                                                                                                                                                               |   Not required                                           |   Not required/Beneficial                                                                                    |
|   SMELL DURING PRINTING  |   Smells bad /strong                                                                                         |   Smells sweet                                                                                                                                                                           |   Smells slightly                                        |   Smells bad /strong                                                                                         |
|   SOLUBILITY             |   Acetone                                                                                                    |   Hot benzene                                                                                                                                                                            |   Water                                                  |   (R)-(+)-Limonene                                                                                           |
|   GREAT FOR              |   Mechanical parts                                                                                           |   High definition parts                                                                                                                                                                  |   Support material for PLA                               |   Mechanical parts Support material for ABS                                                                  |
|   RECYCLING              |   Code #9                                                                                                    |   Code #7                                                                                                                                                                                |   N/A                                                    |   N/A                                                                                                        |
|   PROPERTIES             |   Durable Strong Slightly flexible Heat resistant                                                            |   Tough Strong                                                                                                                                                                           |   Water soluble Great film formation High bonding power  |   Durable Strong Slightly flexible Heat resistant Less warping than ABS                                      |
|   POST-PROCESSING        |   Easy sanding Easy gluing Easy drilling Easy dissolvable in Acetone                                         |   Sanding possible Limited gluing                                                                                                                                                        |   Dissolvable in water                                   |   Easy sanding Easy gluing Easy drilling Easy dissolvable in (R)-(+)-Limonene                                |
|   PROS                   |   Excellent plastic properties Durable and difficult to break Excellent for mechanical parts Heat resistant  |   Bio-plastic Good smell Nontoxic No heated bed required High print speed Less wrapping and shrinking Excellent for small high-resolution parts Hard or flexible variants Easy to paint  |   Recyclable Bio-grade Nontoxic Dissolvable in water     |   Excellent plastic properties Durable and difficult to break Excellent for mechanical parts Heat resistant  |
|   CONS                   |   Heated bed required Smelly                                                                                 |   Slow cooling down Low heat resistance Easier to break Limited post processing                                                                                                          |   Special storage required, because of air moisture      |   Heated bed required Slightly smelly                                                                        |

# Advantages and Disadvantages #

|   Advantages                  |   Disadvantages                         |
|-------------------------------|-----------------------------------------|
|   Budget-Friendly             |   Rough Surface Finishing               |
|   Filament Reusable           |   Warping is common                     |
|   Cloud Server Printing       |   Nozzle Clogging                       |
|   Less Complex                |   Longer Printing Time                  |
|   Easy Ergonomics             |   Layer Adhesion Problem (Layer Shift)  |
|   Variety of Material Choice  |   Weak in Strength                      |
|   Easily Portable             |   Bed Calibration is Needed Frequently  |
|   Compact Design              |                                         |


# Conclusion #

Beginners often struggle to produce quality 3D prints because they are yet to familiarize themselves with 3D printer parts and the appropriate materials to be used. 

Better knowledge of these parts helps with the troubleshooting process which is important to print high-quality models. Understanding how to properly level the print bed confirms better bed adhesion eliminating the chances of print failure. Likewise, knowledge about extruders, stepper motors, and the hot end helps you figure out the precise setting to get fine 3D prints. Your electronics and firmware expertise allows you to fine-tune, customize and upgrade the printer’s performance.

Understanding the materials that can be used in FDM technology is crucial for 3D printer users for several reasons. Firstly, different materials have unique properties such as strength, flexibility, and temperature resistance, which can significantly impact the quality and functionality of the printed objects. Secondly, knowing the material compatibility with the printer and its settings helps in avoiding printing issues like warping or poor adhesion. Additionally, some materials require specific handling and post-processing techniques, which can affect the overall success of the printing process. Lastly, being informed about the available materials allows users to make cost-effective choices and explore innovative applications, enhancing their creativity and efficiency in 3D printing projects.

# References #
1. MY3DConcepts: https://my3dconcepts.com/explore/main-components-of-desktop-3d-printers/
2. Manufactur3D: https://manufactur3dmag.com/understanding-the-four-types-of-fdm-3d-printers-cartesian-delta-polar-scara/#:~:text=Cartesian%2C%20Delta%2C%20Polar%20%26%20Scara,-By%20MANUFACTUR3D&text=When%20we%20talk%20about%20FDM,Polar%2C%20and%20Scara%203D%20Printers.
3. Azurefilm: https://azurefilm.com/2023/10/28/3d-printer-parts-essential-components-and-functions/
4. The Mech Ninja: https://themechninja.com/08/3d-printer-extruder-all-parts-explained/
