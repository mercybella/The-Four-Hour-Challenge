# Figure Replication: Linkage Disequilibrium in *vgsc*

This repository contains the Python script used to replicate a figure from:

**Clarkson et al. (2021)**  
*“The genetic architecture of target-site resistance to pyrethroid insecticides in the African malaria vectors* *Anopheles gambiae* *and* *Anopheles coluzzii*.”

This project was completed as part of the **Four Hour Challenge**, a structured upskilling initiative focused on building consistency in computational biology practice through dedicated weekly work.

---

## 🎯 Project Objective

To reproduce a published linkage disequilibrium (LD) figure analyzing mutation patterns in the **vgsc (voltage-gated sodium channel)** gene, which is the target of pyrethroid insecticides in malaria vectors.

---

## 🧬 Data Source

The analysis uses publicly available genomic data hosted on **MalariaGEN**, along with guidance from their tutorials for data access and mutation extraction.

---

## 🔬 What the Script Does

The workflow includes:

- Extracting relevant **vgsc mutations**
- Filtering mutations based on allele frequency criteria (≥5% in at least one population)
- Constructing haplotypes
- Computing **linkage disequilibrium using Lewontin’s D′**
- Generating the final LD plot

---

## 🛠 Tools & Environment

- Python
- `malariagen` package
- Custom linkage disequilibrium scripts
- Public MalariaGEN resources

---

## 📈 Why This Project?

What initially appeared to be a simple figure required deeper understanding of:

- Haplotypes vs. individual mutations
- Population-scale genomic data handling
- Linkage disequilibrium concepts
- Reproducible computational workflows

This project strengthened both my biological understanding and my computational skills.

---

## 📚 Reference

Clarkson, C. S., et al. (2021).  
*The genetic architecture of target-site resistance to pyrethroid insecticides in* *Anopheles gambiae* *and* *Anopheles coluzzii.*

---

## 🙏 Acknowledgements

- MalariaGEN for open data access and tutorials  
- The authors for sharing a detailed GitHub repository  
- The Four Hour Challenge community for accountability and momentum  

---

## 📜 License

This project is released under the **MIT License**.
