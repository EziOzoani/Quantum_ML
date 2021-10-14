# Quantum_kNN

Files:
Angle Encoding: Uses U gate feature mapping. It calles datasets using sklearn.

Amplitude encoding

KNN : Where the bones of the Algorithm  is.

----------------------------------------------------------------------------------------


# Why

My original aim was to explore Quantum computing in the financial space, this then shifted to wanting to creaate a quantum recommenender system to illustrate the commercial capabilities of quantum machines.
During my research into quantum programmign I realised that outisee of basic circuit buidling proivded by Qiskit the information needed to build a full Quantum Machine learning circuit was distributed amongst different physics based research publications. These publications (some of which are explored more [here]), mostly do not explore all three stages of a quantum machine learnign cirucit 

    - Data encoding: how do you get a quantum computer to read classical data 🤔
    - Quantum Algothims: psst I provide 3 algothims and different apparoaches for each 🤫
    - Quantum Machine execution: Due to the ever evolving nature of quantum computing, some publicaitons could either only theorise possible results or preform their algorithm executions on a quantum simulator. The latter is due to the previous lack of quantum computers or the lack of quantum machines large enough to perform their circuit executions. 

# Aim

I aim was to provide not only a central location with illustrative and deatiled code for how to implement a quantum machine learning circuit, I also aimed to provide a modular approach to each step in the quantum machine learning circuit

- The first and the most important aim is to provide a circuit with all three stages of a quantum machine learning circuit (data encoding, quantum algothim and quanutm machine learning exection) with modular components in an accessible form. This enables future development on this work to be easy and approachable, particularly for quantum enthusiasts and those more literate in software development than in quantum physics. To do so, the necessary python code is presented in a technical manner where detailed knowledge of quantum physics would not be necessary. However, the basic quantum theoretical knowledge will be explained in a concise and austere style

  
 - For the algorithm stage of the circuit, a full quantum machine learning implementation of k-Nearest Neighbour is detailed based on the descriptions detailed in the work 'Algorithm for k-Nearest Neighbours Classification based on the Metric of Hamming Distance' [Sharma, 2020]. Two variations of Grover’s Search algorithm and QSVM are also explored, these are delivered through illustrative and succinct implementations.
    
 -  In order to run classical data on a quantum circuit, quantum readable data is required. Existing data encoding methods, both theoretical and implemented, are dispersed across various research publications. My work presents different methods for data encoding both the circuit design and the code in a centralised location.
 
 -  Finally, bench-marking is performed on the aforementioned quantum machine learning algorithms and their classical counterparts. In addition to the quantum computer execution, my work details an external classical quantum based simulator, the JKU simulator, its advantages, current state and the necessary implementation. These measurement techniques allow for a critical review of the circuit results, for the different circuit components
 
   
