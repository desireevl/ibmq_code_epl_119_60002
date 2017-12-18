# ibmq_code_epl_119_60002
QASM files that were used to generate the results for the publication
'Implementing a distance-based classifier with a quantum interference circuit'
by Schuld, Fingerhuth and Petruccione (2017). The article was published on December 1st 2017
and is one of EPL 2017 Editor's Choice articles.

Article DOI:
https://doi.org/10.1209/0295-5075/119/60002

arXiv link:
https://arxiv.org/pdf/1703.10793.pdf

# How to make use of this repository?

The files are written in quantum assembly language (QASM), which is the programming language used by the online interface
of the IBM Quantum Experience. In order to execute these files you have to make an account with the IBM Quantum Experience,
start a new Experiment and then simply copy & paste the code from one of the two QASM files into the QASM Editor in the IBM
online interface. Then you can either simulate or run the defined quantum circuit on the actual chip.

NOTE: These QASM files were specifically written for the ibmqx2 bowtie chip with 5 qubits.

This repository contains the following two files:
*x0_class0_classification.qasm*
> This file implements the classification of the input vector x' as discussed in the EPL publication.

*x1_class0_classification.qasm*
> This file implements the classification of the input vector x'' as discussed in the EPL publication.

If you happen to use this code please cite our paper:

@article{qdbcl,
  author={M. Schuld and M. Fingerhuth and F. Petruccione},
  title={Implementing a distance-based classifier with a quantum interference circuit},
  journal={EPL (Europhysics Letters)},
  volume={119},
  number={6},
  pages={60002},
  url={http://stacks.iop.org/0295-5075/119/i=6/a=60002},
  year={2017},
 }

*The code is published open-source under a standard MIT License. Feel free to download, modify, use and multiply!*
