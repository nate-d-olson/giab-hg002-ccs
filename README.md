# Small Variant Benchmarking Results
Analysis of small variant benchmarkign results for the HG002 PacBio CCS 15Kb library.
Variant calling was performed using GATK and DeepVariant.
Callsets were benchmarked against the GIAB HG002 V3.3.2 benchmark set using the vcfeval-happy pipeline though the precisionFDA app. 


# TODO

For CCS Paper
============================================
* Read edit draft
* SECTION: Small variant detection
    * Total number of variants called for each callset - JZ
    * Run happy on new callsets - waiting on callsets - NDO
        * Update benchmarking numbers in table 1 and text - NDO
    * Stratification indel numbers for homopolymers > 2bp - JZ will provide code and input files for analysis
        - for use in estimating the percentage of discordant indels in homopolymer runs 
* SECTION: Revising and expanding GIAB
    * Table of manually curated variants - NDO
        * Table legend
        * Clean-up googlesheet table for manuscript
    * IGV screenshot for supplemental - representative variant from manual curation - NDO/JZ
* SECTION: Online Methods
    * Benchmarking and strafication methods - NDO
    * expansion estimates - NDO

Low priority
============================================
* Move code in slow chunks to drake workflow