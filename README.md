# Humor-Type Annotation Corpus – New Yorker Caption Contest

This repository contains a manually annotated humor corpus built from 200 caption contests of the *New Yorker* Caption Contest dataset. Each caption has been labeled for humor type using a custom 5-way classification scheme.

📚 Developed as part of the **Corpus Analysis** course at the Graduate Center, CUNY (Spring 2025), under the guidance of Dr. Kyle Gorman.

---

## 🎯 Project Overview

The goal of this project was to create a high-quality, labeled dataset to support research and modeling of humor in language. Captions were categorized into five humor types:

- **Pun / Wordplay**
- **Irony / Sarcasm**
- **Absurdity / Nonsense**
- **Cultural Reference**
- **Expectation Violation**

The final corpus includes 1,000 caption–cartoon pairs manually annotated with one or more humor types.

---

## 📁 Repo Contents

humor-annotation-corpus/
├── Humor_type_annotation_200_cartoons.xlsx # Final annotated dataset
├── IAA_20_cartoons.xlsx # Inter-annotator agreement (Cohen's Kappa)
├── Humor_Corpus_Project_Report_Leila_Habibi_Final.pdf # Final written report
└── README.md


---

## 🧪 Methodology

- 200 contests were randomly selected; top 5 user-submitted captions per contest were included (1,000 total)
- Annotations were done collaboratively with a second coder using a shared coding manual
- Inter-annotator agreement was calculated using **Cohen’s Kappa (κ = 0.468)**, indicating moderate agreement
- Disagreements were adjudicated to produce a gold-standard version of the corpus

---

## 🔍 Potential Applications

- Humor detection and classification models  
- Corpus linguistics and annotation methodology  
- Studies in pragmatics, creativity, and affect in language  
- Training datasets for NLP systems focused on humor or figurative language

---

## 🧠 Future Work

This corpus is being used in a follow-up project to build an **automatic humor-type tagger** using machine learning (see planned repo: `humor-tagger`). Additional annotations and evaluation metrics may be added in future iterations.

---

## 📚 Acknowledgments

- Source data: [NextML Caption Contest Corpus](https://nextml.github.io/caption-contest-data/)
- Course: *LING78000 – Corpus Analysis*, Graduate Center, CUNY
- Instructor: Dr. Kyle Gorman

---
