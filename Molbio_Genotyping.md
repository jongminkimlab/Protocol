Last update: 7. 9. 2024 <br>
(Jongmin Kim, jk2938@cornell.edu)

# General note
- If you have a good set of primers, you don't need to purify DNA. Just a little bit of lysate is enough.
- When designing primers, if possible, smaller (<300bp) amplicon works better than bigger targets.

# Material
- Taq 2x Master Mix  (M0270L), NEB <br><br>
and/or
- iTaq Universal SYBR green super mix, 5000 rxn  (172-5125), BioRad
- Proteinase K, recombinant PCR grade, ~2.5 units/mg protein (~18mg/mL) (3115828001), Sigma 


  > Regular Taq is error-prone, but in my hands, it worked best in amplifying the targets.<br>
  > Other Polymerases with proofreading functions were never as good.

- Mouse tissue. 2mm length tail end or 2mm x 2mm ear piece are enough.
  > If you can see the tissue piece, that is big enough to PCR.

- Proteinase K lysis buffer
  
|Component| Final| 100mL | 
|---------|----------|--|
|1M Tris-HCl pH 7.5~8.0|10mM Tris-HCl|1mL|
|5M NaCl| 400mM NaCl|8mL|
|0.5M EDTA pH 8|2mM EDTA|400uL|
|10% SDS|0.7% SDS|7mL|
|H2O| .|83.6mL|


# Protocol

1. Make lysis buffer + Proteinase K master mix.
    - Empirically, Proteinase K: lysis buffer = 1:30 works well.
    - 2mm tail or 2mm<sup>2</sup> ear piece, 50uL is enough. If the tissue size is bigger or smaller, adjust the volume accordingly.
    - Make a master mix volume accordingly, depending on the samples to process.
      
2. Add lysis buffer + Proteinase K to tissues.
   
3. Incubate at 60~70C in an oven overnight.

4. Vortex and centrifuge ~13000G for ~5 minutes to remove insoluble debris.

5. Take 5uL of supernatant and mix with 500uL water. You will use this crude lysate for PCR reactions.

<b>[Regular PCR + Agarose gel electrophoresis]</b>

6. Make a master mix (e.g. 10 samples)
   
|Component| Final| 1 rxn | 10 rxn x 10% extra| 
|--|--|--|--|
|Forward primer 10uM|250nM|0.5uL|5.5uL|
|Reverse primer 10uM|250nM|0.5uL|5.5uL|
|2x PCR mix|2x|10uL|110uL|

  - Add 11uL (2x PCR mix + primers) and 9uL of diluted samples per PCR well

7. PCR cycles

|Steps| Temp (C)| Time (min:sec) | # of cycles| 
|--|--|--|--|
|1. Initiation/melting|94|5:00|1|
|2.  Denaturation|94|	0:15| |	
|3.  Annealing (step down) steps 2-3-4 cycle in sequence|	65|	0:30|	10x (dec. 1˚C/cycle)|
|4.  Elongation         	|72|	0:40	| |
|5.  Denaturation|  	94	|0:15	| |
|6.  Annealing steps 5-6-7 cycle in sequence|	55|	0:30|	30x|
|7.  Elongation|	72	|0:40| |	
|8.  Final extension|	72|	5:00	|1|
|9.  Finish| 	12|	∞	|n/a|

8. Perform agarose gel electrophoresis to check PCR products

<i>to be written (qPCR based genotyping protocol)</i>
