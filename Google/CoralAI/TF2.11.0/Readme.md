*Coral AI* (*TensorFlow* ***2.11.0***) binaries (for *Python*)
--------------------------------------------------------------

**Tools** (almost everyone required manual interventions - mostly regarding paths and (dependant tools) versions):

- *TensorFlow*:
    - Sources downloaded from [[GitHub]: tensorflow/tensorflow - (v2.11.0) TensorFlow](https://github.com/tensorflow/tensorflow/tree/v2.11.0)

- *LibEdgeTPU*:
    - Sources downloaded from [[GitHub]: google-coral/libedgetpu - Edge TPU runtime library (libedgetpu)](https://github.com/google-coral/libedgetpu) (**commit *ddfa7bde33c23afd8c2892182faa3e5b4e6ad94e***)
    - Fixed a bug in *api/allocated\_buffer.h* (missing *#include*)
    - Built with *CMake*
    - Using **statically built** versions of *Abseil-CPP*, *FlatBuffers* (see below)

- *LibCoral*:
    - Sources downloaded from [[GitHub]: google-coral/libcoral - libcoral](https://github.com/google-coral/libcoral) (**commit *6589d0bb49c7fdbc4194ce178d06f8cdc7b5df60***)
    - *Eigen* API change bugs fixed

- *PyCoral*:
    - Sources downloaded from [[GitHub]: google-coral/pycoral - PyCoral API](https://github.com/google-coral/pycoral) (**commit *ae743b0b234d66d784826ccfbb4607a69dc1a2a8***)

**Additional tools**:

- *Abseil-CPP*: *20220623.1*
- *FlatBuffers*: *v22.10.26*
- *Python* related:
    - *NumPy*:
        - *Python* *3.7* - *3.10*: *v1.21.2*
        - *Python* *3.11*: *v1.23.2*
    - *PyBind11*: *v2.10.3*

**Platforms**:
- *Linux*

