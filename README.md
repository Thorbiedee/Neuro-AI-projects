# Structural Analysis of Aβ42 E22G Mutation Using AlphaFold

## Background
Amyloid-beta (Aβ) peptides are central to Alzheimer’s disease pathology.  
Aβ42, in particular, forms aggregates that are neurotoxic.  
The E22G mutation (“Arctic mutation”) is known to increase aggregation tendency.

## Objective
Compare the predicted 3D structures of normal Aβ42 and E22G mutant using AlphaFold (ColabFold).

## Methods
- **Software:** ColabFold (AlphaFold2_mmseqs2)
- **MSA mode:** MMseqs2
- **Sequences:**
  - Normal: `DAEFRHDSGYEVHHQKLVFFAEDVGSNKGAIIGLMVGGVVIA`
  - E22G mutant: `DAEFRHDSGYEVHHQKLVFFAGDVGSNKGAIIGLMVGGVVIA`
- **Outputs:** `.pdb` files and structural visualizations

## Results

### Normal Aβ42
![Normal Aβ42 Structure](results/normal/screenshot.png)
- Mostly flexible, small loops and transient helices
- Residue 22: glutamic acid (negatively charged)

### E22G Mutant
![E22G Mutant Structure](results/E22G_mutant/screenshot.png)
- Increased flexibility at residue 22
- Exposed hydrophobic residues F19-F20
- Slight loss of helical content; more extended loops

## Interpretation
- The E22G mutation increases local flexibility and exposes hydrophobic regions
- This structural change likely facilitates aggregation, consistent with disease mechanism

## Files
- **Notebooks:** Interactive ColabFold runs
- **PDB files:** `results/*/ranked_0.pdb`
- **Screenshots:** Visualizations of predicted structures
