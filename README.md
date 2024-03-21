# CIRED 2024 Article

This repository contains the data and simulation code to replicate the hosting capacity study
presented in the CIRED 2024 article titled:

    Roseau Load Flow: A Modern Software Package For The Modelling And Steady-State Simulation Of Power Distribution Grids

<!-- TODO: Add citation when available -->

## Project structure

- The `Article` folder contains the article in pdf format as well as the tikz figures used in the article
- The `data` folder contains the load and PV profiles used in the time series simulation
- The `HostingCapacity.ipynb` Jupyter Notebook contains the code used in the evaluation of the
  hosting capacity of the network presented in the article
- The `.env` file contains the public _Roseau Load Flow_
  [license key](https://roseau-load-flow.roseautechnologies.com/License.html) that can be used to
  execute the notebook

## Installation

Clone this repository then run `poetry install`

## Usage

The goal of the study is presented in the article, make sure to read it first then follow the
instructions in the Jupyter Notebook.
