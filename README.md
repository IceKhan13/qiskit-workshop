Qiskit workshop
===============

Notebook for workshop is called `qiskit-workshop-lab-notebook`.

### Installation

#### Getting IBM Q account and token

1. Go to https://quantum-computing.ibm.com/
2. Register
3. On your welcome page you should see `API token` field which you can copy and use during lab

#### Local jupter + qiskit setup

0. (if you do not have it already) [Install conda](https://www.anaconda.com/products/individual)
1. In terminal: create a new conda env
```shell
conda create --name qiskit-workshop python=3.7
```
2. In terminal: activate env
```shell
conda activate qiskit-workshop
```
3. In terminal: Install dependencies
```shell
conda install jupyter matplotlib
pip install qiskit pylatexenc
```
4. In terminal: launch jupyter
```shell
jupyter notebook
```
