# TSUSY - Tsunami Early Warning and Forecasting System

🌊📲🧠 `#tsunami` `#early-warning` `#earthquake-monitoring` `#operational-system` `#random-forest` `#machine-learning`

---

## Description

**IH-Tsusy** is a real-time operational tsunami system that receives earthquake data from the **USGS**. Upon receiving seismic event data, the system evaluates whether the earthquake meets specific criteria indicative of potential tsunami generation. If so, it automatically launches:

- Numerical simulations of tsunami propagation.
- Notifications through a mobile app.
- Interactive maps showing wave heights and travel times from the epicenter to the impacted coasts.

![](../_static/images/tsusy_logo.png){fig-align="center" width="150"}


---

## Overview

The goal of the current work is to improve IH-Tsusy’s decision support system by replacing the traditional binary criteria — based on **focal depth** and **slip** — which rely heavily on expert judgment.

A machine learning approach is proposed to enhance decision accuracy using a **Random Forest Classifier** trained on historical seismic and tsunami data.

![Current System Output](../_static/images/tsusy-current-results.png){fig-align="center" width="60%"}

🖥️ 🎞️ Full presentation (Nov 28th, 2023): [View on Canva](https://www.canva.com/design/DAFbFyWc57c/ISjeqcPnOdLalJp-zXw_TQ/edit?utm_content=DAFbFyWc57c&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

## Modelling

The following figure illustrates the workflow and modelling methodology for tsunami event classification and simulation.

![Modelling workflow](../_static/images/tsusy-modelling.png){fig-align="center" width="80%"}

---

## Results

The machine learning model was fine-tuned and tested, obtaining the following performance:

![Train/Test Confusion Matrix](../_static/images/tsusy-train-test-conf-mat.png){fig-align="center" width="75%"}

### Comparison with Current System

The machine learning classifier significantly improves performance metrics over the original threshold-based method.

![Comparison with baseline](../_static/images/tsusy-comparison-conf-mat.png){fig-align="center" width="70%"}

---

## More Info

- 🔗 [Official Website](https://ihcantabria.com/specialized-software/ih-tsusy/)
- 🌐 [Web Application Interface](https://tsunami.ihcantabria.com/#/earthquakes)

---

![](../_static/images/UC+FIHAC+IHCantabrianegro.png){width="500px" fig-align="center"}
