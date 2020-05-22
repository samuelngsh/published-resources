These design files are the exact designs used for in the publication "SiQAD: A Design and Simulation Tool for Atomic Silicon Quantum Dot Circuits" (open access, [link](https://ieeexplore.ieee.org/document/8963859)).

Notes:

* All designs have been tested to work on [SiQAD v0.2.0](https://github.com/siqad/siqad/releases/tag/v0.2.0). They should in principle continue to work in later SiQAD versions barring major changes in the ground state model.

* If you don't see any design when opening the files in SiQAD, you should be able to locate them by zooming out a little. This is caused by the way SiQAD handles different screen sizes and resolutions.

* The mu setting is embedded in the filenames. e.g. `or_mu28.sqd` refers to the OR gate with mu = -0.28.

* For all designs, `lambda_TF = 5 nm` and `epsilon_r = 5.6` as stated in the SiQAD paper.

* All of the input perturbers are present. Toggle through different input configurations by deleting the input perturbers.

* As stated in the SiQAD paper, it is expected that further adaptations are required when the gates/circuits are incorporated in larger systems.
