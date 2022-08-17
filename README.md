# Insilico-Molecular-Properties-of-Coumarin-using-DeepChem
# Coumarin Properties:
Coumarin’s exhibit  anti-inflammatory, anti-tumor, antibacterial, and antifungal, anti-Alzheimer effects.

# Prerequisites:
      Delaney(For training)
      Test Dataset(Coumarin)
      Python( Deepchem, Pandas, Numpy)
      Model – MPNN
      Featurizer – Weave 

# WorkFlow:
1) Around 1992 Coumarin derivatives were extracted from PubChem using the Tanimoto Threshold of 90%. Eliminating compounds having substructures narrowed down to 1748 compounds. 

2) For solubility prediction DeepChem package was installed and the model was trained on Deleney dataset to make predictions on Coumarin derivatives. The dataset is widely used to validate machine learning models on estimating solubility directly from molecular structures (as encoded in SMILES strings). Delaney dataset has a total of 1128 compounds. 

3) Then ProTox-II Server was used for toxicity prediction (https://tox-new.charite.de/protox_II/index.php?site=compound_input) which classifies the toxicity into different classes from fatal to non-toxic.

Class I: fatal if swallowed (LD50 ≤ 5)

Class II: fatal if swallowed (5 < LD50 ≤ 50)

Class III: toxic if swallowed (50 < LD50 ≤ 300)

Class IV: harmful if swallowed (300 < LD50 ≤ 2000)

Class V: may be harmful if swallowed (2000 < LD50 ≤ 5000)

Class VI: non-toxic (LD50 > 5000)

# Conclusion:
  1) In this study, the Coumarin analogues namely, (2-oxochromen-3-yl)phosphonic acid, Hydrocoumarin-4-ylphosphonic acid, 2-oxochromene-3-sulfinic acid exhibited good solubility, and less toxic to have better therapeutic effect. 
  
  2) Also, from literatures its evident that the Phosphate and Sulfate analogues exhibit to be potential drug targets.


