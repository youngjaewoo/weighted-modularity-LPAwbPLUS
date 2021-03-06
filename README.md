[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.34055.svg)](http://dx.doi.org/10.5281/zenodo.34055)

weighted-modularity-LPAwbPLUS
=============================

Two algorithms for finding modularity in bipartite networks are presented: LPAwb+ and DIRTLPAwb+.

These are based on the LPAb+ algorithm of Liu & Murata, 2010 for use on bipartite/two-mode networks. The algorithm has been modified such that the weighted modularity of a network can be found (note that the result is equivalent to that found by the LPAb+ algorithm if the network is binary). Code is currently available for Julia, MATLAB/Octave and R langauges.

For details of the methods please [view the draft paper](https://github.com/sjbeckett/weighted-modularity-LPAwbPLUS/blob/master/paper/weightedModularityDraft.pdf?raw=true) (in the 'paper' directory), or in Beckett, 2016.






Usage
---------

Language specific instructions are included with the code.
Source the relevant code in your favourite language; then run


```julia

LPA_wb_plus(MATRIX) # find labels and weighted modularity using LPAwb+


```
where MATRIX is the incidence/biadjacency matrix describing the input network. Three outputs are returned: `redlabels` - the module labels for each row in the input matrix, `bluelabels` - the module labels for each row in the input matrix and `Q` - the modularity score.

Code for plotting modular structure is also provided. Please view the REAME files within the relevant code folder to learn more about computing modularity using LPAwb+ and DIRTLPAwb+.




Details
---------
<br>
The paper describing these algoirithms is now published:

Beckett S.J. 2016. [Improved community detection in weighted bipartite networks](http://dx.doi.org/10.1098/rsos.140536). Royal Society Open Science 3: 140536.
<br><br><br>

For details of the LPAb+ algorithm please see [Liu & Murata, 2010](https://www.fujipress.jp/finder/xslt.php?mode=present&inputfile=JACII001400040010.xml) .

Liu X., Murata T. 2010. An Efficient Algorithm for Optimizing Bipartite Modularity in Bipartite Networks. Journal of Advanced Computational Intelligence and Intelligent Informatics (JACIII) 14(4): 408-415.

This repository has been archived using [Zenodo](https://zenodo.org/) and has been assigned DOI: [10.5281/zenodo.34055](http://dx.doi.org/10.5281/zenodo.34055).
If you use LPAwb+ or DIRTLPAwb+ please cite this repository or the accompanying paper when it becomes available.


Change notes
---------

Click [here](https://github.com/sjbeckett/weighted-modularity-LPAwbPLUS/blob/master/changelog.md) to view notes of changes between release versions.



Contact
--------

This package is authored by Stephen Beckett ([@BeckettStephen](https://twitter.com/BeckettStephen)). If you have any questions please contact me!
