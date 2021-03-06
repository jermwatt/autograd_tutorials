# A few `autograd` tutorial notebooks  

This repo contains a set of Jupyter notebook describing how to use various [autograd](https://github.com/HIPS/autograd) functionalities, complementing the excellent tutorial located at the repo itself, including:

- [**basic_autograd_examples.ipynb**](https://nbviewer.jupyter.org/github/jermwatt/autograd_tutorials/blob/b6d264a62d3f3028406c76db4d3f476c6337fdff/basic_examples.ipynb) covering basic functionalities such as: derivative computation using standard and lambda functions, subtleties involved in automatic differentiation and the array of gradient prototypes provided by `autograd`, and computing partial derivatives of multi-input functions

- [**flattening_functions_using_autograd.ipynb**](https://nbviewer.jupyter.org/github/jermwatt/autograd_tutorials/blob/b775b089460e2204a5d37dcaada5e0842ca3f0de/flattening_functions.ipynb) covering usage of `autograd`'s [flatten_func](https://github.com/HIPS/autograd/blob/master/autograd/misc/flatten.py) function 


These notebooks were produced as supplementary material for the second edition of the textbook Machine Learning Refined, published Cambridge University Press, set for release in mid-2019.  You can find a host of examples employing `autograd` and - in particular - `flatten_func` on the main repository for the textbook [located here](https://github.com/jermwatt/mlrefined) (see for example the drafts on [multi-class classification](https://jermwatt.github.io/mlrefined/blog_posts/7_Linear_multiclass_classification/7_2_Perceptron.html) [fully connected networks](https://jermwatt.github.io/mlrefined/blog_posts/13_Multilayer_perceptrons/13_1_Multi_layer_perceptrons.html)).
