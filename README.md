BookSim Interconnection Network Simulator (Modified to Support Multi-Layered Network-on-Chips Configurations)
=============================================================================================================

BookSim is a cycle-accurate interconnection network simulator.
Originally developed for and introduced with the [Principles and Practices of Interconnection Networks](http://cva.stanford.edu/books/ppin/) book, its functionality has since been continuously extended.
The current major release, BookSim 2.0, supports a wide range of topologies such as mesh, torus and flattened butterfly networks, provides diverse routing algorithms and includes numerous options for customizing the network's router microarchitecture.

We have modified the mesh routing and the topology to isolate the 3 dimnesions in a 3-D configuration, with each dimension having a separate number of nodes. Additionally, the latency can be independently set for each dimension, which could be used to reflect the vertical connections which are smaller and hence have reduced latency associated with them.

---

If you use BookSim in your research, we would appreciate the following citation in any publications to which it has contributed:

Nan Jiang, Daniel U. Becker, George Michelogiannakis, James Balfour, Brian Towles, John Kim and William J. Dally. A Detailed and Flexible Cycle-Accurate Network-on-Chip Simulator. In *Proceedings of the 2013 IEEE International Symposium on Performance Analysis of Systems and Software*, 2013.# booksim2-layered
