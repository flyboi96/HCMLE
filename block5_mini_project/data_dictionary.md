# Data Dictionary – Gallstone Dataset

This document describes the features in the cleaned dataset used to predict gallstone disease.

---

## Target Variable

| Column | Description |
|--------|-------------|
| `has_gallstones` | 1 = patient has gallstones, 0 = patient does not have gallstones |

---

## Demographic and Clinical History

| Column | Description |
|--------|-------------|
| `age` | Age of the patient (years) |
| `gender` | 0 = male, 1 = female |
| `comorbidity` | 0 = none, 1 = one, 2 = two or more conditions |
| `cad` | 0 = no, 1 = yes (coronary artery disease) |
| `hypothyroidism` | 0 = no, 1 = yes |
| `hyperlipidemia` | 0 = no, 1 = yes |
| `diabetes` | 0 = no, 1 = yes |
| `hepatic_fat` | 0 = no, 1 = yes (presence of liver fat by ultrasound) |

---

## Body Size and Composition (Bioimpedance)

| Column | Description |
|--------|-------------|
| `height_cm` | Height (cm) |
| `weight_kg` | Weight (kg) |
| `bmi` | Body mass index (kg/m²) |
| `tbw_kg` | Total body water (kg) |
| `ecw_kg` | Extracellular water (kg) |
| `icw_kg` | Intracellular water (kg) |
| `ecf_tbw_ratio_index` | Ratio of extracellular fluid to total body water (unitless index) |
| `fat_ratio_percent` | Total body fat percentage (%) |
| `lean_mass_percent` | Lean body mass percentage (%) |
| `protein_percent` | Protein content as a percentage of body mass (%) |
| `vfr_score` | Visceral fat rating score (device-specific, unitless) |
| `bone_mass_kg` | Bone mass (kg) |
| `muscle_mass_kg` | Muscle mass (kg) |
| `obesity_percent` | Obesity percentage (%) |
| `fat_mass_kg` | Total fat mass (kg) |
| `visceral_fat_area_cm2` | Visceral fat area (cm², device-estimated) |
| `visceral_muscle_mass_kg` | Visceral muscle mass (kg) |

---

## Laboratory Test Results

| Column | Description |
|--------|-------------|
| `glucose_mg_dl` | Blood glucose (mg/dL) |
| `cholesterol_total_mg_dl` | Total cholesterol (mg/dL) |
| `ldl_mg_dl` | Low-density lipoprotein (LDL cholesterol) (mg/dL) |
| `hdl_mg_dl` | High-density lipoprotein (HDL cholesterol) (mg/dL) |
| `triglyceride_mg_dl` | Triglycerides (mg/dL) |
| `ast_u_l` | Aspartate aminotransferase (AST) (U/L) |
| `alt_u_l` | Alanine aminotransferase (ALT) (U/L) |
| `alp_u_l` | Alkaline phosphatase (ALP) (U/L) |
| `creatinine_mg_dl` | Serum creatinine (mg/dL) |
| `gfr_ml_min` | Estimated glomerular filtration rate (mL/min) |
| `crp_mg_l` | C-reactive protein (mg/L), an inflammation marker |
| `hemoglobin_g_dl` | Hemoglobin (g/dL) |
| `vitamin_d_ng_ml` | Vitamin D concentration (ng/mL) |

---

## Derived or Flag Columns

| Column | Description |
|--------|-------------|
| `glucose_outlier_flag` | 1 = original glucose value was >400 and was capped; 0 = not flagged. Used to track extreme outliers for interpretation.