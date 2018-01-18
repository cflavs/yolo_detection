# README #

## Introdução

Esse repositório contém uma implementação de funções do algoritmo base e da rede neural convolucional utilizada no modelo de detecção de objetos You Only Look Once [YOLO](https://arxiv.org/pdf/1506.02640.pdf) utilizando Keras.
A implementação foi feita para fins didáticos, afim de ilustrar a arquitetura da rede e suas respectivas partes para detecção, a implementação da YOLO está disponível no 
[repositório original](https://github.com/pjreddie/darknet/wiki/YOLO:-Real-Time-Object-Detection). A predição é realizada utilizando um modelo pré-treinado da YOLO.

YOLO é o estado da arte para detecção de objetos em tempo real, alcançando resultados melhores que as redes [SSD](https://arxiv.org/pdf/1512.02325.pdf)
e [Faster RCNN](https://arxiv.org/pdf/1506.01497.pdf). A versão atual da YOLO é a [v2](https://pjreddie.com/darknet/yolo/), podendo ser implementada futuramente
neste repositório.

## Organização do diretório:
 
* imgs: pasta com imagens utilizadas no notebook para explicação da YOLO e para
teste da predição;
* model data: contém o modelo da YOLO no formato h5, além de arquivos com as coordenadas das anchor boxes e as classes treinadas.
* out: contém os arquivos de saída da predição
* source: funções auxiliares 
* notebooks: contém dois notebooks utilizados para implementação. O notebook Arquitetura YOLO contém a implementação apenas das arquiteturas das duas versões da YOLO e suas diferenças e o notebook Algoritmo YOLO contém o algoritmo base.   
 
## Set up

* Ubuntu 17.10
* Jupyter Notebook
* Python 3
* Keras

## Créditos:

* Este repositório foi criado baseado nas aulas e assignments da especialização em Deep Learning ensinada por Andrew Ng no Coursera.

--

This repository contains an implementation of You Only Look Once [YOLO](https://arxiv.org/pdf/1506.02640.pdf) core functions and the convolutional neural network using Keras of both versions.
This implementation is for didactic purposes only to illustrate the network architecture and how the object detection is developed on it, so that it's not 
optimized as the [original network](https://github.com/pjreddie/darknet/wiki/YOLO:-Real-Time-Object-Detection). Also, a pre trained model is used.

YOLO is the state of the art for real time object detection, achieving better results than [SSD](https://arxiv.org/pdf/1512.02325.pdf) and 
[Faster RCNN]((https://arxiv.org/pdf/1506.01497.pdf) models. The ultimate version is YOLO [v2](https://pjreddie.com/darknet/yolo/) which it isn't 
covered in this repository at the moment.

## Directory Organization

* imgs: image folder with the images used to explain YOLO on the notebook and to perform prediction
* model data: contains the YOLO model on h5 extension and files with anchor boxes coordinates and classes names
* out: contains the images with object detection
* notebooks: contains two notebooks that describes YOLO. The YOLO Architecture notebook describes the network implementation itself of both YOLO models, and the notebook YOLO Algoritm contains the core algoritmn.

## Setup ##


* Ubuntu 17.10
* Keras
* Python 3
* Jupyter Notebook

## Credits:

This repository was created based on classes taken on Deep Learning Specialization, taught by Andrew Ng. 
## Quem somos/Team ##

* Cecília Flávia da Silva
* Universidade Federal da Paraíba - UFPB
* Centro de Informática - Visio - LAViD
