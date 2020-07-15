#ANDERSON FIREARMS
##OFFICIAL INSTRUCTIONS MANUAL FOR THE MODEL WILDFIRE
###By Anderson N.





---
#OVERVIEW
Hello, and thanks for downloading and supporting the Anderson Firearms Model WildFire. There are some key differences between this design and the previous Ghostfire Model that sparked the sporadic spread and utility of the general AR Platform. There are a lot of house keeping items we need to go over before you continue, which will answer a lot of questions and prevent y'all from cluttering my communications. First, lets go over what this instruction manual entails:
* **Manufacturing**
* **Assembly**
* **Application**
* **Maintenance**

>**Manufacturing** involves all the big details on how to successfully set up your printer and select the optimal slicer settings for the best print results

>**Assembly** involves how to put these pieces together, including actual AR Lower pieces such as the pins both front and rear, the FCG (Fire Control Group), and the buffer tube. While the accessories are important, their assembly does not require a genius.

>**Application** is how the whole system works, as there are key differences in the manual of arms of custom made 3d printed AR Lowers and accessories.

>**Maintenance** is how to keep your AR rifle in top notch condition. Because we are dealing with 3D printed materials, there are some suprising things I have learned that should be noted when caring for your rifle after excess use.

Now that we have gotten the main contents out of the way, you can go ahead and get started on the official manual! **To get started on your new build, skip over and start on the "MANUFACTURING" section.** However, if there are other house keeping items you want to inquire about, ill post them below in subsections.

###FAQ's and inquiries

####Differences between this build and the Ghostfire model
The biggest revolution of this build and the Ghostfire model is the no metal no nonsense philosophy. This means that other than the standard AR Build Kit, there are no external nut, bolt, washer, or metal of any kind! This means you don't need to visit the hard ware store to get this build into action. No nonsense also means that you do not need to implement any form of 3D Printed tricks of any kind, nor any supports, and because this was entirely designed around the use of PLA, virtually any 3D printed material is compatible with this design. No modification of anything at all, just slap the files on your slicer, and rock in roll. The design was even tested at 40-80% infill, to ensure that even at its weakest and worse, it could still run. All needed supports are already built into the design, which means you don't need to add your own. Because of the small size of each print, these parts are certain to fit smaller print beds. No non-sense, no stupidity, idiot proof, almost marine grunt proof.

####Why did you build and design these lowers?
Because everyone deserves to assert and maintain absolute independence and liberty from tyranical forces foreign and domestic. Because these inalienable rights have been ordained through divine intervention, hard coded and untouchable through nature and God. Because every living organism has the right to exert to the best of their ability the capabilities neccessary for the preservation of life and liberty. Because the Government has failed to fullfill its only oath, to protect, defend, and provide for, the welfare of the people, and as such, through the violations of the social contract, must be punished and put to justice, with extreme predjudice. Stay armed. Stay diligent. Push forward. Big corrupt Government bad.

####Plausible Deniability
Because this has to be said: You print it, thus you are responsible for it's outcome. Under no circumstances am I held responsible should this design go south. However, as you will know, I do in fact check and test my designs and provided proof of these checks and tests to show that the design works. The proof will be found in the Application section, where I will detail the results of long term extreme testing, and the optimal round count before recommended replacement of certain parts, or the whole lower. You have been warned.

On another serious note, any mass killing, mass shooting, or mass (insert illegal crime here) caused by this device is not my fault or intention. I have never designed and intended for this device to be used as a means to an end of a violent crime or violent acts. What you do with my knowledge is your responsibility. The only crime this design will ever commit is to provide the public a means to obtain information to create expident firearms to combat the failures of big Government, because providing for the public good is now a crime (lol).

####On the note regarding private sales
Anyone who tries to sell you this device or the knowledge to sell you this device is ripping you off. This device is of open domain, so unless you don't own a printer and need to buy one from a friend for educational purposes, you're being ripped off. That said, follow your local laws and make sure you understand what manufacturing entails.

