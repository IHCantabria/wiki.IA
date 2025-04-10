
## Santander OEFS AI - Santander Operational Estuary Forecast System based on AI

🌊🤖✨ `#operational-system` `#forecasting` `#hydrodynamic-modelling` `#beach-safety` `#neuronal-network` `#deep-learning` `#artificial-inteligence`

---
### Context
Operational systems based on physical modelling are powerfull tools to predict and forecast meteooceanographic variables. As a counter part, these tools normally required of high computational demands and/or long computational windows to provide to the end users its results. With the aim of obtaining a balance between this requeriements and an optimal results accuracy for the majority of the problems where these variables are used, the training of a deeplearning neuronal network is used in order to be capable to forecasting waterlevels and currents velocity fields in the Bay of Santander.

<figure align="center">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ8FVaKXsJN7SjVZG5-nMK0WaFQ1jprkwRWqg&s" alt="Screenshots of SOSeas mobile application" width="300"/>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRD_-EYNG7j_xt-KUqHngVDuL87gs8YuBTSkg&s" alt="Screenshots of SOSeas mobile application" width="300"/>
    <figcaption><i>Figure 1 - Map of the Bay of Santander (left) and LSTM diagram (rigth)</i></figcaption>
</figure>

### Description
Based on a calibrated and validated implementation of a hydrodynamic physical model on the bay of Santander. A system of Long Short-Term Memory (LSTM) neural networks has been trained to replace the behaviour of the operational physical system, this new system based on artiicial inteligence provides the same output, high resolution water levels, and superficial currents on the area, however it requires of a few minutes to provide these results.

This neural network system is cappable to predict more than 72h of waterlevel and superficial current velocity fields in minutes, instead of hours of coputational effort required by the operational physical model. This present an important change on the reources requierd to mantain this systems working.

This system based on AI only requires the predicted temporal series of the main regional drivers on one point (predictors) to assess the complete high resolution forecasting on the Bay of Santander in a few minutes.

<figure align="center">
    <img src="" width="150"/>
    <figcaption><i>Figure 2 - Results of Santander OEFS AI </i></figcaption>
</figure>

### Insights
🌊 This system provides 3 day hourly high resolution hydrodynamic forecast in the Bay of Santander including the following variables: ↕️water level and 🔀surface currents


⏳ This development allows a significant reduction of the resources required to mantain the system, keeping a reseonable acuracy of the results for the majority of the use cases in which this information is required.

💡 Moreover, the implementation of these deeplearning algorithms allows us to keep researching in the use of this techniques and the intercomparishon with traditional physical models.


### Other Remarks
* This operational system has been developed in the framework of the [PhD thesis of Mirko Rupani](https://ihcantabria.com/en/scientific-production/phd-theses-2/) ex-member of IHCantabria.
    * Scientific publication is under development based on this work

* The development and final integration of the system has been carried out in the framework of different projects:

    * [MARION](https://ihcantabria.com/en/data-science-and-artificial-intelligence-are-some-of-the-methods-used-by-marion-the-marine-pollution-prevention-system-developed-at-ihcantabria/): part of the ThinkInAzul programme and supported by Ministerio de Ciencia e Innovación with funding from European Union NextGeneration EU (PRTR-C17.I1) and by Comunidad de Cantabria 

    <p align="right">
    <img src="../_static/images/PCM-socios.png" height=75/>
    <img src="../_static/images/logos-PCM.png" height=50/>
    </p>

    * [COSNORTH](https://ihcantabria.com/en/cosnorth-offers-improved-environmental-maritime-and-climate-services-on-spains-northern-coastline/): inside the CMEMS National Collabortaion Program funded by Mercator International


<p align="right">
<img src="../_static/images/CMEMS DEMO_2024.png" height=50/>
<img src="../_static/images/Mercator.png" height=50/>
</p>


<p align="center">
<img align="center" src="../_static/images/UC+FIHAC+IHCantabrianegro.png" width="500"/>
</p>
