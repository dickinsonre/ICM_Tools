# ICM_Tools
SQL and Ruby scripts to supplement modeling in InfoWorks ICM
# ICM_Tools

A curated collection of **Ruby** and related automation scripts for extending model-building, querying, import/export, and workflow automation in **InfoWorks ICM**. This public fork of `ngerdts7/ICM_Tools` organizes practical examples across SQL queries, Ruby scripts, ICM Live data retrieval, and IExchange scripting for users who want to accelerate repetitive modeling tasks.[1][2]

## Overview

The current repository README is only a single sentence, but the folder structure shows that the repository is much broader than a small script dump. It groups examples into four major areas: Ruby scripts for ICM, SQL queries for ICM, ICM Live data retrieval, and IExchange example scripts.[1]

That structure fits the way InfoWorks ICM scripting is commonly used in practice. Innovyze's own open-source support materials describe Ruby, SQL, and related code as tools that can be used in Workgroup products to automate tasks, while InfoWorks ICM documentation describes SQL as a built-in language for selecting, updating, and analyzing network objects.[2][3][4]

## What this repository is for

This repository is best understood as a **workflow acceleration toolkit** for InfoWorks ICM users. Rather than being a standalone software package, it provides reusable examples that help modelers automate common tasks such as network edits, batch processing, data extraction, import/export handling, and scripted scenario management.[1][2][5][6]

That makes it especially useful for larger or repeatedly updated models where manual editing becomes slow and error-prone. Public guidance on InfoWorks ICM scripting emphasizes the value of Ruby and SQL for automating repetitive work, processing large data sets, and improving model-building efficiency.[3][5][6]

## Repository structure

The GitHub page shows four top-level content folders plus a minimal root README.[1]

| Folder | Purpose |
|---|---|
| `Example Ruby Scripts for ICM/` | Ruby examples for model editing, automation, and UI- or Exchange-oriented scripting workflows inside InfoWorks ICM.[1][2] |
| `Example SQL Queries for ICM/` | Stored-query style examples for selecting, updating, filtering, and analyzing network objects using ICM's SQL subset.[1][3][4] |
| `ICMLive Data Retrieval/` | Scripts and utilities related to retrieving or handling ICM Live data, likely for operational or near-real-time workflows.[1] |
| `IExchange Example Scripts/` | Examples related to import/export automation and model exchange workflows, including the latest visible commit that mentions model import and export before and after processing.[1] |

GitHub reports the language mix as primarily **Ruby (89.6%)**, with smaller amounts of **PowerShell (5.9%)** and **Batchfile (4.5%)**, which is consistent with a script-oriented automation repository rather than a compiled application.[1]

## Why Ruby and SQL matter in ICM

InfoWorks ICM includes a built-in SQL capability for selecting and updating network objects using a product-specific SQL subset. The official help explains that SQL queries can select objects, deselect them, update fields, clear selections, save stored queries, and open results as grids that can be exported to CSV.[3]

Ruby complements that by providing a higher-level automation layer around model operations, repetitive edits, external file handling, and process orchestration. Public descriptions of ICM scripting note that Ruby can automate repetitive tasks, manipulate network data, process large data volumes, integrate with external data, and support import/export workflows.[2][5][7]

Together, Ruby and SQL form a powerful pair inside ICM: SQL is often ideal for fast object selection and attribute updates, while Ruby is better for workflow logic, looping, orchestration, and advanced automation. That combined approach has also been highlighted in public examples as a way to streamline model-building and analysis work in InfoWorks ICM and SWMM networks.[8][6]

## Likely use cases covered by the repo

Based on the repository organization and the surrounding InfoWorks scripting ecosystem, this repository is likely useful for tasks such as:

- Automating repetitive network edits and data cleanup in large ICM models.[1][5][6]
- Running saved or embedded SQL logic to identify objects meeting hydraulic, geometric, or asset-data criteria.[3][4]
- Importing and exporting network data as part of repeatable model update workflows.[1][9][7]
- Supporting ICM Live or operational data retrieval processes.[1]
- Demonstrating patterns for IExchange-based automation before and after processing steps.[1]

