# QuanTrans: Transforming Quantum Circuits to Minimize Communication in Distributed Simulations

## Overview

Full-state quantum circuit simulations on classical computers are useful for designing and validating quantum algorithms. For better performance, distributed simulations have been proposed to fully utilize the multi-node parallel architecture.  Communication overhead used to be the performance bottleneck because when simulating a multi-level quantum circuit, data from the other nodes are involved at each level of simulation. A novel distributed framework called QuanPath manages to reduce the intermediate multi-level communication to one final merge step for circuits with specific structures. However, if some levels do not meet the requirements, QuanPath can only be applied to the sub-circuits, resulting in more merge operations at the end of each sub-circuit. Therefore, we propose two polynomial-time algorithms, namely QuanTrans, to transform the logical structures of circuits, so that the merge times are minimized. 

Experimental results show that QuanTrans retains the advantages of QuanPath, achieving hundreds of times of reduction in communication time, resulting in several times of acceleration in total simulation time compared with previous techniques, and further achieves up to 11.16$\times$ and 1.56$\times$ speedup in communication and simulation time over QuanPath. 

## Publication

[[pdf]]()

[[code]]()

[[slide]]()

