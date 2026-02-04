The general concept of building a PBPK model has previously been described by Kuepfer et al. ([Kuepfer 2016](#main-references)). Relevant information on anthropometric (height, weight) and physiological parameters (e.g., blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the respective literature studies and was incorporated in PK-Sim® as described previously ([Willmann 2007](#main-references)). 

The applied activity and variability of metabolic enzymes, plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available PK-Sim® Ontogeny Database Version 7.3 ([PK-Sim Ontogeny Database Version 7.3](#main-references)) or otherwise referenced for the specific process.

The model was built combining bottom-up and top-down techniques. An extensive literature search yielded (1) physicochemical parameter values (2) information on active ADME processes and (3) clinical studies of intravenous and oral administration, covering a broad dosing range with observed concentrations. In the intravenous studies, isoniazid was administered in doses of 5-10 mg/kg. In the oral studies, isoniazid was administered in doses ranging from 4.68-10 mg/kg and absolute doses of 300-900 mg. 

The PBPK models for slow, intermediate and fast metabolizers were built based on data from healthy individuals and tuberculosis patients, using the reported sex, ethnicity and mean values for age, weight and height from each study protocol. If the studies did not provide these parameters, mean patients provided by the PK-Sim® software were used. The physicochemical parameters for isoniazid were calculated with cheminformatics software (MarvinSketch; Version 15.11.30.0; ChemAxon Kft., Budapest, Hungary). Metabolic reactions and active transport were integrated into the PBPK model. Michaelis-Menten kinetics were used to describe the reaction rates. 

The clinical datasets for isoniazid PBPK modeling were divided into a training dataset for model building and a test dataset for model evaluation. Both datasets are presented in [Section 2.2](#clinical-data).

A specific set of parameters ([Section 2.3.4.](#model-parameters-and-assumptions-identification)) were optimized to describe the disposition of isoniazid in MATLAB® software (version 8.5.0.197613; The MathWorks, Inc., Natick, MA) by use of the MoBi toolbox for MATLAB (version 6.0.3; Bayer Technology Services GmbH, Leverkusen, Germany).

The model was verified by simulating further clinical studies reporting pharmacokinetic concentration-time profiles after intravenous and oral administration of isoniazid (test datasets).

Details about input data (physicochemical, *in vitro* and clinical) can be found in [Section 2.2](#invitro-and-physico-chemical-data).

Details about the structural model and its parameters can be found in [Section 2.3](#model-parameters-and-assumptions).