To qualify the OSP suite for the prediction of the P-gp DDI potential of new drugs, a set of verified PBPK models of perpetrators, and respective P-gp DDI victim drugs is specified to set up a P-gp-mediated DDI modeling network. 

The following perpetrator compounds were selected: 

- **Rifampicin**
  Model snapshot and evaluation plan (*release* **v2.0**): [https://github.com/Open-Systems-Pharmacology/Rifampicin-Model/releases/tag/v2.0](https://github.com/Open-Systems-Pharmacology/Rifampicin-Model/releases/tag/v2.0)
- **Verapamil**
  Model snapshot and evaluation plan (*release* **v2.1**): [https://github.com/Open-Systems-Pharmacology/Verapamil-Model/releases/tag/v2.1](https://github.com/Open-Systems-Pharmacology/Verapamil-Model/releases/tag/v2.1)
- **Erythromycin** 
  Model snapshot and evaluation plan (*release* **v2.0**): [https://github.com/Open-Systems-Pharmacology/Erythromycin-Model/releases/tag/v2.0](https://github.com/Open-Systems-Pharmacology/Erythromycin-Model/releases/tag/v2.0)
- **Clarithromycin** 
  Model snapshot and evaluation plan (*release* **v2.0**): [https://github.com/Open-Systems-Pharmacology/Clarithromycin-Model/releases/tag/v2.0](https://github.com/Open-Systems-Pharmacology/Clarithromycin-Model/releases/tag/v2.0)
- **Itraconazole** including metabolites 
  Model snapshot and evaluation plan (*release* **v2.0**): [https://github.com/Open-Systems-Pharmacology/Itraconazole-Model/releases/tag/v2.0](https://github.com/Open-Systems-Pharmacology/Itraconazole-Model/releases/tag/v2.0)

The following sensitive P-gp substrates as victim drugs were selected:

- **Digoxin**
  Model snapshot and evaluation plan (*release* **v2.0**): [https://github.com/Open-Systems-Pharmacology/Digoxin-Model/releases/tag/v2.0](https://github.com/Open-Systems-Pharmacology/Digoxin-Model/releases/tag/v2.0)

**Figure 1** shows the prespecified and developed DDI modeling network of interacting perpetrator and victim drugs for the OSP suite qualification of predicting P-gp-mediated DDI.

**Figure** **1: P-gp DDI modeling network**
![DDI P-gp network](images/DDI_P-gp_Compound_Network.png)

<sub>The arrows indicate where at least one clinical DDI study between the two connected substances was available and included in the model network. Red indicates inhibition and green indicates induction as the primary type of interaction. Thin arrows indicate weak, mid-thick arrows moderate and thick arrows strong P-gp modulation by the perpetrator.</sub>

The published DDI studies between the respective perpetrators and victim drugs were simulated and compared to observed data. The following sections give an overview of the clinical studies being part of this qualification report. The respective data identifier (DataID) refers to the **ID** of the dataset in the OSP PK database, version 1.7 ([https://github.com/Open-Systems-Pharmacology/Database-for-observed-data/releases/tag/v1.7](https://github.com/Open-Systems-Pharmacology/Database-for-observed-data/releases/tag/v1.7)).
