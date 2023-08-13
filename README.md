Recreated AA-Forecast: Anomaly-Aware Forecast for Extreme Events

[![Conference](http://img.shields.io/badge/ECML-2022-4b44ce.svg)](https://arxiv.org/abs/2208.09933)
</div>
==============================



## Getting Started

Instructions on setting up project locally or on a cloud platform. To get a local project up and running follow these simple example steps.

### Prerequisites

- Tensorflow 2.1.1
- Nvidia GPU 
### Datasets
Datasets are located in the data folder:

credit-card-sales-covid-19.csv
electricity.csv
tax-sales-hurricane.csv

### Installation

1. Clone the repo.

   ```
   git clone https://github.com/dhamnanineha0801/AA-Forecast-Final-Project-MLP.git
   ```

2. Install requirement packages.

   ```
   pip install -r requirements.txt
   ```

3. Recreate the decomposition (anomaly graph) as shown below by executing AA-Decompose.py file in 'src' folder.


4. Run project.ipynb after the dataset has been gathered.



![Figure 1-1](https://github.com/dhamnanineha0801/AA-Forecast-Final-Project-MLP/blob/main/visualization/Decomposition.png "Figure 1-1")


5. Anomaly detection graph


![Figure 1-1](https://github.com/dhamnanineha0801/AA-Forecast-Final-Project-MLP/blob/main/output/Hotel_Urban_CollierDropOut_0.3.png "Figure 1-1")


### References

```@article{farhangi2022aa,
  title={AA-Forecast: Anomaly-Aware Forecast for Extreme Events},
  author={Farhangi, Ashkan and Bian, Jiang and Huang, Arthur and Xiong, Haoyi and Wang, Jun and Guo, Zhishan},
  journal={arXiv preprint arXiv:2208.09933},
  year={2022}
}
```



