## Week 7

# Visualizing Differential Gene Expression Data

**Weekly overview:** Students will use differential expression results generated with edgeR to recreate the bar plot and volcano plot from Figure 1 of Himes et al. (2014). Through guided analysis in R, students will learn how to interpret fold changes, identify differentially expressed genes, and communicate results using publication-ready visualizations in `ggplot2` and `EnhancedVolcano`.

The week emphasizes connecting biological interpretation, statistical significance, and data visualization to understand how gene expression differs between experimental conditions.

## Weekly learning progression

- Part 1: Building and interpreting volcano plots. Students will construct a volcano plot layer-by-layer in `ggplot2`, classify genes as up-regulated, down-regulated, or unchanged using fold-change and significance thresholds, and explain why false discovery rate (FDR) adjustment is important when testing thousands of genes simultaneously.

- Part 2: Bar plots of fold change. Students will identify relevant columns in differential expression results and normalized counts tables, calculate fold changes, select genes of interest with `dplyr::filter()`, and build bar plots with `ggplot2`. They will summarize donor-level fold changes using means and error bars, then refine their plots to match the published figure.

- Part 3: Understanding differential expression. Students will revisit the Himes et al. (2014) airway smooth muscle dataset and interpret the experimental design and columns in an edgeR results table. They will explore how log2 fold change and adjusted p-values describe the magnitude and statistical significance of gene expression differences.

- Part 4: Publication-ready visualization. Students will use EnhancedVolcano to generate a polished volcano plot, label genes of interest, and compare their visualizations with Figure 1 of Himes et al. (2014).

## End-of-week goal

By the end of the week, students will be able to recreate and interpret the bar plot and volcano plot from Himes et al. (2014) using their own edgeR results, explaining how the visualizations communicate both the magnitude and statistical significance of differential gene expression.
