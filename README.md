# AGR_Dataset

Replication Data Package

Overview

This repository contains all intermediate and final data artifacts generated during the experimental pipeline of the AGR framework.

All data files produced during execution are included to ensure transparency and reproducibility.
Since experiments were conducted in multiple batches and iterative runs, several versions of certain files exist (e.g., _v1, _v2), and file sizes may vary accordingly.

⸻

Data Sources

All raw data originate from publicly available Mozilla open-source platforms:
	•	Firefox Support Forum
https://support.mozilla.org/en-US/questions/firefox
	•	Firefox Official Support Documentation
https://support.mozilla.org/en-US/products/firefox
	•	Mozilla Bugzilla (Firefox product components and historical bugs)
https://bugzilla.mozilla.org/describecomponents.cgi?product=Firefox

These datasets are fully reproducible and can be independently re-collected from the above official sources.

⸻

Included Files

The repository contains:
	•	Raw user feedback datasets
(review_forum.jsonl, support_forum.jsonl, etc.)
	•	Structured and preprocessed feedback
(structured_feedback.jsonl, structured_feedback_v2.jsonl, etc.)
	•	Retrieved evidence artifacts
(retrieved_feedbacks.jsonl, new_retrieved_feedbacks_v*.jsonl, etc.)
	•	Generated reports
(generated_reports.jsonl, generated_reports_v2.jsonl, etc.)
	•	Stored memory artifacts
(stored_feedback.jsonl, stored_feedback_v2.jsonl, etc.)
	•	Baseline comparison outputs
	•	Evaluation and filtering artifacts
(useless_review.json, etc.)
	•	Auxiliary files
(bugs_corpus.jsonl, urls.txt)

Because the pipeline was executed incrementally, multiple versions of similar files are retained to preserve the full experimental history.

⸻

Notes on Reproducibility
	•	All upstream data are publicly accessible.
	•	No proprietary datasets are used.
	•	File size differences reflect different sampling rounds or pipeline iterations.
	•	The repository represents a complete execution trace of the experimental workflow.
