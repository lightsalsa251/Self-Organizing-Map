# Self-Organizing-Map
Figure out the fraud ids in a bank credit card dataset. Self-Organizing Maps have been used for clustering.
SOM is an unsupervised deep learning model, mostly used for feature detection or dimensionality reduction. They output a 2D map for any number of indicators. In present times where staggering amount of data is collected with many indicators, SOMs are one of the most robust clustering techniques we have.\
![2D](http://www.pitt.edu/~is2470pb/Spring05/FinalProjects/Group1a/tutorial/kohonen1.gif)\
Weights are just co-ordinates of the output nodes in the input space. There is no activation function and summation.
Each input data point has a BMU. The BMU along with all of the neurons in its radius get updated.
Finally a 2D map is the output. A colour coding is used to identify any specefic group of data points.
### I have written a detailed article on SOM [here](https://medium.com/@s.ganjoo96/self-organizing-maps-b2cf58b74fdb)
## Installation
### Download the data and clone this repository
* Clone this repository to your computer.
* Get into the folder using cd Self_Organizing_Map.
### Installing the requirements
* pip install pandas
* Use minisom.py as the module for this project
## Usage
Run each cell in the SOM.ipynb file.
## Result
![output](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRmv4WJo3w8wY7Il3AQzAh1JHMR-SybgMuguZdfYE-jwuZOc3HuGQ)\
A list of fraudulent ids who applied for bank credit cards
