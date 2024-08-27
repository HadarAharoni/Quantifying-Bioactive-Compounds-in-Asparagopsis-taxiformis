# Quantifying Bioactive Compounds in *Asparagopsis taxiformis* and Their Impact on Marine Microbial Communities

## Abstract:

Given the urgent need to reduce methane emissions, *Asparagopsis taxiformis*, a red marine macroalgae, has shown great potential in inhibiting methanogenesis in ruminant livestock. However, the broader ecological impacts of cultivating this seaweed, especially on marine microbial communities, remain unexplored. Therefore, this research aims to quantify the bioactive compounds in *Asparagopsis taxiformis* using High-Performance Liquid Chromatography (HPLC) and evaluate their effects on marine microbial communities in controlled lab settings. By integrating metabolomics methods with marine biology, this study will provide an understanding of the ecological implications of cultivating *Asparagopsis taxiformis*. The findings will guide sustainable aquaculture techniques, ensuring that the benefits of methane reduction do not compromise marine biodiversity and ecosystem health.
_____


## Research Goals:

1. **Quantify Bioactive Compounds:** Use High-Performance Liquid Chromatography (HPLC) to measure the concentrations of critical bioactive compounds, including bromoform, in *Asparagopsis taxiformis*.


2.	**Assess Impact on Marine Microbes:** Examine how different concentrations of bioactive compounds from *Asparagopsis taxiformis* affect marine microbial communities in controlled lab experiments, focusing on changes in diversity, abundance, and function.


3.	**Evaluate Environmental Implications:** Analyze the ecological impact of bioactive compounds from *Asparagopsis taxiformis* on marine ecosystems, balancing methane reduction benefits with potential risks to marine biodiversity.
_______


## Methods: 

Below is a summary of the methods I used in order to promote the research idea within the research methods course: 
_____________
## Primer design: 

### Protocol for Designing Primers for Species Identification

#### 1. Gather Sequence Data
- Obtain the target sequence for *Asparagopsis taxiformis* from a reliable database like NCBI GenBank.

