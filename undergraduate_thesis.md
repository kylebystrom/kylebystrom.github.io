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
and with valuable feedback from my PhD student advisor, Danny Broberg. If you use information
in the paper or the code ([pawpyseed](https://github.com/kylebystrom/pawpyseed))
for research in a scientific publication, please cite it:

```
@article{pawpyseed,
  title = {Pawpyseed: A parallelized Python/C package to aid in density functional theory point defect calculations via utilities for band shifting corrections},
  author = {Kyle Bystrom},
  year = {2018},
  month = {Dec},
  url = {https://kylebystrom.github.io/undergraduate_thesis.html}
}
```

I hope to have a peer-reviewed publication on this work at some point, but for the time being
I just wanted to have it publicly accessible.