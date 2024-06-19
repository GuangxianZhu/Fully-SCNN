# Fully-SCNN
An example of SC-FCNN on MNIST. This work is an un-offical implementation of paper: Dynamic Energy-Accuracy Trade-off Using Stochastic Computing in Deep Neural Networks. We use full-SC process, all values are representated as bit-stream. and got result acc = 97.2%.

The first work implement end-to-end PyTorch capable SC process.

# Features
1. Fully-LFSR based SNG, all behavior of hardware are simulated.
2. An end-to-end process using real bit-stream for calculation.
3. All Calculation of SC is implementated, using real XNOR, APC, etc. operation.
