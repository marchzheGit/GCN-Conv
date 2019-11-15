# GCN-Conv

This repo provides the C source code for the GCN convolution layer based on [PyG](https://github.com/rusty1s/pytorch_geometric) implementation. 

The implementation is evaluated on 3 popular citation graph benchmarks: CORA, CiteSeer, and PubMed.

The evaluation is carried out on a Xeon E5-2680 CPU, and the performance on single thread are:

CORA: 354.5 ms

CiteSeer: 953.1 ms

PubMed: 733.8 ms

