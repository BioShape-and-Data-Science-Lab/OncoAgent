**OncoAgent** is a project developed at the [*BioShape and Data Science Lab*](http://www.emanuelamerelli.eu/bigdata/doku.php?id=start) of the University of Camerino . 

This project is aimed to provide a **simulator** that represents the tumour micro-enviornment using **agent-based modeling** approach. In particular, agents' behaviour and environment have been modelled taking the *Renal Cell Carcinoma (RCC)* as a case study.  

Agents may have various behaviours and can make choices based on the interaction with other agents or the environment. The surrounding environment is the context were agents live and interact with one another and it can influence the agents themselves. The theoretical model upon which this project is based on is a stochastic cellular automaton, and can be seen as a generalization of the late [Conway’s Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life).

The software tool used to develop this system is The Repast Suite, a family of advanced, free, and open source agent-based modeling and simulation platforms. In particular it is used the Java implementation of it, *Repast Simphony 2.8*, downloadable from [their official website](https://repast.github.io/) .

### Software Functionalities

* Possibility of changing parameters to influence simulation's outcome;
* 2D and 3D displays to visualize the tumour micro-environment;
* Real time charts for statistics such as _Cells Count_ and _Kill Count_ for each cell.

Moreover, Repast Simphony permits to add additional functionalities, such as exporting data in CSV files or adding custom charts. For more information, please check [Repast official website](https://repast.github.io/).

### Screenshots

2D Display             |  3D Display
:-------------------------:|:-------------------------:
![2d](2d.png)  |  ![3d](3d.png)


![cell_count](cell_count.png)
![kill_count](kill_count.png)

### Pre-Requisites

In order to run the software, you should have Java 11 or a superior version installed on your machine.

### Installation

To install the software, clone the [GitHub repository](https://github.com/BioShape-and-Data-Science-Lab/OncoAgent) and follow the instructions provided in the *README* file.