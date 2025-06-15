---
title: "Antweight Combat Robot"
author: "Kaushik Tadepalli"
description: "Building a vertical spinner 1 lb combat robot to compete at the West Coast Combat Robotics League June Event."
created_at: "2025-05-21"
---
Total Time Spent: 27h

# Day 1: Decisions
Date: 5/21/25  
Total Time Spent: 5h

The goal for today is to finalize the overall robot geometry and make some key design decisions.

We started by looking for inspiration, and came up with the following robots that we could use for reference.   

<a href="url"><img src="https://github.com/user-attachments/assets/88c078f2-95e1-49b0-92bf-1d9a55ef77cd" align="left" height="200" width="auto" ></a>
Our first ideas were based around this style of vertical spinner, with a narrow body, 2wd, and a small vertical hubmotor in the center. We liked its ability to quickly self-right, and the minimal weight requirements of direct drive 2 wheel drive, but didn't like the bite and reach that the small weapon diameter provided.

<a href="url"><img src="https://github.com/user-attachments/assets/e3367c6d-b3ff-45b1-9a9d-5c6b9728c908" align="right" height="200" width="auto" ></a>  

To increase the weapon diameter, we decided to push it further forward and lower to the ground, more similar to the large diameter vertical spinners such as the one to the right. However, we still wanted to keep the dustpan style and self-righting ability of the original design, so we ended up with a combination of the two.

<a href="url"><img src="https://github.com/user-attachments/assets/08424283-32f0-46ee-bc68-04acb21866d3" align="right" height="400" width="auto" ></a>  

By the end of the day, our robot's side profile sketch looked like this, with a weapon diameter of 2.75" and a wheel diameter of 1.375". 

Additionally, we had made some decisions about our drivetrain. As per our project guidelines, we want the robot to have a powerful drive system and be able to control the opponent. This led us to choose a pair of brushless Repeat Mini motors as our drive system, with Banebots wheels for grip. Although more expensive and heavier than N20s or even normal brushed motors, we believe that these motors will give us an advantage in pushing matches and overall driver ability.

That about wraps up our day 1 blog, see you tomorrow!

# Day 2: CAD Time
Date: 5/22/25  
Total Time Spent: 7h

After finalizing our design intent, we started with the bulk of the CAD work. We started with the TPU frame and weapon uprights, adding drive motor mounting and wheels. We then integrated the hubmotor and disk into the uprights. After a few hours of CAD work, our preliminary design was complete. 
<a href="url"><img src="https://github.com/user-attachments/assets/d002c706-cd37-4787-a417-703b639494d2" align="right" height="200" width="auto" ></a>    

<a href="url"><img src="https://github.com/user-attachments/assets/de1e3fe3-b25c-4c42-a9bb-332a12cf04f0" align="left" height="250" width="auto" ></a>  


As we were designing, we noted down all the issues we encountered. One of these issues was securing the polypropelene uprights to the TPU body, and we weren't exactly sure the best way to attach them. Eventually, we decided to add a PA-CF standoff in the middle of the TPU body so that we could run M4 bolts all the way across, securely connecting the TPU with the uprights.

<a href="url"><img src="https://github.com/user-attachments/assets/10a9b383-b169-419c-a844-6d81a1da6e0a" align="right" height="200" width="auto" ></a> 

Another oversight was attaching the wedgelet mounts directly to the TPU frame, as if one of them got sheared off, we would have to replace the entire body. We split off the front TPU into its own part, and made sure to have mounting screws going in multiple axes to try to prevent it from ripping off.


However, the largest issue we faced was with the weapon. The initial weapon design was problematic as it had very little bite and rake angle, which would cause it to not transfer much energy into the opponent. 

<a href="url"><img src="https://github.com/user-attachments/assets/fa4b3e56-0308-490f-a982-de523b607769" align="left" height="200" width="auto" ></a> 

So, we changed the weapon design to have a more aggressive tooth to try to increase bite. Ideally, the tooth would be more triangular with a counterweight in the back, but the large hubmotor and relatively small overall weapon diamater make such a design not possible. 

<a href="url"><img src="https://github.com/user-attachments/assets/3838813b-3006-431e-94cc-155952fafa89" align="right" height="200" width="auto" ></a> 

When designing the weapon, we also had to consider self-righting. In the ideal case, as we are being flipped over, the weapon hits the ground and flips the robot back up. However, if the weapon was not spinning or had stopped as it contacted the ground, we would be stuck in that position. To mitigate this, we decided to have the weapon ears on the upright be slightly lower than the top of the weapon, allowing us to spin up the weapon while upside down and pop back up.

All of these design iterations culminated into the current robot CAD.

<a href="url"><img src="https://github.com/user-attachments/assets/3cf0b4c8-6fe9-4644-b24b-93db13e4a58a" align="center" height="600" width="auto" ></a> 

Tomorrow, we plan to add fasteners, electronics, and work on weight budgeting and reduction, as well as some other minor design details.

