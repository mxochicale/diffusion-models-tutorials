# Setting up conda env 

## Conda
Install [conda](https://github.com/mxochicale/code/tree/main/conda) and create [diffusionmodelsVE](ve.yml).

## Dependencies

* Python package versions
```
$ cd $HOME/repositories/mxochicale/diffusion-models-tutorials/dependencies
$ conda activate diffusionmodelsVE
$ python package_versions.py 

python: 3.10.8 (main, Nov 24 2022, 14:13:03) [GCC 11.2.0]
torch: 1.11.0
torch cuda_is_available: True
torch cuda version: 11.3
torch cuda.device_count  1
sklearn version: 1.2.0
plotly version: 5.11.0

```
* OS
```
$ hostnamectl

 Static hostname: --
       Icon name: computer-laptop
         Chassis: laptop
      Machine ID: --
         Boot ID: --
Operating System: Ubuntu 22.04.1 LTS              
          Kernel: Linux 5.15.0-56-generic
    Architecture: x86-64
 Hardware Vendor: --

```
* GPU
```
$ nvidia-smi -q

==============NVSMI LOG==============

Timestamp                                 : Sat Dec 17 13:27:52 2022
Driver Version                            : 520.61.05
CUDA Version                              : 11.8

Attached GPUs                             : 1
GPU 00000000:01:00.0
    Product Name                          : NVIDIA RTX A2000 8GB Laptop GPU
    Product Brand                         : NVIDIA RTX
    Product Architecture                  : Ampere

```




