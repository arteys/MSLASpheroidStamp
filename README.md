# MSLASpheroidStamp

# Introduction

Cell spheroids, everyone! Seriously, every cell biologist needs spheroids. It's fun and interesting. Okay, maybe not every one, but if you're reading this....
This project is about how you can use an MSLA 3d printer (and, in some cases) two-component silicone to make microwells in an agarose (or even agar) gel poured into a regular culture plastic. And we are not talking about some kind of multiphoton superprinter, the MSLA for $200 from the Amazon/Aliexpress/etc will work fine. 

I propose two approaches: to use silicone molds (molds for casting which can also be printed), in which agar is poured and further transferred into a tablet/flask, or to print a stamp, with which microwells are made directly in the gel poured into the dish/plate. 

<img src="https://github.com/arteys/MSLASpheroidStamp/blob/main/Readme%20files/Mold%20and%20stamp.png" width=40% height=40%>

Silicone mold for 6-well plates (A) and stamp for 96-well plates (B)

Of course I'm not the first to think of this, there's a preprint somewhere below where I've discussed quite a few similar options, including commercial MicroTissue (which cost some wild money for a piece of silicone). 

However, in the literature, the process of making such things is either terribly written, or the authors suggest using thousands of dollars worth of equipment. More often it is both. That's why I lay it all out in the form of protocols, as well as attach all the models. Including in FreeCAD format, offering those who wish to modify everything as you want and need. 

<img src="https://github.com/arteys/MSLASpheroidStamp/blob/main/Readme%20files/Different%20plastic.png" width=80% height=80%>

Microwells in a 96-well plate (A), glass-bottom dish mold for confocal microscopy (B), 6-well plate mold (C) and twin megamold for T-75 culture vials with 28564 microwells (D).