# Day 3: Details
Date: 5/23/25  
Total Time Spent: 5h

We made a few minor design changes to the CAD, and added fasteners and electronics.

<a href="url"><img src="https://github.com/user-attachments/assets/edb95cbb-aa04-4847-880f-662905b6afa6" align="left" height="350" width="auto" ></a> 


We slightly altered the overall dimensions of the robot to better accomodate the electronics, added a slant to the sides to prevent getting stuck on our side, and removed and downsized screws due to weight considerations.

<a href="url"><img src="https://github.com/user-attachments/assets/4f7d3e76-8690-4f76-9313-1dc685fd5619" align="right" height="450" width="auto" ></a> 

Here's our wiring diagram and overall footprint. 


The majority of our time was spent reducing weight wherever we could: originally our spreadsheet said we were 60 grams overweight, but after reducing weight by changing slicing settings and modifiers in specific areas, moving bolts from M4 to M3, and redoing the pocketing on the uprights, we ended up at a calculated 5 grams underweight.

<br>

Our BOM is almost finalized, we just need to add shipping and taxes for all the suppliers. We hope to start printing the TPU body over the weekend, and cut the uprights on Tuesday. After that, we'll wait to be approved by Hack Club and organize our tools and fasteners so we can begin assembly and wiring.


<a href="url"><img src="https://github.com/user-attachments/assets/d5548c7b-a71d-48f5-aa9d-21abe1232e51" align="center" height="300" width="auto" ></a> 


# Day 4: Manufacturing and Money
Date: 5/28/25  
Total Time Spent: 6h

After a bit of a break from the journal, we're back with more updates. Over the weekend, we printed the TPU body and wedgelets, and waited for approval from Hack Club. 

<a href="url"><img src="https://github.com/user-attachments/assets/363653a8-e139-45cb-8c32-def6be4bb530" align="right" height="250" width="auto" ></a> 

With the TPU body complete, we got approval from Hack Club for our advanced project, and received the 350$ grant to purchase our parts. Today, we cut the self-reinforced polypropelene parts on the laser cutter, and test fit them onto the chassis.

First, we completed the 1/8 in top armor and got the middle spacer printed out of Onyx on a Markforged Mark Two. 

<a href="url"><img src="https://github.com/user-attachments/assets/282667ab-e378-4bd6-a0c3-b332df2aa4ec" align="left" height="200" width="auto" ></a>  

<br> <br>
<br> <br>

<a href="url"><img src="https://github.com/user-attachments/assets/07ce9cfa-58d3-4700-a830-e298e525a027" align="right" height="300" width="auto" ></a> 

We then continued to make the 1/4 in weapon uprights, and test fit them onto the chassis. However, we encountered some issues. First, the 1/4 in plate did not cut as cleanly as we would have liked on the laser, with some areas looking really rough and warped. The thicker material caused more of the polypropelene to melt and gum up rather than cut, and we're not really sure how to fix this.

<a href="url"><img src="https://github.com/user-attachments/assets/9a6677dd-d677-4ba2-a340-5ff0ed1d9429" align="left" height="250" width="auto" ></a> 

Additionally, the 1/4 in plates were slightly thicker than we had thought, and some warping due to the laser cutting caused the plates to push the TPU into a banana shape. Although concerning, we believe that once the standoffs and weapon shoulder bolt are put in place, it will resolve the bending by forcing it back to being parallel.


By the end of today, this is how the robot looks. Over the next few days, we'll order all of the parts from our BOM and hopefully start assembling more of the robot by the end of the week!
<a href="url"><img src="https://github.com/user-attachments/assets/26cb6f41-fe35-498b-849c-1ba44edb867a" align="center" height="450" width="auto" ></a>

 
# Day 5: Shipping, Assembly, and Wiring
Date: 6/6/25  
Total Time Spent: 10h


All the parts have arrived!

<a href="url"><img src="https://github.com/user-attachments/assets/e49bce57-f24e-4a04-8e32-b1e0a9e8964b" align="center" height="450" width="auto" ></a>   

Unfortunately, Repeat Robotics sent us the wrong motor shaft size (4mm instead of 3mm), and it'll take another week for the new motors to arrive. Even worse, progress is limited without the drive motors as the frame must be completely disassembled to allow the drive motors to flex into place. Since the weapon wires go through the upright, this means I can't solder anything that goes through the frame without having to remove it later. 


Starting with the battery side, we've had issues trying to fit the components together without squishing them. 

<a href="url"><img src="https://github.com/user-attachments/assets/08f5f46a-057c-435c-8199-808be13ca81c" align="left" height="300" width="auto" ></a>   


The battery leads are quite long and have a long piece of heat shrink on the XT30s which creates a long straight portion of the wire. This forces the leads into the middle wire channel with the current position of the switch. While it fits, it is not ideal and we are looking into moving the switch somewhere else to better accomodate the battery.

