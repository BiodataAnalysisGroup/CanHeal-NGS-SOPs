## Standards and quality metrics for NGS 

- **Sequencing Depth**: The average number of times a nucleotide is sequenced in a given region. Higher sequencing depth increases confidence in variant detection and reduces false positives.

- **Read Quality**: The accuracy of individual reads by assessing the base quality scores. 

- **Mapping Quality**: The reliability of read alignments to a reference genome. Higher mapping quality indicates more accurate alignment and reduces the chances of false positives or false negatives in downstream analyses.

- **Coverage Uniformity**: The evenness of sequencing coverage across the target regions.

- **Error Rates**: The rate of sequencing errors as well ass mutation rate errors including substitution, insertion, and deletion errors. 

- **Duplication Rates**: The extent of PCR or optical duplicates in the sequencing data.

- **GC Bias**: Bias in sequencing data associated with varying GC content. 

- **Strand Bias**: Bias in sequencing data associated with the strands of the reads. 

- **Contamination Levels**: The presence of cross-sample contamination or sample mislabeling.

- **Adapter Contamination**: The presence of adapter sequences that were not adequately removed during library preparation, which can interfere with downstream analyses and lead to false results.

- **Variant Calling Accuracy**: The accuracy of identifying genetic variants from sequencing data. Metrics such as sensitivity, specificity, and positive predictive value (PPV) assess the reliability of variant calls.

- **On-Target Rate**: The percentage of reads that map to the intended target regions, which is critical in targeted sequencing approaches like exome sequencing.

- **Insertions/Deletions (Indel) Detection Sensitivity**: Assess the sensitivity of detecting insertions and deletions, which can often be more challenging than single nucleotide variants (SNVs) in sequencing data.
  
- **Bioinformatics Pipeline Validation**: Ensure the accuracy of the bioinformatics pipeline used for processing NGS data by regularly validating performance against known reference datasets.

