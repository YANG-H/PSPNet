# by Hao Yang

- [x] Current linking errors are caused by the lack of gcc-5 built `libhdf5*` version 10 so files. There are libhdf5.so.10 files in anaconda, but they are not built with gcc-5.
  -  Solutions: A. not use matcaffe; B. try using a MATLAB version compatible with Caffe.
