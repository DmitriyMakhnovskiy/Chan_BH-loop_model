This repository contains Python implementations of magnetic hysteresis models for simulating the nonlinear (B)-(H) behaviour of ferromagnetic cores. The programs include graphical user interfaces (GUIs) and are intended both for studying hysteresis models and for their practical application to magnetic-core and electromagnetic-actuator calculations.

The repository currently contains two main implementations:

Chan-Model-Symmetrical-BHloops ---> This folder contains an implementation of Chan's hysteresis model, a widely known analytical approach for describing the nonlinear magnetic behaviour of ferromagnetic cores. The model is used to generate symmetrical major and minor (B)-(H) hysteresis loops, where (B) is the magnetic flux density and (H) is the magnetic field intensity. The Python program provides a graphical interface for specifying the principal parameters of the magnetic material and excitation conditions and for calculating and visualizing the resulting hysteresis trajectories. The model reproduces the principal characteristics of ferromagnetic hysteresis, including coercivity, remanence, nonlinear magnetization, and magnetic saturation. Chan's model is particularly attractive for engineering calculations because it provides a relatively simple analytical representation of the hysteresis loop while retaining the essential nonlinear properties of a ferromagnetic material.

Chan-Engelhardt-Model-Symmetrical&Asymmetrical-BHloops ---> This folder contains an extended implementation based on the Chan–Engelhardt approach. In addition to symmetrical hysteresis loops, this version is intended to reproduce asymmetrical major and minor (B)-(H) loops arising from arbitrary magnetization histories and reversal points. The implementation extends the basic Chan model by introducing the procedures required to construct hysteresis trajectories after field reversals while preserving the memory of the preceding magnetic state. This makes the model more suitable for simulations in which the magnetic core is subjected to non-symmetrical excitation, DC bias, partial magnetization cycles, or arbitrary sequences of field reversals.

Both implementations are intended to provide computationally efficient hysteresis models that can subsequently be incorporated into simulations of magnetic circuits, transformers, inductors, solenoids, and electromagnetic actuators.

References

The original Chan model: https://ieeexplore.ieee.org/document/75630

A related application of Chan's model to the simulation of nonlinear transformers in LTspice: https://www.allaboutcircuits.com/technical-articles/simulating-non-linear-transformers-in-ltspice/

Patent US7502723 "Asymmetric minor hysteresis loop model and circuit simulator including the same": https://patents.google.com/patent/US7502723B1/en

Additional theoretical background on magnetic circuits, details of the hysteresis models, and examples of their application are provided in the accompanying PDF reports and PPT slide shows.
