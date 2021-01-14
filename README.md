# julia-course-2020

Repository for the 2020 AI2S Julia course.

## The teacher

![Luca Manzoni](/pics/mnz.jpeg)

[Luca Manzoni](https://scholar.google.com/citations?user=ufJKQegAAAAJ&hl=en) is a researcher @ Dept. of Mathematics and Geosciences, University of Trieste, Italy.

His reaserch focuses on evolutionary methods and he regularly uses Julia for his works.

## The course

The course is organized in three lectures of two hours each. The first lecture is an introductory overview, while the latter two present some specific Julia libraries used in the context of AI:

1. Introduction to the Julia language and its standard library
2. Calling R and Python from Julia; Plots and DataFrames; Flux for Machine Learning
3. Differential Equations; Probabilistic programming with Turing; BenchmarkTools

The recordings of the lecture are in the process of being uploaded to YouTube. Follow [this link](https://youtube.com/playlist?list=PLQqPyhvM7LOgU3TmMvbVhKxqAQz-zD_OW) for the playlist containing the videos.

### Prerequisites for optimal understanding

Although the course offers a basic overview of Julia and some of its funtionalities, the attendee should at least have a rudimentary knowledge of other programming languages, such as Python, R, or C/C++. The former two certainly help with the understading of Julia since it was based off of these two.

Moreover, note that this course was thought for attendees with an AI background, so the topics treated relate mainly to Machine Learning/Scientific Computing.

## Installation

For a visual guide, please refer to the intro to the [first video](https://youtu.be/nLkwTjbO0FU) of the lectures.

In order to run these notebooks, you need to install two pieces of software:

1. [Julia](https://julialang.org/downloads/)
2. [Jupyter Notebook](https://jupyter.org/):
For non-expert users, if you're on Windows, we recommend installing [Anaconda](https://www.anaconda.com/products/individual) which already comes with a pre-packaged version  of Jupyter Notebook and Jupyter Lab, in addition to Python and Conda. If you are on Linux, instead, just type `sudo apt install jupyter-notebook`, instead.

### Installing Julia libraries

Moreover, in order to correctly use Julia notebooks with Jupyter Notebook, you'll need to add the package `IJulia` to Julia.

To do so, you can open a Julia console:
* Linux/MacOS: open a terminal and type `julia`
* Windows: run the Julia executable after Julia has been installed

then, you may use one of two commands:
- type `]`, then `add IJulia`. The first command opens the Julia package manager.
- or, type `using Pkg`, then, in a new line, `Pkg.add("IJulia")`. The advantage of this command is that it can be executed also from the Jupyter Notebook, as you can see in the files from the Lecture 2 or 3.

The same two commands may be used to install any library within Julia. For more info, please refer to [the official docs](https://docs.julialang.org/en/v1/stdlib/Pkg/).

## Final notes

Our Association offers courses and seminars on AI, plus useful services for students from the University of Trieste. Please check our site [](www.ai2s.it) for further info on the society and its future initiatives and on how to support us.

Check out our social profiles:
- [Twitter](https://twitter.com/aitwos)
- [Facebook](facebook.com/aistudentsociety)
- [LinkedIn](linkedin.com/company/ai-student-society)

There's also a Julia community in Trieste! [](https://twitter.com/JuliaTrieste)