![step](https://github.com/HadarAharoni/Quantifying-Bioactive-Compounds-in-Asparagopsis-taxiformis/blob/main/photos/step1.jpeg)

#### 2. ClustalW
![step](https://github.com/HadarAharoni/Quantifying-Bioactive-Compounds-in-Asparagopsis-taxiformis/blob/main/photos/step2.png)


#### 3. Choose Primer Design Tool
- Use Primer3 or NCBI Primer-BLAST for designing primers.
- [Primer3 Input](http://primer3.ut.ee/)
- [NCBI Primer-BLAST](https://www.ncbi.nlm.nih.gov/tools/primer-blast/)


#### 4. Set Primer Parameters
- **Primer Length:** 18-24 nucleotides.
- **GC Content:** 40-60%.
- **Melting Temperature (Tm):** 50-60°C.
- **Product Size:** 100-1000 bp.

#### 5. Generate Primers
- Run the tool to generate primer pairs.
- Review for self-dimers, hairpins, and cross-dimers.
![step](https://github.com/HadarAharoni/Quantifying-Bioactive-Compounds-in-Asparagopsis-taxiformis/blob/main/photos/final.png)

### Short Protocol for Creating a Phylogenetic Tree in MEGA11

#### Step 1: Prepare Sequence Data
1. Collect your DNA or protein sequences in FASTA format.

#### Step 2: Import Data into MEGA11
1. Open MEGA11.
2. Go to `File` > `Open File/Session` and select your aligned sequence file.
3. Aligne the DNA using MEGA11 `Align` > `Edit\build alignment`.
4. save as fasta file.

#### Step 3: Build the Phylogenetic Tree
1. Click on `Phylogeny` > `Construct/Test Neighbor-Joining Tree`.
2. Choose the appropriate options for your analysis:
   - **Data Type:** DNA.
   - **Substitution Model:** normal
3. Click `OK`.

![step](https://github.com/HadarAharoni/Quantifying-Bioactive-Compounds-in-Asparagopsis-taxiformis/blob/main/photos/tree.jpeg)
__________


## qPCR - primer design: 

### Bromine compounds under stress 

The *algae Asparagopsis taxiformis* is known for its ability to produce bromine compounds. These bromine compounds are secondary natural substances, meaning they significantly affect the algae itself and related organisms but are not essential for the algae's survival. Therefore, **I hypothesize that under stress conditions such as extreme heat, high salinity, and high acidity, the production of bromine compounds will decrease as energy is diverted towards producing compounds necessary for survival.**

It is known that the enzyme linked to the production of bromine compounds is vanadium-dependent haloperoxidase (VHP), and the genes encoding it are located in the marine CHBr₃ biosynthesis (mbb) locus, including mbb1, mbb2, mbb3, and mbb4. To test this hypothesis, I will expose the algae to various stress conditions associated with global warming (extreme heat, high salinity, and high acidity) and use qPCR to measure changes in the expression of genes responsible for VHP production. **The hypothesis is that more extreme conditions will result in a lower expression of these genes, reflecting reduced production of the enzyme.**

As a reference gene, I will use the rbcL gene, which encodes the large subunit of RuBisCO. This is the most abundant protein in the cell, and its expression level is generally stable and not expected to change significantly under various stress conditions. Therefore, rbcL provides a reliable baseline for normalizing gene expression in qPCR experiments.

### mbb primers: 

LEFT PRIMER: TACCTGATCTCGACGTCACG (20 bp)
 
RIGHT PRIMER: CGTGCGCTCGTTCTGAATAA (20 bp)
 
PRODUCT SIZE: 152 bp
 
tm (both): 59.00 
 
### rbcL primers (referance gene): 

LEFT PRIMER: CAATTGCCGCTTCTGGTGAA (20 bp)
 
RIGHT PRIMER: TTTTACGTGCCCAGACTGC (19 bp)
 
PRODUCT SIZE: 174 bp
 
tm left: 59.40
 
tm right: 58.38

________

### ΔΔCt caculation:

- **Step 1:** Perform qPCR and collect Ct values for target and reference genes.
- **Step 2:** Calculate ΔCt for each sample (ΔCt = Ct(Target) - Ct(Reference)).
- **Step 3:** Calculate ΔΔCt (ΔΔCt = ΔCt(Experimental) - ΔCt(Control)).
- **Step 4:** Calculate relative gene expression using the formula 1.9^(-ΔΔCt).

![aa](https://github.com/HadarAharoni/HadarAharoni_Notebook/blob/main/_posts/images/aa.jpeg)

![bb](https://github.com/HadarAharoni/HadarAharoni_Notebook/blob/main/_posts/images/bb.jpeg) 

______

## Results: 

Below is a summary of the results I generated within the research methods course, they are both not related to this project but they include tools that can help to promote this projecrt idea: 

______


### Analysis of *Annelida* Coverage and Interactions on the Eastern Mediterranean Continental Shelf 


The following assignment focuses on analyzing data from a photo-survey of benthic biota across two transects of the Eastern Mediterranean continental shelf. The data, provided in "Photosurvey_processed_data.csv," includes percentage coverage values for various broad taxonomic groups, with each sample representing processed data from a transect. Four replicate transects were surveyed at each location, covering two sites, two seasons, and three seafloor depths per year. Metadata for each transect ID is detailed in "Photosurvey_metadata.csv." This analysis will concentrate on a specific taxonomic group, *Annelida*, examining its coverage in relation to site, season, and seafloor depth, and will explore its interactions with other taxonomic groups through graphic representations and statistical analysis. 

### 1) ANOVA Results for *Annelida* Coverage Analysis 

|                               | Df | Df.res | F value |     Pr(>F)    |
|-------------|----|--------|---------|---------------|
| site                          |  1 |    328 | 23.7248 | 1.7322e-06 *** |
| as.factor(depth)              |  2 |    328 | 17.6815 | 5.0985e-08 *** |
| season                        |  1 |    328 |  4.0616 |   0.044683 *   |
| site:as.factor(depth)         |  2 |    328 | 18.9300 | 1.6583e-08 *** |
| site:season                   |  1 |    328 |  3.9629 |   0.047344 *   |
| as.factor(depth):season       |  2 |    328 |  5.2343 |   0.005785 **  |
| site:as.factor(depth):season  |  2 |    328 | 10.9338 | 2.5298e-05 *** |


![Annelida Anova](https://github.com/HadarAharoni/HadarAharoni_Notebook/blob/main/images/ANOVA.png)

### 2) Correlation Between *Annelida* and *Chordata* Coverage on the Eastern Mediterranean Continental Shelf

![Annelida and Chordata Correlation](https://github.com/HadarAharoni/HadarAharoni_Notebook/blob/main/images/Rplot03.png)

The correlation is  0.3187752, so there is no correlation between Annelida and Chordata Coverage on the Eastern Mediterranean Continental Shelf.

______

### MS (GNPS): 

![GNPS](https://github.com/HadarAharoni/Quantifying-Bioactive-Compounds-in-Asparagopsis-taxiformis/blob/main/photos/F03671F6-C684-4C67-8295-0A1A1FE2F50F_1_105_c.jpeg)