####Will there be future models?
Yes. The next model(s) are going to:
* Provide a functional lower for AR-10 platform (yessssss, also most likely for DPMS AR-10.)
* Unobtruded access to the fire selector and rear take-down pin
* Select Fire (maybe, depends on if I can hide from the FBI)
* Experimental PLA only suppressor (Thanks to my incrediable experience, I may know how to get this idea to work. Also depends on if I can hide from both the ATF and the FBI.)
* Provide a website for all of this (maybe, if this becomes bigger than just me.)
* 22Lr single shot multi use pistol (if its fun enough, sure)





---
#MANUFACTURING

###Naming convention

Listen carefully, because there is a specific naming convention that I have applied to each file part. These files were named in this way because I picked them up from learning in the field of engineering, and have realized that this convention is very effecient at organizing and specifying exactly what parts or models are what, and that this way, things will get done faster and more orderly.

Here is an example of a file name and all the components of that name:

>**AF-WF-LR-PRT-001-STL.stl**

* **AF** ------> Company or Organization : "**A**nderson **F**irearms"
* **WF** ------> Product or Model: "**W**ild **F**ire"
* **LR** ------> Component: "**L**ower **R**eciever"
* **PRT** -----> Part
* **001** -----> Numbered Part
* **STL** -----> Type of file, in this case an STL file
  
Heres another example of a file name that is similar but different in other ways:

>**AF-WF-GS-MDL-002-SLDWRKS.sw**

* **AF** ------> Company or Organization: "**A**nderson **F**irearms"
* **WF** ------> Product or Model: "**W**ild **F**ire"
* **GS** ------> Component: "**G**host **S**ights"
* **MDL** -----> Model, which concist of parts
* **002** -----> Numbered Part
* **SLDWRKS** ------> Type of file, in this case a SolidWorks File

Now that you got an idea of how the naming convention works, it's time to make sense of the whole system.

###Choosing what to print and what not to

First things first: This is not just a lower; Its a whole system that will convert your AR into a battle-ready rifle. This whole 'kit' is the whole deal, and heres what's inside:

* WildFire Lower
* Adjustable Ghost ring sights, front and rear ("Iron sights")
* Pistol Grip
* Stock
* Keymod only Thermal Covers (Barrel Covers)
* Keymod only Vertical Foregrip
* Flash Light attachment
* Custom Side Plate

Now for some notes:
  
* I only did keymod because thats all I have on my rifle. I would do MLOK, but im lazy and only bothered designing what I had in hand. Plus, Keymod is actually open source (correct me if im wrong), which means its friendly for all kinds of stuff.
* You don't have to use everything provided in the kit. If all you want is the lower, be my guest.
* The front sights adjust for elevation, and the rear sights adjust for windage.
* The flashlight attachment only works for flashlights with a one inch diameter. Again this is because I picked the cheapest metal flashlights I can find and simply worked with that.

Select what you want to print, and leave the rest of the files alone. They should be conviently named after their function. If all you want is to print, look for the STL files of each product you desire. If you want to modify designs for yourself, look into the SolidWorks files, because I used Solidworks to craft this product.

###Slicing preferences

During testing, the WildFire Lower was printed at 80% while the rest of the parts were printed at 40% to 60%. However, for safety sake print according to the graph shown below for the best possible results. **All prints were done in PLA, not ABS, not PETG, not Resin, just plain-o PLA. I cannot guarantee that the kit will work with anything other than PLA, but im pretty sure that if it works in PLA, theres a high chance it'll work in ABS or other materials. Let me know what your results look like.**

