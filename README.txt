Build for 

precision-7530 Notebook
Host bridge
product: 8th Gen Core Processor Host Bridge/DRAM Registers

  description: CPU
          product: Intel(R) Xeon(R) E-2186M  CPU @ 2.90GHz
          bus info: cpu@0
          version: Intel(R) Xeon(R) E-2186M  CPU @ 2.90GHz



 +-----------------------------------------------------------------------------+
| NVIDIA-SMI 440.64.00    Driver Version: 440.64.00    CUDA Version: 10.2     |
|-------------------------------+----------------------+----------------------+
| GPU  Name        Persistence-M| Bus-Id        Disp.A | Volatile Uncorr. ECC |
| Fan  Temp  Perf  Pwr:Usage/Cap|         Memory-Usage | GPU-Util  Compute M. |
|===============================+======================+======================|
|   0  Quadro P2000        On   |
                                                                               


run:
./bazel-bin/tensorflow/tools/pip_package/build_pip_package /tmp/tensorflow_pkg
pip3 install /tmp/tensorflow_pkg/tensorflow-version-tags.whl


https://www.tensorflow.org/install/source
