# DIGITAL RIVERSCAPES - A digital large-scale modelling platform of freshwater ecosystems 
#rivernetworks #virtualwatersheds #ecosystem indicators #random forest #extreme gradient boosting #deep-learning

## Context

Monitoring data from various ecosystem components—including abiotic factors, biodiversity, and ecosystem functioning—across vast territories requires substantial human and economic resources. As a result, researchers and managers of water resources and natural areas often have to rely on scattered information, with different types of data frequently lacking spatial alignment. The digital landscape and virtual watershed approaches, combined with advanced machine and deep learning techniques, enable the prediction of various ecosystem components across entire river networks. 

## Description

Since 2012, IHCantabria has been developing virtual river networks and watersheds, aka **DIGITAL RIVERSCAPES**, at large spatial scales (e.g., Spain and EU, Uruguay, Chile). A digital riverscape is essentially a digital representation of a watershed’s characteristics, designed to simulate spatially explicit watershed processes. It is typically structured as a fluvial network enriched with diverse layers of information, including topography, climate, geology, land use, and land cover, among others. It also incorporates data on key anthropogenic pressures affecting freshwater ecosystems, such as organic and industrial pollution, dams, reservoirs, and weirs.
These digital riverscapes are integrated with ecological datasets from various databases, which are used to train and validate models applied across the entire river network. The data span multiple ecosystem dimensions, including abiotic factors (e.g., nutrient levels, hydrological classifications), biodiversity (e.g., species presence, abundance, or biomass), and ecosystem functioning (e.g., river metabolism, organic matter decomposition). 

![Scheme of the modelling approach to model the ecological reference condition sensu WFD in Spain](../_static/images/Imagen_REEFCON.png){width="45%" fig-align="center"}

##

The integration of digital riverscapes with ecological datasets forms the foundation for developing machine and deep learning algorithms that will enable the following:

1. **Determine the predictor variables** that contribute significantly to each model.
2. Predict the values of the target ecological component **across the entire digital riverscape**  and understand the spatial patterns associated with their distribution.
3. **Evaluate the spatial distribution**of predicted values to understand the spatial patterns associated with their distribution.
4. **Interpret and contextualize the result** within the broader ecological and legal framework, such as the concept of Ecological Status under the Water Framework Directive.

## Insights

* A variety of machine and deep learning approaches from Random Forest to Neural Networks or Extreme Gradient boosting can be implemented within the general modelling approach
* Providing information of freshwater ecosystems to entire river networks set the basis for river management based on decision support systems

## Additional Notes

* Object of several scientific publications:
    *    doi: [10.1002/lno.70019](https://doi.org/10.1002/lno.70019) 
    *    doi: [10.1016/j.jhydrol.2019.03.056](https://doi.org/10.1016/j.jhydrol.2019.03.056)
    *    doi: [10.1016/j.scitotenv.2015.12.109](http://dx.doi.org/10.1016/j.scitotenv.2015.12.109)
    *    doi: [10.1002/rra.3456](https://doi.org/10.1002/rra.3456)
                          
* Other implementation done by IHCantabria in Uruguay ([Reference](https://saras-institute.org/es/cuencas-virtuales/))
* IH Cantabria collaborates with **Terrain Works (USA)** for the development of digital riverscapes
* These tools have been funded by several research and technical assistance projects including MARCE, RIVERLANDS, HANSEL or REFCON

![UC FIHAC IHCantabrianegro](../_static/images/UC+FIHAC+IHCantabrianegro.png){width="500px" fig-align="center"}
