# CAD Mechanical Components Classification
Convolutional neural network approach to a classification task on a dataset composed of CAD models divided in 68 classes.  
The models in this repository are trained on datasets of images generated from projections of the .obj models made
available by the group which built the original dataset.

## References
['A Large-scale Annotated Mechanical Components Benchmark for Classification and Retrieval Tasks with 
Deep Neural Networks'](https://link.springer.com/chapter/10.1007/978-3-030-58523-5_11) present more information on the
process of models gathering and taxonomy.

## Dependencies
Python 3.10 (3.10.14)

## Setup 
1. Define a virtual environment (optional)  
`python3 -m venv venv`  
2. Activate the venv (optional)  
`source venv/bin/activate`  
3. Install python dependencies  
`pip install -r requirements.txt`  

## Data sources
1. [Original .obj dataset 2.3 GB](https://mcb-dataset.s3.sa-east-1.amazonaws.com/MCB_A.tar.gz)
2. [64x64 pixels projection views 652 MB](https://mcb-dataset.s3.sa-east-1.amazonaws.com/MCB_A_images_64.zip)
3. [256x256 pixels projection views 4.4 GB](https://mcb-dataset.s3.sa-east-1.amazonaws.com/MCB_A_images_256.zip)
4. [1024x1024 pixels projection views 10.2 GB](https://mcb-dataset.s3.sa-east-1.amazonaws.com/MCB_A_images_1024.zip)