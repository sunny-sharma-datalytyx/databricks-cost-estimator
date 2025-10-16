# Databricks Cost Estimator

## Overview
The **Databricks Cost Estimator** is an interactive web-based tool designed to estimate the monthly and annual costs of running Databricks workloads across multiple cloud providers (AWS, Azure, GCP). 
It provides a user-friendly interface to configure workspace settings, workload composition, and infrastructure parameters to model costs for Development, Staging, and Production environments. 
The tool is built using HTML, CSS, and JavaScript, and it reflects pricing data accurate as of October 2025.

This project was created by Sunny Sharma from Mphasis Datalytyx to help organizations plan and optimize their Databricks deployments.

## Features
- **Cloud Provider Selection**: Choose between AWS, Azure, or GCP with region-specific pricing adjustments.
- **Workspace Configuration**: Customize security levels, commitment contracts, and tier options (e.g., Premium, Enterprise).
- **Workload Composition**: Allocate workloads between Data Engineering, Data Science, and Data Analytics using sliders.
- **Storage & Networking**: Input managed storage and data egress to estimate infrastructure costs.
- **Cost Breakdown**: View detailed cost breakdowns for DBUs, compute, workspace management, support, and infrastructure.
- **Per-Workspace Costs**: See cost estimates for Production, Staging, and Development environments.
- **Export Functionality**: Save your configuration and cost estimate as a JSON file.
- **Cloud Comparison**: Compare estimated costs across AWS, Azure, and GCP.
- **Optimization Tips**: Includes best practices for cost optimization, such as using spot instances and auto-termination.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/sunny-sharma-datalytyx/databricks-cost-estimator.git
