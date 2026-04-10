---
title: "Projects"
subtitle: "Open-source code projects on GitHub"
description: "Open-source Python and Go projects by Reinert Huseby Karlsen – including eplines, kdlines, sondera, and gohbv for hydrology, meteorology, and time-series visualisation."
comments: false
lastmod: 2026-04-10
---

# Code projects currently on GitHub

## eplines
[eplines repository](https://github.com/rhkarls/eplines) | [eplines on PyPI](https://pypi.org/project/eplines/)

A small visualization package producing empirical and exceedance probability/frequency heatmaps and cycle plots of many or long time-series.

Can for example be used to visualize exceedance frequency at different times of the year for streamflow time series — basically a flow-duration curve for each day of the year:

![Discharge exceedance frequency heatmap showing cumulative frequency of streamflow for each day of the year](/img/discharge_exceedance_example.png)

The above graph shows the cumulative frequency of streamflow for each day of the year: how often specified discharges were equaled or exceeded. Low flows are exceeded often (values close to 1, with 1 meaning exceeded 100% of the time). Extreme high flows occur less often and have lower exceedance frequency.

Or the frequency distribution over the year for air temperature time series:

![Empirical cumulative distribution function heatmap of daily air temperature across the year](/img/temperature_ecdf_example.png)

---

## kdlines
[kdlines repository](https://github.com/rhkarls/kdlines) | [kdlines on PyPI](https://pypi.org/project/kdlines/)

Similar to eplines, this is a small visualization package producing kernel density heatmaps of many or long time-series.

---

## sondera
[sondera repository](https://github.com/rhkarls/sondera) | [sondera on PyPI](https://pypi.org/project/sondera/)

sondera is a Python package providing clients for accessing Swedish hydrology and meteorology related open data. Currently supports SMHI open data APIs metobs and hydroobs for meteorological and hydrological observations, and basic support for SGU groundwater levels.

sondera is currently at a very early stage, but functional for basic retrieval of data.

---

## gohbv
[gohbv repository](https://github.com/rhkarls/gohbv)

A Go (golang) implementation of the HBV hydrological model. The aim of this project was to learn Go. The current state is quite rough, but the model is functional.

Future plan is to provide a CLI for gohbv and make the model more user-friendly.

---

## stevens-connect-client
[stevens-connect-client repository](https://github.com/rhkarls/stevens-connect-client)

Python API client for [Stevens-Connect](https://stevens-connect.com/) cloud data acquisition system. Currently supports data retrieval to pandas Series and DataFrames.

---

## sensormanager-client
[sensormanager-client repository](https://github.com/rhkarls/sensormanager-client)

Python API client for sensormanager.net cloud data acquisition platform. The API is not documented or officially supported; the authentication and data retrieval which this client provides has been reverse-engineered.

