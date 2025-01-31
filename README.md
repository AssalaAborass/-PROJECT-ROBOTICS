[![Documentation Status](https://readthedocs.org/projects/verifai/badge/?version=latest)](https://verifai.readthedocs.io/en/latest/?badge=latest)  
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)  

# VerifAI  

*VerifAI* is a software toolkit designed for the formal analysis and design of systems that incorporate artificial intelligence (AI) and machine learning (ML) components.  
The project focuses on applying formal methods to perception and learning-based components, including neural networks, while modeling and analyzing system behavior in uncertain environments.  

The current version of the toolkit enables intelligent simulation guided by formal models and specifications, supporting various applications, including:  
- Temporal-logic falsification (bug detection).  
- Model-based robustness testing.  
- Parameter synthesis.  
- Counterexample analysis.  
- Dataset augmentation.  

Further details can be found in the [CAV 2019 paper](https://people.eecs.berkeley.edu/~sseshia/pubs/b2hd-verifai-cav19.html).  

For installation instructions, tutorials, and publications using VerifAI, please refer to the [documentation](https://verifai.readthedocs.io/).  

### Author  

This project was developed by *Asala AboRass*, with contributions from other researchers in the field.  

### Repository Structure  

- *docs*: Source files for the [documentation](https://verifai.readthedocs.io/).  
- *examples*: Examples and additional documentation for specific simulators, including CARLA, Webots, X-Plane, and OpenAI Gym.  
- *src/verifai*: The source code for the verifai package.  
- *tests*: The VerifAI test suite.
