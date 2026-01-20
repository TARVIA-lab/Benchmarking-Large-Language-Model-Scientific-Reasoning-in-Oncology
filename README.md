Benchmarking Large Language Model Scientific Reasoning in Oncology

Author

Omar Lujano Olazaba, Ph.D.
Biomedical AI Scientist | Computational Oncology | LLM Research

⸻

Project Overview

Large language models (LLMs) are increasingly used in biomedical research, clinical decision support, and scientific knowledge synthesis. However, their ability to reason accurately about complex cancer biology mechanisms remains poorly validated.

This project systematically benchmarks LLM scientific reasoning in oncology by comparing model-generated responses to PhD-level expert gold standards, focusing on mechanistic accuracy, depth of reasoning, and hallucination risk.

⸻

Key Questions
	•	Can LLMs accurately reason about multi-step cancer biology mechanisms?
	•	Where do LLMs hallucinate or oversimplify biological processes?
	•	How reliable are LLMs for translational oncology and hypothesis generation?
	•	Why is expert human evaluation essential for biomedical AI?

⸻

Dataset
	•	50–100 expert-authored oncology questions
	•	Domains include:
	•	NF-κB signaling
	•	Integrin biology and ECM remodeling
	•	Therapy resistance and relapse mechanisms
	•	Experimental interpretation (in vitro / in vivo)

Each question includes:
	•	A gold-standard expert answer
	•	Stepwise biological reasoning
	•	Annotated failure modes commonly observed in LLM outputs

⸻

Models Evaluated
	•	GPT-4.x
	•	Claude (Anthropic)
	•	Open-source LLM (LLaMA-based)

⸻

Evaluation Metrics

Metric	Description
Factual Accuracy	Correctness of biological statements
Mechanistic Depth	Ability to explain causal relationships
Hallucination Rate	Fabricated or unsupported claims
Overconfidence	Incorrect answers delivered with high certainty
Instruction Adherence	Alignment with prompt constraints


⸻

Methodology
	•	Prompts executed via Python notebooks (Google Colab)
	•	Outputs scored using expert evaluation rubrics
	•	Quantitative metrics combined with qualitative error analysis
	•	Visualizations highlight systematic failure patterns

⸻

Key Findings (Example Placeholder)
	•	LLMs perform well on surface-level biology but struggle with context-dependent signaling
	•	Hallucinations increase when prompts involve ECM dynamics or temporal relapse models
	•	Expert correction significantly improves downstream response quality

⸻

Why This Matters

Unvalidated AI reasoning in healthcare poses real risks. This project demonstrates why human-in-the-loop evaluation is critical before deploying LLMs in biomedical and clinical settings.

⸻

Technologies Used
	•	Python
	•	Google Colab
	•	LLM APIs
	•	Pandas / NumPy / Matplotlib

⸻

Future Directions
	•	Expand dataset to genomics and imaging-based reasoning
	•	Incorporate automated uncertainty detection
	•	Release expert-annotated benchmark publicly
