# GraphGAN-The-new-way-to-learn-graph-
GraphGAN combines graph-based methods with GANs, utilizing a generator to create fake graph data and a discriminator to evaluate its authenticity. It's useful for graph generation, link prediction, and node classification, with applications in social networks and recommendation systems.

if you want to run this project
1. cd project_location/src/GraphGAN
2. python train.py


this project include:
1. link_prediction 
2. node_classfication
3. recomendation

   ### Requirements
The code has been tested running under Python 3.6.5, with the following packages installed (along with their dependencies):

- tensorflow == 1.8.0
- tqdm == 4.23.4 (for displaying the progress bar)
- numpy == 1.14.3
- sklearn == 0.19.1


### Input format
The input data should be an undirected graph in which node IDs start from *0* to *N-1* (*N* is the number of nodes in the graph). Each line contains two node IDs indicating an edge in the graph.

##### txt file sample

```0	1```  
```3	2```  
```...```


### Basic usage
```mkdir cache```   
```cd src/GraphGAN```  
```python graph_gan.py```


you can see them in src/evaluation


you can clone the files form here link (https://drive.google.com/file/d/1OQGVUegFWz9RC0bwqtw3xYaUYqLy6T3A/view?usp=drive_link)
first you have to download this file 
after that you have to unzip file then open it pycharm