<a href="url"><img src="https://github.com/user-attachments/assets/6d014575-82c6-42e5-a53d-8bad932198b5" align="right" height="250" width="auto" ></a>   
<a href="url"><img src="https://github.com/user-attachments/assets/fe1acc0b-de30-41bb-be2f-d8b1e667eb86" align="left" height="250" width="auto" ></a>   



<br><br><br><br><br>
The weapon module went together smoothly and the disk feels balanced and rotates well. The banana-ing issue we saw earlier is mostly (but not completely) resolved by the middle standoffs holding it in compression. The weapon lock also works and we are happy with the amount of bite the weapon has while upside-down (1/8 inch).

<a href="url"><img src="https://github.com/user-attachments/assets/32cd5fc7-7baf-4ed3-93c3-ff56988bdffb" align="left" height="300" width="auto" ></a>   

On the main TPU frame, we've printed out a full spare set of every component with extra front wedgelet mounts and wedgelets. We also switched to using longer thread-rolling screws in some areas for more engagement with the TPU. 

I've held off on soldering the weapon ESC and drive ESC as I want to wait for the drive motors and standoffs to be in place before cutting the wires down to length so it doesn't become a pain in the future.
<br><br>
Once the motors arrive, we'll be able to assemble and solder the rest and (hopefully) not fry the electronics. Then I can set up the radio and mixing, as well as test out the drive and weapon motors.


# Day 6: Testing and Fixing
Date: 6/14/25  
Total Time Spent: 15h

With the new motors, we were able to finish the assembly of the robot and wire it up.

<a href="url"><img src="https://github.com/user-attachments/assets/d7609d62-43fa-4a0a-8a37-54c520a00829" align="left" height="300" width="auto" ></a>   


We started by soldering the weapon ESC to the bottom of the double sided power soldering pads on the Repeat dual drive ESC, so that we didn't have to splice the power wire. We then soldered the weapon ESC wires but did not shrink the heat shrink since the weapon ESC is unidirectional, so wires may need to be swapped to spin the right way.

We then soldered the closest side drive motor, battery leads from the XT30 pigtail, and finally the far side motor wires, which were very barely able to reach the ESC. On the battery side, we ended up leaving it the same way it was before and it seems to be working. A lot of the wiring was made more difficult since the wires threaded through holes in the chassis and the plates which made soldering harder as everything had to be in its final place while soldering. Wire channels would have been a better approach, but it ended up being fine.

<a href="url"><img src="https://github.com/user-attachments/assets/93ff751c-08ae-4be6-afa4-6165f911129e" align="right" height="300" width="auto" ></a>   

After wiring was complete, we were ready for the first power on. The total weight came to about .92 lbs, so we had some breathing room to make changes. We used a multimeter to check for any shorts and everything worked when we powered it on. Unfortunately, the Repeat dual ESC wasn't flashed with the pretuned AM32 firmware so I used an Arduino Uno as a link to flash it with the bidirectional settings. Then I set up the mixes and failsafe on my Radiomaster Pocket and everything was functional!

<a href="url"><img src="https://github.com/user-attachments/assets/2f41e444-e828-4de0-9e61-7147efbbaaa1" align="left" height="300" width="auto" ></a>   

I quickly realized that the weight distribution was a huge issue- since the weapon and battery are both pushed to the very front, the wheels have no traction and didn't really move the robot in a controllable way. The robot drove super well upside down and self-righting worked great, but right-side up driving did not work. 


https://github.com/user-attachments/assets/c87e3813-71e4-4854-8e02-279d12350a75


To fix this, we added magnets to the back right side as it was both front heavy and left heavy due to the battery, and the magnets worked extremely well to counter this effect by increasing the downforce in the opposite corner. If we want to later compete at a wooden floored event such as BCRC, we would need to make major changes to the robot. 

<a href="url"><img src="https://github.com/user-attachments/assets/b7639bbb-4796-4c09-b939-90f32c87a6b7" align="center" height="300" width="auto" ></a>   



https://github.com/user-attachments/assets/f46638b3-1f18-4b48-a354-72a768e52daa


We also spun up the weapon outside and found that it spun backwards, so we flipped two of the wires and it worked great. The weapon is well-balanced and it is quite scary even though we only went to around 50% throttle. 

Over the testing period, we found a bunch of durability concerns to be addressed. The largest one was the screws backing out of the wheel assembly. The set screws of the wheel hubs and the motor mounting screws both backed out, causing the wheels to jam and make the motor get really hot. To fix this, we drilled out the threads in the hubs and retapped to a larger thread size, and will also buy Vibratite VC-3 as threadlocker (currently using superglue). We will also replace most of the thread-rolling screws with longer ones for more rigidity as the short ones on the BOM do not have enough engagement. Since we still have some extra weight, we may try to add some back armor to protect the motors, but no more major changes need to be made before WCCRL. 

Overall, we are really happy with the robot and will hopefully get one more journal entry deciding the name and doing final testing (hitting stuff with the weapon) before the event.
