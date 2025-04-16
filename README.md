# Entity-Resolution-for-AML-Investigations

# Entity Resolution for AML Investigations

![GitHub License](https://img.shields.io/badge/license-MIT-blue) ![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen)

## Overview

This project focuses on **Entity Resolution** to identify duplicate or related entities in customer data for Anti-Money Laundering (AML) investigations. The goal is to help investigators uncover hidden connections between individuals or organizations involved in financial crime by leveraging synthetic data, entity resolution techniques, and network visualization.

Key features of this project include:
- Synthetic data generation for realistic customer profiles.
- Entity resolution using libraries like `dedupe` and `pandas`.
- Network graph visualization to uncover relationships (e.g., shared accounts, IPs, addresses).
- Tools to assist in AML compliance and fraud detection.

---

## Table of Contents

1. [Project Objectives](#project-objectives)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)

---

## Project Objectives

The primary objective of this project is to:
- Simulate realistic customer data with overlapping attributes (e.g., names, addresses, shared accounts).
- Resolve duplicate or related entities using rule-based and machine learning techniques.
- Visualize relationships between entities using network graphs.
- Provide a reusable framework for AML investigators and compliance teams.

---

## Features

- **Synthetic Data Generation**: Create realistic datasets with intentional overlaps using Python's `Faker` library.
- **Entity Deduplication**: Use `dedupe` and custom logic to identify duplicates and related entities.
- **Network Visualization**: Build interactive graphs using `networkx` and `matplotlib` to uncover hidden connections.
- **Scalability**: Designed to handle small to medium-sized datasets, with potential for scaling to larger systems.

---

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/priyakashyap/entity-resolution-aml.git
   cd entity-resolution-aml

