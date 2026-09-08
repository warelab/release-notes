### Baseline Gene Expression (Atlas)

**All studies**

Currently, SorghumBase has total 16 bulk expression studies, consisting of 11 studies with baseline expression and 5 with differential expression gene expression data for the S. bicolor BTx623 (NCBIv3) genome reference. Each dataset is manually curated, validated, and configured by the SorghumBase team in collaboration with the EMBL-EBI Expression Atlas [EMBL-EBI Expression Atlas](https://www.ebi.ac.uk/gxa/). Expression Atlas reanalyzes high-quality datasets using a standardized pipeline, providing consistent and comparable results across studies. All datasets previously mapped to the sorghum version 3 genome are being remapped to version 5. The Expression tab presents gene expression as an interactive heatmap. Use the heatmap to examine expression across tissues, developmental stages, treatments, and environmental conditions.
SorghumBase supports both baseline and differential expression, making it possible to explore normal expression patterns as well as responses to stress or experimental treatments. Here is an example of the expression profile of msd2 gene (SORBI_3006G095600) that encodes lipoxygenase gene under All Studies tab. 
**All Studies**

Click on All Studies Tab compares the baseline expression of the msd2 gene across the available Expression Atlas studies on SorghumBase site.
This view helps identify the tissues and developmental stages in which the gene is most highly expressed and reveals whether its expression pattern is consistent across experiments. The above view depicts baseline gene expression data for a whole plant (top anatogram on the left of the results box). Experiments are organized by study on the left side, and by tissue or developmental stage on the top of the graph. Unique data points are colored in blue, with intensity increasing in proportion to the level of expression (i.e., higher expression data points are shown in darker blue). When you hover the cursor over a data point, the data point is highlighted in yellow, a more detailed summary pops up, and the corresponding tissue is colored in pink in the anatograms. If instead, you hover over a tissue on the anatogram on the left, the name of the tissue will pop up, and the points corresponding to expression data from this tissue will light up. This feature is the product of the collaboration with the EBI-Atlas. 

<img width="1443" height="659" alt="Exp_AllStudies" src="https://github.com/user-attachments/assets/2c7cc595-cf4c-4033-b6b6-9c68a9cacc7a" />

**Paralogs**
Click on Paralogs tab displays the expression profiles of the queried gene and its paralogs within the reference study. Comparing paralogs can reveal shared expression patterns, tissue-specific specialization, or possible functional divergence within the gene family. 
<img width="1457" height="712" alt="Exp_Baseline" src="https://github.com/user-attachments/assets/323f0443-f4fe-4d2e-afe5-6921e93c7f10" />



**eFP Browser**

The Sorghum eFP Browser includes data from ten studies covering seedlings, roots, stems, leaves, panicles, seeds, and other tissues. It also includes developmental stages and responses to several abiotic stresses.The browser was developed by the Bio-Analytic Resource for Plant Biology at the University of Toronto [eFP browser](https://bar.utoronto.ca/) in collaboration with SorghumBase. 

<img width="864" height="667" alt="Exp_eFPBrowser" src="https://github.com/user-attachments/assets/41c4d9cc-9770-4495-a12a-0c2935bd6e29" />

The above example depicts the  pictographic expression profiles for 10 sorghum studies on development and stress; the  bundle-sheath/mesophyll cell views is shown above. Expression is displayed on a color scale from zero (yellow) to the gene's maximum expression (red). Note that the scale is relative to each gene displayed.In an eFP image, each plant tissue or organ is colored according to the expression level of the selected gene. Lighter yellow and orange shades indicate lower expression, while darker orange and red shades indicate higher expression. The color scale ranges from zero to the maximum expression value within the selected study and is based on the gene’s TPM values. Always check the scale displayed with each image, because the maximum value may differ among studies.





