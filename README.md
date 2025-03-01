OEMOF Research Model
Overview

This repository contains an OEMOF (Open Energy Modeling Framework) research model developed for analyzing and optimizing energy systems. The model is designed to simulate various energy scenarios, evaluate system efficiency, and support decision-making in sustainable energy planning.
Features

    Energy system optimization using OEMOF
    Modular structure for flexibility and scalability
    Integration of renewable energy sources
    Scenario analysis for policy evaluation
    Data visualization for insightful results

Installation

To run this model, ensure you have Python installed and set up a virtual environment. Then, install the required dependencies:

git clone https://github.com/Foziljoniy/oemof_model_energy/tree/main
cd oemof-research-model
pip install -r requirements.txt

Usage

Run the model by executing:

python main.py

For custom scenarios, modify the input data in data/ and update the configuration in config.py.
Dependencies

    oemof
    pandas
    numpy
    matplotlib

Install them via:

pip install oemof pandas numpy matplotlib

This repository contains an OEMOF-based energy system model, designed for analyzing and optimizing Uzbekistan's energy sector. The model focuses on renewable energy integration and investment planning using OEMOF-Solph.
Repository Structure

    
    prof_energy_my.ipynb – Secondary energy model analysis
    oemof_model.ipynb – Main Jupyter Notebook for the energy model
    Energy data files (.xlsx, .csv, .pdf) – Input data for model execution

Installation & Requirements

Before running the model, install the necessary dependencies:

    Clone the repository:

git clone https://github.com/Foziljoniy/oemof_model_energy.git
cd oemof_model_energy

Set up a Python environment (recommended):

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install OEMOF-Solph and dependencies:

pip install oemof-solph pandas numpy matplotlib

Install required solvers:

    CBC Solver: (Recommended for linear optimization)

conda install -c conda-forge coincbc

GLPK Solver: (Alternative open-source solver)

        conda install -c conda-forge glpk

Running the Model

Execute the main notebook:

jupyter notebook Untitled7.ipynb

Useful Links

    OEMOF-Solph Documentation: OEMOF-Solph GitHub
    OEMOF Visualization Tools: OEMOF-Visio GitHub

Contribution

Feel free to contribute by submitting issues, feature requests, or pull requests.
License

This project is licensed under the MIT License.
