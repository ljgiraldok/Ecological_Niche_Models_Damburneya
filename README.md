# Ecological_Niche_Models_Damburneya
This repository contains the R scripts employed to perform the ecological niche models, and the niche overlap analyses contained in the article **"Ecological niche comparison among closely related tree species of Lauraceae using climatic and edaphic data"** by **L. Giraldo-Kalil et al.** (2023) publisehd in the journal ***Frontiers of Biogeography***

Climatic data were obtained from WorldClim (19 bioclimatic variables), and edaphic data were obtained from SoilGrids. Please see detailed information and methods in the manuscripts.


The scripts are named according to the data set employed for niche models as follows

**Combined climatic and edaphic data:**   "Model_Damb_bioclimsoil_02mar23.Rmd"

**Climatic-only data:**                   "Model_Damb_bio_27feb23.Rmd"

**Edaphic-only data:**                    "Model_Damb_soils_01mar23.Rmd"




The main results of the manuscript were generated with these scripts. The environmental raster layers were processed with ArcMap, and the species occurrence data can be found in the Supplementary material, in the **Appendix S2**.

Here you can find also other three scripts created to create response curves of the top 5 models with the best evaluation metrics to assess model selection. The plots can be found in the manuscript supplementary material, in the **Appendix S3, Figures S1,S2 and S3.**

The scripts are named according to the data set employed as follows

**Combined climatic and edaphic data:**   "Resp_plots_summ_lambda_biosoils.Rmd"

**Climatic-only data:**                   "Resp_plots_summ_lambda_bio.Rmd"

**Edaphic-only data:**                    "Resp_plots_summ_lambda_soils.Rmd"
