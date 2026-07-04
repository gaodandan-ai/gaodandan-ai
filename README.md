<div align="center">

# Dandan Gao

### Computational Biology · Microbial Systems · Reproducible Bioinformatics


[![GitHub](https://img.shields.io/badge/GitHub-gaodandan--ai-181717?style=flat&logo=github)](https://github.com/gaodandan-ai)
[![Research](https://img.shields.io/badge/Research-Computational%20Biology-2E7D32?style=flat)](#research-interests)
[![Bioinformatics](https://img.shields.io/badge/Bioinformatics-Reproducible%20Pipelines-1565C0?style=flat)](#featured-projects)
[![Systems Biology](https://img.shields.io/badge/Systems%20Biology-Regulatory%20Networks-6A1B9A?style=flat)](#featured-projects)

</div>

---

## About

I work at the intersection of **computational biology**, **microbial systems biology**, and **bioinformatics workflow development**.

My projects focus on transforming biological datasets into interpretable computational tools, including whole-genome resequencing, CRISPRi screening, high-throughput growth analysis, transcriptional regulation, metabolic network mapping, and interactive scientific visualization.

---

## Research Interests

- Microbial genomics and functional genomics
- Gene regulatory networks and transcription factor-target relationships
- CRISPRi screening and sgRNA-level data analysis
- Genome-scale metabolic modeling and strain engineering
- Multi-source biological data integration
- Reproducible bioinformatics pipelines
- Interactive visualization for biological networks

---

## Featured Projects

<table>
<tr>
<td width="50%">

### [Cgl Regulation Explorer](https://github.com/gaodandan-ai/cgl_regulation)

An interactive regulatory-metabolic analysis platform for *Corynebacterium glutamicum*.

It integrates transcription factor and sRNA regulatory evidence with genome-scale metabolic models, enzyme constraints, pathway-level analysis, topology annotation, and AI-assisted literature summaries.

**Live demo:**  
https://cgl-regulation.vercel.app/

**Methods:** regulatory networks, metabolic modeling, RF scoring, FBA/ecFBA, Cytoscape.js, RAG

</td>
<td width="50%">

### [Whole-Genome Resequencing Pipeline](https://github.com/gaodandan-ai/cg_sequencing)

A reproducible pipeline for *Corynebacterium glutamicum* whole-genome resequencing analysis.

The workflow covers FASTQ quality control, trimming, BWA alignment, variant calling, allele-frequency filtering, snpEff annotation, and structured report generation.

**Methods:** WGS, BWA, samtools, bcftools, snpEff, FastQC, MultiQC

</td>
</tr>

<tr>
<td width="50%">

### [CRISPRi Thermal Screening Pipeline](https://github.com/gaodandan-ai/CRISPRi_thermal)

An automated analysis pipeline for CRISPR interference screening data under thermal stress.

It supports both single-gene and dual-gene sgRNA library workflows, from spacer extraction to alignment and count matrix generation.

**Methods:** CRISPRi, sgRNA screening, bowtie2, count matrix analysis, thermal stress

</td>
<td width="50%">

### [GP960 Growth Screen Pipeline](https://github.com/gaodandan-ai/GP960-growth-screen-pipeline-Red)

A Python-based analysis pipeline for high-throughput microbial growth curve screening data.

It converts GP960 raw Excel files into standardized OD tables, cleans abnormal curves, calculates fitness metrics, and generates visual summaries.

**Methods:** growth curves, high-throughput screening, stress tolerance, Python, data analysis

</td>
</tr>
</table>

---

## Methods & Tools

<table>
<tr>
<td><b>Programming</b></td>
<td>Python · JavaScript · Bash</td>
</tr>
<tr>
<td><b>Bioinformatics</b></td>
<td>BWA · samtools · bcftools · snpEff · FastQC · MultiQC · bowtie2</td>
</tr>
<tr>
<td><b>Data Analysis</b></td>
<td>pandas · NumPy · openpyxl · statistical reporting · Excel automation</td>
</tr>
<tr>
<td><b>Visualization</b></td>
<td>Cytoscape.js · Chart.js · network visualization · interactive dashboards</td>
</tr>
<tr>
<td><b>Research Engineering</b></td>
<td>reproducible pipelines · documentation · Docker · web deployment</td>
</tr>
</table>

---

## Research Workflow

```text
Biological question
        ↓
Data preprocessing and quality control
        ↓
Computational modeling and statistical analysis
        ↓
Network-level or pathway-level interpretation
        ↓
Reproducible pipeline / interactive research tool
