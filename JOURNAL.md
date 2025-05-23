---
title: "Antweight Combat Robot"
author: "Kaushik Tadepalli"
description: "Building a vertical spinner 1 lb combat robot to compete at the West Coast Combat Robotic League June Event."
created_at: "2025-05-21"
---
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
<a href="url"><img src="https://github.com/user-attachments/assets/a95c631f-5e58-4188-b3fc-f113a74e6de8" align="right" height="200" width="auto" ></a>    

<a href="url"><img src="https://github.com/user-attachments/assets/de1e3fe3-b25c-4c42-a9bb-332a12cf04f0" align="left" height="250" width="auto" ></a>  


As we were designing, we noted down all the issues we encountered. One of these issues was securing the polypropelene uprights to the TPU body, and we weren't exactly sure the best way to attach them. Eventually, we decided to add a PA-CF standoff in the middle of the TPU body so that we could run M4 bolts all the way across, securely connecting the TPU with the uprights.

<a href="url"><img src="https://github.com/user-attachments/assets/10a9b383-b169-419c-a844-6d81a1da6e0a" align="right" height="200" width="auto" ></a> 

Another oversight was attaching the wedgelet mounts directly to the TPU frame, as if one of them got sheared off, we would have to replace the entire body. We split off the front TPU into its own part, and made sure to have mounting screws going in multiple axes to try to prevent it from ripping off.


However, the largest issue we faced was with the weapon. The initial weapon design was problematic as it had very little bite and rake angle, which would cause it to not transfer much energy into the opponent. 

<a href="url"><img src="https://github.com/user-attachments/assets/fa4b3e56-0308-490f-a982-de523b607769" align="left" height="200" width="auto" ></a> 

So, we changed the weapon design to have a more aggressive tooth to try to increase bite. Ideally, the tooth would be more triangular with a counterweight in the back, but the large hubmotor and relatively small overall weapon diamater make such a design not possible. 

<a href="url"><img src="https://github.com/user-attachments/assets/3838813b-3006-431e-94cc-155952fafa89" align="right" height="200" width="auto" ></a> 

When designing the weapon, we also had to consider self-righting. In the ideal case, as we are being flipped over, the weapon hits the ground and flips the robot back up. However, if the weapon was not spinning or had stopped as it contacted the ground, we would be stuck in that position. To mitigate this, we decided to have the weapon ears on the upright be slightly lower than the weapon diameter, allowing us to pop back up when the weapon is spinning but also self-right by hitting a wall or an opponent.

All of these design iterations culminated into the current robot CAD.

<a href="url"><img src="https://github.com/user-attachments/assets/3cf0b4c8-6fe9-4644-b24b-93db13e4a58a" align="center" height="600" width="auto" ></a> 

Tomorrow, we plan to add fasteners, electronics, and work on weight budgeting and reduction, as well as some other minor design details.
