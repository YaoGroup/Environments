# Environments
This repo provides the environments suitable for running our ice codes on Della-gpu, group workstation, and your local machine

`cudatoolkit` is requrired for IAS's cluster (according to Yongji and Ray). Ray also tested and confirmed the cudatoolkit is also compatible with our workstation (though not required)

`cudann` is the toolbox needed to activate GPU for tensorflow

### Princeton Cluster
environment-cluster-tf24.yml: For running our code using Tensorflow 2.4 on Della-gpu


### Group Workstation
environment-wokstation-tf24.yml: For running our code using Tensorflow 2.4 on our workstation

environment-wokstation-tf115.yml: For running our code using Tensorflow 1.15 on our workstation

environment-wokstation-tf114.yml: For running the origional PINN code in Raissi (2019). It uses tf.contrib and thus too old for Tensorflow 1.15

## Local Machines (e.g. personal computer)
environment-win.yml: For running our code using Tensorflow 2.5 on a windows computer (Note that Tensorflow 2.4 wouldn't work on Windows)

environment-osx.yml: For running our code using Tensorflow 2.4 on a mac computer
