# 4. On Construction 
**Charles R Paez Monzon** - 2020 - aNatureTechnologies

           - " Time exists in order that everything does not happen all at once, 
               and Space exists so that it does not happen to you" - Susan Sontag
        
4. TOC
{:toc}

## 4.1. Gon on-Ball Conducts Through the Bounded Landscape
Gon is on control of the ball in an arbitrary alpha point and is free to go through the bounded landscape creating a 
sequence of intentional skill actions on his body and on the ball conducting it around with a final destination to an omega 
point where he can end up the effective final action to score a goal.

    - The set of _things_ is a tuple: {goals,ball}
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
ball or on-ball control. But, Gon now knows that he has to do an huge effort because all that space-time is created and happen
on only himself. He **needs team mates to do it one and again and again** in order to have simultaneity and sequentiality of
events and that the action be distributed between all agent in the boundade landscape. Now on, Gon knows that he is
constrained to be in the on-ball state and that most of the time he will be in the off-ball state. That he must concentrate on
how to move and when he must be focus to get control of the ball and decide which is the best action to decide.

![](/images/Gon1inUL-v1.mp4 "Figure 4.1. Animation: Gon on-ball Control on the Bounded Landscape")

## 4.2. Architecture of Space of the Bounded Landscape
### 4.2.1. The Patched Bounded Landscape
In aFootball our perspective of the game is in spatial-temporal terms. This view yields us to state that _there is an
**architecture of the football game** in the bounded landscape. This architecture of aFICS in the bounded landscape is all
about **creating space guided by affordances** and **coming into space at the right time**. 

Therefore, a main idea of strategy to play football in the bounded playground is about **organizing space**. A spatial
practice in geolocalization, as in aFICS for football, to be analysed would be in terms of:
- the static framed bounded landscape or the **aBLandscape** and,
- the teams' dynamics as **Football Flow**

Gon needs _a model of the bounded landscape_ that guides his decision making in any point in the environment when he is off-
ball or on-ball control. But, Gon now knows that he has to do an huge effort because _all that space-time is created 
sequentially but all happen on only himself_.

This model must take into account all spatial reference that Gon has acquiered from exploring the bounded landscape. 
- Gon knows the difference in scale about the **near by and the far away**
- Gon knows the difference between the **inner area and the outter area**
- Gon knows which directions of movement of the ball and of his body are in **sidewayness or counter-sydewayness**.

Let us analyze the framed bounded landscape aBLandscape as the common reference for spatial practice of football.

![](/images/landscapeaB.png "Figure 4.2. Organization of aFootball Space in a Patched Bounded Landscape")

### 4.2.2. Spatial Relations of Patches

**Patches** are _circles, semicircular sectors and circunferences subspaces_. They exhibit spatial relationships between
subspaces and their concatenation as set of subspaces constitute the **spatial organization of the bounded landscape** in the
aFootball Universe whose **inside** is bounded by a **permeter** and the perimeter is conformed by a **lateral** and
**counter-lateral** arcs and the *inside* by an **outter** and an **inner** subspaces as shown in Figures 4.3. and 4.4.

The bounded landscape is organizaed in two halves, **own half** and **opponent half**, each one asociated to a goal object
Each half is sub-organized into nine **patches**. In total, The bounded landscape is a perimeter of the proto-aFootball field.
There are an **inside** ajust and inside. When the ball goes trhough the perimeter we use two code words to identify in which
**perimeter subline** the game is re-assumed. {00} for **contralateral subline clsl** reposition and {10} for **lateral
subline lsl** reposition. There are eighteen patches with id_code in the range (01..09,11,..,19). The **inner subspace** 
contains the patches subset {06,07,08,09,16,17,18,19}. The **outter subspace** contains  the patches subset
{01,02,03,04,05,11,12,13,14,15}. Table 4.1. summarizes the set of spatial relations between patches in the organization of the
bounded landscape.

![](/images/aBlandscape_whole_aFootball.png "Figure 4.3. Components of aFootball Space in PB_Landscape")

