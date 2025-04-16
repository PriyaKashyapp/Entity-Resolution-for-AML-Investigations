

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
---

2.Install the required dependencies:

pip install -r requirements.txt


3. Generate synthetic data and run the scripts:

python generate_synthetic_data.py
python entity_resolution.py

---
 
## Usage

1. Generate Synthetic Data

Run the script to create synthetic customer profiles:

python generate_synthetic_data.py
This will generate a CSV file (synthetic_customer_data.csv) containing customer profiles with overlapping attributes.

2. Perform Entity Resolution

Run the entity resolution script:

python entity_resolution.py
This script identifies duplicate or related entities and outputs clusters of resolved entities.

3. Visualize Relationships

Run the visualization script to generate a network graph:
python visualize_network.py
The output will be a visual representation of relationships between entities.

---

## Contributing

We welcome contributions from the community! Whether you're fixing bugs, adding new features, or improving documentation, your input is valuable. Here's how you can contribute:

Fork the Repository : Click the "Fork" button on the top-right corner of this page.
Clone Your Fork :
git clone https://github.com/priyakashyap/entity-resolution-aml.git
cd entity-resolution-aml
Create a New Branch :
git checkout -b feature/your-feature-name


### Make Changes : Implement your changes or improvements.
### Test Your Changes : Ensure your code works as expected.
### Submit a Pull Request : Push your changes to your fork and submit a pull request to the main branch of this repository.
 
 
## Guidelines for Contributors

Follow the existing coding style and conventions.
Write clear and concise commit messages.
Include tests for any new functionality.
Document your changes in the README if necessary.
If you're unsure about what to work on, check out the Issues tab for open tasks or suggestions.

---
## License

This project is licensed under the MIT License . See the LICENSE file for details.
---

## Contact

Have questions or want to collaborate? Feel free to reach out:

Email: priyakashyapp007@gmail.com
GitHub: @priyakashyap
LinkedIn: https://www.linkedin.com/in/priyaa-kashyapp/
 
 
## I appreciate your interest and look forward to collaborating with you!


















