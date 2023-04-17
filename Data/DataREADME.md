# Title of dataset
Data from: Chilean bee diversity: Contrasting patterns of species and phylogenetic turnover along a large-scale ecological gradient 

# Authors of dataset
Leon Marshall<sup>1,2</sup>, John S. Ascher<sup>3</sup>, Cristian Villagra<sup>4</sup>, Amaury Beaugendre<sup>1</sup>, Valentina Herrera<sup>4</sup>, Patricia Henríquez-Piskulich<sup>4</sup>, Alejandro Vera<sup>5</sup>, Nicolas J. Vereecken<sup>1</sup>

1.  Agroecology Lab, Université libre de Bruxelles (ULB), Boulevard du Triomphe CP 264/2, B 1050 Brussels, Belgium 
2.	Naturalis Biodiversity Center, Darwinweg 2, 2333 CR Leiden, The Netherlands
3.  Department of Biological Sciences, National University of Singapore, 14 Science Drive 4, Singapore 117543, Singapore
4.	Instituto de Entomología, Universidad Metropolitana de Ciencias de la Educación, Santiago, Región Metropolitana, Chile
5.	Departamento de Biología, Universidad Metropolitana de Ciencias de la Educación, Santiago, Región Metropolitana, Chile

# Abstract
Chile’s isolation and varied climates have driven the evolution of a unique biodiversity with a high degree of endemism. As a result, Chile encompasses diverse environments, including the Mediterranean-type ecosystem, a global biodiversity hotspot. These environments are currently threatened by anthropogenic land use change impacting the integrity of local biomes and associated species. This area is the most intensively sampled of the country with high endemicity of native bee species. Characterising habitat requirements of bees is a pressing priority to safeguard these insects and the ecosystem services they provide. We investigated broad-scale patterns of bee (Hymenoptera: Apoidea: Anthophila) diversity using newly accessible expert-validated datasets comprising digitized specimen records from Chilean and US collections, and novel expert-validated type specimen data for the bees of Chile. We used a generalised dissimilarity modelling (GDM) approach to explore both compositional and phylogenetic β-diversity patterns across latitudinal, altitudinal, climate and habitat gradients in well-sampled bee assemblages in Central Chile. Using the GDM measures of increasing compositional and environmental dissimilarity we categorised and compared the most important drivers of these patterns and used them to classify ‘wild bee ecoregions’ (WBE) representing unique assemblages. Turnover of bee assemblages was explained primarily by latitudinal variation (proxy for climate) from south to north in Chile. However, temperature variations, precipitation and the presence of bare soil also significantly explained turnover in bee assemblages. In comparison, we observed less turnover in phylogenetic biodiversity corresponding to spatial gradients. We identified six de novo ecoregions (WBE), all with distinct taxa, endemic lineages, and representative species. The WBE represent distinct spatial classifications but have similarities to existing biogeographical classifications, ecosystems and bioclimatic zones. This approach establishes the baseline needed to prioritise bee species conservation efforts across this global biodiversity hotspot. We discuss the novelty of this classification considering previous biogeographical characterisations and their relevance in assessing conservation priorities for bee conservation. We argue that Chile’s WBE highlight areas in need of funding for bee species surveys and description, distribution mapping and strengthening of conservation policies.

# Usage notes
The dataset contains species occurrence data of chilean bees aggregated to a 5 x 5 km grid shapefile. The shapefile of the grid and the raster mask of the Central Chilean study area are also included. Finally, a database of type specimen data used to supplement the dataset is included here.  The code for the analysis can be found at: https://github.com/lmar116/ChileanBeeDiversity.

Shapefiles, rasters, CSV files and code were all loaded and analyzed using R statistics software. 

Four files are included:
1. Marshall-et-al-2023_Ecosphere_DataTable_bee_grid: contains all species occurrence data used in GDM analysis, Grid column refers to cl.5km.shp. 
2. cl.5km.shp (and associated files): 5 x 5 km grid shapefile of the Central Chilean study area
3. chile.mask.tif: raster outline of the Central Chilean study area
4. Marshall-et-al-2023_Ecosphere_CentralChileTypeSpecimens.xlsx: contains type specimen data used to supplement species occurrence dataset.
