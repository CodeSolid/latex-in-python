# Python LaTeX

This is the companion repository to the article [Using LaTeX in Python](https://codesolid.com/using-latex-in-python/).

## Getting started:


```
conda env create -f environment.yml -n latex
conda activate latex
jupyter lab
```

Or: 
```
python -m venv venv
source venv/bin/activate
# On Windows use: venv\Scripts\activate.bat
pip install -r requirements.txt
jupyter lab
```

Most of the notebooks here are usable with just the above setup. There are two exceptions, however:

To edit sample.tex, you'll need to also install pdflatex or a similar tool.  The SageMathExample.ipynb notebook also needs SageMath installed -- see for example [Introducing Sage Math:  Symbolic Math Software in Python](https://codesolid.com/introducing-sage-math-python-based-mathematics/).

## Additional Resources

This [List of LaTeX Mathematical Symbols](https://oeis.org/wiki/List_of_LaTeX_mathematical_symbols#Set_and.2For_logic_notation)
focuses on many mathematical symbols that should work across LaTeX as well as MathJax, so they're suitable for use in Jupyter Notebooks.

For full LaTeX, there are many resources to get started.  One popular resource is [Overleaf.com](https://overleaf.com), which features an online editor as well as lots of beginner tutorials and other documentation on LaTeX.