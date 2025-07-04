# Isoniazid-Model
Whole-body PBPK model of isoniazid

## Repository files
Within this repository, we share a whole-body PBPK model of isoniazid. The model was developed using data of 11 clinical studies of intravenous (dosing range 5 - 10 mg/kg) and oral administration (dosing range 4.68 - 20 mg/kg and 300-900 mg).

The PK-Sim project file contains simulation examples and the observed data of all clinical studies used for model development and evaluation. For further details, quantitative model evaluation, sensitivity analysis and extensive documentation please refer to [1]. A PBPK model including the metabolites (acetylisoniazid, isonicotinic acid, isonicotinylglycine, hydrazine, acetylhydrazine and diacetylhydrazine) is available [1], but not included in this repository as it requires deining the stoechiometry of the enzymatic reactions in MoBi which is currently not supported by the requalification workflow. 

## Code of conduct
Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution
We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License
The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## Reference
[1] Cordes H, Thiel C, Aschmann HE, Baier V, Blank LM, Kuepfer L. A physiologically based pharmacokinetic model of isoniazid and its application in individualizing tuberculosis chemotherapy. Antimicrob Agents Chemother 2016, [http://doi.org/10.1128/AAC.00508-16](https://journals.asm.org/doi/10.1128/aac.00508-16)
