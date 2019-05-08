## [Pawpyseed: A parallelized Python/C package to aid in density functional theory point defect calculations via utilities for band shifting corrections]({{ site.baseurl }}/documents/undergraduate_thesis.pdf)

Significant progress has been made recently in the automation and standardization
of ab initio point defect calculations in the form of improved formation
energy corrections for charged defects and workflow software to aid in
calculation setup and post-processing. However, the task of developing, implementing,
and benchmarking charge corrections for density functional theory (DFT) point defect calculations
is still an open challenge. To contribute to this goal, a parallelized Python and C package called pawpyseed
is developed to perform numerical analysis of DFT
wavefunctions in the projector augmented wave (PAW) formalism. The utilities
contained in the code can be used to perform perturbative band shifting
corrections for point defect calculations. The theory and implementation
of pawpyseed for this application is discussed, and other potential applications
of the code are mentioned briefly in the discussion. In addition,
various correction methods, including a perturbative band shifting
method implemented using pawpyseed, are used to calculate the
formation energies and transition levels of several point
defects in silicon (phosphorous, boron, sulfur, and copper
substitutionals and the single vacancy). The transition level predictions are compared to
each other as well as previous experimental and theoretical data.
A discussion of the correction methods is presented in the context of
the studied defects, and hypotheses are presented for
errors for different correction methods. Possible
future developments of corrections for high-throughput
point defect calculation workflows are discussed.

## Notes

I wrote this thesis under the supervision of Mark Asta (Materials Science and Engineering, UC Berkeley)
and with valuable feedback from my PhD student advisor, Danny Broberg.

If you use information
in the paper or the code ([pawpyseed](https://github.com/kylebystrom/pawpyseed))
for research in a scientific publication, please cite the arxiv paper on pawpyseed
(which is more concise than my thesis and contains better-developed data and results):

```
@ARTICLE{2019arXiv190411572B,
       author = {{Bystrom}, Kyle and {Broberg}, Danny and {Dwaraknath}, Shyam and
         {Persson}, Kristin A. and {Asta}, Mark},
        title = "{Pawpyseed: Perturbation-extrapolation band shifting corrections for point defect calculations}",
      journal = {arXiv e-prints},
     keywords = {Condensed Matter - Materials Science},
         year = "2019",
        month = "Apr",
          eid = {arXiv:1904.11572},
        pages = {arXiv:1904.11572},
archivePrefix = {arXiv},
       eprint = {1904.11572},
 primaryClass = {cond-mat.mtrl-sci},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2019arXiv190411572B},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}

```

You can view the paper at <https://arxiv.org/abs/1904.11572>.
