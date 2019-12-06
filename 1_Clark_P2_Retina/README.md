# Single cell analysis of P2 mouse retinal cells using Seurat
Single cell analysis of P2 mouse retinal cells using Seurat
Here, I show the basic pipleline to analyse single cell data.

This analysis contains downsampling, standard preprocessing, dimensional reduction, clustering, and identification of cell types.

To see more detail in data source, please refer to the reference below.   
Clark BS. Neuron. 2019 Jun 19;102(6):1111-1126.e5.   

This is the R script   
[Clark_P2_Retina.ipynb](./Clark_P2_Retina.ipynb)   

This is the thre dimesntional UMAP. Please download this file and save locally and open it.   
This file enables interactive view of 3d UMAP.   
[plot_cell_types.html](./plot_cell_types.html)    

This is a gif image of 3d UMAP    
<img src="./plot_cell_types.gif" width="600">

For easy UMAP visualization, I extract subset of information using the script below   
[Extract_information_for_UMAP_visualization.ipynb](./Extract_information_for_UMAP_visualization.ipynb)   
