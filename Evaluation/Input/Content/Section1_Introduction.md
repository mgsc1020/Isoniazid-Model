The presented model building and evaluation report evaluates the performance of a PBPK model for isoniazid (INH) in healthy adults.

The herein presented model was initially developed and published by Cordes *et al.* ([Cordes 2016](#main-references)), extended for a hepatic hydrazine clearance reaction and adjusted later on to PK-Sim® V12. The PBPK model by Cordes *et al.* includes the metabolites (acetylisoniazid, isonicotinic acid, isonicotinylglycine, hydrazine, acetylhydrazine and diacetylhydrazine). However, the metabolites require defining the stoehiometry of the enzymatic reactions in MoBi. Since MoBi projects are currently not supported by the qualification workflow, the presented model includes only the parent compound.

Isoniazid is used as standard treatment for tuberculosis either as a single agent, such as for prevention therapy for latent tuberculosis and in HIV-infected individuals, or as a comedication together with rifampin, pyrazinamide, and ethambutol for the treatment of active pulmonary tuberculosis ([WHO 2015](#main-references)). 

Isoniazid undergoes extensive metabolism, and its elimination is a major determinant of its pharmacokinetics behaviour. Clinical observations linked patient susceptibility to the trimodal pharmacokinetics caused by the genetic polymorphisms of N-acetyltransferase type 2 (NAT2). Although various NAT2 polymorphisms are known, patients can be categorized according to the number of functional NAT2 alleles that they have into slow, intermediate, and fast acetylator phenotypes ([Cordes 2016](#main-references)). Besides acetylation, humans metabolize isoniazid into various compounds, some of which are known to be toxic. Since the complex metabolism of
INH is mainly dependent on NAT2 pharmacogenomics, NAT2 polymorphisms alter the PK of the parent drug, isoniazid, as well as the PK of downstream metabolites, including the toxic compounds hydrazine (Hz) and acetylhydrazine (AcHz) ([Cordes 2016](#main-references)).

The PBPK model of isoniazid has been developed using 11 clinical studies, including intravenous and oral administration to healthy volunteers and tuberculosis patients. The model has then been evaluated by comparing simulations to observed data of both intravenously and orally administered isoniazid covering a dosing range from 4.75 to 20 mg/kg as well as absolute doses of 300 mg and 900 mg po ([Cordes 2016](#main-references)). 

The presented model includes the following features:

- metabolic reactions (NAT2 and NAAA)
- urinary excretion reactions

