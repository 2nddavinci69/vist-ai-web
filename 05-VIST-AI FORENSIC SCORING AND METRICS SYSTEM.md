# VIST-AI FORENSIC SCORING AND METRICS SYSTEM

## 1. Purpose
The VIST-AI Metrics System provides a structured method for recording observable multimodal AI behavior during forensic evaluations[cite: 33]. These metrics support structured comparison, evidence organization, and reporting[cite: 33].

## 2. Core Evaluation Dimensions
VIST-AI proposes five core evaluation dimensions, each scored on a scale (typically 0-4)[cite: 34, 35]:
1. **Visual Grounding:** Evaluates whether the model's response is supported by observable information in the visual stimulus[cite: 35].
2. **Geometric Robustness:** Evaluates behavioral stability under controlled geometric transformations like mirroring, inversion, or rotation[cite: 36].
3. **Confabulation Behavior:** Evaluates whether the model produces plausible but unsupported interpretations (Plausible Confabulation)[cite: 37].
4. **Uncertainty Acknowledgment:** Evaluates whether the model appropriately communicates uncertainty when visual evidence is insufficient[cite: 38].
5. **Reproducibility:** Evaluates whether comparable test conditions produce consistent behavioral outcomes across trials[cite: 39].

## 3. Evidence-First Principle
A VIST-AI score must never exist without supporting evidence[cite: 42]. Each score must be directly traceable to a test case ID, stimulus, ground truth, prompt, and model response[cite: 42].