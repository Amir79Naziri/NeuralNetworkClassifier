<div align="center">
  
  <h1 align="center">360 Fruits Classifier</h1>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="usage">Usage</a>
      <ul>
        <li><a href="#usage">Requirements</a></li>
        <li><a href="#run">Run</a></li>
      </ul>
    <li>
      <a href="#Phases">Phases</a>
      <ul>
        <li><a href="#phase1">Preprocess Data</a></li>
        <li><a href="#phase2">Forward Propagation</a></li>
        <li><a href="#phase3">Non-Vectorized Backward Propagetion</a></li>
        <li><a href="#phase4">Vectorized Backward Propagetion</a></li>
        <li><a href="#phase5">Final Test</a></li>
        <li><a href="#phase6">Hyperparameters Analyzing</a></li>
        <li><a href="#phase7">Learning Rate Decay</a></li>
        <li><a href="#phase8">Deeper Network !!!</a></li>
          <ul>
            <li><a href="#phase8-1">Preprocess Data</a></li>
            <li><a href="#phase8-2">Train and Test</a></li>
          </ul>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li> 
  </ol>
</details>

## About The Project
This project implements a `feed-forward neural network` from scratch with `numpy` and uses the `360 Fruits` Dataset as a training and testing model. there are seven phases in this project which complete neural network implementation step by step, which includes the following steps  

* [Preprocess Data](#phase1)
* [Forward Propagation](#phase2)
* [Non-Vectorized Backward Propagetion](#phase3)
* [Vectorized Backward Propagetion](#phase4)
* [Final Test](#phase5)
* [Hyperparameters Analyzing](#phase6)
* [Learning Rate Decay](#phase7)
* [Deeper Network !!!](#phase8)

as input data are images, so there are some feature extraction codes that can transform images into fixed dimensional vectors, so model uses .pkl extension files as input (not direct images). In the beginning, non-vectorized backward propagation had been implemented, and after that implementation changed to the backward to vectorized form.  

feel free to use code ...  

###### Thanks for your reading
 

<p align="right">(<a href="#top">back to top</a>)</p>

## Usage  
#### Requirements
we used numpy array for increasing speed, then you should install `numpy` library.
```bash
$ pip install numpy
```
also, we used `pygame` for visualizing solving procedure.
```bash
$ pip install pygame
```
#### Run 
```bash
$ python3 csp.py
```

#### Example Run
``` bash
$ python3 csp.py
Which constraint propagation algorithm would you prefer?
 1) MAC
 2) Forward Checking
1
10 10
- 0 - - - - - - - -
- 0 - - - - - 1 - 0
1 - - - 1 0 - - - -
- - - 0 - - - - - 1
- - - - 1 - - - - -
- - - - - - 1 1 - -
- 1 - 1 - - 1 - - -
0 - - - - - - - 0 -
- 1 - - 1 - - 1 0 -
- - - 0 - 0 - - - -
```
then you can see the solving procedure as follows  

![Example Run](./pic/preview.gif)  

<p align="right">(<a href="#top">back to top</a>)</p>

## License

Distributed under the MIT License. See `LICENSE.md` for more information.  

<p align="right">(<a href="#top">back to top</a>)</p>

## Contact
[Amirreza Naziri](https://github.com/Amir79Naziri)  
Email: naziriamirreza@gmail.com  

<p align="right">(<a href="#top">back to top</a>)</p>
