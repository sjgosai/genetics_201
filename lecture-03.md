# Lecture 03 - 9/7/2016
Given by Fred

### Dom/rec tests

|diploid genotype|phenotype|
|---|---|
|wt|CisS|
|cis1|CisR|
|cis2|CisR|


|cross|diploid|phenotype|conclusion|
|---|---|---|---|
cis1 x wt|+/cis1|CisS|rec|
cis2 x wt|+/cis2|CisR|dom|

Easily done for 100's of mutants

## Complementation tests
+ Done on recessive mutations
+ a test of function
+ (erased)
+ (erased)

cis1, cis3, cis4, - all recessive

1. cross mutants by each other
2. test the phenotype of the diploid

|cross|diploid phenotype|conclusion|# genes|
|---|---|---|---|
|cis1 x cis3|CisS|complement|2|
|cis1 x cis4|CisR|don't complement|1|

Can be done on a large scale

_Issues with complementation_

1. Intragenic complementation
  + 2 mutations in the same gene complement
  + Usually in cases where the protein has multiple domains
  
_yeast HIS4 gene_

|comp group|step in histidine biosynthesis|
|---|---|
|his4A|3rd|
|his4B|2nd|
|hist4C|10th|

3 genes close together or 1 gene w/ 3 functions?

2. Unlinked noncomplementation
  + 2 recessive mutations in different genes that fail to complement
  + Can be members of a multigene complex
  
geno/phenotype = g/ptype

|diploid gtype|ptype|level of complex|
|---|---|---|
|+/+|wt|100%|
|+/cis1|wt|50%|
|+/cis5|wt|50%|
|+/cis1,+/cis5|CisR|<<50%|

Wildtype phenotype above some threshold of active complex

## Linkage
_Linkage is a test of position_

first reported - Bateson and Punnet in the early 1900s

1911 - T.H. Morgan - linkage in Dros.

Morgan's hypothesis - genes can be on the same chromosome and the degree of linkage is proportional to their physical distance

_Tetrad analysis_ - essential for many things
1. mutant analysis
2. location of 2 mutations w.r.t. each other
3. cloneing a gene
4. strain construction
5. whole genome sequencing

|generation|genotypes|
|---|---|
|haploid parents|a;CIS1+ x alpha;cis1|
|diploid|CIS1+/cis1|
|sporulation (miosis)  <br> replication (premiotic S phase)||
|4-strand (4-chromatids) stage|CIS1/CIS1 cis1/cis1|
|meiosis I||
|sisters segregate together||
|miosis II||
|sisters segreagate apart||

4 haploid products <br> 2:2 segregation if trait is monogenic

Question: Does a mutation segregate in a Mendelian fashion? <br> 2:2 ? <br> yes - probably due to a single mutation <br> no - not Mendelian

__Insert Sporulation figures (w/ and w/o likage and crossovers)__

When 2 markers are linked, a TT tetrad arises by a single crossover

AB x ab -> 90 PD, 10 TT, 0 NPD

(# of recombinants / total progeny) x 100 = linkage

100 tetrads = 400 spores = total progeny

10 tetratypes -> 20 recombinants

(20 recombinants / 400 total progeny) x 100 = 5% linkage = 5 map units = 5 cM <br> (0.5TT/total tetrads) x 100 = cM

__Insert figure regarding double crossing over__

frequency of double crossover results are P:N:T at ratio of 1:1:2
