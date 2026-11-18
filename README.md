# Computer Vision and Graph-Based Damage Index Estimation of Reinforced Concrete Columns

[![Research](https://img.shields.io/badge/Project-Research-blue)]()
[![Code License](https://img.shields.io/badge/Code-MIT-green)]()
[![Materials License](https://img.shields.io/badge/Materials-CC%20BY%204.0-lightgrey)]()
[![DOI](https://img.shields.io/badge/DOI-Pending-orange)]()

This repository contains the supplementary materials, datasets, and computational resources associated with a research framework for **automated damage assessment of reinforced concrete (RC) columns using computer vision, graph theory, and machine learning**.

The research investigates the relationship between surface crack-network characteristics and structural damage, developing an image-to-graph processing pipeline and machine-learning models to estimate stiffness- and strength-based damage indices.

---

## 📄 Publication

**Article title:** Automated Inspection of Seismically Damaged Reinforced Concrete Columns Using Multi-Attribute Graph-Theoretic Computer Vision and Explainable Machine Learning

**Authors:** Pouya H. Khosravi, Mohammadjavad Hamidia

**Journal:** [Insert journal name]

**Publication year:** [YYYY]

**DOI:** [Insert DOI]

**Article:** [Insert publisher URL]

---

## 🔬 Research Overview

The proposed framework combines computer vision, graph theory, and machine learning to estimate earthquake-induced damage in RC columns from surface crack patterns.

The methodology consists of four main stages:

1. **Image processing:** Digitization and processing of crack patterns to identify crack boundaries and corner candidates.
2. **Graph construction:** Conversion of crack patterns into graph representations consisting of nodes and edges.
3. **Topological feature extraction:** Quantification of crack morphology, connectivity, and network organization through 14 graph-based descriptors.
4. **Machine learning:** Development of CatBoost regression models to estimate stiffness-based (*DIK*) and strength-based (*DIS*) damage indices using graph features and structural parameters.

The framework is investigated through multiple feature configurations, cross-validation, sensitivity analyses, and validation using additional independent RC column specimens.

---

## 📁 Repository Structure

The repository is organized into the following components:

*Note: The directory structure will be updated as additional materials and source code are released.*

### Supplementary Materials

**Supplementary Table S1** provides the inventory of the candidate crack patterns compiled from published experimental studies, including specimen identifiers, source references, failure modes, damage indices, and inclusion/exclusion status.

Additional supporting materials will be documented in this section.

---

## 💻 Code and Reproducibility

The computational resources associated with this research will include the image-to-graph processing pipeline, graph-feature extraction procedures, machine-learning implementations, and evaluation scripts.

Instructions for software requirements, dependencies, data preparation, model training, and reproduction of the reported results will be provided alongside the corresponding code.

---

## 📚 How to Cite

If you use the methodology, supplementary materials, datasets, or computational resources provided in this repository, **please cite the associated research article and the specific repository release whenever applicable.**

### Research Article

[Insert complete bibliographic reference]

### Repository

[Insert repository citation and DOI after archival publication]

For reproducibility, please specify the repository version or release used in your research.

---

## ⚖️ Licensing and Terms of Use

Licensing is specified according to the type and origin of the materials:

- **Original source code:** MIT License, permitting reuse, modification, and redistribution subject to its terms.
- **Original supplementary documentation and materials:** Creative Commons Attribution 4.0 International (CC BY 4.0), subject to the stated scope of the license.
- **Third-party data and materials:** Remain subject to their respective copyright, licensing, and usage conditions. Their inclusion in this repository does not transfer ownership or grant additional redistribution rights.

Please consult the individual license files and source acknowledgments before reusing any material.

---

## 📬 Contact

For questions, collaboration inquiries, or technical discussions concerning this research, please contact:

**Email:** p.khosravihajivand@mail.sbu.ac.ir

**LinkedIn:** https://www.linkedin.com/in/thisispouyakh/

**Personal website:** https://pouyakh.ir/

---

*This repository is maintained to promote transparency, traceability, and reproducibility in computer-vision-based structural damage assessment.* 
