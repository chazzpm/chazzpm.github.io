# 4. Space Architecture of Patched Bounded Landscape
**Charles R Paez Monzon** - 2020 - aNatureTechnologies

       - " Time exists in order that everything does not happen all at once, 
           and Space exists so that it does not happen to you" - Susan Sontag
        
4. TOC
{:toc}

## 4.1. Gon on-Ball Conducts Through the Bounded Landscape
Gon is on control of the ball in an arbitrary alpha point and is free to go through the bounded landscape creating a 
sequence of intentional skill actions on his body and on the ball conducting it around with a final destination to an omega 
point where he can end up the effective final action to score a goal.

    - The set of _things_ is a triple: {goals,ball}
    - The set of _agents_ is a singleton: {Gon}
    - The set of _events_ is: {stasis, transf0, transf1, ..., transfn} = {Ball's positional-stasis, Gon's positional-change,
    Ball-positional-change, ..., goal}

Gon has to develop a **set of actions** or intentional skills to execute on himself and on the ball in the landscape as shown
in the animation of Figure 4.1.

Each Gon's _positional change_ is a movement that can be classified as {standing, walking, jogging, running} to qualify the 
velocity and acceleration of Gon's position from point _p_ to gain point _o_ in bounded space and keep control of the ball.

The cognitive lessons that Gon acquiered were that
- the _main static reference of aFICS_ are **the goals** and, 
- the _main dynamic references of aFICS_ is the **ball location** and the **direction of movement**
- the main objective is the _effective contralateral action_ with which Gon scores the goal

In his perception of the events in the landscape he must have these lessons into account but mainly the recall of the AcEmFC
trainer that he must **finally conduct the ball in contralateral direction** and to **execute an end-up effective 
contralateral action to score**.

Gon needs a **model of the bounded landscape** that guides his decision making in any point in the environment when he is off-
ball or on-ball control. But, Gon now knows that he has to do an huge effort because _all that space-time is created and
happen on only himself_. He **needs team mates to do it one and again and again** in order to have simultaneity and 
sequentiality of events and that the action be distributed between all agent in the boundade landscape. Now on, Gon knows that
he is constrained to be in the on-ball state and that most of the time he will be in the off-ball state. That he must
concentrate on **how and where to move** and when he must be focus to get control of the ball and decide **how to play** or
which is the best action to decide [^1].

'''python
from IPython.display import YouTubeVideo
YouTubeVideo('jymI1Q_XiEU')
'''

![](/images/Gon1inUL-v1.mp4 "Figure 4.1. Animation: Gon on the Bounded Landscape - Visit aNT-aFICS channel in YouTube")

## 4.2. Architecture of Space of the Bounded Landscape
### 4.2.1. The Patched Bounded Landscape
In aFootball our perspective of the game is in spatial-temporal terms. This view yields us to state that there is an
**architecture of the football game** in the bounded landscape. This architecture of aFICS in the bounded landscape is all
about **creating space guided by affordances** and **coming into space in coherence with his actions**. 

Therefore, a main idea of strategy to play football in the bounded playground is about **organizing space**. A spatial
practice in geolocalization, as in aFICS for football, to be analysed would be in terms of:
- the static framed bounded landscape or the **aPBLandscape** and,
- the teams' dynamics as **Football Flow**

Gon needs _a model of the patched bounded landscape_ that guides his decision making in any point in the environment when he
is off-ball or on-ball control. But, Gon now knows that he has to do an huge effort because _all that space-time is created 
sequentially but all happen on only himself_.

This model must take into account all spatial reference that Gon has acquiered from exploring the bounded landscape. 
- Gon knows the difference in scale about the **near by and the far away**
- Gon knows the difference between the ** core area, the inner area and the outter area**
- Gon knows which directions of movement of the ball and of his body are in **sidewayness or counter-sydewayness**.

Let us analyze the framed bounded landscape aBLandscape as the common reference for spatial practice of football.

![](/images/landscapeaB.png "Figure 4.2. Organization of aFootball Space in a Patched Bounded Landscape")

### 4.2.2. Spatial Relations of Patches

**Patches** are _circles, semicircular sectors and circunferences subspaces_. They exhibit spatial relationships, like n-
adjecency -  between subspaces and their concatenation as set of subspaces constitute the **spatial organization of the
patched bounded landscape aPBLandscape** in the aFootball Universe whose **inside** is bounded by a **perimeter** and the
*perimeter* is conformed by a **lateral** and **counter-lateral** arcs and the *inside* by an **outter**, an **inner** and 
a **core** subspaces as shown in Figures 4.3. and 4.4.

The aPBLandscape is organizaed in two halves, **own half** and **opponent half**, each one asociated to a goal object
Each half is sub-organized into nine **patches**. In total, The bounded landscape has a perimeter of the proto-aFootball
field. There is an **inside**. When the ball goes trhough the perimeter we use two code words to identify in which
**perimeter sublane** the game is re-assumed. {18} for **contralateral sublane clsl** reposition and {19} for **lateral
sublane lsl** reposition. There are eighteen patches with id_code in the range (00..08,09,..,17). The **inner subspace** 
contains the patches subset {05,06,07,08,14,15,16,17}. The **outter subspace** contains  the patches subset
{00,01,02,03,04,9,10,11,12,13}. Table 4.1. summarizes the set of spatial relations between patches in the organization of the
patched bounded landscape.

![](/images/aBlandscape_whole_aFootball.png "Figure 4.3. Components of aFootball Space in PB_Landscape")

