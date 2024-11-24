# Community detection algorithms: FLPA and LPA - A Complex Network Project
This project compares the synchronous Label Propagation Algorithm (LPA), asynchronous LPA, and the Fast Label Propagation Algorithm (FLPA) in terms of speed and clustering quality. The analysis includes synthetic networks Erdos-Rényi, Barabási-Albert, Forest Fire, and Stochastic Block Model. Empirical networks are also tested, comparing algorithms on small networks with known partitions using NMI and large networks using modularity. 

## Requirements
Please be sure to have installed the following python packages:
- networkx
- timeit
- numpy
- random
- matplotlib.pyplot
- tqdm

## Code Description
- **1.ER_withFLPAandLPA**: Evaluating computational time for the FLPA, Asyn. LPA, Syn. LPA acting on ER synthetic networks.
- **2.BA_withFLPAandLPA**: Evaluating computational time for the FLPA, Asyn. LPA, Syn. LPA acting on BA synthetic networks.
- **3.ForestFire_withLPAandFLPA**: Evaluating computational time for the FLPA, Asyn. LPA, Syn. LPA acting on Forest Fire synthetic networks.
- **4.SBM_mix_param**: Evaluating computational time for the FLPA, Asyn. LPA, Syn. LPA acting on SBM synthetic networks.
- **5.SBM_NMI**: Evaluating the NMI for the FLPA, Asyn. LPA, Syn. LPA acting on SBM synthetic networks.
- **6.NMI_smallEmpNet**: Evaluating the NMI for the FLPA, Asyn. LPA, Syn. LPA acting on three small empirical networks with a known sociological division of nodes into communities.
- **7.FLPA_LPA_EmpNet**: Evaluating computational time and Modularity for the FLPA, Asyn. LPA, Syn. LPA acting on six large empirical network.

