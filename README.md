# breast-cancer-drug-targets-
"Drug-gene interaction analysis using DGIdb to identify potential pharmacological agents and interaction mechanisms for key high-degree therapeutic targets in breast cancer networks."
# Drug-Gene Interaction Analysis

## Overview
This repository contains the results of a drug-gene interaction analysis performed using the [Drug Gene Interaction Database (DGIdb)](https://dgidb.org/). The data provides a comprehensive mapping of potential pharmacological agents and their interaction mechanisms for key therapeutic targets. 

## Project Context
This dataset serves as a critical downstream step following the identification of high-degree centrality nodes via Cytoscape network analysis. By querying these central genes—which represent critical vulnerabilities in the breast cancer network—against DGIdb, this analysis bridges the gap between topological network importance and clinical druggability.

## Data Structure
The primary data file (`gene_interaction_results-27_2_2026.tsv`) is a tab-separated values export containing the interaction metrics. Standard DGIdb outputs typically include:
* **Gene Name:** The target gene symbol.
* **Drug Name:** The interacting pharmacological agent.
* **Interaction Type:** The mechanism of action (e.g., inhibitor, antagonist, antibody).
* **Source:** The database source for the interaction (e.g., DrugBank, ChEMBL).

## Strategic Applications
* **Targeting Network Hubs:** Prioritizing drugs that act as inhibitors or antagonists against the most highly connected nodes identified in the network analysis.
* **Regulatory Alignment:** Cross-referencing the identified therapeutic agents with FDA medical device and drug classification pathways to evaluate potential repurposing opportunities and regulatory feasibility.
