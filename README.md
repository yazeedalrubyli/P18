# Performance Impact Investigation of Tensorflow, Tensorflow Lite and Tensorflow Mobile

## Description
In this project, all three versions of Tensorflow(Normal, Lite, Mobile) will be compiled and installed from source files to take advantage of the instructions available from the actual CPU on the system. The goal is to develop some benchmarks that can point out the differences between the versions of the framework. The main differences of interests are:
1. Execution performance on modern consumer-grade CPUs.
2. Size of the models generated by the frameworks.
3. Accuracy of the model if there is any degradation in one of the frameworks. 

> All of the measurements must be acquired during the inference phase, not training.

* Compare different neural networks under different frameworks.
* Assess the complexity of the network benchmarks in terms of:
    * Runtime memory requirements.
    * Estimated model size and GFlops (gigafloating operations per seconds) complexity. 

> At the end a set of scripts must be able to run all the benchmarks developed on different platforms. If possible (available), results should include multiple machines (CPUs or GPUs).

---

## References
* https://www.tensorflow.org/mobile/tflite/ 
* https://www.tensorflow.org/mobile/mobile_intro 
* https://www.tensorflow.org/install/install_sources
