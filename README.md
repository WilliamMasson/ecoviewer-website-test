# 🌿 EcoViewer

**EcoViewer** is an open-access environmental reference platform combining GBIF ecosystem indicator species occurrence data with global environmental layers — to help ecologists, researchers, and conservation practitioners understand ecosystems anywhere on Earth.

The platform is built on [Google Earth Engine](https://earthengine.google.com/) and is freely accessible, with no login or licence fees required.

🌐 **Website:** [ecoviewer.org](https://ecoviewer.org)


## What EcoViewer does

EcoViewer provides two complementary types of data for any location on Earth:

- **Ecosystem indicator species** — GBIF species occurrence records matched to ecosystem types and biomes from the [IUCN Global Ecosystem Typology](https://global-ecosystems.org/), using peer-reviewed ecological literature
- **Environmental layers** — global datasets covering climate, vegetation, water & wetlands, and fire disturbance, harmonised from verified public repositories

Click anywhere on the map to get instant ecological context for that location. Switch between thematic panels to explore different dimensions of the environment.


## Repositories

### [`ecoviewer-app`](https://github.com/ecoviewer/ecoviewer-app)
Holds all code required to run the EcoViewer Google Earth Engine application — including the environmental layers, GBIF ecosystem indicator species panel, and the interactive map interface.

### [`ecoviewer-gbif-processing`](https://github.com/ecoviewer/ecoviewer-gbif-processing)
Holds all code required to extract and process GBIF species occurrence data for EcoViewer, using BigQuery and the asynchronous pygbif API.

### [`ecoviewer-website`](https://github.com/ecoviewer/ecoviewer-website)
Holds all code required to build and deploy the EcoViewer website, built with plain HTML, CSS, and JavaScript and hosted on GitHub Pages.


## Feedback & contributions

We welcome feedback, bug reports, dataset suggestions, and feature requests. Please open an issue in the most relevant repository:

- [`ecoviewer-app`](https://github.com/ecoviewer/ecoviewer-app/issues) — anything related to the app, its layers, or datasets
- [`ecoviewer-gbif-processing`](https://github.com/ecoviewer/ecoviewer-gbif-processing/issues) — anything related to the GBIF data pipeline
- [`ecoviewer-website`](https://github.com/ecoviewer/ecoviewer-website/issues) — anything related to the website


## About

EcoViewer was developed at the [Global Ecology Lab](https://www.globalecologylab.org/) at James Cook University, Townsville, Australia. All code is open source and published under the MIT licence.
