# Multi-Scale Model for Influenza A Variant Dissemination

This repository contains a multi-scale computational framework that links
molecular-level mutations in the Hemagglutinin (HA) protein of Influenza A
to population-level epidemiological dynamics.

## Project Overview
The project integrates:
- Classical machine learning models to estimate a transmissibility-related
  fitness score from HA sequence mutations.
- An agent-based epidemiological model (ABM) that uses this fitness score
  to simulate viral dissemination.
- Empirical validation by comparing simulated epidemic curves with real
  epidemiological data from past Influenza seasons.

## Repository Structure
See the directory structure for data, notebooks, source code, and results.

## Data Sources
- Molecular data: GISAID / NCBI Virus
- Epidemiological data: FluNet (WHO)

## Requirements
- Python 3.10+
- See `requirements.txt` or `environment.yml`

## Authors
- Cátia Rosário
- Elidiane do Rosário
- Karolina Barbosa
- Vanessa Rodrigues
- João Ferreira
