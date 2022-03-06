
# Making GIFs with Python

A GIF (which is an acronym for ‘Graphics Interchange Format’) is a file format for animated images that are created by looping several frames. GIFs can break down datasets into smaller segments, show trends, and in general, tell a visual story in ways a static figure cannot. Therefore, GIFs can be used as a data analysis and visualisation tool for STEM Ph.D. students and data scientists.

Ιn this tutorial, we will see how to turn a static visualisation into a GIF with Python and the **[`gif`](https://pypi.org/project/gif/)** package. As an example, I decided to visualise how the emission spectrum of a semiconductor changes with temperature. The temperature dependence of our imaginary semiconductor is studied within a range from 4 to 300 K (in other words, from -270 °C to room temperature). Throughout this whole range, the material emits in the microwave regime (energy lower than the infrared).

The result is:

<p align="center"><img width="600" src="T-dependence.gif"></p>


## Resources Used

Python Version: 3.10.2 <br>
Jupyter Notebook Version: 6.4.8 <br>
Packages: Matplotlib (3.5.1), gif (3.0.0), NumPy (1.22.2), Pandas (1.4.1)
