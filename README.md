# Kmeans with Theano

## Objective

In this project, the authors performed K-means to images, through <a href= http://deeplearning.net/software/theano/> Theano </a>, in order to get <a href =https://en.wikipedia.org/wiki/Color_quantization >  color quantization</a>. 

## Execution

In order to use your GPU, use the following code : 
```
THEANO_FLAGS=floatX=float32,device=gpu,allow_gc=False,nvcc.flags=-D_FORCE_INLINES,nvcc.fastmath=True jupyter notebook
```

## Organisation
- data/images : contains many images, with different size, used in the Jupyter notebook
- doc : ?
- notebook : contains two Jupyter notebook
  - xxx : 
  - yyy : 
- rapport : contains a rapport, written in French, explaining the project  
- results : contains some results obtained via Kmeans 

## Examples

![alt tag](https://github.com/dvp-tran/K-means_Cuda/blob/master/data/images/beautiful-02.jpg)

