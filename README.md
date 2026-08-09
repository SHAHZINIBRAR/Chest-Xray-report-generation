# 🩻 Chest X-ray Report Generation Using Multimodal Transformers

A deep learning framework for automated Chest X-ray report generation by combining visual and textual information through multimodal transformer-based learning.

## 📌 Overview

Automated medical report generation aims to assist radiologists by generating descriptive clinical reports from medical images.

This project focuses on generating textual reports from Chest X-ray images using a multimodal deep learning framework. The approach combines visual representations extracted from Chest X-ray images with language modeling techniques to generate clinically relevant reports.

The project also evaluates generated reports using both conventional Natural Language Processing metrics and clinically oriented metrics.

---

## 🎯 Objectives

- Generate automated reports from Chest X-ray images.
- Extract meaningful visual features from medical images.
- Generate coherent medical descriptions using a transformer-based language model.
- Evaluate generated reports using multiple text-generation metrics.
- Analyze clinical precision, recall, and F1-score.
- Perform qualitative comparison between reference and generated reports.
- Investigate model behavior using explainability techniques.

---

## 🧠 Methodology

The overall workflow consists of the following stages:

```text
Chest X-ray Image
        ↓
Image Preprocessing
        ↓
Visual Feature Extraction
        ↓
Multimodal Feature Representation
        ↓
Transformer-based Report Generation
        ↓
Generated Chest X-ray Report
        ↓
Multi-Metric Evaluation
