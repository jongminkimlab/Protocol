Last updated: 6. 17. 2026 <br>
by Jongmin Kim (jk2938 at Cornell dot edu)

# Material 
- Invitrogen Dynabeads Protein A for Immunoprecipitation (Cat #: 10002D)
    > Protein A for rabbit antibodies. Protein G for mouse. 

# Conjugate antibodies to magnetic beads
  > Usually people do IP w/o crosslinking. This step is helpful if you do not want antibodies elute with immunoprecipitated material.<br>
  > If your protein of interest is not ~25 (light) or ~50kDa (heavy chain), then okay without crosslinking.

[below example for 4 IPs]

1. Take 200uL Protein A dynabeads (30uL/IP and 20uL/preclear) x 4 IPs
    > Mix beads well before taking an aliquot
 
2. Use a magnet to attract beads and remove the supernatant 
 
3. Immediately replace liquid (before beads dry) with 500uL 3% BSA in PBSt (0.1% tween) 
    > Mix 300mg BSA in 10mL PBSt
 
4. Magnet, aspirate and wash with another 500uL 3% BSA in PBSt
 
5. Magnet, aspirate and resuspend beads in 500uL 3% BSA in PBSt
 
6. Separate into 2 tubes and label: ‘Beads+Ab’ (300uL) or ‘Preclear’ (200uL). 
 
7. Aspirate the ‘Beads+Ab’ tube, and add 800uL lysis buffer (no need protease inhibitors for this step). 

|Component| Final| 1mL | 20mL|
|---------|----------|--|--|
|1M Tris-HCl, pH 8.0|20mM Tris-HCl, pH 8.0|20|400|
|5M NaCl| 135mM NaCl|27|540|
|50% Glycerol|10% Glycerol|200|4000|
|10% Igepal|1% Igepal|100|2000|
|0.5M EDTA, pH 8.0| 5mM EDTA, pH 8.0|10|200|
|25X cOmplete protease inhibitor|1X cOmplete protease inhibitor|40|800|
|H2O| .|603|12060|
 
8. Add antibodies <br>
e.g.)<br>
400uL – 2uL (~0.2-1ug) of CHD4 (ab72418, Abcam) antibody<br>
400uL – 2uL (~1ug) of IgG <br>
    > Amount of antibody used is empirical. <br>
    > I use 2mL round bottom tubes for better mixing.

9. Incubate at RT for 1 hour on a rotator for antibodies to bind protein A/G
 
10. Remove supernatant
<br><br>
> <b>*Below step is to crosslink antibodies to the beads.</b>  <br>
> <b>If you are not going to crosslink, then wash once with lysis buffer and store @ 4C </b><br>

11. Add 1mL 0.2M triethanolamine pH 8.2
    > [0.2M triethanolamine prep]<br>
    > e.g. 1160uL of 6.7M Triethanolamine 35mL H2O, pH w/ HCl (last time, 3200uL 1N HCl used), bring to final vol. of 40mL <br><br>
    > Note most recent calculation: Triethanolamine (T58300) - 1.124g/mL, 149.19g/mol, so 7.5M, so based on this, need to add 1067uL <br>
    > Or if you use 'weight',<br>
    > 149.19 g:1 mol = x g: 0.2 mol, x = 29.8g/1000mL, add 2.98g for 100mL <br>
 
12. Repeat triethanolamine wash x2 (5 min. each wash)
 
13. Add 1mL dimethylprimelimidate (DMP) to beads (5.4mg DMP into 1mL 0.2M triethanolamine)
    > I save DMP aliquots in 5mL tubes, sealed with parafilm in 4C. 5mL tubes are stored in a sealed container with dessicants.  

14. Incubate at RT for 30min. on a rotator
 
15. Discard supernatant
 
16. Add 1mL 50mM Tris, pH 7.5, wash 15min with mixing
    > Tris to quench unreacted fixatives.
    > You will notice beads becoming ‘clumpy’ as the solution does not have detergents.

17. Discard supernatant
 
18. Wash 3x with 1mL PBSt
 
19. Resuspend ‘Beads+Ab’ in 200uL PBSt, store at 4C.
    > You can prepare crosslinked antibodies overnight. 
  
# Preparing for lysates
 
> Making a good lysate (solubilizing your protein of interest) is the crucial step. It can be a balancing act of detergents, salt concentration, and physical force (homogenization, sonication, freeze-thaw) to maintain protein-protein interaction while breaking up cellular components for solubilization. <br><br>
> Traditionally, chromatin-modifying proteins were purified by nuclear extraction. There are many variations of this protocol, but the core principles are: 1) swell cells in a hypotonic solution, 2) Dounce homogenize to disrupt the cytoplasm and centrifuge to collect nuclei, 3) gradually add high-salt buffer drop by drop to "extract" chromatin-bound factors, imagine squeezing out proteins bound to chromatin, and 4) use the extract for biochemical assays, such as transcription assays, IP, etc. <br><br>
> I still used this method when I was growing liters of Sf9 cells. However, it is not the most efficient approach when working with small numbers of cells from in vivo samples. Therefore, I am constantly modifying lysate preparation protocols, and the version below is our current protocol, although it is not necessarily the most optimal. For general lysate preparation, see Biochem_IP.md.<br><br>
>

