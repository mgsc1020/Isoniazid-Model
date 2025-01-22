The presented model building and evaluation report evaluates the performance of a PBPK model for isoniazid in healthy adults.

The herein presented model was initially developed and published by Cordes et al. [Cordes 2020](#5-references) and adjusted later on to PK-Sim V11. 

Isoniazid as standard treatment for tuberculosis either as a single agent, such as for prevention therapy for latent tuberculosis and in HIV-infected individuals, or as a
comedication together with rifampin, pyrazinamide, and ethambutol for the treatment of active pulmonary tuberculosi [WHO 2015](#5-references)). 

Isoniazid undergoes a extensive metabolism process, and its elimination is a major determinant of its pharmacokinetics behaviour. Clinical observations linked
patient susceptibility to the trimodal pharmacokinetics caused by the genetic polymorphisms of N-acetyltransferase
type 2 (NAT2). Although various NAT2 polymorphisms are
known, patients can be categorized according to the number of
functional NAT2 alleles that they have into slow, intermediate,
and fast acetylator phenotypes [Cordes 2020](#5-references) . Besides acetylation, humans
metabolize isoniazid into various compounds, some of which are
known to be toxic. Since the complex metabolism of
INH is mainly dependent on NAT2 pharmacogenomics, NAT2
polymorphisms alter the PK of the parent drug, isoniazide, as well as the PK of downstream metabolites, including the toxic compounds hydrazine (Hz) and acetylhydrazine (AcHz)[Cordes 2020](#5-references) .

The herein presented PBPK model of isoniazide has been developed using 12 clinical studies, including intravenous and oral administration to healthy volunteers and tuberculosis patients. The model has then been evaluated by comparing simulations to observed data of both intravenously and orally administered isoniazide covering a dosing range from 4.75 to 20 mg/kg as well as absolute doses of 300 mg and 900 mg po [Cordes 2020](#5-references). 

The presented model includes the following features:

- metabolism of isoniazide into its metabolites (AcINH, INA,
INAG, AcHz, DiAcHz, and Hz)
-  metabolic reactions (NAT2<sub>INH</sub> , NAT2<sub>Hz</sub>, NAT2<sub>AcHz</sub>, NAAA<sub>INH</sub>, NAAA<sub>AcINH</sub> , GLYAT<sub>INA</sub>)
- active transport reactions (SLC16A10<sub>INA</sub>, SLC16A10<sub>INAG</sub>)
- urinary excretion reactions (INH, AcINH, INA, INAG, Hz, AcHz, and DiAcHz)