|     File Name     |     Infill %     |     Layers Lines     |     Quantity     |
| :---: | :---: | :---: |  :---:  |
| AF-WF-LR-PRT-001 | >=80 | 3 | 1 |
| AF-WF-LR-PRT-002 | 100 | 6 | 1 |
| AF-WF-LR-PRT-003 | 100 |  |  |
| AF-WF-LR-PRT-004 | 100 |  |  |
| AF-WF-LR-PRT-005 | 100 |  |  |
| AF-WF-LR-PRT-006 | 100 |  |  |
| AF-WF-LR-PRT-007 | 100 |  |  |
| AF-WF-LR-PRT-008 | 100 |  |  |
| AF-WF-LR-PRT-009 | 100 |  |  |
| AF-WF-PG-PRT-001 | 100 | 3 | 1 |
| ANY CUSTOM SIDE PLATE | 100 | 3 | 1 |
| AF-WF-GS-MDL-001 | >=60 | 3 | 1 |
| AF-WF-GS-MDL-002 | >=60 | 3 | 1 |
| AF-WF-TC-PRT-001 | >=60 | 3 | DEPENDS ON RAIL |
| AF-WF-TC-PRT-002 | >=60 | 3 | DEPENDS ON RAIL |
| AF-WF-VF-PRT-001 | >=80 | 3 | 1 |
| AF-WF-VF-MDL-001 | >=80 | 3 | 1 |
| AF-WF-SS-PRT-001 | >=60 | 4 | 1 |
| AF-WF-SS-MDL-001 | 100 | 6 | 4 |

###Printing Preferences
* Do not print with supports
* Do not print with brims (unless you can clean it up)
* Try not to print diagonally on the print bed, unless your print bed is too small. Since I have never tested the results of a part printed diagonally, I can't guarentee its success.
* Orientate the part to print on it's flatest side. Refer to the "Printing Orientation" section below to see the correct orientations.
* Print at temperatures that is most optimal for you.
* All prints were designed to work with the standard 1.75mm filament, no higher, no lower.
* Print at your standard layer height (normal), but if you want more details, only the AF-WF-LR-PRT-001 will benefit more from higher detail layer height.
* All of the pieces with bolts were designed to print "sideways." Look into the "Printing Orientation" section below and you will know what I mean.

###Printing Orientation
When loading the STL's onto the print bed, the orientation matters, and you will have to rotate the pieces. Ideally you should print on the flattest side, and since theres a specific orientation required for each piece, you will have to refer to the images below to see the orientation required.




---
#ASSEMBLY





---
#APPLICATION

###Manual of Arms and Rules
When the WildFire Lower is assembled correctly, it will function identically to any other AR-15 platform of rifles. To use, make sure you follow all rules of your local range, and to follow the four fundamental rules of firearms:
1. Keep your finger off the trigger until you're ready to fire.
2. Be wary of what you are shooting at and beyond that.
3. All firearms are to be treated as if they're loaded
4. Be wary of where your muzzle is pointing at

###Dry Firing Practice
Once you have memorized the rules, you should be ready to fire. Dry-firing is a good way to practice before shooting. Start by checking if your firearm is loaded, and lock the bolt open. Operate the fire-selector from "FIRE" to "SAFE." Insert an empty magazine into the lower, practicing the use of your work space to operate the firearm easily. Once inserted, close the bolt. Take aim, ensuring that your finger remains off the trigger. Switch the fire selector to "FIRE," and dry fire when the target is aquired.

###Magazine Compatability
The firearm was tested with the following kinds of magazines, all with success:
* PMAGS GEN II
* PMAGS GEN III
* Aluminium magazines with steel butt plates (GI Mags)
* STANAGS (falls under GI Mags)
* MFT Magazines
* Custom spray painted mags (rougher to insert, but worked fine)

###Mortoring
Mortoring is when a malfunction renders the bolt inoperatable by the charging handle, and thus must be forcfully ejected by slamming the stock into the ground while yanking down on the charging handle. That said, mortering is unfortunately a weakness of this kit, because limitations on the stock means that mortering of any kind will most likely break not the stock but its bolts. Thus when mortoring, expect to replace the bolts.

###Zeroing using Ghost Ring Sights
These are essentially diopter sights, and should be treated like the standard iron sights used on the M4/M16 platform of rifles. The difference is that there is only one option instead of flippable long range and short range, and its pretty big compared to the pin holes of other diopter sights. This choice was made because bigger pin holes would allow the eye to aquire a sight picture faster, at the cost of some precision. However, this was also a utilitarian choice: you would still be able to hit man size targets out to 100 yards, and four inch groups at 50 yards. It's not perfect, but it works.

