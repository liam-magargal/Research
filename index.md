[<<Back to homepage](https://liam-magargal.github.io/Liam-Magargal/)

# Project Overview
A PhD student at the [University of Massachusetts Amherst](https://scholarworks.umass.edu/open_access_dissertations/516/) developed a program which uses lifting line theory to develop the wake of a wind turbine from given input parameters, such as wind vector, blade length, and blade aspect ratio. The project was then continued by a PhD student at [Lehigh University](https://preserve.lehigh.edu/etd/4247/) to include aeroelastic blades. After this was implemented, the results were studied in a stability analysis. The code still needed a significant amount of cleaning up, however.

# Progress
To start my research, I had to study lifting line theory, the Kutta-Joukowski theorem, and various different numerical methods in order to understand how the program functions, as I hadn't taken an aerodynamics class when I began the research. After familiarizing myself with the program, I began studying finite element analysis and vibrations in order to develop an aeroelastic structure in a related flapping wing program. By the end of summer, I was able to successfully implement an aeroelastic flapping wing to the code using Newmark's method, a differential equation solver and Aitken's method, a predictor-corrector method.
