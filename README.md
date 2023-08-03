# llm-env (Large Language Model Environment)

There are two scripts for quick setup of llm model traing and serving on Ubuntu
* setup/gpu_training.sh
  - upgrade apt
  - install python 3.10
  - install CUDA
  - install conda
  - mount external storage
  - clone qlora
    
* setup/cpu_serving.sh:
  - upgrade apt
  - install python 3.10
  - install conda
  - mount external storage
  - clone llama.cpp
  - clone llam-cpp-python
