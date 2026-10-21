<div align="center">

# 🩺 Pharmacovigilance Task 2: Individual Case Safety Report (ICSR)
### **Step-by-Step Guide & Standardized ADR Reporting Form Completion**

---

**Standard Framework:** Philippine FDA / CIOMS Form I Guidelines  
**Case Study:** Amoxicillin-Induced Hypersensitivity Reaction (*Ramesh Patel*)  
**Prepared By:** Emmalyn Chua Mondano-Mariquit, RPh *(Healthcare Virtual Assistant Intern)*  
**Host Organization:** VirtualWorks Lab / Noivrn Internship Program  

---

</div>

## 📌 Executive Summary & Learning Objectives

This repository demonstrates the end-to-end workflow for receiving, evaluating, and documenting a **Suspected Adverse Drug Reaction (ADR)** in accordance with global pharmacovigilance (PV) standards and Philippine FDA regulatory frameworks.

### **Core Competencies & Modules Covered:**
* **Patient & Event Triage:** Extracting clinical data from raw medical records and spontaneous reports.
* **Structured Data Entry:** Populating standard ICSR sections (Patient Information, Suspected Drug, Adverse Event Details, Reporter Info).
* **Medical Terminology Standard:** Coding clinical signs and symptoms using **MedDRA** (Medical Dictionary for Regulatory Activities) preferred terms.
* **Causality & Dechallenge Analysis:** Objective risk evaluation utilizing the **Naranjo Probability Scale** and **WHO-UMC Causality System**.

---

## 📋 Primary Case Data (Raw Clinical Scenario)

| Parameter | Clinical Record Details |
| :--- | :--- |
| **Patient Name / Initials** | Ramesh Patel (RP) |
| **Age / Gender / Weight** | 32 Years Old \| Male \| 65 kg |
| **Diagnosis / Indication** | Acute Bacterial Sinusitis |
| **Medical / Family History** | Personal: No history of allergy.<br>Family: No family history of diabetes or hypertension. |
| **Suspected Medication** | Tab. Amoxicillin 500 mg TID (3x daily) for 5 days |
| **Treatment Timeline** | **Started:** 1st March 2026<br>**Onset of ADR:** 3rd March 2026<br>**Drug Stopped:** 3rd March 2026<br>**Recovery Date:** 6th March 2026 |
| **Adverse Reaction Signs** | Generalized itching and skin rashes over chest. |
| **ADR Intervention & Outcome**| Drug discontinued immediately; treated with oral antihistaminics. Recovered completely. |

---

## 📑 SUSPECTED ADVERSE DRUG REACTION REPORTING FORM
*(Structured according to Phil FDA / CIOMS Form I Standard Specifications)*

### Section A: Patient's Information

| Field | Form Value |
| :--- | :--- |
| **1. Patient Initials** | **RP** (Ramesh Patel) |
| **2. Age at Time of Event** | **32 yrs** |
| **3. Sex** | **Male** [x] / Female [ ] |
| **4. Weight** | **65 kg** |
| **5. Relevant Pre-existing Medical History** | No personal history of allergy. No family history of diabetes or hypertension. |

---

### Section B: Details of Suspected Adverse Reaction

| Field | Form Value |
| :--- | :--- |
| **1. Date Reaction Started** | **03 / 03 / 2026** (3rd March 2026) |
| **2. Date of Recovery** | **06 / 03 / 2026** (6th March 2026) |
| **3. Reaction / Event Description** | Generalized itching and skin rashes over chest following administration of oral Amoxicillin. |
| **4. MedDRA Terminology Mapping** | **LLT:** Skin rash / Itching<br>**PT:** Rash maculo-papular / Pruritus |
| **5. Seriousness Criteria** | Non-Serious<br>*(Does not involve death, life-threatening risk, hospitalization, or persistent disability)* |
| **6. Outcome** | **Recovered Completely** |

---

### Section C: Suspected Medication(s) Details

