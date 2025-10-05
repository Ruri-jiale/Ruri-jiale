# Hi, I'm Jiale Chen (Ruri-jiale)

Independent Researcher in Neuroimaging & Computational Neuroscience
Open Science • Reproducible Methods • Meta-analytic Design

---

## About Me

I am a 20-year-old independent researcher working on computational neuroimaging, meta-analysis methodology, and reproducible research infrastructure. My work focuses on building transparent tools for functional brain imaging analysis and developing rigorous methodological frameworks for neuroscience research.

**Research Areas**:
- Functional neuroimaging analysis (connectivity, meta-analysis)
- Coordinate-based meta-analytic methods (ALE, MKDA)
- Biomedical literature mining and classification
- Neuroimaging software development
- Reproducible research practices

I operate independently outside traditional institutional frameworks, with full autonomy over research direction and implementation decisions.

---

## Research Projects

### NMAP Research Suite

The NMAP (NeuroMap Alignment Pipeline) suite encompasses coordinate-based meta-analysis infrastructure and literature mining systems for neuroimaging research.

---

**NMAP-Fusion-α** (Literature Mining System)
**Status**: Active development (~85% complete)

Proprietary biomedical literature mining pipeline for PubMed data classification and relevance assessment. Independent software development project.

**Current scope**: 1,107 records across 46 classification categories in addiction and depression research

**Processing stack**: TF-IDF, Word2Vec, BioBERT-v1.1 with dual validation workflow (AI scoring + human expert review)

**Technical implementation**: Streamlit-based expert review interface with YAML configuration system

**Archival**: [Zenodo v0.2](https://zenodo.org/records/15355619) (software release, independent of any review protocol)

**Clarification**: The author is separately fulfilling a systematic review protocol registered in PROSPERO ([CRD420251044665](https://www.crd.york.ac.uk/PROSPERO/view/CRD420251044665)). That protocol describes a traditional manual meta-analysis with no relation to this AI-driven software system. The NMAP-Fusion software suite represents independent technical innovation developed during personal time on personal equipment, sharing only nomenclature similarity with the review title.

---

**NMAP Core** (Coordinate-Based Meta-Analysis Engine)
**Status**: Production-ready (v1.2.0)

Core meta-analysis engine implementing Activation Likelihood Estimation (ALE) algorithms for coordinate-based neuroimaging research.

**Performance**: 8,000-13,000 coordinates/second on standard datasets

**Validation**: Algorithm accuracy r=0.938, Dice=0.955 against GingerALE reference using BrainMap data

Python implementation with Numba JIT compilation. Supports batch processing and automated result reporting.

---

### MEENet (Moderation-Mediation Effects Estimation Network)

**Status**: v1.0.0 development complete, publication-ready

Statistical toolkit for mediation and moderation analysis in exposure-health research and causal inference studies.

**Core capabilities**:
- Mediation analysis with bootstrap inference (Imai et al. 2010 framework)
- Johnson-Neyman analysis for conditional process modeling
- Robust standard errors (HC0-HC3, cluster-robust)
- High-dimensional mediator screening (LASSO/Elastic Net)

**Integration**: MOFA2, mixOmics, NHANES survey data pipelines

Automated AGReMA and STROBE compliance reporting for publication requirements.

---

### MRForge (Mendelian Randomization Framework)

**Status**: v1.0.0 complete

Computational framework integrating statistical and machine learning approaches for Mendelian randomization analysis.

**Implementation**:
- R statistical engine (3,806 lines core analysis code)
- Python ML pipeline (2,917 lines) with GPU acceleration support
- Cross-language integration for statistical and ML workflows

**Methods**: IVW, MR-Egger, weighted median, MR-PRESSO, multivariable MR, bidirectional causality testing

Comprehensive test suite (>5,000 lines) ensuring reproducibility and quality assurance.

---

### NeuroCompass

**Status**: v1.0.0 released (October 2025) | [Zenodo (in preparation)](https://zenodo.org/uploads/16754316)

GPU-accelerated neuroimaging toolkit for brain extraction, image registration, and motion correction.

**Current implementation**:
- Brain extraction (BET): 4.3s average on clinical T1-weighted MRI (GPU)
- 17× improvement over naive CPU baseline
- Validated on OpenNeuro dataset (5 subjects)
- Modern CLI with Rich/Typer interface

**Development note**: Initial release delayed due to project management challenges and Linux/Git workflow learning curve (including accidental `rm -rf` data loss incident in September 2025). Lesson learned: backup strategies and systematic version control are non-negotiable.

**Roadmap**: v1.1.0 (Q4 2025) - Enhanced quality metrics, FLIRT registration, MCFLIRT motion correction.

**Technical foundation**: Python + PyTorch CUDA backend, C++17 core planned for future integration.

**Legal notice**: Independent implementation. Not affiliated with FSL, FMRIB, or University of Oxford. Algorithms based on public domain methods from peer-reviewed literature.

---

## Research Infrastructure

**All research conducted independently on personal computing equipment**:

- **Hardware**: Intel Core i9-13900H (13th Gen) + NVIDIA GeForce RTX 4060 Laptop GPU (8GB VRAM)
- **Software environment**: Ubuntu 22.04 (WSL2), self-configured development stack
- **Funding**: Self-supported, conducted during personal time outside any institutional obligations
- **Independence**: Full autonomy over research direction, methodology, and publication decisions

No institutional resources, computing clusters, or external funding utilized. All projects developed, tested, and validated on a single personal laptop workstation.

---

## Research Philosophy

**Independence without compromise**: I operate as an independent researcher by choice, maintaining full control over research direction, methodology, and publication decisions. This is not a temporary status but a deliberate operational model.

**Transparency and reproducibility**: All methodological work is accompanied by open-source code and replication materials. Reproducibility is not optional.

**Rigorous validation**: Claims require evidence. Performance metrics are benchmarked against established references. Quality thresholds are documented and enforced.

**Learning from failure**: The NeuroCompass delay taught me that technical competence requires systematic practice. I document mistakes to prevent recurrence.

---

## Peer Review Activity

Active reviewer for multiple *Frontiers* specialty journals ([Frontiers Profile](https://loop.frontiersin.org/people/2906735/overview)):

- *Frontiers in Endocrinology* (Gut Endocrinology)
- *Frontiers in Cellular and Infection Microbiology* (Intestinal Microbiome)
- *Frontiers in Microbiology* (Microorganisms in Vertebrate Digestive Systems)
- *Frontiers in Immunology*

**Review record** (as of October 2025):
- 4 published reviews
- 4 manuscripts under review
- Total: 10 review invitations accepted

**Current expertise areas**: Microbiome-gut-brain axis, endocrine signaling, immunology, computational methods

**Future aspirations**: Expanding review portfolio to neuroimaging and computational neuroscience (*Frontiers in Neuroscience*, *Frontiers in Neuroimaging*)

Reviewing is a professional responsibility, not gatekeeping.

---

## Additional Work

**Data Science**: Modeling and computational experiments on [Kaggle @mokuyojiale](https://www.kaggle.com/mokuyojiale)

---

## Contact & Identifiers

- Email: jlchen7080@gmail.com
- ORCID: [0009-0008-3902-9675](https://orcid.org/0009-0008-3902-9675)
- GitHub: [@Ruri-jiale](https://github.com/Ruri-jiale)

---

## Research Ethos

> "Build carefully. Publish transparently. Defend rigorously."

> "Independence is not isolation. It is autonomy with accountability."

> "Reproducibility is not a courtesy. It is a requirement."

Science is a right, not a privilege. Independent research is legitimate research.
