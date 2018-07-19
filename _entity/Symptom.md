---
layout: entry
title: "Symptom"
shortdef: "Symptoms for lung diseases"
order: 3
---

The definition of 'Symptom' is based on <a href="https://icd.who.int/browse11/l-m/en">ICD-11</a>, published by WHO.

'Symptoms', which can be a group in phenotype, will be annotated in this category. 
The following words/phrases should be annotated as 'Symptom'.

- breathing disorder
  - sleep breathing disorder

~~~ ann
The impact of IPF-related sleep breathing disorders (SBDs) on survival.
T1 Disease 14 17 IPF
T2 Symptom 26 51 sleep breathing disorders
T3 Symptom 53 57 SBDs
T4 Phenotype 62 71 survival
R1 is_eqivalent Arg1:T3 Arg2:T1
~~~

<!-- details -->