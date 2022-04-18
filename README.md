# Graph-Covolution-Network

In this project, I have implemented Graph Convolution Networks (GCN) using python. I have tried to explain the prediction made by GNN using the first-order-logic formulas in Markov Logic Networks (MLN). GCN is a deep learning model that uses the relational knowledge to perform the inference. However, it is hard to explain the predictions made by deep models. In this project, I have incorporated MLN to describe the inference outcomes made by GCN. The project work is still in progress. In future, the new explanation algorithms will be added. I have used publicly available cora data set. 

# Running Program
In GCN_Project.ipynb  notebook he code of Gibbs sampling based  MLN approach is implemented in the first part.

To implement GCN, I have used the code from https://stellargraph.readthedocs.io/en/v1.0.0rc1/demos/node-classification/gcn/gcn-cora-node-classification-example.html

You have to  run the following command_1 and command_2 respectively in the 
GCN_Project.ipynb  notebook:

command_1: In order to get CORA MLN explanation for the prdiction: WORDS,Store_Explanation_r=MLN__Cora_explanation(). Here WORDS are the evidence file, and Store_Explanation_r contains the explanations of the queries. 

command_2: To get GCN outcomes you have to run: GCN_Result(WORDS,Store_Explanation_r)

# Software requirements
The following softwares are required:
1. Python 3
2. Jupyter Notebook
3. GCN pckages: stellargraph,stellargraph.mapper,stellargraph.layer
4. Tensflow packages: tensorflow.keras
5. IPython.display packages need to be installed
