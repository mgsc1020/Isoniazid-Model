### In vitro and physicochemical data <a id="invitro-and-physico-chemical-data"></a>

Isoniazid and its metabolites physicochemical properties were predicted from MarvinSketch software  [MarvinSketch V15.11.3](#main-references). The information is summarized in the table below, and was used for model building. Final model parameters are stated in [Section 3.1](#31-isoniazid-final-input-parameters).

| **Parameter**           | **Unit** | **Value** | **Source**| **Description** |
| :---------------------- | ------| -----  | ------------------------------------ | ------------------------------------------------------------ |
| ****Isoniazid****                      |
| MW                      | g/mol    | 137.14    | Predicted [MarvinSketch V15.11.3](#main-references)   | Molecular weight |
| pK<sub>a</sub> (acid)   |          | 13.61      | Predicted [MarvinSketch V15.11.3](#main-references) | acid dissociation constant |
| pK<sub>b</sub> (base)   |          | 2.36, 3.36      | Predicted [MarvinSketch V15.11.3](#main-references)   | base dissociation constant |
| Solubility    | g/L    | 42.15      |  Predicted [MarvinSketch V15.11.3](#main-references)    | solubility @ pH 7.4|
| logP                    |          | -0.67     |Predicted [MarvinSketch V15.11.3](#main-references)| Partition coefficient between octanol and water |
| fu                      | %        | 0.9      |     [Herrera 1990](#main-references)           | Fraction unbound in plasma    | 


### Clinical data <a id="clinical-data"></a>

A literature search was performed to collect available clinical data on isoniazid in adults. 

The following publications were used for model building (training dataset) and model verification (test dataset):

| **Dose** | **Dosing<sup>(a)</sup>** |**Genotype<sup>(b)</sup>**|**Sample**|**Dataset**| **Reference** |
| :---------------------- | ------| -----  | ------------------------------------ | ----------------|---------------------------------------------- |
| 8.38, 9.874 mg/kg| iv | FF, SS|Blood, urine|training and verification|[Boxenbaum 1974](#main-references) |
| 5 mg/kg| iv |  FF, FS, SS|Blood, urine|verification|[Ellard 1973](#main-references) |
| 10 mg/kg| iv |  SS|Blood|verification|[von Sassen 1985](#main-references) |
| 300 mg| po |  FF, FS, SS|Blood|training and verification|[Haegeli 2007](#main-references) |
| 300, 600, 900 mg| po | FF, FS|Blood|verification|[Chen 2011](#main-references) |
| 4.75, 4.68 mg/kg| po | FF, SS|Blood|verification|[Pea 1999](#main-references) |
| 300 mg| po |FF, SS|Blood|verification|[Peretti 1987](#main-references) |
| 300 mg| po | FF, SS|Blood|verification|[Lauterburg 1985](#main-references) |
| 300 mg| po | FF, SS|Blood|verification|[Lauterburg 1981](#main-references) |
| 5 mg/kg| po | FF, SS|Urine|verification|[Mitchell 1975a](#main-references) |
| 20 mg/kg| po |FF, SS|Urine|verification|[Ellard 1976](#main-references) |

<sup>(a)</sup> intravenous (iv) or per os (po) administration route
<sup>(b)</sup> fast acetylator (FF), intermediate acetylator (FS), slow acetylator (SS) genotype
