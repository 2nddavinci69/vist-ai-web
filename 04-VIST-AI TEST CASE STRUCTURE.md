# VIST-AI TEST CASE STRUCTURE

## 1. Purpose
The VIST-AI Test Case Structure defines a standardized forensic record for documenting individual multimodal AI evaluation cases[cite: 18]. Each test case must be uniquely identifiable and traceable from the original visual stimulus to the final forensic finding[cite: 18, 19].

## 2. Canonical Case ID
Each case receives a unique identifier using the format: `VIST-[YEAR]-[SEQUENCE]` (e.g., `VIST-2026-0001`)[cite: 18, 19].

## 3. Required Test Case Fields
* **Case Identification:** Case ID, Test ID, Case Title, Test Date, Test Time, Analyst[cite: 19, 20].
* **Model Information:** Model Name, Version, Provider, Interface/API Used, Configuration, Temperature/Parameters[cite: 20].
* **Stimulus Information:** Stimulus ID, File, Type (e.g., Mirror-Script, Inverted), Script Type, Transformation Type, Resolution[cite: 20, 21].
* **Ground Truth:** Verified expected interpretation stored independently from the model response[cite: 21, 22].
* **Initial Test:** Exact prompt and complete original model response[cite: 22].
* **Adversarial Challenge:** Challenge prompt and complete challenge response[cite: 22].
* **Observed Behavior & Failure Signature:** Factual description and classification (Perceptual Collapse, Plausible Confabulation, Admission of Limitation)[cite: 22, 23].
* **Analyst Finding & Limitations:** Evidence-based interpretation separating observed evidence from architectural assumptions, plus documented limitations[cite: 23, 24].