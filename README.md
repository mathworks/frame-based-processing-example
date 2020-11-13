The Simulink file and dependencies used as an example in the "Improving Simulation Performance with Frame-Based Processing" video.

To get started, launch "Audio_Signal_Processing.slx". 

Frame-based processing can be used in Simulink models to accelerate simulations and mimic the behavior of real-time systems. Paired with DSP System Toolbox, signal processing blocks can be configured to create and operate on frames of data, allowing for multiple sequential samples to be handled in a single timestep. 

Experiment with the effects of differing signal frame sizes by modifying the "Samples per audio channel" parameter of the From Multimedia File block. Sample time colors and signal dimensions are enabled under the Information Overlays menu to reflect the frame-based changes you make. Simulation performance can be evaluated with the Simulink Profiler tool located under Debug>Performance Advisor>Simulink Profiler.

[![View Frame-Based Processing Video Example Files on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/82773-frame-based-processing-video-example-files)

