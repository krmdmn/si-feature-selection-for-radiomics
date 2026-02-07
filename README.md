# SI-based feature selection




# check yaml source files, create each miniconda environment:
#1) pso based cox analysis 2) ga based cox analysis 3) pso based rsf analysis (including others with shortcut)

#common libraries but careful versions (yaml) to reproduce the results
pip install pandas matplotlib tqdm numpy scikit-learn scikit-survival  lifelines

# for particle swarm optimization
pip install ps-optimize

# for genetic algorithm
pip install sklearn-genetic

Please cite the following paper when using the code:

A Novel Swarm Intelligence-Driven Feature Selection for Interpretable Machine Learning in GBM Overall Survival Analysis
Abdulkerim Duman, Xianfang Sun, James R. Powell, Emiliano Spezi
medRxiv 2025.04.16.25325927; doi: https://doi.org/10.1101/2025.04.16.25325927