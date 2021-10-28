
1. Clone the MPTCP's repository

``` 
git clone https://github.com/mkheirkhah/mptcp.git
```

2. Configure and build 

``` 
CXXFLAGS="-Wall" ./waf configure build 
```

3. Run a simulation

``` 
./waf --run "mptcp"
```

# Simulations

A simple simulation script is available [here](./scratch/).

# Contact

```
Morteza Kheirkhah, University College London (UCL), m.kheirkhah@ucl.ac.uk
```

# How to reference this source code?

If you use this source code in part or entirely, please refer to it
with the following bibtex:

```
@article{kheirkhah2015multipath,
  author  = {Kheirkhah, Morteza and Wakeman, Ian and Parisis, George},
  title   = {{Multipath-TCP in ns-3}},
  journal = {CoRR},
  year    = {2015},
  url     = {http://arxiv.org/abs/1510.07721},
  archivePrefix = {arXiv},
}
```


