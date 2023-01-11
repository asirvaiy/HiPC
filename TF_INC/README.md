# Steps to run the Intel optimized TensorFlow and Intel Neural Compressor sample

1. Open the terminal and activate the oneAPI from source. 
   <br /> source /opt/intel/oneapi/setvars.sh
   
2. Now To create the environment with TensorFlow and Neural Compressor, run 
   <br /> bash intelai-hipc2022/handson/TensorFlow_INC/pip_set_env.sh
   
3. Once env creation is finished. It should create a kernal for jupyter, inc_tf
4. Open the notebook and all the cells one by one, 
<br />intelai-hipc2022/handson/TensorFlow_INC/inc_tensorflow_sample.ipynb 
    
      








# Intel® Neural Compressor Sample for TensorFlow*

Low-precision optimizations can speed up inference. You can achieve
higher inference performance by converting the FP32 model to INT8 or
BF16 model. Additionally, Intel&reg; Deep Learning Boost technology in
the Second Generation Intel&reg; Xeon&reg; Scalable processors and
newer Xeon&reg; processors provides hardware acceleration for INT8 and
BF16 models.

Intel&reg; Neural Compressor simplifies the process of converting the
FP32 model to INT8/BF16.

At the same time, Intel&reg; Neural Compressor tunes the quanization
method to reduce the accuracy loss, which is a big blocker for
low-precision inference.

Intel&reg; Neural Compressor is part of Intel&reg; AI Analytics
Kit (AI Kit) and works with Intel&reg; Optimizations for TensorFlow*.

Refer to the official web site for detailed information and news:
[https://github.com/intel/neural-compressor](https://github.com/intel/neural-compressor).


## Purpose

This sample shows the whole process of building a convolutional neural
network (CNN) model to recognize handwritten numbers and increasing
the inference performance by using Intel&reg; Neural Compressor.

We will learn how to train a CNN model with Keras and TensorFlow,
use Intel&reg; Neural Compressor to quantize the model, and compare the
performance to see the benefit of Intel&reg; Neural Compressor.


## Prerequisites

| Optimized for                     | Description
|:---                               |:---
| OS                                | Linux* Ubuntu* 18.04 or later, Windows 10*
| Hardware                          | The Second Generation Intel&reg; Xeon&reg; Scalable processor family or newer Xeon&reg; processors
| Software                          | Intel&reg; AI Analytics Toolkit 2021.1 or later
| What you will learn               | How to use Intel&reg; Neural Compressor tool to quantize the AI model based on TensorFlow* and speed up the inference on Intel&reg; Xeon&reg; CPUs
| Time to complete                  | 10 minutes





## Key Implementation Details

- Use Keras from TensorFlow* to build and train a CNN model.


- Define a function and class for Intel&reg; Neural Compressor to
  quantize the CNN model.

  The Intel&reg; Neural Compressor can run on any Intel&reg; CPU to
  quantize the AI model.

  The quantized AI model has better inference performance than the
  FP32 model on Intel CPUs.

  Specifically, the Second Generation Intel&reg; Xeon&reg; Scalable
  processors and newer Xeon&reg; processors provide hardware
  acceleration for such tasks.


- Test the performance of the FP32 model and INT8 (quantization) model.


## Prepare Software Environment



   
    

  



## License

Code samples are licensed under the MIT license. See
[License.txt](https://github.com/oneapi-src/oneAPI-samples/blob/master/License.txt)
for details.

Third party program Licenses can be found here:
[third-party-programs.txt](https://github.com/oneapi-src/oneAPI-samples/blob/master/third-party-programs.txt)
