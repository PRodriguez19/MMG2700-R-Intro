## Week 3

### Introduction 

**How can we use RNA-sequencing to investigate what happens to cells and tissues during disease?**

This week, we will begin exploring RNA-sequencing (RNA-seq) data using a subset of the data published by Blackmore et al. (2017), Influenza infection triggers disease in a genetic model of experimental autoimmune encephalomyelitis.

The goal of the study was to investigate how an upper-respiratory influenza infection affects gene expression in the central nervous system (CNS). Gender-matched eight-week-old C57BL/6 mice were inoculated intranasally with either saline or Influenza A virus. RNA was then collected from the cerebellum and spinal cord at 0, 4, and 8 days post-infection, and RNA-seq was used to characterize changes in the transcriptome.

In this course, we will use a subset of these data to begin learning how to work with biological datasets in R. Our goal is not yet to perform a complete RNA-seq analysis. Instead, we will first learn how to explore, organize, and visualize RNA-seq data in R. Later in the course, we will return to RNA-seq and learn how to perform statistical analyses such as differential gene expression.

### The dataset

The dataset is provided as a comma-separated values (CSV) file. Each row represents a gene expression measurement for one gene in one sample.

The first eleven columns contain information about the gene, sample, and experimental conditions:

| Column | Description |
| ------ | ----------- |
| gene | The name of the gene that was measured |
| sample | The name of the sample the gene expression was measured in |
| expression | The value of the gene expression |
| organism | The organism/species - here all data stem from mice |
| age | The age of the mouse (all mice were 8 weeks here) |
| sex | The sex of the mouse |
| infection | The infection state of the mouse, i.e. infected with Influenza A or not infected. |
| strain | The Influenza A strain. |
| time | The duration of the infection (in days). |
| tissue | The tissue that was used for the gene expression experiment, i.e. cerebellum or spinal cord. |
| mouse | The mouse unique identifier. |

### What should you be able to do by the end of this week?

By the end of this week, you should be able to:

* Describe the biological question addressed by the Blackmore et al. study.
* Describe what a data.frame is.
* Load external data from a .csv file into a data frame.
* Summarize the contents of a data frame.
* Describe what a factor is.
* Convert between strings and factors.
* Reorder and rename factors.
* Export and save data.
