The presented qualification report performs simulations of drug disposition and pharmacokinetics in subjects with hepatic impairment (HI) to qualify the parameterization of the foundational anatomy and physiology parameters for virtual populations with HI in the Open Systems Pharmacology (OSP) Suite.

The liver is an important biotransformation site that serves key roles in the metabolism and clearance of drugs and toxins. HI is defined by a loss of functional hepatocytes which leads to connective tissue and nodule formation in the liver. The resulting pathophysiology of hepatic impairment is multifactorial; however, several outcomes are apparent. Hepatic impairment is often associated with shunting of blood around the cirrhotic liver which can lead to encephalopathy, decreased drug protein binding, hyperbilirubinemia, and the development of ascites and varices. To describe the disease progression (severity) and estimated prognosis with these factors in consideration, the Child-Pugh score was developed. The Child-Pugh score is designated as A (Mild: 5-6), B (Moderate: 7-9), or C (Severe: ≥10). It is calculated from summing the scores derived from the table shown below.

**Table 1. Child-Pugh scoring determined by factors affected by HI** <a id="table_1">

| **Factor**             | **1**    | **2**    | **3**    |
|------------------------|----------|----------|----------|
| Bilirubin (M)          | <34      | 34-51    | >51      | 
| Albumin (g/dL)         | >3.5     | 3-3.5    | <3       |
| Prothrombin time (INR) | <1.7     | 1.7-2.3  | >2.3     |
| Ascites                | None     | Slight   | Moderate |
| Encephalopathy         | None     | Minimal  | Advanced |

Quantitative anatomical and physiological changes observed in hepatically impaired individuals have an impact on drug pharmacokinetics. These modifications include changes in blood flows (decreased portal and renal blood flow, and increased hepatic arterial blood flow), cardiac output (increased), plasma binding protein concentrations (decreased), hematocrit (decreased), hepatic intrinsic clearance, and renal intrinsic clearance. With respect to hepatic intrinsic clearance, several enzymes, CYP3A4, CYP1A2, and CYP2E1 are known to be affected in the disease process.

This report builds upon the work by Edginton and Willmann (1) and Johnson, Boussery (2) to qualify the parameterization of a HI population implemented in PK-Sim. Section 2 describes the generation of HI populations. Section 3 evaluates the predicted effects of HI on the pharmacokinetics of eight compounds: alfentanil, levetiracetam, metoprolol, midazolam, sildenafil, theophylline and lidocaine. Evaluation for each compound is split into two steps: an initial model calibration against a healthy population, followed by an extension to populations of subjects with relevant severities of HI.