![](/images/Circos_aBlandscape_neighborhood.png "Figure 4.4. Neighborhood Spatial Relations in aFootball PB_Landscape")

### Table 4.1.Spatial Relations in Organized Patched Bounded Landscape

|pid|wholeU| HF|subspace| 0-neighbor  |     1-neighbors   |        2-neighbors      |   3-neighbors  |4-neighbor|5-ne|
|---|------|---|--------|-------------|-------------------|-------------------------|----------------|----------|----|

| 00|inside|own| outter |    {18}     |     {01,02,05}    |     {03,04,06,07,08}    |{12,13,15,16,17}|{10,11,14}|{09}|
| 01|inside|own| outter |   {18,19}   |    {00,03,05,06}  |   {02,07,08,13,16,17}   |{04,11,14,15,17}|{09,10,12}|{09}| 
| 02|inside|own| outter |   {18,19}   |    {00,04,05,07}  |   {01,06,08,12,15,17}   |{03,10,14,16,18}|{09,11,13}|{09}| 
| 03|inside|own| outter |    {18}     |    {01,06,13,16}  |   {00,05,08,11,14,17}   |{02,07,09,14,15}|  {04,10} |{12}| 
| 04|inside|own| outter |    {18}     |    {02,07,12,15}  |   {00,05,08,10,14,17}   |{01,06,09,14,16}|  {03,11} |{13}| 
| 05|inside|own| inner  |     {}      |{00,01,02,06,07,08}|    {03,04,15,16,17}     |{10,11,12,13,14}|    {09}  | {} | 
| 06|inside|own| inner  |     {}      |  {01,03,05,08,16} |  {00,02,07,11,13,14,17} | {04,09,10,15}  |    {12}  | {} | 
| 07|inside|own| inner  |     {}      |  {02,04,05,08,15} |  {00,01,06,10,12,14,17} | {03,09,11,16}  |    {13}  | {} | 
| 08|inside|own| inner  |     {}      |   {05,06,07,17}   |{00,01,02,03,04,14,15,16}|{09,10,11,12,13}|     {}   | {} | 
| 09|inside|opp| outter |    {18}     |     {10,11,14}    |     {12,13,15,16,17}    |{03,04,06,07,08}|{01,02,05}|{00}|
| 10|inside|opp| outter |   {18,19}   |    {09,12,14,15}  |   {11,16,17,04,07,08}   |{13,02,05,06,08}|{00,01,03}|{00}| 
| 11|inside|opp| outter |   {18,19}   |    {09,13,14,16}  |   {10,15,17,03,06,08}   |{10,00,04,06,07}|{00,02,04}|{00}| 
| 12|inside|opp| outter |    {19}     |    {10,15,04,07}  |   {09,14,17,02,05,08}   |{11,16,00,05,06}|  {13,01} |{03}| 
| 13|inside|opp| outter |    {19}     |    {11,16,03,06}  |   {09,14,17,01,05,08}   |{10,15,00,05,07}|  {12,02} |{04}| 
| 14|inside|opp| inner  |     {}      |{09,10,11,15,16,17}|    {12,13,06,07,08}     |{01,02,03,04,05}|    {00}  | {} | 
| 15|inside|opp| inner  |     {}      |  {10,12,14,17,07} |  {09,11,16,02,04,05,08} | {13,00,01,06}  |    {03}  | {} | 
| 16|inside|opp| inner  |     {}      |  {11,13,14,17,06} |  {09,10,15,01,03,05,08} | {12,00,02,07}  |    {04}  | {} | 
| 17|inside|opp| inner  |     {}      |    {14,15,16,08}  |  {09,10,11,12,13,05,06} |{00,01,02,03,04}|     {}   | {} |
| 18|perims|own| periss | {00,01,02}  |  {              } |      {              }   | {            } |   {  }   | {} | 
| 19|perims|opp| periss | {09,10,11}  |  {              } |      {              }   | {            } |   {  }   | {} |
| 20|perims|opp| periss |{01,03,13,11}|  {              } |      {              }   | {            } |   {  }   | {} |
| 21|perims|opp| periss |{02,04,12,15}|  {              } |      {              }   | {            } |   {  }   | {} |

Alternative views of the organization of the patched bounded landscape are shown in Figure 4.5. for 1-neighborhoods and in 
Figure 4.6. for team halves.

![](/images/aFootball_1Neighborhood.png "Figure 4.5. Adjacency Meso Subspaces {Box, Perimeter, Inner, Outter} PB_Landscape")

![](/images/aFootball_team_half.png "Figure 4.6. Adjacency Meso Subspaces {Own, Them, Both} Team Halves in PB_Landscape")

## 4.3. Space Architecture for aFootball on PB-Landscape

The organization of space reveals the existence of a terrain **hierarchy** in the patched bounded landscape that invites to
responds with tasks propers of an **organic aFootball strategy**. One in which a **core-modulus** is positional set up in
order to play in the inner subspace and with a larger **membrane-modulus** positional set up. One in a kind of convex closure
of a shape that contains all outter patches. It is the **convex hull**, a geometric concept that emerges from the space
architecture as *complexity of the landscape*. An invitation to move and play the ball in this convex hull that currently 
separates inner and outter subspaces.

All these relational organizations of space into subspaces and the Figure 4.7. that shows the shortest path patch 
relationships constitute the **architecture of space** of the patched, bounded landscape PB_Landscape.

![](/images/aFootball_KSpace_Architecture.png "Figure 4.7. Architecture of Space of PB_Landscape for aFootball")

[^1]: The fastai.template does not support dynamic content yet. Visit on youtube our **aNT-aFICS** channel.
