# LaTeX-to-Abstract-Generation-Challenge
This competition required us to take a dataset of jumbled LaTeX research information and generate an abstract from using a ML model! 

# Overview

This challenge asks you to generate a paper abstract from raw LaTeX manuscript content. For each row in test.csv, you receive the paper body/source in the latex field and must predict a concise, high-quality abstract that captures the core contribution, method, and findings.

The novelty is in forcing summarization directly from noisy, technical source text rather than clean prose. In real research workflows, abstracts are critical because they determine first impressions, search visibility, and reviewer triage. A strong model for this task can support faster drafting, editing assistance, and consistent abstract quality at scale.

The competition is also intentionally practical: strong results can come from prompt optimization, lightweight adaptation, and slight fine-tuning strategies, not only from training large models from scratch.
