# DLC-apptainer

The apptainer.def file contains the definition file to build an apptainer container for DeepLabCut to put on the DCCN High Performance Computer.

To build the container:
```{bash}
apptainer build apptainer deeplabcut.sif apptainer.def
```

and uploaded to `/opt/deeplabcut/{VERSION}/deeplabcut.sif` on the HPC. 

Currently maintained by @grandjeanlab. 

