---
title: ENA Raw Read Submission
layout: default
---

# ENA Metadata collection

## Mandatory metadata for samples checklist: 


1. Taxonomy ID of the organism as in the  NCBI Taxonomy database. For example 9606 for Homo sapiens and 10090 for Mus musculus.

2. Scientific name

3. Sample alias, title and description. Alias is a unique ID, will be generated if not available.

4. Collection date - could range from missing to restricted access to 2008-01-23 or 2008. Exact info is not needed.

5. Geographic location - for example, Germany, if the experiment was performed at Charité.


Other info like sex, tissue type, isolate, cell line, strain etc. are optional.

---


## Mandatory metadata for reads checklist:


Read file formats supported: CRAM, BAM, Single-end FASTQ, Paired-end FASTQ, HDF5 and FAST5


1. Sample: **Sample accessions** provided by ENA when samples checklist was uploaded (Samples Report)

2. Study: Study accession (Study Report)

[Sample and Study accessions are available only after starting the submission process]

3. Instrument_model: There are options to pick from. For example, Illumina Novaseq 6000

4. Library_name: could be similar to sample alias, etc

5. Library_source: choose from options available while downloading checklist from portal, e.g., TRANSCRIPTOMIC

6. Library_selection: choose from options, e.g., PCR, cDNA

7. Library_layout: Options: single or paired reads

8. Forward_file_name and forward_file_md5; Reverse_file_name and reverse_file_md5

---
