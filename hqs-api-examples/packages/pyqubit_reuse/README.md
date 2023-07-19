&copy; 2023 by Quantinuum. All Rights Reserved. The software code included in this repository is exclusively for users and/or organizations having H-Series hardware and/or emulator access and to be used solely with the H-Series hardware and/or emulators. Do not distribute to a third-party that’s not affiliated with your organization any software code included in this repository without prior written permission of Quantinuum.

# Qubit Reuse

This repository provides a `pytket` compiler pass for applying the compilation strategy for reducing the number of qubits in a quantum circuit as detailed in [Qubit-reuse compilation with mid-circuit measurement and reset](https://arxiv.org/abs/2210.08039) by Matthew DeCross, Eli Chertkov, Megan Kohagen and Michael Foss-Feig.

`pytket` is a python module for interfacing with `TKET`, a quantum computing toolkit and optimising compiler developed by Quantinuum, and is available through `pip`. `pytket` is open source and documentation and use examples can be found at the [github repository](https://github.com/CQCL/pytket) and in Jupyter notebooks in the 
*Examples* tab on the [Quantinuum User Portal](https://um.qapi.quantinuum.com/).

## Installation

Please download a wheel that matches your environment from the `releases` folder and install it with `pip install <wheel-name>`. 

To download a wheel file, click the *Download* button to download the full set of user portal examples and navigate to the folder, rather than clicking on a file in the portal as this will cause an user portal error.

**Note:** It's important that your version of `pytket` exactly match the installation requirement. This should automatically be taken care of, but if you later update `pytket` after installing `pyqubit_reuse`, then it may cause issues. We will endeavour to make sure that the `pyqubit_reuse` package wheels are updated as new `pytket` releases are made, but it is possible at times they may not be aligned.

## Example

An example notebook showing how to use the `pytket` compiler pass for qubit reuse is provided in this folder.

## How to Cite

If you wish to cite the `pyqubit_reuse` package in any academic publications, we recommend citing our paper [Qubit-reuse compilation with mid-circuit measurement and reset](https://arxiv.org/abs/2210.08039).