# Multi Person Activity Recognition using CSI (Wi-Fi Sensing)

This project investigated two deep learning architectures: CSITime (Yadav et al., [2022](https://www.sciencedirect.com/science/article/abs/pii/S0893608021004391)) as well as a compact, smaller version of XCeption (Chollet, [2016](https://arxiv.org/abs/1610.02357)). Both models were trained and tested on 7 interactions from the HHI dataset (Alazrai et al., [2022](https://www.mdpi.com/1424-8220/22/16/6018)). More informations about the dataset is contained in its own subsection.

The project had two aims: 
1) To investigate the efficacy of the CSITime architecture on multi-person Wi-Fi sensing.
2) To propose a lightweight model for the multi classification problem.


# Project Structure 
- models.ipynb: Contains the code for running and testing different models as well as evaluating them. 
- Preprocessing.ipynb: Contains code for accessing the raw CSI recordings and preprocessing them. 
- TestingArea.ipynb: Contains code for plotting the subcarriers for a single interaction. 

This project used:
- NumPy
- matplotlib
- Pandas
- Tensorflow
- sci-kit learn.

# Pre-processing

# Model Testing and Evaluation
