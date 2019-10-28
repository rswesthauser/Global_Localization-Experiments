# Global_Localization-Experiments

Topic: Global localization for drones, using a satellite image as a map, and inputs from a drone camera.

Datasets: I have 3 datasets, consisting of images and coordinates (ground truth), each one representing a flight.

Current scenario: In the application, there are 5 parameters that need to be reworked as I usually vary it in a way that seemed coherent but learned to be wrong. An example would be a certain parameter ranging from 0 to 1, which I have tested in steps of 0.2. In addition, I have done some experiments varying one parameter and leaving the others fixed.

First steps: Change the design of the experiments, seeking to cover a larger universe of configurations, reducing redundancy.

Computation and display: I will process and display the results using ggplot, while leaving everything documented (I currently do in python with mathplotlib).
