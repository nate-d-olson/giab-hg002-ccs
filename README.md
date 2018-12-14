# Small Variant Benchmarking Results
Analysis of small variant benchmarkign results for the HG002 PacBio CCS 15Kb library.
Variant calling was performed using GATK and DeepVariant.
Callsets were benchmarked against the GIAB HG002 V3.3.2 benchmark set using the vcfeval-happy pipeline though the precisionFDA app. 


# TODO

For CCS Paper
============================================
* Read edit draft
* SECTION: Small variant detection
    * Total number of variants called for each callset
    * Run happy on new callsets - waiting on callsets
        * Update benchmarking numbers in table 1 and text 
    * Figure 3A benchmark metrics
    * Stratification indel numbers for homopolymers > 2bp - JZ will provide code and input files for analysis
        - for use in estimating the percentage of discordant indels in homopolymer runs 
    * Add text with benchmark stratification results (1 - 2 sentences)
    * Supplemental Figure R4-1: Key stratification results including overview and homopolymers
* SECTION: Improving Small Variant Detection with Haplotype Phasing
    * Impact of re-genotyping on benchmarking results (Table 1, Supplemental Fig R6-1)
* SECTION: Revising and expanding GIAB
    * Total number of CCS hap.py variants the 60 were selected from
    * Table of manually curated variants
        * Table legend
        * Clean-up googlesheet table for manuscript
    * IGV screenshot for supplemental - representative variant from manual curation
    * Check numbers in text
    * Add expansion estimates
* SECTION: Online Methods
    * Benchmarking and strafication methods
    * expansion estimates

Low priority
============================================
* Move code in slow chunks to drake workflow