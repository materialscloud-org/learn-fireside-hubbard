# learn-fireside-hubbard

This is a tutorial for density-functional theory (DFT) with extended Hubbard functionals (DFT+U+V) where U and V are on-site and inter-site Hubbard parameters. The DFT+U+V tutorial is based on the open-source [Quantum ESPRESSO distribution](https://www.quantum-espresso.org/) (QE)[1,2].

Quantum ESPRESSO is already installed in the Quantum Mobile (see below), a virtual machine (VM) that can run on any Windows, Mac, or Linux laptop/desktop.

# Using the Quantum Mobile Virtual Machine

The setup of the Quantum Mobile requires you to download the [Quantum Mobile image](https://github.com/marvel-nccr/quantum-mobile/releases/) (we use the v21.06.04 release) and the open-source Virtual Box (VBox) virtualizaton software. In order to import the image inside VBox, please refer to [this documentation](https://docs.oracle.com/cd/E26217_01/E26796/html/qs-import-vm.html).

NOTE: If you are running this tutorial on a laptop, beware that some manufacturers disable the Virtualization technology at the BIOS level. This feature can be reactivated, but we would advise against doing it yourself unless you know exactly what you are doing, and it might be wiser to install Quantum ESPRESSO v6.7 natively on your machine - for this, [see instructions](https://www.quantum-espresso.org/Doc/user_guide.pdf)

# Exercises

 - [Exercise 1](1_DFT/README.md): Standard DFT calculation

## Bibliography
1. P. Giannozzi, S. Baroni, N. Bonini, M. Calandra, R. Car, C. Cavazzoni, D. Ceresoli, G. L. Chiarotti, M. Cococcioni, I. Dabo, et al., Journal of physics: Condensed matter 21, 395502 (2009).
2. P. Giannozzi, O. Andreussi, T. Brumme, O. Bunau, M. B. Nardelli, M. Calandra, R. Car, C. Cavazzoni, D. Ceresoli, M. Cococcioni, et al., Journal of Physics: Condensed Matter 29, 465901 (2017).
