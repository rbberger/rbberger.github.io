---
layout: page
title: Publications
permalink: /publications/
---

* [Google Scholar](https://scholar.google.com/citations?user=hrDvB8AAAAAJ)
* [ORCID](https://orcid.org/0000-0002-3044-8266)

## 2016

<a name="dissertation"></a>
### Efficiency and Quality Control for Particle Simulations

<table>
<tr><th>Author:</th><td><b>R. Berger</b></td></tr>
<tr><th>Type:</th><td>Ph.D. Dissertation</td></tr>
<tr><th>URL:</th><td><a href="https://epub.jku.at/obvulihs/content/titleinfo/1009602" target="_blank">https://epub.jku.at/obvulihs/content/titleinfo/1009602</a></td></tr>
<tr><th>Files:</th><td><a href="/assets/files/phd_dissertation.pdf" target="_blank">PDF</a></td></tr>
</table>

This work describes the efforts of improving the efficiency and quality of the LIGGGHTS open-
source software package for Discrete Element Methods (DEM). It explains the core algorithms
present in this code and how a test harness was developed to support refactoring by automated
testing and validation. Because of this testing facility, iterative refactoring of the code base could
take place without damaging existing functionality.

Major modifications were made to the code base to simplify the common task of creating new
force models both for particle-particle and particle-wall contacts. This paved the way for further
advances such as multi-threaded OpenMP versions of all granular force kernels. Along the way
many improvements were made to the core functionality in LIGGGHTS. Through measuring
and profiling, performance bottlenecks in the existing implementation were found and improved.

Finally, an MPI/OpenMP hybrid parallelization was developed which extends the existing
MPI parallelization of the code. Problems encountered and the solutions implemented to achieve
scalable performance using both parallelization models are explained in this text. Three case
studies, including two real-world applications with up to 1.5 million particles, were evaluated
and demonstrate the practicality of this approach. In these examples, better load balancing
and reduced MPI communication led to speed increases of up to 44% compared to MPI-only
simulations. This shows that by using the hybrid parallelization of LIGGGHTS, current and
future computing resources can be used more effectively.


## 2015

### Hybrid parallelization of the LIGGGHTS open-source DEM code

<table>
<tr><th>Authors:</th><td><b>R. Berger</b>, C. Kloss, A. Kohlmeyer, S. Pirker</td></tr>
<tr><th>Published in:</th><td>Powder Technology</td></tr>
<tr><th>URL:</th><td><a href="https://doi.org/10.1016/j.powtec.2015.03.019" target="_blank">https://doi.org/10.1016/j.powtec.2015.03.019</a></td></tr>
<tr><th>Keywords:</th><td>LIGGGHTS, Discrete Element Method, Hybrid parallelization, MPI, OpenMP</td></tr>
</table>

This work presents our efforts to implement an MPI/OpenMP hybrid
parallelization of the LIGGGHTS open-source software package for Discrete
Element Methods (DEM). We outline the problems encountered and the solutions
implemented to achieve scalable performance using both parallelization models.
Three case studies, including two real-world applications with up to 1.5
million particles, were evaluated and demonstrate the practicality of this
approach. In these examples, better load balancing and reduced MPI
communication led to speed increases of up to 44% compared to MPI-only
simulations.

## 2013

### Reverse engineering and visualization of the reactive behavior of PLC applications

<table>
<tr><th>Authors:</th><td>H. Prähofer, C. Wirth and <b>R. Berger</b></td></tr>
<tr><th>Published in:</th><td>11th IEEE International Conference on Industrial Informatics (INDIN)</td></tr>
<tr><th>URL:</th><td><a href="https://doi.org/10.1109/INDIN.2013.6622946" target="_blank">https://doi.org/10.1109/INDIN.2013.6622946</a></td></tr>
</table>

This paper presents an approach to reverse engineering and dynamic analysis of
the reactive behavior of PLC programs. Based on execution traces, it is shown
how to derive a state model representation of the reactive program behavior and
how this model supports dynamic program analysis. In particular, the state
model is used for mining execution patterns which occur repeatedly in a program
execution. We discuss the key ideas of the approach, the various analysis and
visualization methods available, and results from a case study.

## 2012

### A tool for trace visualization and offline debugging of PLC applications

<table>
<tr><th>Authors:</th><td>H. Prähofer, C. Wirth and <b>R. Berger</b>, H. Prähofer, C. Wirth and R. Schatz</b></td></tr>
<tr><th>Published in:</th><td>2012 IEEE 17th International Conference on Emerging Technologies & Factory Automation (ETFA 2012)</td></tr>
<tr><th>URL:</th><td><a href="https://doi.org/10.1109/ETFA.2012.6489785" target="_blank">https://doi.org/10.1109/ETFA.2012.6489785</a></td></tr>
</table>

This paper describes a tool for offline debugging and trace visualization of
PLC applications. Based on trace data obtained by a deterministic replay
technology for multi-threaded Soft PLC applications, the tool allows
visualizing an application run in its various aspects and on various levels of
abstraction. Each view shows a different level of detail, allowing the user to
dive into the program from high-level views showing abstract program behavior
to low-level views showing each executed statement or variable value in detail.
With a set of views the tool supports the user to get an overview of the
program execution, to identify abnormal program behavior, to discover the
causes for program failures, and finally to locate defects in the source code.
The paper presents the conceptional background of the approach, shows how
program runs can be visualized, and how they can be analysed in detail. Then it
demonstrates how the the tool supports a debugging process by an illustrative
example.

<a name="diplom"></a>
### A Tool for Offline Debugging and Trace Visualization of SoftPLC Programs

<table>
<tr><th>Author:</th><td><b>R. Berger</b></td></tr>
<tr><th>Type:</th><td>Diplom Thesis</td></tr>
<tr><th>Files:</th><td><a href="/assets/files/diplom_thesis.pdf" target="_blank">PDF</a></td></tr>
</table>

This thesis describes the Trace Visualization Tool developed at the Christian Doppler Laboratory
for Automated Software Engineering. It was part of a larger project, Capture & Replay, whose
goal is the development of methods and tools for recording real-time PLC applications for
deterministic replay, off-line debugging, and dynamic program analysis. The project is conducted
in cooperation with and funded by KEBA AG.

This tool allows PLC developers to explore and analyse program recordings using a variety
of different views. Each view shows a different level of detail, allowing the user to dive into
the program from high-level views to a low-level views. Unlike a regular single-step debugger,
it allows navigating the entire program run and examining the program’s state at any point in
time.

The thesis describes the different views provided by the tool, gives an introduction of how
they are used for debugging, and outlines their implementation using the Windows Presentation
Foundation. It also describes the main challenges of handling the huge amount of data and
preparing it for display. Finally, a case study is presented which was developed to validate both
the Capture & Replay approach and the visualization tool.
