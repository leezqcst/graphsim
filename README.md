graphsim
--------

Graph similarity algorithms based on NetworkX.

**BSD Licensed** 

[![Build Status](https://travis-ci.org/caesar0301/graphsim.svg?branch=master)](https://travis-ci.org/caesar0301/graphsim)


Install
-------

First, install building tool:

    $ yum install -y scons

On Mac OS:

    $ brew install scons

Then install graphsim via PyPI:

    $ pip install -U graphsim

**Permission Issue:** `sudo` is required to give permission to install cpp modules into /usr/local/{lib,include}. 


**NOTE**: `libtacsim` was tested on Ubuntu 12.04, Ubuntu 16.04, CentOS 6.5 and Mac OS 10.11.2.


Usage
-----

    >>> import graphsim as gs


Supported algorithms
--------------------

* `gs.ascos`: Asymmetric network Structure COntext Similarity, by Hung-Hsuan Chen et al.
* `gs.nsim_bvd04`: node-node similarity matrix, by Blondel et al.
* `gs.hits`: the hub and authority scores for nodes, by Kleinberg.
* `gs.nsim_hs03`: node-node similarity with mismatch penalty, by Heymans et al.
* `gs.simrank`: A Measure of Structural-Context Similarity, by Jeh et al.
* `gs.simrank_bipartite`: SimRank for bipartite graphs, by Jeh et al.
* `gs.tacsim`: Topology-Attributes Coupling Similarity, by Xiaming Chen et al.
* `gs.tacsim_combined`: A combined topology-attributes coupling similarity, by Xiaming Chen et al.
* `gs.tacsim_in_C`: an efficient implementation of TACSim in pure C.
* `gs.tacsim_combined_in_C`: an efficient implementation of combined TACSim in pure C.


Supported utilities
-------------------

* `gs.normalized`: L2 normalization of vectors, matrices or arrays.
* `gs.node_edge_adjacency`: Obtain node-edge adjacency matrices in source and dest directions.

Citation
----------

```tex
@article{Chen2017,
  title = "Discovering and modeling meta-structures in human behavior from city-scale cellular data",
  journal = "Pervasive and Mobile Computing ",
  year = "2017",
  issn = "1574-1192",
  doi = "http://dx.doi.org/10.1016/j.pmcj.2017.02.001",
  author = "Xiaming Chen and Haiyang Wang and Siwei Qiang and Yongkun Wang and Yaohui Jin"
}
```

Author
------

Xiaming Chen <chenxm35@gmail.com>
