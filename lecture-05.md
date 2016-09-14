# Lecture 5 - 9/14/16
Given by Fred

_Last Class_
+ Finished Linkage
+ look at flow chart
+ ratios are key
+ identify mutant gene by cloning

_Today_
+ whole genome sequencing
+ gene replacement
+ genomics

## Whole genome sequencing
Isolated Cis<sup>R</sup> mutants -> mutagenesis<br>
cis1 mutation segregates 2:2 in a cross<br>
after mutagenesis ~100 mutations<br>
+ 1 mutation causes the phenotype
+ 99 mutations do not

Cross cis1 x wt

|mutant|x|wildtype|
|---|---|---|
|cis1,a,b,c,d,...<br>note:only cis1 is causal, lowercase letters indicate non-causal mutant allels elseware in genome||CIS1<sup>+</sup>,A,B,C,D,...|
||mate,sporulate,dissect tetrads<br>identify <Cis<sup>R</sup>, Cis<sup>S</sup> progeny||
|pool ~50 Cis<sup>R</sup> progeny||pool ~50 Cis<sup>S</sup> progeny|
|_allele_-_frequency_<br>cis1 - 100%<br>CIS1<sup>+</sup> - 0%<br>a - ~50%<br>A - ~50%||_allele_-_frequency_<br>cis1 - 0%<br>CIS1<sup>+</sup> - 100%<br>a - ~50%<br>A - ~50%|

All non-causal alleles present at ~50%

Look for the allele(s) that are inherited only in the mutant pool (see Birkeland et al. 2010)

5-fluoro-orotic acid 5FOA

|genotype|phenotype|
|---|---|
|URA3<sup>+</sup><br>ura3del|Ura<sup>+</sup>, 5FOA<sup>S</sup><br>Ura<sup>-</sup>, 5FOA<sup>R</sup>|

__Goal__ - Replace CIS1 with the mutant cis1 allele (single bp change)
+ Gene Replacement

__INSERT FIGURE HERE__

__Why do gene replacements__
+ Yeast Biology
+ outside yeast - human disease gene with a yeast orthologue
  + test disease alleles in yeast
  
Gene replacement - specific alleles

Genome-wide approaches
+ transcription √
+ translation
+ protein levels
+ protein modifications
+ protein-DNA interactions √
+ protein-RNA interactions

Does Cis1 regulate transcription?
Whole genome expression analysis - RNA-seq

__RNA-seq__ CIS1<sup>+</sup>,cis1

1. prepare polyA enriched RNA
2. fragment RNA
3. synthesize cDNA
4. DNA is PCR amplified
5. HT-sequenced

Determine the number of sequencing reads over the genome
+  the number of times a region is sequnced is proportional to the level of the RNA

__Computational approaches__
1. Do co-regulated genes share a regulatory sequence?
2. How do the changes in cis1 compare to other mutants?

Does Cis1 bind to DNA/chromatin?<br>
__ChIP-seq__

1. grow yeast cells (wt)
2. add formaldehyde (crosslinks)
3. isolate the crosslinked chromatin
4. fragment by sonication ~250bp
5. Immunoprecipitate Cis1 protein
6. Reverse the crosslinks (heating)
7. purify DNA
8. HT-sequence
