# Analysis of *Annelida* Coverage and Interactions on the Eastern Mediterranean Continental Shelf #


The following assignment focuses on analyzing data from a photo-survey of benthic biota across two transects of the Eastern Mediterranean continental shelf. The data, provided in "Photosurvey_processed_data.csv," includes percentage coverage values for various broad taxonomic groups, with each sample representing processed data from a transect. Four replicate transects were surveyed at each location, covering two sites, two seasons, and three seafloor depths per year. Metadata for each transect ID is detailed in "Photosurvey_metadata.csv." This analysis will concentrate on a specific taxonomic group, *Annelida*, examining its coverage in relation to site, season, and seafloor depth, and will explore its interactions with other taxonomic groups through graphic representations and statistical analysis. 

## 1) ANOVA Results for *Annelida* Coverage Analysis ##

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

## 2) Correlation Between *Annelida* and *Chordata* Coverage on the Eastern Mediterranean Continental Shelf

![Annelida and Chordata Correlation](https://github.com/HadarAharoni/HadarAharoni_Notebook/blob/main/images/Rplot03.png)

The correlation is  0.3187752, so there is no correlation between Annelida and Chordata Coverage on the Eastern Mediterranean Continental Shelf.