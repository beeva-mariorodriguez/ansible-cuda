cuda
====

install nvidia CUDA

Requirements
------------

none

Role Variables
--------------

* ``install_cudnn``: install cudnn packages (detailed instructions bellow). default: False

cudnn
-----

you must download cudnn packages from developer.nvidia.com:
* libcudnn6_6.0.21-1+cuda8.0_amd64.deb
* libcudnn6-dev_6.0.21-1+cuda8.0_amd64.deb
* libcudnn6-doc_6.0.21-1+cuda8.0_amd64.deb

and copy the files to files/cudnn/ 

to download the files you must register as nvidia developer and accept the license


Dependencies
------------

none


License
-------

BSD

Author Information
------------------

Mario Rodríguez

