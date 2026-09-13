# HBB-Genomic-Mutation-Profiler
An automated pipeline built with Python and BioPython to identify and translate disease-defining point mutations in human genetic variants.
# Genomic Mutation Profiler: Molecular Analysis of Sickle Cell Anemia

## Project Overview
This dry-lab bioinformatics script automates the detection of point mutations within human genomic data. Using Python and the Biopython framework, the pipeline conducts a sequence-level comparison of the human Hemoglobin Beta (HBB) gene to flag single nucleotide polymorphisms (SNPs) and track downstream translational consequences.

## Software Frameworks & Skills Demonstrated
* **Programming Language:** Python 3
* **Libraries Utilized:** BioPython (`Bio.Seq`)
* **Concepts:** Computational Genomics, Translation Simulation, Sequence Alignment Alignment, Mutation Tracking.

## Pipeline Architecture
1. **Sequence Object Ingestion:** Standardizes string formats into biological sequence objects.
2. **Automated Mutation Alignment:** Evaluates comparative nucleotide alignments to isolate positional coordinates of variations.
3. **Translational Analysis:** Simulates ribosomal translation to map the physiological structural shifts in resulting polypeptide chains.

## Execution Results & Findings
* **Genomic Mutation Location:** Position 20, A ➔ T Transversion.
* **Downstream Translational Change:** Position 7, Glutamic Acid (E) ➔ Valine (V).
* **Molecular Significance:** Successfully modeled the critical missense mutation where a highly hydrophilic, charged residue is substituted by a rigid, hydrophobic residue. This shifts the protein's physical behavior, giving rise to abnormal hemoglobin polymerization tendencies under cellular stress conditions.
