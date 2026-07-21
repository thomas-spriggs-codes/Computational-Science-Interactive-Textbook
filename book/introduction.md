# An introduction to computational methods in physics: a python interactive textbook
## About this book
In this book, you will learn to solve problems in physics using computational tools by programming these problems into a computer.

## Why are programming and computational tools important in physics?
One reason is that while many of the (toy) problems you will encounter in an undergraduate physics program have analytical solutions (since they are chosen carefully by the teachers of your course), most problems encountered in physics will in general not have an analytical answer, and so if you really need to know the solutions of these non-simplified problems, you will have to calculate them numerically.

Another useful reason is that computational solutions to problems can often provide quick insight into complex equations without too much work: once you know how to program the numerical solution, you can use your computer to do numerical "experiments", playing with parameters to explore what happens.

And finally, programming itself has become an essential toolbox for the physicist: from programming the control and acquisition of data in experiments, to the processing, plotting, and analysis of data from experiments; and from visualising and exploring theoretically derived formulas, to numerical computations for simulating complex problems in physics: the list goes on. A high proficiency in programming is now considered an essential skill in physics, and is one that is also highly valuable for careers outside of physics.

## Python
The programming language we will use is Python, one of the most popular programming languages right now, and one which has come to dominate the physical sciences. It has become popular because of its flexibility and simple syntax. Although it is slower than some of the traditional low-level languages like C or Fortran, this has become less of an issue for many problems as computers have gotten faster, and for heavier numerical calculations, it can easily interface to libraries that run highly optimized code pre-compiled in low-level languages.

## This book
This JupyterBook offers an interactive environment for you to learn about, and implement, the algorithms you will most often need to solve or quickly benchmark a physics problem.

*Importantly*, while this book provides an interactive environment for you to code the solutions to our questions, your work is not saved in this JupyterBook! You can save a PDF version of what you have done by clicking the 'Download'-looking icon within each section; you will also see an option to download the `.ipynb` file, too, so you can keep these exercises and try them locally if you wish (but downloading this way does not keep your progress, it just downloads the state of the notebook before you changed it, unlike downloading the PDF!).

The solutions are provided alongside the questions. They are hidden under the 'show code cell source' buttons so can be accessed at any time if you lose your progress. Please try and solve the problem yourself first, and run the cells for checking your answers to get feedback *before* resorting to checking the answer. 

## Prerequisities
This book is aimed at undergraduate students: primarily for physicists wanting to learn how to numerically solve many of the problems they learn about in undergradutate physics courses, but also to other students from a science, technology, engineering, or maths (STEM) discipline wanting to expand their computational or problem solving capabilities.  As a result, some familiarity with the basics of the physics in which these problems are set is desired, but not required. However, you will need basic familiarity with Python and you should be somewhat proficient in NumPy.

## What you can expect to learn
On a high level, our goal is that after this course you are able to simulate problems in physics using Python. The topics we will cover are:

* Numerical Differentiation
* Numerical Integration
* Root finding
* Linear algebra
* Fourier transforms 
* Random numbers
* Ordinary Differential Equations 
* Partial Differential Equations 

## Citing this book
If this book leads to any scientific work then please cite it using the following:
```
@book{steele2025computationalscience,
    title = "Computational Science: Interactive Textbook",
    author = "Gary Steele, Jeroen Kalkman, Thomas Spriggs, and Eliska Greplova",
    year = "2025",
    note={\url{https://oit.tudelft.nl/Computational-Science-Interactive-Textbook/main/intro.html}}, 
}
```