## Repository status

The repository is a public fork of `ngerdts7/ICM_Tools` and the visible GitHub page shows it is **16 commits behind** the upstream master branch.[1] The current snapshot shows **24 commits**, **1 branch**, **0 tags**, no releases, and no published packages.[1]

That suggests the repository functions mainly as a preserved and browsable example library rather than a packaged software product. Users should expect to review scripts, adapt them to local standards, and test them in their own InfoWorks ICM environments before production use.[1]

## What a better README should include

A stronger README should do more than say the repo contains SQL and Ruby scripts. It should explain:

- Which folders map to which ICM automation areas.[1]
- Whether scripts are intended for UI scripting, Exchange scripting, Live workflows, or external batch execution.[1][2][7]
- Any InfoWorks ICM version assumptions or licensing requirements, especially for ICMExchange-related automation.[7]
- Whether sample inputs, outputs, or example networks are expected.[1]
- How users should safely test scripts before applying them to production databases or version-controlled networks.[3][9]

## Recommended README draft

Below is a more complete GitHub-facing README draft you could use in the repository:

***

# ICM_Tools

`ICM_Tools` is a collection of **Ruby**, **SQL**, and related automation scripts for extending workflows in **InfoWorks ICM**. The repository is intended as a practical example library for modelers who want to automate repetitive tasks, query and update network objects, retrieve data, and streamline import/export operations.[1][2][3]

## Purpose

This project brings together script examples for several different parts of the InfoWorks ICM ecosystem. Instead of a single application, it provides reusable building blocks that can help speed up model setup, data maintenance, QA/QC, network interrogation, and exchange workflows.[1][5][6]

## Repository contents

- `Example Ruby Scripts for ICM/` — Ruby examples for automating model operations and repetitive edits inside InfoWorks ICM.[1][2][5]
- `Example SQL Queries for ICM/` — SQL examples for selecting, filtering, updating, and analyzing network objects using the built-in ICM SQL engine.[1][3][4]
- `ICMLive Data Retrieval/` — examples related to retrieving or processing ICM Live data.[1]
- `IExchange Example Scripts/` — scripts for model exchange and import/export automation workflows.[1][7]

## Why these scripts are useful

InfoWorks ICM includes built-in SQL support for selecting and updating network objects and a Ruby scripting environment for automating tasks and handling larger workflows.[3][5] Used together, these tools can reduce manual editing, improve consistency, and make repeatable modeling workflows easier to maintain across large projects.[8][6]

## Typical applications

This repository is relevant for:

- Batch model edits and repetitive data updates.[5][6]
- SQL-based QA/QC checks and object filtering.[3][4]
- Import/export workflow automation.[9][7]
- ICM Live data handling and retrieval.[1]
- Learning from script examples before writing custom production tools.[1][2]

## Notes for use

These scripts should be treated as examples and adapted carefully for local databases, naming conventions, object types, and software versions.[1] Before using any script in production, it is good practice to test it on a copy of the network or within a controlled version-management workflow.[3][9]

## Repository status

This repository is a fork of `ngerdts7/ICM_Tools` and currently trails upstream by 16 commits according to the visible GitHub page.[1] It appears to function primarily as a preserved example collection rather than a release-managed software package, with no tags or releases currently published.[1]

## Related references

- [Innovyze Open Source Support](https://github.com/innovyze/Open-Source-Support) [2]
- [InfoWorks ICM SQL help](https://help2.innovyze.com/infoworksicm/Content/HTML/ICM_IN_ILCM/Using_SQL.htm) [3]
- [InfoWorks ICM Open Data Export Centre help](https://help2.innovyze.com/infoworksicm/Content/HTML/ICM_IN_ILCM/Open_Data_Export_Centre_Dialog.htm) [9]

***
