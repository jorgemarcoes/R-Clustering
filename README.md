

# R-Clustering


[arXiv:1910.13051](https://arxiv.org/abs/2305.10457) (preprint)

> <div align="justify">Time series data, spanning applications ranging from climatology to finance to healthcare, presents significant challenges in data mining due to its size and complexity. One open issue lies in time series clustering, which is crucial for processing large volumes of unlabeled time series data and unlocking valuable insights. Traditional and modern analysis methods, however, often struggle with these complexities. To address these limitations, we introduce R-Clustering, a novel method that utilizes convolutional architectures with randomly selected parameters. Through extensive evaluations, R-Clustering demonstrates superior performance over existing methods in terms of clustering accuracy, computational efficiency and scalability. Empirical results obtained using the UCR archive demonstrate the effectiveness of our approach across diverse time series datasets. The findings highlight the significance of R-Clustering in various domains and applications, contributing to the advancement of time series data mining.</div>

Please cite as:

```bibtex
@article{marco2023time,
  title={Time Series Clustering With Random Convolutional Kernels},
  author={Marco-Blanco, Jorge and Cuevas, Rub{\'e}n},
  journal={arXiv preprint arXiv:2305.10457},
  year={2023}
}
```


## Reproduce the experiments in your web browser
Access the experiments in Google Colab without the requirement of any installations: [`Experiments`](https://colab.research.google.com/github/jorgemarcoes/R-Clustering/blob/main/R_Clustering_on_UCR_Archive.ipynb)

## Code

### [`Jupyter Notebook`](R_Clustering_on_UCR_Archive.ipynb)

#### Requirements

* Python
* Numba
* NumPy
* Pandas
* scikit-learn
* sktime



## Results

### UCR Archive

* Results from the hyperparameter search with varying number of kernels and kernel length. The columns indicate the pairings of kernel length and kernel size: [Hyperparameter search results](results/hyperparameters_search.csv)


* The outcomes of the evaluation of R-Clustering in comparison to other benchmark algorithms across the validation datasets: [R-Clustering comparison](results/benchmark_UCR_results.csv)



