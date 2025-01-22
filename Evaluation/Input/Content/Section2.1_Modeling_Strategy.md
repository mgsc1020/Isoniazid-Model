The general concept of building a PBPK model has previously been described by Kuepfer et al. ([Kuepfer 2016](#5-references)). Relevant information on anthropometric (height, weight) and physiological parameters (e.g., blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the respective literature studies and was incorporated in PK-Sim® as described previously ([Willmann 2007](#5-references)). 

The applied activity and variability of metabolic enzymes, plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available PK-Sim® Ontogeny Database Version 7.3 ([PK-Sim Ontogeny Database Version 7.3](#5-references)) or otherwise referenced for the specific process.

A mean model was built based on clinical data from studies with intravenous and oral administration of isoniazide. The studies reported plasma concentrations of isoniazide following intravenous and oral administration. In the intravenous studies, isoniazide was administered in doses of 5–10 mg/Kg. In the oral studies, isoniazide was administered in doses ranging from 4.75–20 mg/Kg and actual doses of 300-900 mg. The mean PBPK model The PBPK models were built based on data from healthy individuals, using the reported sex, ethnicity and mean values for age, weight and height from each study protocol.  If the studies did not provide these parameters, mean patients provided by the PK-SIM software were used. The physicochemical parameters for INH and its metabolites were calculated with cheminformatics software (MarvinSketch; Version 15.11.30.0; ChemAxon Kft., Budapest, Hungary).  Metabolic reactions and active transport were integrated into the PBPK model. Michaelis-Menten kinetics were used to describe the reaction rates. 

The clinical datasets for isoniazide PBPK modeling were divided into a training dataset for model building and a test dataset for model evaluation. Both datasets are presented in [Section 2.2](#22-data-used).

A specific set of parameters ([Section 2.3.4.](#model-parameters-and-assumptions-absorption-identification)) were optimized to describe the disposition of furosemide using the Parameter Identification module provided in PK-Sim®. 

The model was verified by simulating further clinical studies reporting pharmacokinetic concentration-time profiles after intravenous and oral administration of isoniazide (test datasets).

Details about input data (physicochemical, *in vitro* and clinical) can be found in [Section 2.2](#22-data-used).

Details about the structural model and its parameters can be found in [Section 2.3](#23-model-parameters-and-assumptions).




