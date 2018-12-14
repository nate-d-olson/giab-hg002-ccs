# Small Variant Benchmarking Results
Analysis of small variant benchmarkign results for the HG002 PacBio CCS 15Kb library.
Variant calling was performed using GATK and DeepVariant.
Callsets were benchmarked against the GIAB HG002 V3.3.2 benchmark set using the vcfeval-happy pipeline though the precisionFDA app. 


# TODO

For CCS Paper
============================================
* Read edit draft
* SECTION: Small variant detection
    * Run happy on new callsets - waiting on callsets
        * Update benchmarking numbers in table 1 and text 
    * Stratification indel numbers for homopolymers > 2bp - JZ will provide code and input files for analysis
    * Add text with benchmark stratification results
    * Supplemental Figure R4-1: Key stratification results including overview and homopolymers
* SECTION: Revising and expanding GIAB
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