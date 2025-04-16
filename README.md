# Multilevel Resource Clustering for Service Placement in Fog Computing

This repository contains datasets and configurations used in the paper:

**Use of Multilevel Resource Clustering for Service Placement in Fog Computing Environments**  
Presented at the *IEEE/ACM 15th International Conference on Utility and Cloud Computing (UCC 2022)*.

## Overview

The materials provided here support the analysis of service placement strategies in fog computing environments, based on multilevel clustering techniques. The datasets include real and synthetic network topologies, application descriptions, and clustering results derived from geolocation and computational characteristics.

---

## Contents

### 1. Topologies

- **`melb_resources_features.csv`**  
  Combines geolocation data from the EUA Dataset with node resource characteristics (CPU, RAM, Bandwidth) from the IoT-Compute-Dataset.

- **`multi-level-clustering-resources.csv`**  
  Output of the multilevel clustering process using the K-Means algorithm on `melb_resources_features.csv`.

- **Germany Topology**  
  A real-world topology representing a segment of the German ISP infrastructure.

- **Synthetic Topology**  
  Artificially generated topology for evaluating scalability and abstraction.

---

### 2. Applications

- **`application-config.csv`**  
  Describes a set of applications and their respective microservice requirements (CPU, memory, storage, bandwidth).

- **`apps_data_01/`**  
  Contains 20 applications, each composed of 4 to 29 microservices, with incremental growth in service quantity.

- **`apps_data_02/`**  
  Contains 20 applications, each ranging from 4 to 80 microservices, growing in steps of 4.

---

## Source Datasets

This repository integrates data from the following public sources:

- [**iFogSim2**](https://github.com/Cloudslab/iFogSim)  
  Extended fog computing simulator supporting mobility, clustering, and microservice orchestration.

- [**EUA Dataset**](https://github.com/swinedge/eua-dataset)  
  Provides geolocation data of edge computing nodes.

- [**IoT-Compute-Dataset**](https://github.com/saifulislamPhD/IoT-Compute-Dataset)  
  Offers detailed resource profiles for a variety of IoT and edge nodes.

---

## Reference

Mahmud, R., Pallewatta, S., Goudarzi, M., & Buyya, R.  
[iFogSim2: An Extended iFogSim Simulator for Mobility, Clustering, and Microservice Management in Edge and Fog Computing Environments](https://arxiv.org/abs/2109.05636)  
*Journal of Systems and Software (JSS), Volume 190, Pages 1–17, August 2022, Elsevier.*

---

## Citation

Please cite this repository if it supports your research or application development.