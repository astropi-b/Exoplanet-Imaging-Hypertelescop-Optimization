**Project Overview**

This project is a reproduction and exploration of the results from the paper "Optimization of a One Dimensional Hypertelescope for Direct Imaging in Astronomy" by Paul Armand, Joe ̈l Benoist, Elsa Bousquet, Laurent Delage, Serge Olivier, and François Reynaud. The primary goal is to find the optimal relative positions of the output pupils and the moduli of the beams through each pupil of a linear array of telescopes. This optimized design allows for the creation of a hypertelescope capable of imaging exoplanets.

The problem is modeled as a semi-infinite nonlinear minimization problem, which is transformed into a minimization problem with a finite number of constraints through simple discretization. This problem is then solved using a minimization solver implemented in Python's SciPy library.

The project involves a series of optimization cases, each with a different number of mirror pairs (referred to as "pupils") in the hypertelescope and a different range for the optimization parameters. The optimization parameters represent the relative positions and beam intensities of the pupils.

For each case, the optimization process is used to find the parameters that minimize the "dynamic" value (a measure of system performance) and maximize the "central flux" (a measure of the intensity of the central image).

The results of the optimization process for each case are displayed in tabular form and visualized with a graph, providing a clear and intuitive representation of the optimized hypertelescope design and its performance.

This work acknowledges the original authors Paul Armand, Joe ̈l Benoist, Elsa Bousquet, Laurent Delage, Serge Olivier, and François Reynaud for their valuable contributions in this field.
