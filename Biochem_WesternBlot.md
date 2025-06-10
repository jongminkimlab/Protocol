Last updated: 6. 10. 2025

# Material 
  - Cell or tissue lysates <br>
    See 'Making lysates' below.<br><br>
  - Western running buffer (25mM Tris, 192mM glycine, 0.1% SDS)
 
|Component for 10X| for 1L|
|---------|----------|
|Tris base, FW:121.1|30.3g|
|Glycine, FW:75.1|   144g|
|SDS| 10g|
|H2O     |Fill up to 1L (no need to pH)|
  
  > To make 1X, 900mL H2O, 100mL 10X running buffer
  <br>
  
  - Western transfer buffer (25mM Tris, 192mM glycine, 20% Methanol)
  
|Component for 10X| for 1L|
|---------|----------|
|Tris base, FW:121.1|30.3g|
|Glycine, FW:75.1|   144g|
|H2O     |Fill up to 1L (no need to pH)|

  > To make 1X, 700mL H2O, 100mL 10X transfer buffer, 200mL Methanol
  <br>

  - Lysis buffer
 
|Component| Final| 1mL | 20mL|
|---------|----------|--|--|
|1M Tris-HCl, pH 8.0|20mM Tris-HCl, pH 8.0|50|1000|
|5M NaCl| 135mM NaCl|27|540|
|50% Glycerol|10% Glycerol|200|4000|
|10% Igepal|1% Igepal|100|2000|
|0.5M EDTA, pH 8.0| 5mM EDTA, pH 8.0|10|200|
|10% SDS|0.5% SDS|50|1000|
|25X cOmplete protease inhibitor|1X cOmplete protease inhibitor|40|800|
|H2O| .|563|11260|
  > Usually okay without protease inhibitor.
  > I make 1X without SDS and keep in 4C for up to one year. <br>
  > I add SDS in the aliquot of the lysis buffer before use. <br>
  > I do not pre-add SDS because sometimes I need lysis buffer w/o SDS.
  <br>
    
  - 5X loading buffer (5% b-ME, 0.02% Bromophenolblue, 30% Glycerol, 10% SDS, 250mM Tris pH6.8)
    
# Protocol

## Making lysates

0. Methods for homogenization.
    - Cell pellets, mouse embryos, or very soft tissues will be readily dissolved
    - Soft tissues, you can try homogenizing using blue pestle (fitting 1.7mL test tubes) or going through successive 22G->25G needles (up&down about 10 times).<br>
      Instead of needles, you can also use 1mL sized dounce homogenizer.
    - Hard tissues, first grinding in LN2 and then homogenizing works the best.

2. Add lysis buffer.
    - 30-50uL per 1mg tissue (1mg/30-50uL = 20-33ug/uL range. But since it's not' dry protein weight', actual conc. will be far lower) 
    - 10-25uL per 1M cells (assuming 50ug total protein/1M cells, to get 2-5ug/uL range lysate)

3. Homogenize with your favorite method.

4. Add 1-2uL benzonase. Wait until lysate is no longer viscous (10-20 minutes).
    > You can pre-add Benzonase (1uL per 100uL lysis buffer)

5. If still viscous, sonicate (Bioruptor high, 30sec on / 30sec down, 3 times)

6. Measure concentration with BCA (w/ SDS).
    > You can use Bradford if the buffer did not contain SDS.<br>
    > I sometimes like to dissolve the tissue/cells in non-SDS containing buffer first, measure protein conc. with Bradford, and then add SDS. 
7. Calculate loading volumes and make loading samples by mixing 5X loading buffer. 
(Load 10-20ug of protein/well, 15uL max.)

## Running the Gel

Gel: 4-20% Mini-PROTEAN TGX Precast Gel #456-1096 (15ul x 15 wells) 
> Or whatever gel you like.

1. Remove tape and take the comb out of the gel 

2. Assemble the gel running apparatus with gels and fill the running tank with 1X running buffer. 

3. Boil the samples (>95C) for 5-7 minutes total. While boiling, cleanup the wells by pipetting running buffer into the wells. 

4. Load Ladder: 5uL / Sample: up to 15uL 

5. Run at about 100 volts for approximately 2~3 hours.  Run the gel to the bottom


## Transfer

* Preparation
  - Transfer buffer: dilute 10x transfer buffer (100mL) in methanol (200mL) and water (700mL, DW). Make right after start running the gel. Keep at 4C.
  - Foam and gel plastic holder
  - Whatman paper cut in gel size (thin, 4 pieces, next to the gel apparatus shelf)
  - PVDF (next to the gel apparatus shelf): cut out small pieces, do not touch them with hands

1. Activate PVDF in methanol (*nitrocellulose in water*) for 30 seconds.<br>
Equilibrate by submerging in transfer buffer for 5~20 minutes

2. Soak the holder, foam and Whatman paper in 1x transfer buffer.

3. Open the gel using a wedge.  Cut off the top and the bottom ridge of the gel. <br> 
   Lift & move to transfer buffer facing down.

4. Assemble<br><br>
![Transfer setup](https://github.com/jongminkmg/Storage/blob/main/TransferSetup.png?raw=true "Transfer setup")

>***After putting on PVDF, make sure there’s no bubble btw the gel and PVDF.*** 

5. Start transfer
    - Put cassette into transfer chamber 
    - Go to cold room
    - Set, manual: 45mA, for 400vH (volt-hours)
 
 
 ## Antibody hybridization, develop
 
 
 ### Block
 
* Prepare blocking buffer (2.5g milk in 50mL of 0.1% Tween PBSt )    

1. Take out / Check with ponceau / wash out with water / take a picture

2. Make necessary cuts (sides / divide for different antibodies) 

3. Block for 10 minutes to 2 hours at room temperature (rotating or rocking or whatever).


### Primary
* Prepare 2% Skim milk in PBSt (0.1% Tween) 

1. Mix the primary antibody in the 2% skim milk in appropriate dilution, incubate in 4C overnight (2 nights fine). 


### Wash 1
* 3 times wash in PBSt (0.1% Tween) in 10 minutes interval while rocking.

### Secondary
* Prepare 2% Skim milk in PBSt (0.1% Tween) 

1. Mix the secondary antibody in the 2% skim milk in appropriate dilution, incubate in RT for 2 hours (I do 4C overnight).


### Wash 2
* 3 times wash in PBSt (0.1% Tween) in 10 minutes interval while rocking.



### Develop

1. Mix 2 ECL solutions (2mL + 2mL)

2. Incubate the membrane for ~1 minutes

3. Put the membrane between two OHP films in the cassette. 

4. Put western films and develop 3sec, 10sec, 30sec, 90sec, 4.5min, 13.5min.
     > With chemi-Doc system, get first image at 1sec and get images every 20 seconds for 10 minutes.<br>
     > You can do an another 'fine' every 5 sec? acquisitions for one minute to get a better range for strong bands.<br>


 
