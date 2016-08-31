# Lecture 01 - 9/31/2016
Given by Max

## Genetics
__Biological question__

"What is inherited, and how?"
+ dominant and recessive traits
+ linkage between traits
+ how variations arise and spread
+ how genetic variants predict traits (disease) genotype-phenotype

__Tool__

"Use to study molecular mechanism in living, intact organisms"
+ what factors control a biological process
+ how do they interact (up/downstream)
+ when and where do they act
+ what is the role of molecular feature (ex/ phospho site) in vivo

__Model organism__

+ fast and cheap
+ some simplicity (e.g. small genome)
+ grow in large numbers
Goal: identify mechanism in one model and generalize to other organisms

| Your Model    |            | Other organisms  |
| ------------- |:-------------:| -----:|
| Biological process      |  | Biol. process |
| genetic screen \/      |       |   /\ do they affect |
| discover genes |  --->     |    disrupt orthologous genes |
| "Forward" |              | "Reverse"      |
|screens,selections,mapping | | knockouts,CRISPER,RNA |

__Methods__

1. Clasical and modern methods coexist
  * screens, crosses, mapping --- CRISPR/Cas9, whole-genome seq.
2. Concepts and methods **translate across models**
  * ex: dom and rec from peas ---> all organisms
  *     CRISPR from bacteria ---> all organisms

## Mendel and peas
+ identify _binary_ traits and consider each _separately_

   Ex. pea shape - round/wrinkled | no intermediates
       pea color - yellow/green   | or blending
+ count *large numbers* - reduce *chance fluctuations*
+ constructed *pure-breading* stocks with defined traits

__Experiment 1__

|Generation     |     Phenotype   |
|---------------|-----------------|
| P0            | round x wrinkled|
| F1  (hybrid)  | all round       |
| F2            | 5474 (round) : 1850 (wrinkled) **3:1**|

__Experiment 2__

| Generation | Phenotype |
|---|---|
| F2 | Start with 565 round F2 peas |
|F3| **"pure" F2** | **"hybrid" F2** |
| | all-round -- round;wrinkled |
| | 193 pure -- 372 hybrid |
| | AA -- Aa |
| | 1:2 |

__Key Terms__

+ AA or aa - "pure" breads true Homozygote
+ Aa, heterozygote - "hybrid" does not bread true
+ alleles - alternative forms of a gene
+ genotype - which alleles an individual carries
+ phenotype - which traits are expressed

Ex. Mouse Knockout

KO/+ (male) x KO/+ (female)
  |
 \/
 want KO/KO
 expect 25%
 what if 4 or 25?
 
Q: When is a ratio 3:1?

  Total: 5474:1850 3.0:1
  plant #4 19:10 1.9:1
  pland #7 88:24 3.7:1
  
"How likely is it that these deviations arose by chance due to sample size?"
+ [chi-square test](https://youtu.be/lSmDoKHfym4)

__Experiment 3__ examine two traits

+ Shape - A,round a,wrinkled
+ Color - B,yellow b,green

|Generation|phenotype|genotype|
|---|---|---|
|P0|round;yellow x wrinkled;green|AABBxaabb|
|F1|all round;yellow|AaBb "dihybrid"|
|F2|round;yellow(315) wrinkled;yellow(101) round;green(108) wrinkled;green(32)|all combos|
||**9:3:3:1**|

__Interpretation__

+ Round(315+108=423):Wrinkled(101+32=133) => 3:1
+ Yellow(315+101=416):Green(108+32=140) => 3:1

Punnet Square of AaBb x AaBb (F1 self-cross)

||AB|Ab|aB|ab|
|---|---|---|---|---|
|AB|AABB|AABb|AaBB|AaBb|
|Ab|AABb|AAbb|AaBb|Aabb|
|aB|AaBB|AaBb|aaBB|aaBb|
|ab|AaBb|Aabb|aaBb|aabb|


|Phenotypes|genotypes|counts|
|---|---|---|
|round;yellow|A-B-|9|
|winkled;yellow|aaB-|3|
|round;green|A-bb|3|
|wrinkled;green|aabb|1|

__Mendel's laws__

1. For a single trait - sperm and egg carry 1 allele at random and combine at random
2. For multiple traits - sperm and egg carry 1 allele of each trait at random and combine at random

_Exceptions_

how are traits expressed
+ multiple genes
+ partial dominance
+ epistasis

which alleles are inherited
+ linkage

__Epistasis__

ex: Labrador retrievers

| Generation | Phenotype (count) | Genotype |
|---|---|---|
|P0|brown x yellow|aaBB x AAbb|
|F1|black|AaBb|
|F2|black (9)|A-B-|
||brown (3)|aaB-|
||yellow (3)|A-bb|
||yellow (1)|aabb|

+ Yellow is epistatic to brown
+ bb is epistatic to aa
+ B gene is epistatic to A gene

+ dominance - alleles of same gene
+ epistasis - alleles of different gene

When two different phenotypes are confered by different genes (A and B), if the expressed phenotype is confered by B, B is epistatic to A.
