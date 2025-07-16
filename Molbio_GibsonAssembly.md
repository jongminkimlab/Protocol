# Gibson Assembly (NEBuilder® HiFi)

**Last updated:** 2025-07-16  
**By:** Jongmin Kim   
**Overview:**  
This protocol describes how to perform Gibson Assembly using PCR-amplified inserts (e.g. from Twist gene fragments) and a restriction enzyme-digested plasmid backbone. We use NEBuilder® HiFi DNA Assembly Master Mix. You can follow the manufacturer's protocol, but here are some suggestions.

---

## Materials

### Reagents
- [NEBuilder® HiFi DNA Assembly Master Mix (NEB #E2621)](https://www.neb.com/en-us/products/e2621-nebuilder-hifi-dna-assembly-master-mix)
- Twist-synthesized gene fragment (diluted to 10 ng/μL)
- Restriction enzymes (for plasmid digestion)
- PrimeSTAR Max Premix (2X) (Takara #R045A)
- PCR purification kit (e.g. Zymo DNA Clean & Concentrator)
- Agarose gel and loading dye
- Competent cells (e.g. NEB 5-alpha or homemade)

### Equipment
- Thermocycler
- Gel electrophoresis setup
- 37°C incubator or oven
- Nanodrop or Qubit
- Ice bucket
- Heat block or water bath at 50°C

---

## Step-by-Step Protocol

### 1. **Insert Preparation by PCR**

1. Dilute Twist gene fragment to **10 ng/μL**.
2. Set up PCR reactions using **PrimeSTAR Max Premix (2X)**:
   - Try multiple input DNA amounts: **5 ng, 10 ng, and 20 ng**.
   - Run a small aliquot (~5 μL) on an agarose gel to check band quality.
3. Set up duplicate PCR reactions if you need more product.
4. Pool and purify PCR products using a PCR cleanup kit.
5. Quantify DNA concentration.
6. Note: You may not get >200 ng; this is fine — adjust vector:insert ratio by **molar amount** instead of ng. Use a calculator:
   - [Hongjiang's calculator](https://docs.greysea.cc/molecular-weight-calculator)
   - [Bioline DNA calculator](https://www.bioline.com/media/calculator/01_07.html)

---

### 2. **Backbone Preparation by Restriction Digest**

1. Digest plasmid backbone with appropriate restriction enzymes for **1–2 hours** at 37°C.
   - Can use a **dry incubator or oven at 37°C**.
2. Run a small aliquot of digested and undigested plasmid side-by-side on a gel to confirm complete digestion.
3. Purify the digested backbone.

---

### 3. **NEBuilder® HiFi Assembly**

1. Calculate molar ratio of insert and vector (recommended 2:1 or 3:1 insert:vector).
2. Set up 10 μL Gibson reaction:
   - x μL Insert (NEB recommends 0.03-0.2 pmols, usually we end up lower than 0.03 pmols, but for simple cloning, usually okay)
   - y μL Vector 
   - 5 μL NEBuilder® HiFi DNA Assembly Master Mix
   - ddH₂O to 10 μL total
3. Include a **"no-insert" negative control** to assess background from uncut vector.
4. Incubate at **50°C for 15–60 minutes**.

---

### 4. **Transformation**

1. Transform 1–2 μL of Gibson reaction into 25 μL chemically competent cells.
2. Plate on appropriate antibiotic selection plates.
3. Optional: Plate transformation of "no-insert" control for comparison.

---

## Tips and Notes

- Always verify complete plasmid digestion to reduce background colonies.
- PCR yield is often low from gene fragments; adjust reaction conditions or scale as needed.
- Molar ratios are more important than mass. Use calculators!
- If needed, consider DpnI treatment after PCR to remove template plasmid (if you are PCR amplifying plasmids).
- We perform all NEB reactions in 1/2 volume of what is suggested in the manufacturer's protocol

---

## References

- [NEBuilder HiFi DNA Assembly Protocol - NEB](https://www.neb.com/protocols/2014/08/11/protocol-nebuilder-hifi-dna-assembly)
