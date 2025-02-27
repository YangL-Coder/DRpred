# DRpred
## Title:DRpred: A Novel Deep Learning-Based Predictor for Multi-Label mRNA Subcellular Localization Prediction by Incorporating Bayesian Inferred Prior Label Relationships
The subcellular localization of messenger RNA (mRNA) not only helps to understand the localization regulation of gene expression, but also helps to understand the relationship between RNA localization pattern and human disease mechanism, which has profound biological and medical significance. Several predictors have been proposed for predicting the subcellular localization of mRNA. However, there is still considerable room for improvement in their predictive performance, especially regarding multi-label prediction. This study proposes a novel multi-label predictor, DRpred, for mRNA subcellular localization prediction. This predictor firstly utilizes Bayesian networks to capture the dependencies among labels. Subsequently, it combines these dependencies with features extracted from mRNA sequences using Word2vec, forming the input for the predictor. Finally, it employs a neural network combining BiLSTM and an attention mechanism to capture the internal relationships of input features for mRNA subcellular localization. The experimental validation on an independent test set demonstrates that DRpred obtained competitive predictive performance in multi-label prediction and also outperformed state-of-the-art predictors in predicting single subcellular localizations, obtaining accuracy of 82.14%, 93.02%, 80.37%, 94.00%, 90.58%, 84.53%, 82.01%, 79.71%, and 85.67% for chromatin, cytoplasm, cytosol, exosome, membrane, nucleolus, nucleoplasm, nucleus, and ribosome, respectively. It is anticipated to offer profound insights for biological and medical research
.<div align=center>![image](https://github.com/user-attachments/assets/d9ae70ba-652e-473c-91f2-61545637d005)</div>
## DRpred uses the following dependencies:<br>
python: 3.9<br>
pandas: 1.4.4<br>
sklearn: 1.0.2<br>
numpy: 1.21.5<br>
PyTorch: 2.0.0<br>
## How to Use the Code in Jupyter (iPython) Notebooks:<br>
1.Clone the Repository:<br>
  First, clone the repository to your local machine. Open your terminal or command prompt and run the following command:<br>
  ```git clone https://github.com/YangL-Coder/DRpred.git```<br>
2.Navigate to the Repository Directory:<br>
  Change the directory to the cloned repository:<br>
  ```cd DRpred```<br>
3.Create a Virtual Environment:<br>
  It is recommended to create a virtual environment to manage dependencies. You can create a virtual environment using venv:<br>
 ```python3.9 -m venv venv```<br>
4.Activate the Virtual Environment:<br>
  On Windows:<br>
  ```venv\Scripts\activate```<br>
  On macOS and Linux:<br>
  ```source venv/bin/activate```<br>
5.Create a requirements.txt File:<br>
  If a requirements.txt file is not already in the repository, create one with the following content:<br>
  pandas==1.4.4<br>
  sklearn==1.0.2<br>
  numpy==1.21.5<br>
  PyTorch==2.0.0<br>
6.Install the Required Dependencies:<br>
  Install the required dependencies using the requirements.txt file:<br>
  ```pip install -r requirements.txt```<br>
7.Open Jupyter Notebook:<br>
  ```jupyter notebook```<br>
8.Navigate and Open the Notebook:<br>
  In the Jupyter Notebook interface, navigate to the directory where you cloned the repository. Open the notebook file (typically with a .ipynb extension) you want to work with.<br>
## Note:<br>
This code is for the article 'DRpred: A Novel Deep Learning-Based Predictor for Multi-Label mRNA Subcellular Localization Prediction by Incorporating Bayesian Inferred Prior Label Relationships'.
