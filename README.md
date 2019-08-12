# tipsntricks

## Adding Latex to README markdown
Based on [this](https://chaonan99.github.io/2016/how-to-add-equation-on-github-markdown-file/) blog post

1. Design your Latex formula here: https://www.codecogs.com/latex/eqneditor.php
2. Encode the resulting formula as an URL: https://www.url-encode-decode.com/
3. Add the encoded URL after the question mark in this URL: http://latex.codecogs.com/svg.latex?
4. Add the resulting SVG as an image in the README. `![img](http://latex.codecogs.com/svg.latex?<FORMULA_GOES_HERE>)`

Example: `![img](http://latex.codecogs.com/svg.latex?%5Cfrac%7B%5Csigma%7D%7B%5Cmu%7D)` renders ![img](http://latex.codecogs.com/svg.latex?%5Cfrac%7B%5Csigma%7D%7B%5Cmu%7D)