To zero the sights, the front post adjust for elevation, while the rear post adjust for windage. Heres how I adjust my sights:
1. Attach the front and rear sights onto the upper, and boresight the sights at 25 yards.
2. Once boresighted, assemble the AR, load 3 cartridges, and fire directly at bullseye at 25 yards.
3. Observe the shot group, and make adjustments if neccessary, with each adjustment following another 3 cartridges until the group is directly over the bullseye.
4. Place the weapon at the 50 yard mark, and repeat the tests, ensuring that the shot placement can concistantly hit a man size target.

The idea is not to get head shots or bullseyes. The idea is to be able to reliably hit man size targets should you touch out to 100 or even 200 yards. One thing you should note is that this device was never tested out to 100 yards, but tests at 50 yards showed that the sights can hold zero. This was a limitation of the ranges I have been to, so if I had the option to shoot out to 100, I would have.

###Testing
This is a big part of all of my devices: To ensure that they're tested to work and work reliably in the field. The purpose of this test is to show that my lower can withstand 300 rounds, and if so, you may test further to see how much cartridges you can expend before failure or seizure. That said, my testing was done through 2 trips to the range with a friend and we blasted 300 rounds without major malfunctions and issue. We had only ever encountered one failure to feed on the first cartridge of a fully loaded magazine when racking the charging handle, and the bolt did not pick up a round. I later discovered that the malfunction was not caused by the lower, but by the magazine, which was an aluminum STANAG. This magazine was given to me because another friend who used it reported issues with it when shooting 300 BLKOUT with this magazine. Other than that, the lower experienced no issues, and chugged 300 cartridges without any malfunction or breakage. Note that in between range trip one and two, the only major change to the lower was a reprint of a better and more ergonomic pistol grip. The new grip was a far superior design in terms of confort and gripability. Overall a huge success.




---
#MAINTENANCE

###Basic Cleaning
For the most part, the upper reciever will be cleaned normally, as the lower was found to leave no plastic residue that required anything else to be cleaned. The lower however, will have to be cleaned as frequently as the upper. Previously, metal lowers do not need to maintained at all like the uppers because residue does not impact the Fire Control Group's ability to function. Because PLA is printed in layers, excess carbon can build up in between layers and would increase friction on the fire control group, which may impact the ability for the trigger to function. I say maybe because I have never experienced the trigger failing to function, but have noted that as carbon begans to build up in excess of 200 rounds during testing, the trigger pull was in fact heavier, but it continues to function as intended. When cleaning the lower, focus on wiping carbon off the magazine well, as well as carbon imparted on the hammer, and the inside well of the fire control group. You do not need to disasemble to the Fire Control Group, just wipe any spots with carbon on them. 

###Advance Cleaning (Must read)
There is one major instance where a full break down and clean is required: When the weapon is deployed in adverse conditions (rain and mud). This means disassembling the Fire Control Group and wiping the section dry. What I notice is that rust can rapidly develop in the lower. To be frank, Im not sure why, but I would assume the reason boils down to some property of layers and PLA retaining moisture which means a through clean is required. This is something that I'am very adament about: clean the gun after you get water in it.

###Replacing parts
The WildFire was designed to blast through a clean 1000 cartridges, and then have the buffer tube connector and support struts replaced. Rather than printing the whole lower everytime it failed, this design allows you to only print the parts you need to replace, and not the whole lower each time. This saves a lot of material, time, and allows you to bring replacement parts on the field to repair it in the field, although this should not be neccessary. This design was also done to take advantage of increased strutural strengh by allowing the normal force of the Bolt Carrier Group to act against layer lines, not with it. You will know that this means when you print and realize that the adhesion of layer lines is the real flaw of printed piece's ability to withstand compression and tension, and that the orientation of the printed pieces eliminate this possibility. Replace pieces if neccessary when enough rounds (1000) have been put through them, or when cracks and heat warping is observed.

