# MoM-analytics
This is a public repository to analyze the flood prediction model (MoM) performance using historical records. The goal is to provide clarity on the MoM scientific outputs (interpretation, relationship and formats), expose potential issues with the data sources or model performance and, most importantly, **provide a justified basis for proposing any changes or improvements to MoM code**. 

Suggested format to share these insights is Jupiter Notebook files with preserved outputs. This will allow to demonstrate both the methods used for the analysis, and present the findings in the form of Tables, Graphs and Maps. 

The examples of the analyses to be done:

* Data structure

  * Output formats produced by each model
  * File naming conventions
  * Output frequency
  * Available parameters and data types

* Data completeness

  * Missing files or time gaps
  * Incomplete records
  * Missing variables
  * Unexpected data quality issues

* Data trends

  * Statistical distributions and ranges
  * Temporal patterns
  * Geographic patterns
  * Alert frequency by location and period

* Data compatibility

  * Consistency across output formats
  * Precision differences between datasets
  * Redundant parameters
  * Derivable fields and relationships

## Contributing guidelines

### 1. Choose an Issue

1. Open the **Issues** page.
2. Select an unassigned issue.
3. Assign yourself to the issue.

### 2. Create (if doesn't exist yet) and update your working copy 

#### Option A: GitHub Web Interface

1. Fork this repository.
2. Open your fork.
3. Before starting work, click **Sync fork** and update your `main` branch.

#### Option B: GitHub Desktop

1. Fork the repository on GitHub.
2. Clone your fork using GitHub Desktop.
3. Before creating a branch, fetch and pull the latest changes from `main`.

### 3. Create a Branch

Create a branch named after the issue, for example 'issue-42-data-completeness-check'

### 4. Create a Draft Pull Request

As soon as work starts:

1. Push your branch (if created from GitHub Desktop - this will sync your locally created branch to the online repo).
2. Create a **Draft Pull Request**.
3. Link this PR to the corresponding Issue using 'Development' section. This makes it visible who is working on what and automatically closes the issue once PR is merged.

<img width="398" height="786" alt="image" src="https://github.com/user-attachments/assets/a37ebbf8-f32d-4b7d-8178-146e8e210ff2" />

### 5. Implement Changes

Make changes using your desktop IDE or GitHub Codespaces.

### 6. Submit for Review

1. Convert the Draft PR to a regular PR.
2. Assign at least one reviewer.
3. Address review comments if any.

