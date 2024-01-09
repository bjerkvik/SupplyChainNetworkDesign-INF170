# SupplyChainNetworkDesign-INF170

This repository contains models and solutions for a supply chain network design project focused on bioethanol production in Texas. The project, part of the INF170 course, involves the modelling and optimization of a network of suppliers, biorefineries, and potential hubs.

## Project Overview

The project is divided into three main tasks, each addressing different aspects of the supply chain for bioethanol production. The tasks involve the location of biorefineries, introduction of hubs, and incorporation of third-party suppliers to meet increased demand.

## Table of Contents
- [Task 1: Biorefineries Location Optimization](#task-1-biorefineries-location-optimization)
- [Task 2: Introduction of Hubs](#task-2-introduction-of-hubs)
- [Task 3: Inclusion of Third-Party Supply](#task-3-inclusion-of-third-party-supply)
- [Data Files](#data-files)
- [Results and Reports](#results-and-reports)

## Task 1: Biorefineries Location Optimization
The first task focuses on determining optimal locations for biorefineries, considering suppliers in various counties and transportation costs. The aim is to minimize the total cost while meeting a production target.

## Task 2: Introduction of Hubs
This task explores the potential of adding intermediate hubs (train stations) to the network. The objective is to redesign the supply chain, minimizing total cost while meeting a production target.

## Task 3: Inclusion of Third-Party Supply
The final task involves incorporating third-party suppliers to meet an increased demand for bioethanol. The challenge is to redesign the supply chain, considering the new supply sources along with the existing network.

## Data Files
The `data` folder contains all the datasets used in this project:

- `suppliers.csv`: Contains information about the biomass suppliers.
- `plants.csv`: Details the potential locations for biorefineries.
- `roads_s_p.csv`: Road transportation details between suppliers and plants.
- `hubs.csv`: Information on potential hubs (train stations).
- `railroads_h_p.csv`: Rail transportation details between hubs and plants.

## Results and Reports
The project's outcomes are detailed in the `INF170_Mandatory_Assignment_Report.pdf`. This report includes:
- Detailed mathematical models used for each task.
- Results of the Gurobi optimization.

## Models and Code
The code is available in the Jupyter notebook file `INF170_Mandatory_Assignment_Code.ipynb`.