#### **1. Suspected Drug Product Table**
| Field | Product Data |
| :--- | :--- |
| **Brand / Generic Name** | **Tab. Amoxicillin** |
| **Manufacturer & Batch / Lot No.** | Generic / Lot # AMX-2026-RP8 *(Simulated)* |
| **Dose Used** | **500 mg** |
| **Route Used** | **Oral (PO)** |
| **Frequency** | **TID** (Three times daily) |
| **Date Therapy Started** | **01 / 03 / 2026** |
| **Date Therapy Stopped** | **03 / 03 / 2026** (Stopped on Day 3 upon rash onset) |
| **Reason for Use / Indication** | **Acute Bacterial Sinusitis** |

#### **2. Dechallenge & Rechallenge Action**
* **Dechallenge (Did reaction abate after stopping drug?):** **Yes** — Drug was stopped on 03/03/2026 and reaction resolved completely by 06/03/2026 (**Positive Dechallenge**).
* **Rechallenge (Did reaction reappear after reintroduction?):** **N/A** — Re-exposure was ethically withheld to ensure patient safety.

#### **3. Concomitant Medical Products**
| Drug Name | Dose & Route | Date Started | Date Stopped | Reason for Use |
| :--- | :--- | :--- | :--- | :--- |
| **None Reported** | — | — | — | No other concurrent medications reported. |

---

### Section D: Reporter Information & Management

| Field | Form Value |
| :--- | :--- |
| **1. Name & Professional Title** | **Emmalyn Chua Mondano-Mariquit, RPh** |
| **2. Occupation / Designation** | Registered Pharmacist / Healthcare Virtual Assistant Intern |
| **3. Healthcare Institution / Facility** | Community Pharmacy Practice / VirtualWorks Lab |
| **4. Contact Email** | `emmalyn.mariquit1276@gmail.com` |
| **5. Treatment Given for Reaction** | Amoxicillin stopped immediately; administered symptomatic treatment with oral antihistaminics. |
| **6. Date of Report Submission** | **21 / 10 / 2026** |

---

## 🔬 Causality Assessment & Clinical Narrative

### **Naranjo Adverse Drug Reaction Probability Scale**

| Question / Assessment Parameter | Yes | No | Do Not Know | Score |
| :--- | :---: | :---: | :---: | :---: |
| 1. Are there previous conclusive reports on this reaction? | +1 | 0 | 0 | **+1** |
| 2. Did the adverse event appear after the suspected drug was administered? | +2 | -1 | 0 | **+2** |
| 3. Did the adverse reaction improve when the drug was discontinued? | +1 | 0 | 0 | **+1** |
| 4. Did the adverse reaction reappear when the drug was re-administered? | +2 | -1 | 0 | **0** |
| 5. Are there alternative causes that could have caused the reaction? | -1 | +2 | 0 | **+2** |
| 6. Did the reaction reappear when a placebo was given? | -1 | +1 | 0 | **0** |
| 7. Was the drug detected in blood/fluids in toxic concentrations? | +1 | 0 | 0 | **0** |
| 8. Was the reaction more severe when the dose was increased/decreased? | +1 | 0 | 0 | **0** |
| 9. Did the patient have a similar reaction to the same or similar drugs? | +1 | 0 | 0 | **0** |
| 10. Was the adverse event confirmed by any objective evidence? | +1 | 0 | 0 | **+1** |
| **TOTAL NARANJO SCORE** | | | | **+7** |

> **Causality Classification:** **PROBABLE** *(Naranjo Score Range: 5–8)*  
> **WHO-UMC Causality Category:** **PROBABLE / LIKELY**

---

### **Final Clinical Case Summary**

> **Narrative:**  
> Ramesh Patel, a 32-year-old male weighing 65 kg with no prior history of allergies or chronic disease, was prescribed oral Tablet Amoxicillin 500 mg TID on March 1, 2026, for acute bacterial sinusitis. On March 3, 2026 (Day 3 of therapy), the patient developed generalized itching and skin rashes over his chest. Amoxicillin was immediately discontinued on the same day, and symptomatic treatment with oral antihistaminics was initiated. The rash and itching abated progressively, resulting in complete recovery by March 6, 2026. A formal causality assessment using the Naranjo Algorithm yielded a score of **+7 (Probable)**, confirming a drug-induced hypersensitivity reaction.
