---
title: "Antweight Combat Robot"
author: "Kaushik Tadepalli"
description: "Building a vertical spinner 1 lb combat robot to compete at the West Coast Combat Robotics League June Event."
created_at: "2025-05-21"
---
Total Time Spent: 17h

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

When designing the weapon, we also had to consider self-righting. In the ideal case, as we are being flipped over, the weapon hits the ground and flips the robot back up. However, if the weapon was not spinning or had stopped as it contacted the ground, we would be stuck in that position. To mitigate this, we decided to have the weapon ears on the upright be slightly higher than the top of the weapon, allowing us to spin up the weapon while upside down and pop back up.

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

<a href="url"><img src="https://github.com/user-attachments/assets/282667ab-e378-4bd6-a0c3-b332df2aa4ec" align="left" height="200" width="auto" ></a>  

<br> </br> <br> <br> <br> <br>
First, we completed the 1/8 in top armor and got the middle spacer printed out of Onyx on a Markforged Mark Two. 

<a href="url"><img src="https://github.com/user-attachments/assets/07ce9cfa-58d3-4700-a830-e298e525a027" align="right" height="300" width="auto" ></a> 

We then continued to make the 1/4 in weapon uprights, and test fit them onto the chassis. However, we encountered some issues. First, the 1/4 in plate did not cut as cleanly as we would have liked on the laser, with some areas looking really rough and warped. The thicker material caused more of the polypropelene to melt and gum up rather than cut, and we're not really sure how to fix this.

<a href="url"><img src="https://github.com/user-attachments/assets/9a6677dd-d677-4ba2-a340-5ff0ed1d9429" align="left" height="250" width="auto" ></a> 

Additionally, the 1/4 in plates were slightly thicker than we had thought, and some warping due to the laser cutting caused the plates to push the TPU into a banana shape. Although concerning, we believe that once the standoffs and weapon shoulder bolt are put in place, it will resolve the bending by forcing it back to being parallel.


By the end of today, this is how the robot looks. Over the next few days, we'll order all of the parts from our BOM and hopefully start assembling more of the robot by the end of the week!

<a href="url"><img src="https://github.com/user-attachments/assets/26cb6f41-fe35-498b-849c-1ba44edb867a" align="left" height="350" width="auto" ></a> 