![](/images/aBlandscape_Neighbors.png "Figure 4.4. Neighborhood Spatial Relations in aFootball PB_Landscape")

## Table 4.1.Spatial Relations in Organized Bounded Landscape

|pid|wholeU| HF|subspace| 0-neighbor |     1-neighbors   |        2-neighbors      |   3-neighbors  |4-neighbor|5-ne|
|---|------|---|--------|------------|-------------------|-------------------------|----------------|----------|----|
| 00|perims|own| periss | {01,02,03} |  {              } |      {              }   | {            } |   {  }   | {} | 
| 01|inside|own| outter |    {00}    |     {02,03,06}    |     {04,05,07,08,09}    |{14,15,17,18,19}|{12,13,16}|{11}|
| 02|inside|own| outter |   {00,10}  |    {01,04,06,07}  |   {03,08,09,15,18,19}   |{05,13,16,17,19}|{11,12,14}|{11}| 
| 03|inside|own| outter |   {00,10}  |    {01,05,06,08}  |   {02,07,09,14,17,19}   |{04,12,16,18,19}|{11,13,15}|{11}| 
| 04|inside|own| outter |    {10}    |    {02,07,15,18}  |   {01,06,09,13,16,19}   |{03,08,11,16,17}|  {05,12} |{14}| 
| 05|inside|own| outter |    {10}    |    {03,08,14,17}  |   {01,06,09,12,16,19}   |{02,07,11,16,18}|  {04,13} |{15}| 
| 06|inside|own| inner  |     {}     |{01,02,03,07,08,09}|    {04,05,17,18,19}     |{12,13,14,15,16}|    {11}  | {} | 
| 07|inside|own| inner  |     {}     |  {02,04,06,09,18} |  {01,03,08,13,15,16,19} | {05,11,12,17}  |    {14}  | {} | 
| 08|inside|own| inner  |     {}     |  {03,05,06,09,17} |  {01,02,07,12,14,16,19} | {04,11,13,18}  |    {15}  | {} | 
| 09|inside|own| inner  |     {}     |   {06,07,08,19}   |{01,02,03,04,05,16,17,18}|{11,12,13,14,15}|     {}   | {} | 
| 10|perims|opp| periss | {11,12,13} |  {              } |      {              }   | {            } |   {  }   | {} |
| 11|inside|opp| outter |    {00}    |     {12,13,16}    |     {14,15,17,18,19}    |{04,05,07,08,09}|{02,03,06}|{01}|
| 12|inside|opp| outter |   {00,10}  |    {11,14,16,17}  |   {13,18,19,05,08,09}   |{15,03,06,07,09}|{01,02,04}|{01}| 
| 13|inside|opp| outter |   {00,10}  |    {11,15,16,18}  |   {12,17,19,04,07,09}   |{14,02,06,08,09}|{01,03,05}|{01}| 
| 14|inside|opp| outter |    {10}    |    {12,17,05,08}  |   {11,16,19,03,06,09}   |{13,18,01,06,07}|  {15,02} |{04}| 
| 15|inside|opp| outter |    {10}    |    {13,18,04,07}  |   {11,16,19,02,06,09}   |{12,17,01,06,08}|  {14,03} |{05}| 
| 16|inside|opp| inner  |     {}     |{11,12,13,17,18,19}|    {14,15,07,08,09}     |{02,03,04,05,06}|    {01}  | {} | 
| 17|inside|opp| inner  |     {}     |  {12,14,16,19,08} |  {11,13,18,03,05,06,09} | {15,01,02,07}  |    {04}  | {} | 
| 18|inside|opp| inner  |     {}     |  {13,15,16,19,07} |  {11,12,17,02,04,06,09} | {14,01,03,08}  |    {05}  | {} | 
| 19|inside|opp| inner  |     {}     |    {16,17,18,09}  |  {11,12,13,14,15,06,07} |{01,02,03,04,05}|     {}   | {} |



