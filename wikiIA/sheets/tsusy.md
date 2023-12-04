# TSUSY

**IH-Tsusy**  is a tsunami operational system designed to receive seismic information from the USGS. Using this data, the system assesses earthquake events to determine if they exhibit the necessary characteristics to trigger a tsunami. In the event of such a determination, IH-Tsusy performs numerical simulations of the tsunami's propagation. Subsequently, it delivers notifications through the app and presents interactive maps containing pertinent information. This includes data such as wave amplitude (or height) and travel times from the origin area to potentially affected coastal regions.

<div align="center">
  <a>
    <img src="https://play-lh.googleusercontent.com/OZrEhDUa5LchoPY08_SQTh2nFnMUTu3Szg6v9Tup5vID5mHI8cXvSusQ_4j-iyiwFA=w240-h480-rw" alt="Logo" width="200" height="200">
  </a>
</div>


## Overview
The motivation of this work is mainly focused as a proposal to improve the current IH-Tsusy decision system to classify earthquake events into potential tsunamis.

The current system is based on the fulfillment of a criterion based on the evaluation of two parameters (focal depth and slip) of earthquake events. The thresholds of these parameters are defined under "expert judgment".

<div align="center">
  <a>
    <img src="../_static/images/tsusy-current-results.png" width="50%">
  </a>
</div>
<br/>

The full presentation of this work, carried out Nov 28th 2023 is available [here](https://www.canva.com/design/DAFbFyWc57c/ISjeqcPnOdLalJp-zXw_TQ/edit?utm_content=DAFbFyWc57c&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton).

<div align="center">
  <a>
    <img src="../_static/images/tsusy-thumbnail-presentation.PNG" alt="Website thumbnail" width="30%">
  </a>
</div>


## Modelling

The modelling methodology used is the following.

<div align="center">
  <a>
    <img src="../_static/images/tsusy-modelling.png" alt="tsusy-modelling" width="75%">
  </a>
</div>

## Results

The following results are obtained by fine-tuning a Random Forest Classifier.

<div align="center">
  <a>
    <img src="../_static/images/tsusy-train-test-conf-mat.png" alt="tsusy-results-conf-mat" width="75%">
  </a>
</div>

### Improvement of the current system
The improvements achieved comparing with current decision system are the following.

![tsusy-comparison-conf-mat](../_static/images/tsusy-comparison-conf-mat.png)

---
## More info

[Official website of the operational system](https://ihcantabria.com/specialized-software/ih-tsusy/)

[Web application](https://tsunami.ihcantabria.com/#/earthquakes)
