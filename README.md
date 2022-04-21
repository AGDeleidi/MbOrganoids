# MbOrganoids
This repository helps to process single cell data from midbrain organoids
Scripts/Code available

# R SessionInfo
R version 4.1.0 (2021-05-18)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 19044)

Matrix products: default

locale:
[1] LC_COLLATE=English_Germany.1252  LC_CTYPE=English_Germany.1252   
[3] LC_MONETARY=English_Germany.1252 LC_NUMERIC=C                    
[5] LC_TIME=English_Germany.1252    

attached base packages:
[1] splines   stats4    stats     graphics  grDevices utils     datasets 
[8] methods   base     

other attached packages:
 [1] monocle_2.22.0              DDRTree_0.1.5              
 [3] irlba_2.3.3                 VGAM_1.1-6                 
 [5] BiocManager_1.30.16         dplyr_1.0.7                
 [7] Matrix_1.4-0                monocle3_1.0.0             
 [9] SingleCellExperiment_1.16.0 SummarizedExperiment_1.24.0
[11] GenomicRanges_1.46.1        GenomeInfoDb_1.30.1        
[13] IRanges_2.28.0              S4Vectors_0.32.3           
[15] MatrixGenerics_1.6.0        matrixStats_0.61.0         
[17] Biobase_2.54.0              BiocGenerics_0.40.0        
[19] SeuratWrappers_0.3.0        Signac_1.6.0               
[21] magrittr_2.0.1              cowplot_1.1.1              
[23] ggplot2_3.3.5               patchwork_1.1.1            
[25] SeuratObject_4.0.4          Seurat_4.1.0               

loaded via a namespace (and not attached):
  [1] utf8_1.2.2                reticulate_1.24          
  [3] R.utils_2.11.0            tidyselect_1.1.2         
  [5] htmlwidgets_1.5.4         combinat_0.0-8           
  [7] grid_4.1.0                docopt_0.7.1             
  [9] BiocParallel_1.28.3       Rtsne_0.15               
 [11] munsell_0.5.0             ScaledMatrix_1.2.0       
 [13] codetools_0.2-18          ica_1.0-2                
 [15] future_1.24.0             miniUI_0.1.1.1           
 [17] withr_2.5.0               batchelor_1.10.0         
 [19] fastICA_1.2-3             colorspace_2.0-2         
 [21] knitr_1.38                rstudioapi_0.13          
 [23] ROCR_1.0-11               tensor_1.5               
 [25] pbmcapply_1.5.0           listenv_0.8.0            
 [27] labeling_0.4.2            slam_0.1-50              
 [29] GenomeInfoDbData_1.2.7    polyclip_1.10-0          
 [31] pheatmap_1.0.12           bit64_4.0.5              
 [33] farver_2.1.0              parallelly_1.31.0        
 [35] Matrix.utils_0.9.8        vctrs_0.3.8              
 [37] generics_0.1.2            xfun_0.30                
 [39] lsa_0.73.2                ggseqlogo_0.1            
 [41] R6_2.5.1                  rsvd_1.0.5               
 [43] hdf5r_1.3.5               bitops_1.0-7             
 [45] spatstat.utils_2.2-0      DelayedArray_0.20.0      
 [47] assertthat_0.2.1          promises_1.2.0.1         
 [49] scales_1.2.0              gtable_0.3.0             
 [51] beachmat_2.10.0           globals_0.14.0           
 [53] goftest_1.2-3             rlang_1.0.1              
 [55] RcppRoll_0.3.0            lazyeval_0.2.2           
 [57] spatstat.geom_2.3-0       yaml_2.3.5               
 [59] reshape2_1.4.4            abind_1.4-5              
 [61] httpuv_1.6.3              tools_4.1.0              
 [63] ellipsis_0.3.2            spatstat.core_2.3-2      
 [65] RColorBrewer_1.1-3        proxy_0.4-26             
 [67] ggridges_0.5.3            Rcpp_1.0.7               
 [69] plyr_1.8.6                sparseMatrixStats_1.6.0  
 [71] zlibbioc_1.40.0           densityClust_0.3.2       
 [73] purrr_0.3.4               RCurl_1.98-1.6           
 [75] rpart_4.1.16              deldir_1.0-6             
 [77] pbapply_1.5-0             viridis_0.6.2            
 [79] zoo_1.8-9                 grr_0.9.5                
 [81] ggrepel_0.9.1             cluster_2.1.2            
 [83] data.table_1.14.2         RSpectra_0.16-0          
 [85] scattermore_0.7           ResidualMatrix_1.4.0     
 [87] lmtest_0.9-39             RANN_2.6.1               
 [89] SnowballC_0.7.0           fitdistrplus_1.1-8       
 [91] mime_0.12                 evaluate_0.15            
 [93] xtable_1.8-4              RhpcBLASctl_0.21-247.1   
 [95] sparsesvd_0.2             gridExtra_2.3            
 [97] HSMMSingleCell_1.14.0     compiler_4.1.0           
 [99] tibble_3.1.6              KernSmooth_2.23-20       
[101] crayon_1.5.1              R.oo_1.24.0              
[103] htmltools_0.5.2           mgcv_1.8-38              
[105] later_1.3.0               tidyr_1.1.4              
[107] speedglm_0.3-4            DBI_1.1.2                
[109] tweenr_1.0.2              MASS_7.3-55              
[111] leidenbase_0.1.11         cli_3.1.1                
[113] R.methodsS3_1.8.1         parallel_4.1.0           
[115] igraph_1.2.9              pkgconfig_2.0.3          
[117] plotly_4.10.0             scuttle_1.4.0            
[119] spatstat.sparse_2.0-0     XVector_0.34.0           
[121] stringr_1.4.0             digest_0.6.27            
[123] sctransform_0.3.3         RcppAnnoy_0.0.19         
[125] spatstat.data_2.2-0       Biostrings_2.62.0        
[127] rmarkdown_2.13            leiden_0.3.9             
[129] fastmatch_1.1-3           uwot_0.1.10              
[131] DelayedMatrixStats_1.16.0 shiny_1.7.1              
[133] Rsamtools_2.10.0          lifecycle_1.0.1          
[135] nlme_3.1-155              jsonlite_1.7.2           
[137] BiocNeighbors_1.12.0      limma_3.50.3             
[139] viridisLite_0.4.0         fansi_0.5.0              
[141] pillar_1.7.0              lattice_0.20-45          
[143] fastmap_1.1.0             httr_1.4.2               
[145] survival_3.2-13           glue_1.5.0               
[147] remotes_2.4.2             FNN_1.1.3                
[149] qlcMatrix_0.9.7           png_0.1-7                
[151] bit_4.0.4                 ggforce_0.3.3            
[153] stringi_1.7.5             BiocSingular_1.10.0      
[155] future.apply_1.8.1       
