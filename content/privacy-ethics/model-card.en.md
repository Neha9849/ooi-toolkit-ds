---
title: "Machine Learning Model Card"
description: Model cards help you document how your model was made. Use this overview to make your own model cards.
author: Mike Nolan
categories: privacy-ethics
tags: ["design", "template"]
downloadBtn: "true"

---

_The following is an editable version of the model card proposed in [arxiv.org/abs/1810.03993](https://arxiv.org/abs/1810.03993)_.


## Model details

Basic information about the model.

* Person or organization developing model
* Date of last update
* Model version
* Model type
  (information about training algorithms, parameters, fairness constraints or other applied approaches, and features)
* Paper or other resource for more information
* Citation details
* License
* Maintainer contact details


## Intended use

Use cases that were envisioned during development.

* Primary intended uses
* Primary intended users
* Out-of-scope use cases


## Factors

Factors could include demographic or phenotypic groups, environmental conditions, technical attributes, or others.

* Relevant factors
* Evaluation factors


## Metrics

Metrics should be chosen to reflect potential real-world impacts of the model.

* Model performance measures
* Decision thresholds
* Variation approaches


## Evaluation data

Details on the dataset(s) used for the quantitative analyses in the card.

* Datasets
* Motivation
* Preprocessing


## Training data

May not be possible to provide in practice.
When possible, this section should mirror Evaluation Data.
If such detail is not possible, minimal allowable information should be provided here, such as details of the distribution over various factors in the training datasets.


## Quantitative analyses

Quantitative analyses should be broken down by the chosen factors.

* Unitary results
* Intersectional results


## Ethical considerations

In this section, you should explore and document the following:

* **Sensitive Data**:
  Does the model use any sensitive data (e.g. protected classes)?
* **Human life**:
  Is the model intended to inform decisions about matters central to human life or flourishing – e.g., health or safety? Or could it be used in such a way?
* **Mitigations**:
  What risk mitigation strategies were used during model development?
* **Risks and harms**:
  What risks may be present in model usage?
  Try to identify the potential recipients, likelihood, and magnitude of harms.
  If these cannot be determined, note that they were considered but remain unknown.
* **Use cases**:
  Are there any known model use cases that are especially fraught?


## Caveats and recommendations

This section should list additional concerns that were not covered in the previous sections.

To be written.
