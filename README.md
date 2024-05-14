
# Robust Federated Graph Neural Network Against Adversarial Backdoor Attacks

## Overview

This repository contains the code and data used for the experimental analysis of graph poisoning on three benchmark datasets: Cora, Pubmed, and Citeseer. The experiments utilize the DeepRobust library to perform adversarial attacks through edge flipping, aiming to analyze the impact of these perturbations on the performance of a Graph Convolutional Network (GCN).

## Datasets

The datasets used in this project are:

- **Cora**
- **Pubmed**
- **Citeseer**

All datasets are publicly available in the PyTorch Geometric library.

## Repository Structure

```
.
├── Poison_Cora.ipynb
├── Poison_Pubmed.ipynb
├── Poison_Citeseer.ipynb
└── README.md
```


## Usage

### Running the Experiment

Each dataset has its own Jupyter Notebook file to run the experiments:

1. **Poisoning Cora dataset:**
   - Open and run `Poison_Cora.ipynb`.
   - This notebook trains the GNN on the Cora dataset, applies various levels of poisoning (5%, 10%, 15%, 20%, and 25%), and evaluates the accuracy of the poisoned GNN.
   - Give it a try on Colab with the link attached.

2. **Poisoning Pubmed dataset:**
   - Open and run `Poison_Pubmed.ipynb`.
   - This notebook trains the GNN on the Pubmed dataset, applies various levels of poisoning (5%, 10%, 15%, 20%, and 25%), and evaluates the accuracy of the poisoned GNN.
   - Give it a try on Colab with the link attached.

3. **Poisoning Citeseer dataset:**
   - Open and run `Poison_Citeseer.ipynb`.
   - This notebook trains the GNN on the Citeseer dataset, applies various levels of poisoning (5%, 10%, 15%, 20%, and 25%), and evaluates the accuracy of the poisoned GNN.
   - Give it a try on Colab with the link attached.

### Script Details

- **`Poison_Cora.ipynb`:** Contains the implementation and results for poisoning the Cora dataset.
- **`Poison_Pubmed.ipynb`:** Contains the implementation and results for poisoning the Pubmed dataset.
- **`Poison_Citeseer.ipynb`:** Contains the implementation and results for poisoning the Citeseer dataset.


## Acknowledgements

This project utilizes the DeepRobust library for adversarial attacks. Special thanks to the authors of the library and the maintainers of the PyTorch Geometric library for providing the datasets.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

