# Current release v.0.1.5 (June 2023)
https://github.com/JeremyMain/ngputop/releases

# Background
For the past ~~two~~ **several** years, I have been **slowly** improving the features of GPUProfiler for Windows environments and often heard requests for a tool like that for Linux, or even a monitor to give users greater and immediate insight into what GPU features are doing. I wanted a tool like this and so I just started making it.

# Features of ngputop
Display that utilization of GPU resources for all NVIDIA GPUs detected in a bare-metal machine, some hypervisor hosts (XenServer, RHEL RHV, ESXi) or virtual machines* 
(*see limitations)

UI Example - Graphics view mode
![Example UI Screenshot of 'Graphics' view mode](https://i.imgur.com/j0OEmnX.png)

Inferencing on a Ubuntu vGPU VM
![Inferencing on an Ubuntu vGPU VM](https://i.imgur.com/EzJXoKl.jpg)

# View Modes
ngputop currently has two view modes, "compute" and "graphics". 
Each view displays more or less data based on the typical utilization metrics each use case is interested in observing.

# Compute View (default)
![Compute mode view - default](https://i.imgur.com/XwapV04.png)

Compute mode displays for each detected NVIDIA GPU the following 'gauges':

SM: Shader-Module utilization

FB: Frame buffer utilization

CL: SM Clock

PW: Power consumption

TP: GPU temperature in Celsius

FN: Fan speed (% of maximum) 

# Graphics View
![ngputop 'Graphics' view example screenshot](https://i.imgur.com/j0OEmnX.png)

The Graphics mode displays for each detected NVIDIA GPU the following 'gauges'

SM: Shader-Module utilization

FB: Frame buffer utilization

MC: Memory controller utilization

EN: Encoder utilization

DE: Decoder utilization

PW: Power consumption

TP: GPU temperature in Celsius

# Project Wiki
https://github.com/JeremyMain/ngputop/wiki
