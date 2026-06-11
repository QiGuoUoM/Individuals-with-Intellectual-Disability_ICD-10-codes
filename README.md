# Individuals-with-Intellectual-Disability_ICD-10-codes
This code list comprises the ICD-10 diagnostic codes used to flag individuals with intellectual disability within the HES dataset.

To construct the ICD-10 code list, two main sources were used:

•	NHS guidance on improving the identification of people with learning disabilities (based on SNOMED CT coding)
•	Previously published studies using ICD-10 codes to identify intellectual disability

1.Sheehan R, Mansour H, Broadbent M, Hassiotis A, Mueller C, Stewart R, Strydom A, Sommerlad A. Recording of intellectual disability in general hospitals in England 2006–2019: Cohort study using linked datasets. PLoS medicine. 2023 Mar 20;20(3):e1004117.

2.Zylbersztejn A, Stilwell PA, Zhu H, Ainsworth V, Allister J, Horridge K, Stephenson T, Wijlaars L, Gilbert R, Heys M, Hardelid P. Trends in hospital admissions during transition from paediatric to adult services for young people with learning disabilities or autism: Population-based cohort study. The Lancet Regional Health–Europe. 2023 Jan 1;24.

3. Lin E, Balogh R, Cobigo V, Ouellette‐Kuntz H, Wilton AS, Lunsky Y. Using administrative health data to identify individuals with intellectual and developmental disabilities: a comparison of algorithms. Journal of Intellectual Disability Research. 2013 May;57(5):462-77.

4. NHS England Learning Disabilities Local CQUIN Templates.https://www.england.nhs.uk/publication/learning-disabilities-local-cquin-templates-2016-17/

5. Durbin A, Balogh R, Lin E, Palma L, Plumptre L, Lunsky Y. Community and Hospital Healthcare Use by Adults With and Without Intellectual and Developmental Disabilities in Ontario, Canada, During the First 2 Years of the COVID‐19 Pandemic. Journal of Intellectual Disability Research. 2025 Apr;69(4):318-27.

6. Learning disabilities in Sandwell Joint Strategic needs assessment

Only codes that explicitly indicate intellectual disability were included for case identification. Although the NHS guidance also lists codes that may suggest a learning disability, we decided to restrict inclusion to definitive diagnostic codes only. This decision was based on the assumption that the risk of missing relevant cases using a narrower definition is low.
 
Method used to identify ICD-10 codes:

•	SNOMED-to-ICD mapping

SNOMED terms from the NHS guidance (“Improving identification of people with a learning disability: guidance for general practice”) were searched in the ICD-10 browser. Where matches were found, corresponding ICD-10 codes and terms were recorded.

•	Synonym search via MedGen

If no direct match was identified, synonyms of SNOMED terms were searched using MedGen (NCBI). These synonyms were then re-checked in the ICD-10 browser, and any matches were recorded.

•	SNOMED CT browser and reference sets

If no match was still identified, SNOMED CT International Browser was used, and mapped ICD-10 codes were extracted using available reference sets.
After compiling all codes, each term was reviewed to confirm whether it was truly linked to intellectual disability. Each code was annotated with an inclusion decision and rationale.

In addition, ICD-10 codes from previous studies were also reviewed. One study categorised codes into: “Exact diagnosis”, “High-risk conditions” (≥75% likelihood of learning disability), “Associated conditions” (30–75% likelihood). Consistent with the first source, only definitive diagnostic codes were included. Duplicate codes were removed and all remaining codes were individually reviewed for relevance.

This list is also checked and reviewed by clinicians specialised in intellectual disability.
