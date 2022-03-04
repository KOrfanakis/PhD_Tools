# Interactive Plots with ipywidgets

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/KOrfanakis/PhD_Tools/main?labpath=%2FInteractive_Widgets%2FInteractive_Widgets.ipynb)

Usually, creating a static figure is enough; we can visualise the data and extract meaningful insights.
However, we sometimes might want to interactively change the figure without manually changing the parameters and rerunning the code. 

We can easily achieve this by using the **[`ipywidgets` library](https://ipywidgets.readthedocs.io/en/latest/index.html#)**. 
Ipywidgets, also known as jupyter-widgets or simply widgets, are interactive HTML widgets (e.g. sliders, text boxes, etc.)
for Jupyter notebooks and the IPython kernel.

Notebooks come alive when interactive widgets are used as users gain control of their data and can visualize changes in the data.
As the [creators stated](https://github.com/jupyter-widgets/ipywidgets): ‘*Learning becomes an immersive, fun experience.
Researchers can easily see how changing inputs to a model impact the results*’.

In this short tutorial, we will use the ipywidgets library to demonstrate how the plot of an exponentially damped sinusoid changes as we vary its parameters.
Our analysis uses four types of widgets:  IntSlider, FloatSlider, ColorPicker, and Text. For a full list, please check the [official documentation](https://ipywidgets.readthedocs.io/en/latest/index.html).

<br>

## Resources Used

Python Version: 3.10.2 <br>
Jupyter Notebook Version: 6.4.8 <br>
Packages: numpy (1.22.2), matplotlib (3.5.1), ipywidgets (7.6.5) <br>
