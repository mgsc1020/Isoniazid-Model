### Absorption<a id="model-parameters-and-assumptions-absorption"></a>

The parameter value for  `Specific intestinal permeability` and `Intestinal Paracellular permeability` were predicted from physicochemical properties by PK-SIM®, and the `Specific intestinal permeability` was adjusted based on PK data for slow and fast acetylators after oral administration, see [Section 2.3.4](#model-parameters-and-assumptions-identification). The  solubility used was predicted (see [Section 2.2.1](#invitro-and-physico-chemical-data)). A Lint80 formulation was implemented. 

### Distribution<a id="model-parameters-and-assumptions-distribution"></a>

The INH fraction unbound (fu) in blood was taken from the literature (see [Section 2.2.1](#invitro-and-physico-chemical-data)).

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim®, observed clinical data was best described by choosing the partition coefficient calculation by `Schmitt` and cellular permeability calculation by `Charged dependent Schmitt`.

### Metabolism and Elimination <a id="model-parameters-and-assumptions-metabolism"></a>

Metabolic reactions and active transport were integrated into the PBPK model. Michaelis-Menten kinetics were used to describe the reaction rates. Tissue-specific relative enzyme and transporter abundances were quantified by gene expression data provided by the PBPK modeling software [Meyer 2012](`#main-references`). 

Isoniazid is mainly acetylated by NAT2 to acetylisoniazid. Besides the acetylation pathway, isoniazid is directly converted into isonicotinic acid and hydrazine by an unknown hydrolase. Here, we assumed that NAAA catalyzed this reaction, since the molecular site of the reaction is the same as that in the hydrolysis of acetylisoniazid to isonicotinic acid and acetylhydrazine.

Renal clearance was implemented as glomerular filtration for isoniazid ([Ellard 1976, Mitchell 1975b](#main-references)).

### Automated Parameter Identification<a id="model-parameters-and-assumptions-identification"></a>

The following parameters have been estimated in the model for isoniazid:

| Model Parameter | 
|--------------|
| `Vmax` and `Km`(NAT2) | 
| `Vmax` and `Km`(NAAA)     |
|`Specific intestinal permeability`| 
| `Intestinal permeability (paracellular)`| 
| `Tablet dissolution Weibull Shape`|
| `Tablet dissolution Weibull Time`|
 
