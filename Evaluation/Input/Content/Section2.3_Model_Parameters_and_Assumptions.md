### Absorption <a id="model-parameters-and-assumptions-absorption"></a>

The parameter value for  `Specific intestinal permeability` and `Intestinal Paracellular permeability` were predicted from physicochemical properties by PK-SIM, see [Section 2.3.4](#model-parameters-and-assumptions-identification). The  solubility used was predicted (see [Section 2.2.1](#invitro-and-physico-chemical-data)). A dissolved formulation was implemented. 

### Distribution <a id="model-parameters-and-assumptions-distribution"></a>

The INH fraction unbound (fu) in blood was taken from the literature, while the unknown fu values of the downstream metabolites were estimated during model development (see [Section 2.2.1](#invitro-and-physico-chemical-data) and [Section 2.3.4](#model-parameters-and-assumptions-identification)).

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim®, observed clinical data was best described by choosing the partition coefficient calculation by `Schmitt` and cellular permeability calculation by `Charged dependent Schmitt`.

### Metabolism and Elimination <a id="model-parameters-and-assumptions-metabolism"></a>

Metabolic reactions and active transport were integrated into the PBPK model. Michaelis-Menten kinetics were used to describe the reaction rates. Tissue specific relative enzyme and transporter abundances were quantified by gene expression data provided by the PBPK modeling software [Meyer 2012](#5-references). 

INH is mainly acetylated by NAT2 (NAT2INH) to acetylisoniazid (AcINH). AcINH is then hydrolyzed by an unknown acetylisoniazid hydrolase into isonicotinic acid (INA) and acetylhydrazine (AcHz). N-acylethanolamine acid amidase (NAAA) was defined to be the catalyst for this metabolization step (NAAAAcINH). INA is conjugated toglycine by an unknown transferase to form isonicotinylglycine (INAG).
On the basis of the chemical and structural similarity of INAG and hippuric acid, glycine-N-acyltransferase (GLYATINA) was assumed to catalyze this reaction ([kubota 1991](#5-references), [van der Westhuizen 2000](#5-references)). Due to its broad substrate spectrum, the basolateral T-type amino acid transporter (SLC16A10) was used for activeINA and INAG transport (SLC16A10INA and SLC16A10INAG, respectively) [Uchino 2002](#5-references). Besides the acetylation pathway, INH is directly converted into INA and hydrazine (Hz) by an unknown INH hydrolase. Here, we also assumed that NAAA catalyzed this reaction (NAAAINH), since the molecular site of the reaction is the same as that in the hydrolysis of AcINH to INA and AcHz. Hydrazine is acetylated by NAT2 (NAT2Hz) to AcHz, which is further acetylated by NAT2 to diacetylhydrazine (DiAcHz) [Ellard 1976](#5-references).

Since each of the considered metabolites is found in the urine renal excretion processes for these all metabolites were integrated into the PBPK model([Mitchell 1975a](#5-references), [Ellard 1976](#5-references)). For acetylisoniazid, isonicotinic acid, isonicotinoyl glycine, hydrazine, acetylhydrazine, and diacetylhydrazine glomerular filtration was considered, while for isoniazid and  acetylisoniazid an active tubular secretion process based on Michaelis-Menten kinetics was introduced to match experimental data [Mitchell 1975b](#5-references). The INH conjugation reaction with α-ketoglutarate and pyruvate were lumped together into the active tubular secretion process, since no pharmacokinetic data for those metabolites was available.


### Automated Parameter Identification <a id="model-parameters-and-assumptions-identification"></a>

The following parameters have been estimated in the model for isoniazide:

| Model Parameter | 
|--------------|
| `Vmax` and `Km`(NAT2IHZ) | 
| `Vmax` and `Km`(NAT2Hz)  |
| `Vmax` and `Km`(NAT2)    | 
| `Vmax` and `Km`(NAT2AcHz)    | 
| `Vmax` and `Km`(NAAAINH)     |
| `Vmax` and `Km`(NAAAAcINH)   |
| `Vmax` and `Km`(GLYATINA)    |
| `Vmax` and `Km`(SLC16A10INA) |
| `Vmax` and `Km`(SLC16A10INAG) |
| `Vmax` and `Km`(renal excretion) |

`Specific intestinal permeability`| 
| `Intestinal permeability (paracellular)`| 
| `Tablet dissolution Weibull Shape`|
| `Tablet dissolution Weibull Time`|


 
