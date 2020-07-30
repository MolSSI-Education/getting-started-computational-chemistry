---
title: "Introduction"
teaching: 10
exercises: 0
questions:
- "What is Computational Chemistry?"
objectives:
- "Understand the workflow of computational chemistry research."
- "Identify key computational tools you may use your research."
keypoints:
- "The basic workflow of most computational chemistry research is setting up input files for calculations or simulations, running those calculations, retrieving the output, and processing and analyzing the results."
---
# Getting Started in Computational Chemistry
Participating in computational chemistry research requires some skills that you may not have acquired in your previous classes or computer experience.  This guide is designed to introduce you to some of those skills.

The basic workflow of most computational chemistry research is
1. Set up input files for calculations or simulations.
2. Run calculations.
3. Retrieve output of calculations.
4. Process and analyze results.

The input files for your calculations are often plain text files.  These files do not contain the same formatting information that typeset files like Word documents or Google documents would.  You often use software called a *text editor* to prepare such files.  

Very often you will not run calculations on your local laptop or workstation, you will use remote computing resources.  You will need to learn to connect to these remote computers and submit your jobs according to the rules of that computer's *queuing system*.  A queuing system keeps up with all the calculations users want to run and what the computing requirements of those jobs are.  

Once your calculation or simulation has finished running and you retrieve your output files, you need to process these files and analyze the results.  Sometimes you will use specialized software to parse the output files and sometimes you will need to write code yourself to do this.  One of the most popular programming languages for scientific data analysis is [Python](https://www.python.org/).  If you need to learn to use Python, [MolSSI](https://molssi.org) offers [a complete module](https://education.molssi.org/python_scripting_cms/) about scripting and data analysis in Python.  

This module is designed to introduce you to the software tools you will need to participate in computational chemistry research.   There are also lessons about specialized computational chemistry software package provided by our [MolSSI Community Code Partners](https://molssi.org/molssi-community-code-partners/).

{% include links.md %}
