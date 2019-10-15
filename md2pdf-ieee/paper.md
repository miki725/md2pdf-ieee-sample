---
title: Basic Title
subtitle: Very Important Subtitle
author:
  - name: Miroslav Shubernetskiy
    affiliation: GameChanger
    location: New York
    email: example@gc.com
numbersections: yes
lang: en
bibliography: |
  @article{shell2019use,
    title={How to use the IEEEtran LATEX class},
    author={Shell, Michael},
    journal={IEEE Design \& Test},
    year={2019},
    publisher={IEEE}
  }
abstract: |
    This paper is a basic example with LaTeX metadata with IEEE template.
header-includes: |
  \usepackage{booktabs}

...

---

**Super** amazing article *here* about
[cats](https://www.pexels.com/search/cat/).
See @fig:cat.

Shell [@shell2019use] writes more about `IEEEtran` file.

![[amazing cat](http://bit.ly/2pilsGS)](cat.jpg){#fig:cat}

# References

---
nocite: '@*'
---
