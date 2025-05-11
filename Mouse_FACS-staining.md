Last updated: 5. 11. 2025, by Jongmin Kim (jk2938@cornell.edu)

# Materials

- **Freshly dissociated single cells in PBS**
- **Zombie Green Fixable Viability Kit** (BioLegend, Cat# 423111)  
  > For use on MGH Melody sorter (Laser setup: Blue-488 nm, Yellow-Green-561 nm, Red-640 nm)
- **Zombie NIR Fixable Viability Kit** (BioLegend, Cat# 423105)  
  > For use on Cornell Melody sorter (Laser setup: Violet-408 nm, Blue-488 nm, Red-640 nm)
- **10% BSA in PBS** – frozen aliquots
- **Cold PBS**
- **Cold PBS + 2 mM EDTA**

---

## Antibodies

### Undifferentiated Spermatogonia  
(Markers: THY1⁺ & ITGa6⁺, or THY1⁺ & ITGb1⁺, or THY1⁺ alone)

| Antibody Target | Clone/Label | Catalog Number | Dilution | Supplier |
|-----------------|-------------|----------------|----------|----------|
| **THY1 (CD90.2)** | APC | 130-123-783 | 1:50 | Miltenyi Biotec |
| **ITGa6 (CD49f)** | PE, REAfinity™ | 130-119-807 | 1:50 | Miltenyi Biotec |
| **ITGb1 (CD29)** | PE | 130-102-602 | 1:10 | Miltenyi Biotec |

---

### Differentiating Spermatogonia  
(Markers: THY1⁻ & c-KIT⁺ or c-KIT⁺ alone)

| Antibody Target | Clone/Label | Catalog Number | Dilution | Supplier |
|-----------------|-------------|----------------|----------|----------|
| **CD117 (c-KIT)** | PE | 130-122-937 | 1:500 | Miltenyi Biotec |

> * Antibody stock concentrations can vary. Always verify concentrations and optimize dilutions for your assay.


## Buffers & Reagents

| Reagent                   | Final Concentration           |
|---------------------------|-------------------------------|
| PBS + EDTA                | 2 mM EDTA                     |
| Zombie Green/NIR Stain    | 1 µL per 1 mL PBS             |
| Wash Buffer (Zomb quench) | PBS + 0.5% BSA                |
| Antibody Staining Buffer  | PBS + 2 mM EDTA + 0.1% BSA    |
| Sorting Buffer            | PBS + 2 mM EDTA + 0.1% BSA    |


# Protocol 

---
## Step 1: Initial Wash

- Wash cells once with **cold PBS + 2 mM EDTA**.
- Centrifuge: **400 × g**, **6 min**, **4°C**.

  > * If cells were previously in DMEM + FBS, wash thoroughly. FBS (especially albumin) quenches Zombie Green/NIR.

---

## Step 2: Viability Staining (Zombie Green/NIR)

- Prepare stain: **1 µL Zombie Dye per 1 mL PBS**.
- Resuspend cells (~10M cells/mL) in Zombie Dye/PBS.
- Incubate at **room temperature**, **20–30 min**, protected from light.

  > * Zombie Dye is amine-reactive. Staining at 4°C may reduce reactivity. Manufacturer recommends RT.  
  > * In my experience, most sorting goes okay w/o excluding 'dead/Zombie Dye+' cells. But I had some problem for THY1(+) cell sorting w/o Zombie Dye+ step.
  > * There was no particular reason to use Zombie Dyes. Other cell viability stain is okay as well.

---

## Step 3: Quench & Wash

- Add **~45 mL PBS + 0.5% BSA** directly to stained cells.
- Centrifuge: **400 × g**, **6 min**, **4°C**.

  > * Relatively high percentage of BSA to 'quench' Zombie Dye. 
  > * I try to minimize 'centrifuge/remove supernatant' cycles, because I lose cells every Cfg cycle. So I directly add an excess amount of wash buffer into the existing cell suspension to wash.

---

## Step 4: Antibody Staining

- Resuspend in **PBS + 2 mM EDTA + 0.1% BSA**, with antibodies.
- Cell density: **~10M cells/mL**.
- Incubate: **4°C**, **30–60 min**, protected from light.

  > * Surface markers may internalize at RT — stain on ice or at 4°C.
  > * I was told that cell surface proteins need to be stained at 4°C, otherwise they will be endocytosed. Not sure how much this matters. I get a higher proportion of stained cells when incubated at least for 60 min, so I usually do a 60 min incubation.

---

## Step 5: Final Wash

- Add cold **PBS + 2 mM EDTA** to bring volume to **~50 mL**.
- Centrifuge: **400 × g**, **6 min**, **4°C**.

---

## Step 6: Resuspension for Sorting

- Resuspend in **PBS + 2 mM EDTA + 0.1% BSA**.
- Final cell density: **~10M cells/mL**.
  > * Sorting facility recommends ~5M cells/mL. If you account for cell losses during wash steps, if you aim for 10M/mL, it will be <5M/mL, I think.

---

## Notes for Sorting

- Pre-coat all plasticware (tubes, filters, pipettes) with **0.1% BSA in PBS** to reduce cell loss.
- **Dead cell exclusion** using Zombie Dyes is optional but important for certain gates (e.g., THY1⁺).
- **Typical yields** from one adult mouse (two testes):
  - Total: **30–50M** cells
  - **c-KIT⁺**: 300–500K cells (differentiating spermatogonia)
  - **THY1⁺**: 30–50K cells (undifferentiated spermatogonia)
  - **Spermatocytes**: 300–500K cells
  - **Round spermatids**: 2-3M cells

---

![THY1 profile, 1,000,000 events](https://github.com/jongminkmg/Storage/blob/main/THY1.png?raw=true "THY1 profile, 1,000,000 events")
<br> THY1&ITGa6 profile, 1,000,000 events, ~0.2% of total 'events' (not cells) <br><br>

![THY1 result](https://github.com/jongminkmg/Storage/blob/main/THY1_cells.png?raw=true "THY1 result")
<br> THY1&ITGa6 result<br><br>

![cKIT profile, 100,000 events](https://github.com/jongminkmg/Storage/blob/main/cKIT.png?raw=true "cKIT profile, 100,000 events")
<br> cKIT profile, 100,000 events, 2~4% of total 'events' (not cells)<br><br>

![cKIT result](https://github.com/jongminkmg/Storage/blob/main/cKIT-1_cells.png?raw=true "cKIT result")
<br> cKIT result<br><br>
