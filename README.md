## Introduction

This repository collects examples of training Deep Learning models on SageMaker, and demonstrates how SageMaker Debugger/Profiler
can help in monitoring, troubleshooting and performance optimization.

Ok those are big words and for now the examples are very limited to say the least...
I hope I can can improve on them in the next few months as I'm learning how use these tools to optimize models.


* `examples/1-traditional-way.ipynb` - the "traditional way" of training a model on a notebook
* `examples/2-train-job.ipynb` - the recommended way by SageMaker - launching a training job outside the notebook
* `examples/3-train-profile-debug` builds on the previous examples and enables debugger/profiler capabilities


### How to reproduce?

* Open your AWS Console -> SageMaker
* Start SageMaker Studio
* Copy the examples/ folder into a _subfolder_ (like `examples/`).
  Important because SageMaker uploads the folder in which your training script is located
  when you start a training job. You don't want to copy the root folder.
