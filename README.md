# Regression-Discontinuity

RDにおいて重要なのはband-width selectionとcut offにおけるjumpの推定の精度です。
本レポではこの二点についてコードと手法を紹介します。


[CVでのband width selectionの簡単な実装](http://nbviewer.jupyter.org/github/keiikegami/Regression-Discontinuity/blob/master/RD%20-%20Julia.ipynb)

[Kernel Regressionの簡単な実装](http://nbviewer.jupyter.org/github/keiikegami/Regression-Discontinuity/blob/master/kernel%20Regression.ipynb)


とはいえ、実証研究において最も大事なのは**Fuzzy RDはIVである**という点ですので、Angristでちゃんと勉強しましょう。