20. Collect a single-cell suspension from mouse testes.
    - Whole testes can also be used, but preparing a single-cell suspension may make it easier to collect nuclei while minimizing fibrous connective tissue and other debris.

21. Add lysis buffer (See above recipe. Add protease inhibitor).
    - 30-50uL per 1mg tissue (1mg/30-50uL = 20-33ug/uL range. But since it's not' dry protein weight', actual conc. will be far lower) 
    - 10-25uL per 1M cells (assuming 50ug total protein/1M cells, to get 2-5ug/uL range lysate)
      > Lyse first try with 1mL of lysis buffer per animal (two testes).

22. Mix well and leave at 4C for 5 minutes to dissolve cytoplasm.
23. Centrifuge at 2000G for 5min to collect nuclei. Save cytoplasmic fraction (supernatant).
24. Resuspend with the same volume of high-salt, Triton lysis buffer

|Component| Final| 1mL | 20mL|
|---------|----------|--|--|
|1M Tris-HCl, pH 8.0|20mM Tris-HCl, pH 8.0|20|400|
|5M NaCl| **300mM** NaCl|60|540|
|50% Glycerol|10% Glycerol|200|4000|
|10% Igepal|1% Igepal|100|2000|
|**10% Triton-X 100**|**0.1% Triton-X 100**|**10**|**200**|
|0.5M EDTA, pH 8.0| 5mM EDTA, pH 8.0|10|200|
|25X cOmplete protease inhibitor|1X cOmplete protease inhibitor|40|800|
|H2O| .|603|12060|

25. Mechanically homogenize/disrupt the nuclei with 1mL Dounce homogenizer (tight) by >20x strokes
    > or Mechanically homogenize/disrupt nuclei with a syringe (1mL syringe and a 21/23/25G sequential needles)
 
26. Incubate lysate at 4C for 30 minutes on a rotator.
    > Not sure if this step is absolutely necessary. 
 
27. Spin the lysates down at max speed for 10 minutes at 4C. Take supernatant. 
    > If you are making lysates for the first time, do not throw away pellets. Check with Western later to see if you are not losing your protein in the pellet. 


# Immunoprecipitation
> You may add equal volume of lysis buffer without NaCl/Triton-X to decreace salt/Triton concentration for potentially more efficient IP.

28. Measure concentration using Bradford Assay (Blank, 5, 10, 15, 20). Use 1~2uL. 
 
29. Take out ~5ul (~30ug lysate, ~2% of IP) of lysate for Western. (INPUT). Freeze.
 
30. Preclear the cell lysate: Add lysates to the washed beads (w/o Ab), and incubate on the rotator for 30min @ 4C.

31. Block the antibody-conjugated beads in 3% BSA PBSt for 30 min @ 4C. 
 
32. Using magnet, remove the supernatant from antibody-conjugated beads.
 
33. Take pre-cleared lysates after magnet separation.
 
34. Add lysates to the blocked antibody-conjugated beads and incubate for 4 hrs to O/N on rotator @ 4C

 
# Post incubation wash, elution
Elution buffer
|Component| Final| 1mL |
|---------|----------|--|
|1M Tris-HCl, pH 8.0|50mM Tris-HCl, pH 8.0|50|
|10% SDS| 1% SDS|100|
|0.5M EDTA, pH 8.0| 5mM EDTA, pH 8.0|10|
|25X cOmplete protease inhibitor|1X cOmplete protease inhibitor|40|
|H2O| .|800|

35. Turn heat block to 70C. 
    > I like to use oven because solution evaporates to the tube tops in heat blocks.

36. Using magnet, collect supernatant. Save as 'flow through' for Western blot later. 
 
37. Wash. Immediately replace the depleted supernatant with 1mL cold lysis buffer and incubate beads on rotator for 5 min @ 4C
Wash with lysis buffer.
 
38. Repeat wash 2x with 1mL lysis buffer wash (don’t spin between washes, use magnet!)
 
39. Resuspend dynabeads in 100uL lysis buffer and transfer to new tube.
    > This step is supposedly not to collect contaminants sticked to the tubes. Not sure if this is that helpful. 
 
40. Add 15~50 uL fresh elution buffer to the Dynabeads (made fresh + protease inhibitors) 
 
41. Vortex lightly briefly. 
 
42. Incubate bead in elution buffer @ 70C for 30 min. with frequent (every 5 min) light vortexing. 
 
43. Spin tubes at RT for 10 seconds to take evaporated liquid down. 
 
44. Hold beads in place with magnet and transfer all the supernatant to a new tube. This is your IPed material.


# TCA precipitation 

> Sometimes you want to load all the IPed material for Western or mass spec. TCA precipitation can effectiverly precipitate protein to reduce sample volume. 
 
1. Add 50uL of TCA to 200uL eluate (20% TCA final)
 
2. mix and incubate >1hr in 4C.
 
3. 14K 15min spin
 
4. -20C acetone wash (1mL) (– leave on ice 5min before cfg.)
 
5. remove acetone, dry, resuspend in 13uL 1X western loading buffer.
    > You can also submit TCA-precipiated pellet (pellet may not be visible) to mass spec facility.
