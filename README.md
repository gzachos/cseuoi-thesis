# cseuoi-thesis

Repository for my thesis authored in partial fulfillment of the requirements for the Diploma of Engineering degree at the [Department of Computer Science and Engineering](https://www.cse.uoi.gr),
[School of Engineering](https://engineering.uoi.gr/), [University of Ioannina](https://www.uoi.gr/). 


## Abstract
[George Z. Zachos](https://gzachos.com), Diploma, Department of Computer Science and Engineering,
School of Engineering, University of Ioannina, Greece, September 2021.

___Topology and synchronization in OpenMP for NUMA manycore systems.___

Advisor: [Vassilios V. Dimakopoulos](https://www.cse.uoi.gr/~dimako/), Associate Professor.

The growing need for more processing power has led to the proliferation of _non-uniform
memory access_ (NUMA) systems which constitute the architectural evolution
of _symmetric multiprocessors_ (SMPs) and can be equipped with a large number of
processing cores. These systems provide a shared-address space and therefore can
be programmed using widespread _application programming interfaces_ (APIs) such as
the OpenMP API. Due to the complex architectural organization of NUMA systems,
achieving the best possible performance usually requires using information related
to the topology of the underlying system, that is, information about how its hardware
is organized. Since version 4.0 of the OpenMP specification, topology-related
features such as _OpenMP places_ and _OpenMP processor binding policies_ have beed introduced
in order to allow users to control the assignment of threads to the available
processing elements. In the context of this diploma thesis, the OpenMP places and
OpenMP processor binding policies primitives were fully implemented. In addition,
synchronization functions, specifically barriers, were redesigned to function efficiently
on large NUMA systems.


## Modification Notes
This text was based on this [unofficial XeLaTeX template for Diploma theses](https://github.com/gzachos/thesis-template-uoi).


## Thesis Text (in Greek)
 - [Hosted on paragroup.cse.uoi.gr](https://paragroup.cse.uoi.gr/publications/files/187zachos2021.pdf)
