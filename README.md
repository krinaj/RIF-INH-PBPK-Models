# RIF-INH-PBPK-Models
Rifampin and isoniazid whole-body PBPK models, including various central nervous system (CNS) comparments and genotype effects, to allow simulations of pharmacokinetics in TB meningitis patients

Previously validated whole-body PBPK model of isoniazid was utilized and was unchanged [Cordes 2016]. The model includes effects of NAT2 genotype. The model also includes distinct compartments for brain interstitial fluid and brain tissue and thus enables simulations of isoniazid PK at site of action in tuberculosis meningitis patients. Original codes for isoniazid model can be obtained from https://github.com/HenrikCordes/isoniazid-PBPK-model.

Previously validated whole-body PBPK model was used as the base model [Hanke 2018]. The model included the effect of hepatic organic anion‐transporting polypeptide transporter OATP1B1 (encoded by the gene SLCO1B1) on rifampin clearance. We added the covariate effect of SLCO1B1 variability by modeling a dataset that included rifampin PK and SLCO1B1 genotypes, derived from a cohort of 72 pulmonary TB patients from Africa, North America, and Spain [Weiner 2010]. The updated rifampin with SLCO1B1 genotype effect is provided here in this repository.

Codes for post-processing of the simulations to calculate Cmax and AUC at various doses are also incuded here in this repository. 