If everything is done correctly (and it's really not difficult) you can get such cuties as on the picture below. And then do all sorts of strange things with them. 

<img src="https://github.com/arteys/MSLASpheroidStamp/blob/main/Readme%20files/Different%20cells.png" width=80% height=80%>
Spheroids made from cells of different cultures in microwells in the wells of a 96-well plate. Further they will be poisoned (at least some of them) with all sorts of poisons under the sound of laughter, as befits a mad scientist. 


# Files
Unfortunately the stl files are too big for github, so they are on [zenodo.com](https://zenodo.org/records/14562031) and on [Printables](https://www.printables.com/model/1243707-stamps-and-molds-for-mslaspheroidstamp)  


### Z-offset 

<img src="https://github.com/arteys/MSLASpheroidStamp/blob/main/Readme%20files/Single%20well%20offset%20illustration.png" width=25% height=25%>

The standards for culture plastic sizes are a joke. Especially for depth, so I attach stamp models with different z-offset to match to specific plates




# Molds

## 6-plate/dish microwell production

### Silicone Mold prodoctuion
#### The choice of silicone
This is the tricky part. Staying in the ideology of accessibility and DIY, I used the usual model two-component silicone available in the hobby store. Two-component platinum-based silicones definitely do not work - there is some kind of reaction between the silicone and the printed part and the silicone does not polymerize. Tin-based silicones remain, they generally work well. However, not all, I have met at least one that sticks to MSLA printed parts tightly and then it is impossible to separate the finished molds. Accordingly, if someone decides to make such molds, silicone will have to be selected empirically. And I didn't use any chemical separators because I didn't want to add their remnants to the biological medium.

#### Tools and equipment

- Vacuum chamber
- Two-component silicone (that you are sure about)
- Dye for silicone (with it is better to see how well mixed silicone, as well as you can use different colours for colour coding
- Disposable wooden or plastic spatulas.
- Wipes and gloves (this process will inevitably be messy)

#### Process
The total volume of silicone depends on how many molds you make at a time. Also silicone is quite hard to transfer quantitatively, it's a skill. Therefore, it is better to take with reserve. You will need two portions of silicone. The first portion is about ten grams per mold, the second twenty. 

1. Mix the first (smaller) portion of silicone with the hardener and dye 
2. Transfer to the molds and spread evenly with the spatula, making sure that the silicone covers the entire area evenly.
3. Transfer the molds to the vacuum chamber and evacuate, then let air in and evacuate again. Leave under vacuum for 3-5 minutes
4. Mix the second batch of silicone with hardener and dye (another colour can be used)
5. Release air, take the molds out of the vacuum chamber and pour the second portion of silicone into them
6. Remove the excess with a spatula
7. Leave for 24 hours (or as recommended by the silicone manufacturer) until curing

### Gel mold productuion
#### Before starting work
Nothing is sterile by default or even intended to be. In the laminar flow hood, it is highly recommended to treat the molds and stamps with 70% isopropyl or ethyl alcohol before the first use. You can use a spray bottle, but it is better to treat them by immersing them in a alcohol for a few minutes. 
I would not advise autoclaving, and molds and stamps, in principle, should withstand such treatment, but without guarantees. 
It is most convenient to store it in the box of tips, this box can also be treated with alcohol and stored inside the laminar flow hood while working. 



#### Tools and equipment

- Laminar flow hood
- Microwave or other way to melt the gel
- Molds
- Plastic pasteur pipettes (2-5 ml)
- Tips for 10-200 ul pipette
- Agar/agarose solution with a concentration of about 1-3% mass. The minimum volume required per plate is about 5 ml, but it is better to melt 10-20 so that the melted gel in the bath does not solidify so quickly.

#### Process
1.	Melt the agar/agarose solution, preferably bring to a boil 
2.	Using a paster pipette, transfer the gel to the silicone molds, spreading it gently over the surface, large bubbles can be sucked up with the pipette
3. If you use a silicone mold with a small size of micropins (300 um), air bubbles often get stuck on them, which spoil the agarose mold. To get rid of them mold should be ‘ironed’ for example with a 10-200 tip (Watch the video below). 
4. Agarose hardens for 10-20 minutes, after which the mold can be carefully removed from the mold and transferred to a plate cell 6-well plate cell or a suitable dish.
5.	Agarose molds are ready for cell seeding




<img src="https://github.com/arteys/MSLASpheroidStamp/blob/main/Readme%20files/Mold.png" width=60% height=60%>


https://github.com/user-attachments/assets/4c41e45f-066e-499b-a9de-289ee6c0a233


_Process of filling mold with agarose_


https://github.com/user-attachments/assets/55440b95-25c6-4f36-a674-90fb6afe1f3b


_Process of removing bubbles from the mold_



https://github.com/user-attachments/assets/c4b449f8-795c-471a-a6a9-0f1629ddc110


_Extracting of the agarose mold_

 
#### Cell seeding
1.  Detach the cells using the laboratory procedure. 
2.	Count the cells in suspension and dilute to the required number per microwell. About 300 µl can be poured into the recess of the agarose mold. 
3.	Transfer the cell suspension into the recess of the mold
4.	Allow 15-30 minutes for the cells to settle under gravity.
5.	Tilt the plate with molds and carefully remove the medium with excess cells that did not fall into the wells
6.	Add fresh medium, including the empty space around the mold.
7.	Place the plates in the incubator until the spheroids consolidate for 24 hours


## Stamps



### 96-plate microwell production

#### Before starting work
Nothing is sterile by default or even intended to be. In the laminar flow hood, it is highly recommended to treat the molds and stamps with 70% isopropyl or ethyl alcohol before the first use. You can use a spray bottle, but it is better to treat them by immersing them in a alcohol for a few minutes. 
I would not advise autoclaving, and molds and stamps, in principle, should withstand such treatment, but without guarantees. 
It is most convenient to store it in the box of tips, this box can also be treated with alcohol and stored inside the laminar flow hood while working. 

#### Tools and equipment

- Laminar flow hood
- Microwave or other way to melt the gel
- Stamps - 6 pieces
- Multichannel pipette (capable of dispensing 50 µl of liquid) - 1 piece
- Tub for multichannel pipette
- Tips for pipette
- 96-well plate  
- Agar/agarose solution with a concentration of about 1-3% mass. The minimum volume required per plate is about 5 ml, but it is better to melt 10-20 so that the melted gel in the bath does not solidify so quickly.

#### Process

Working with molten agar/agarose requires care and, more importantly, speed, so it is better to prepare everything within reach in advance
1. Set the pipette to 50 µl 
2.	Melt the agar/agarose solution, preferably bring it to a boil 
3.	In a laminar flow hood, pour the agarose into the tub for the multichannel pipette
4.	Use the pipette to transfer 50 µl into the two columns of the plate and immediately place a stamp in these columns. Make sure that the stamp is fully inserted (there is a tab on it centring it in the well, make sure it is inserted). It is necessary to do everything as quickly as possible, so that the gel does not freeze in the spouts of the dispenser
5.	Pour two more columns, set the stamp, repeat until all the stamps are installed 
6.	Wait for the gel to solidify (10-15 minutes, depending on agar/agarose and room temperature)
7.	Remove the stamps. This is the most critical step. It is most convenient to turn the plates with the short part towards yourself and remove the stamps with two hands from the sides. Gently rock the stamp back and forth before removal. If the gel concentration is optimal and the gel is fully cured, the stamp should come out clean and free of gel pieces and the microwells should remain intact inside the tablet. A few wells per plate usually come with bubbles, it's a matter of luck and it's hard to do anything about it. A video of the extraction process is shown below
8.	The microwells are ready for seeding of cells

https://github.com/arteys/MSLASpheroidStamp/assets/7783671/63acb3b1-17a5-44c3-86e2-7b8f0d8d8371

_Process of extracting the stamp from the plate_

#### Cell seeding

Before conducting a serious experiment, it is best to determine the optimal number of cells needed to form spheroids. They should not be too many or the extra cells in the well will form spheroids of uncontrolled size outside the microwells. The figure below shows spheroids formed from HeLa with different numbers of cells per cell. In this case about 1000-500 cells per microwell is optimal, when dense spheroids are formed after a day and there are practically no cells outside the cells. 

You will need standard equipment and supplies for working with cell cultures, as well as a microwell plate made in the previous step, and:
- Centrifuge or vortex with a plate rotor (optional)

1. Detach the cells using the laboratory procedure.  
2.	Count the cells in suspension and dilute to the required number per microwell. One plate well can be filled with 50 - 100 µl of medium. 
3.	Transfer the cell suspension to the tub for the multichannel pipette
4.	Using the multi-channel pipette, transfer the cell suspension into the plate
5.	Either centrifuge at minimum speed to allow the cells to settle to the bottom of the microwells or hold the plates for 15-30 minutes to allow the cells to settle by gravity.
6.	Some cells are deposited between the cells or above or at the top of the plate cell where the stamp entered the agarose. To remove excess cells the plate should be tilted at 45 degrees and carefully remove the medium with excess cells with a multichannel pipette, pipetting several times.   
7.	50-100 µl of new medium can be poured in place of the removed medium 
8.	Place the plates in the incubator until the spheroids consolidate for 24 hours




<img src="https://github.com/arteys/MSLASpheroidStamp/blob/main/Readme%20files/96%20well.png" width=50% height=50%>


### Glass bottom dish microwell production

#### Before starting work
Nothing is sterile by default or even intended to be. In the laminar flow hood, it is highly recommended to treat the molds and stamps with 70% isopropyl or ethyl alcohol before the first use. You can use a spray bottle, but it is better to treat them by immersing them in a alcohol for a few minutes. 
I would not advise autoclaving, and molds and stamps, in principle, should withstand such treatment, but without guarantees. 
It is most convenient to store it in the box of tips, this box can also be treated with alcohol and stored inside the laminar flow hood while working. 

#### Tools and equipment

- Laminar flow hood
- Microwave or other way to melt the gel
- Stamps
- Plastic pasteur pipettes (2-5 ml)
- Tips for pipette
- Glass bottom dishes plate  
- Agar/agarose solution with a concentration of about 1-3% mass. The minimum volume required per dish is about 1 ml, but it is better to melt 10-20 so that the melted gel in the bath does not solidify so quickly.

#### Process

Working with molten agar/agarose requires care and, more importantly, speed, so it is better to prepare everything within reach in advance
1.	Melt the agar/agarose solution, preferably bring it to a boil 
2.	In a laminar flow hood, pour the agarose into the tub for the multichannel pipette
3.	Use the pipette to transfer 1-2 ml into the dish of the plate and immediately insert a stamp. Make sure that the stamp is fully inserted (there is a tab on it centring it in the well, make sure it is inserted)
4.	Wait for the gel to solidify (10-15 minutes, depending on agar/agarose and room temperature)
5.	Remove the stamp. 
6.	The microwells are ready for seeding of cells

#### Cell seeding

Before conducting a serious experiment, it is best to determine the optimal number of cells needed to form spheroids. They should not be too many or the extra cells in the well will form spheroids of uncontrolled size outside the microwells. The figure below shows spheroids formed from HeLa with different numbers of cells per cell. In this case about 1000-500 cells per microwell is optimal, when dense spheroids are formed after a day and there are practically no cells outside the cells. 

You will need standard equipment and supplies for working with cell cultures, as well as a microwell plate made in the previous step, and:
- Centrifuge or vortex with a plate rotor (optional)

1. Detach the cells using the laboratory procedure.  
2.	Count the cells in suspension and dilute to the required number per microwell. One dish can be filled with 200 - 400 µl of medium. 
3.	Using the pipette, transfer the cell suspension into the plate
4.	Place the dishes in the incubator until the spheroids consolidate for 24 hours

<img src="https://github.com/arteys/MSLASpheroidStamp/blob/main/Readme%20files/Stamp%20glass%20bottom%20dish.png" width=75% height=75%>

# Reproducibility
Of course it would be ridiculous to say much about the reproducibility of my methodology, but not to test it. So scientists in other laboratories (not affiliated with the authors of the study), having received stamps, silicone molds and instructions, were able to reproduce the process of stamp printing and spheroids manufacturing. They used other cell cultures, laboratory plastic from other manufacturers, as well as agar and agarose of other brands. Instructions as well as 3d models are available on the project page on GitHub and in the supplement materials


#  Reference
Preprint: https://www.biorxiv.org/content/10.1101/2024.05.12.593682v2

Paper: https://www.sciencedirect.com/science/article/pii/S2405886625000326?dgcid=author

# Acknolegments
For testing our methodology and proving its reproducibility, I am grateful to
Anatoliy Zubritskiy from FRC "Fundamentals for Biotechnology" RAS (Moscow, Russia),
Kuzmich Alexandra and Yurchenko Ekaterina from Pacific Institute of Bioorganic Chemistry
RAS (Vladivostok, Russia), Alexandra Dalina from Engelhardt Institute of Molecular Biology
RAS (Moscow, Russia) and Saida Karshieva from National University of Science and
Technology MISIS (Moscow, Russia)
