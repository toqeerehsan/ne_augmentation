# NER Datasets for Low-Resource Pakistani Languages

[![Task](https://img.shields.io/badge/Task-Named%20Entity%20Recognition-blue)]()
[![Languages](https://img.shields.io/badge/Languages-Urdu%20%7C%20Shahmukhi%20%7C%20Sindhi%20%7C%20Pashto-green)]()
[![Area](https://img.shields.io/badge/Area-Low--Resource%20NLP-orange)]()
[![Venue](https://img.shields.io/badge/Venue-W--NUT%202025-purple)]()
[![Format](https://img.shields.io/badge/Format-BIO%20Tagging-lightgrey)]()

This repository provides **Named Entity Recognition (NER) datasets** for low-resource Pakistani languages.

The datasets are associated with the paper:

**Enhancing NER Performance in Low-Resource Pakistani Languages using Cross-Lingual Data Augmentation**

**Authors:** Toqeer Ehsan and Thamar Solorio
**Venue:** Proceedings of the Tenth Workshop on Noisy and User-generated Text, 2025
**Pages:** 117–132

---

## Overview

This repository contains NER datasets and resources for the following languages:

* Urdu
* Shahmukhi / Punjabi
* Sindhi
* Pashto

The datasets are useful for research on:

* Named Entity Recognition
* Low-resource NLP
* Multilingual NLP
* Cross-lingual learning
* Data augmentation
* Token classification
* Pakistani language processing
* South Asian NLP

---

## Entity Types

The datasets contain three coarse-grained named entity types:

| Label | Meaning          |
| ----- | ---------------- |
| `PER` | Person           |
| `LOC` | Location         |
| `ORG` | Organization     |
| `O`   | Non-entity token |

---

## Data Format

The datasets follow token-level BIO format.

Example:

```text
لاہور B-LOC
آرٹس I-LOC
کونسل I-LOC
نے O
پروگرام O
منعقد O
کیا O
```

Each line contains:

```text
TOKEN LABEL
```

Sentences are separated by a blank line.

---

## BIO Tags

| Tag     | Meaning                             |
| ------- | ----------------------------------- |
| `B-PER` | Beginning of a person entity        |
| `I-PER` | Inside a person entity              |
| `B-LOC` | Beginning of a location entity      |
| `I-LOC` | Inside a location entity            |
| `B-ORG` | Beginning of an organization entity |
| `I-ORG` | Inside an organization entity       |
| `O`     | Outside any named entity            |

---

## Datasets Included

This repository includes NER resources for:

| Language            | Dataset                 |
| ------------------- | ----------------------- |
| Urdu                | Urdu-WikiAnn / MK-PUCIT |
| Shahmukhi / Punjabi | Shahmukhi NER dataset   |
| Sindhi              | SiNER                   |
| Pashto              | Pashto-WikiAnn          |

Depending on the dataset, the repository may include:

* Train files
* Validation files
* Test files
* BIO-formatted annotations
* Corrected annotations
* Entity dictionaries
* Augmented datasets
* Multilingual training files

---

## Research Background

Named Entity Recognition remains challenging for low-resource languages because of limited annotated datasets and weak representation in multilingual language models.

This repository supports research on NER for Pakistani languages by providing datasets used in experiments with multilingual and generative models such as:

* Glot500-base
* XLM-RoBERTa-large
* LLaMA3-8B-Instruct
* Mistral-7B-Instruct

The associated paper proposes a **cluster-based cross-lingual data augmentation method** for generating culturally and linguistically plausible NER training examples.

---

## Applications

These datasets can be used for:

* Named Entity Recognition
* Urdu NER
* Shahmukhi NER
* Punjabi NER
* Sindhi NER
* Pashto NER
* Multilingual NER
* Cross-lingual NER
* Low-resource NLP
* Data augmentation
* Token classification
* Few-shot NER
* Zero-shot NER
* Evaluation of multilingual LLMs
* Pakistani language processing
* South Asian computational linguistics

---

## Keywords

Named Entity Recognition, NER, Urdu NER, Shahmukhi NER, Punjabi NER, Sindhi NER, Pashto NER, Pakistani languages, low-resource NLP, multilingual NLP, cross-lingual learning, data augmentation, BIO tagging, token classification, South Asian languages, XLM-RoBERTa, Glot500, LLaMA, Mistral.

---

## Citation

If you use this repository, datasets, annotations, augmented data, or entity dictionaries, please cite:

```bibtex
@inproceedings{ehsan2025enhancing,
  title={Enhancing NER Performance in Low-Resource Pakistani Languages using Cross-Lingual Data Augmentation},
  author={Ehsan, Toqeer and Solorio, Thamar},
  booktitle={Proceedings of the Tenth Workshop on Noisy and User-generated Text},
  pages={117--132},
  year={2025},
  publisher={Association for Computational Linguistics}
}
```

---

## Contact

For questions, issues, or collaboration, please open an issue in this repository or contact the authors of the paper.

---

## License

Please check the `LICENSE` file for usage terms. These datasets are intended for academic and research purposes.
