# Lightweight Cryptographic Performance Dataset for Healthcare Scenarios

This repository contains a curated subset of the heterogeneous medical dataset used in the paper titled:

**"Performance Evaluation of Lightweight Cryptosystems on Varied File Types in Cyber-Physical Systems"**


## 📄 Overview

This dataset is designed to support the evaluation of lightweight encryption algorithms under healthcare-specific scenarios. It includes representative data types such as PDF reports, DICOM images, medical videos, and sensor outputs.

> *The dataset files will be uploaded to this repository after the related study is officially published.*


## 📂 Dataset Structure

The dataset is organized into five scenario-based folders:

```

├── scenario1\_pdf\_reports/
│   └── 100 PDF files (\~2 MB each)
├── scenario2\_video\_and\_dicom/
│   ├── 1 video (AVI, \~30 sec)
│   └── 10 DICOM images (512x512 resolution)
├── scenario3\_mixed/
│   ├── 50 PDFs
│   ├── 20 JPGs
│   ├── 5 DICOM files
│   └── 1 video
├── scenario4\_real\_time\_data/
│   ├── 14 PDF reports
│   └── 7 CSV sensor logs (heart rate, blood pressure, etc.)
├── scenario5\_archiving/
│   ├── 200 PDF files
│   ├── 50 DICOM files
│   └── 5 video files

```

## ⚙️ Technical Specifications

- **PDF**: Synthetic reports simulating clinical documents.
- **DICOM**: Grayscale.
- **Video**: AVI format,
- **Images**: JPG/PNG formats from medical image datasets.
- **CSV**: Simulated time-series physiological data.


## 📚 Citation

This dataset supports a manuscript currently under review. Full bibliographic citation will be provided here following publication.
