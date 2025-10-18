---
layout: page
title: Publications
permalink: /publications/
---

* [Google Scholar](https://scholar.google.com/citations?user=hrDvB8AAAAAJ)
* [ORCID](https://orcid.org/0000-0002-3044-8266)

## 2025

### Enhancing HPX with FleCSI: Automatic Detection of Implicit Task Dependencies

<table>
<tr><th>Authors:</th><td>
Davis Herring, Maxim Moraru, Scott Pakin, Julien Loiseau, <b>Richard Berger</b>, Philipp V. F. Edelmann, and Ben Bergen
</td></tr>
</table>

### LAMMPS: A Case Study For Applying Modern Software Engineering to an Established Research Software Package

<table>
<tr><th>Authors:</th><td>
Kohlmeyer, Axel, <b>Berger, Richard</b>
</td></tr>
<tr><th>Published in:</th><td>USRSE25 Conference Proceedings</td></tr>
<tr><th>URL:</th><td><a href="https://doi.org/10.5281/zenodo.17117559" target="_blank">https://doi.org/10.5281/zenodo.17117559</a></td></tr>
</table>

We review various changes made in recent years to the software development
process of the LAMMPS simulation software package and the software itself. We
discuss how those changes have impacted the effort and workflow required to
develop and maintain a software package that has been in existence for more
than 30 years and where a significant part of the code base is contributed by
external developers. We also look into how those changes have affected the code
quality and ease of modifying and extending the software while at the same time
its audience has changed from a cohort with a generally strong software
development background to a group containing many researchers with limited
software development skills. We explore how this contributes to LAMMPS’
significant growth in popularity in that time. We close with an outlook on
future steps.

### A Hands-On Curriculum for Training in HPC Cluster Deployment and Management

<table>
<tr><th>Authors:</th><td>
Posada, Edwin Fernando, <b>Berger, Richard</b>
</td></tr>
<tr><th>Published in:</th><td>USRSE25 Conference Proceedings</td></tr>
<tr><th>URL:</th><td><a href="https://doi.org/10.5281/zenodo.17252661" target="_blank">https://doi.org/10.5281/zenodo.17252661</a></td></tr>
</table>

This paper presents the design, methodology, and outcomes of the
High-Performance Computing Technologies (HPCT) course, a hands-on training
program focused on the system-side of HPC cluster deployment and
administration. Delivered as part of the Master in High Performance Computing
(MHPC) program, the course introduces students to key concepts in cluster
configuration, including networking, software stack provisioning, job
scheduling, and monitoring. Initially taught in person, the course was
transitioned to an online format during the COVID-19 pandemic. This shift led
to the development of openly available instructional material and a
flipped-classroom approach that continues to support both in-person and hybrid
delivery.  All course materials are publicly available at
www.hpc.temple.edu/mhpc/hpc-technology/index.html. By documenting the
structure, infrastructure, and evolution of HPCT, this paper offers a model for
accessible HPC system training that supports workforce development in
computational science.

## 2024

### Singularity-EOS: Performance Portable Equations of State and Mixed Cell Closures

<table>
<tr><th>Contributors:</th><td>
Jonah M. Miller, Daniel A. Holladay, Jeffrey H. Peterson, Christopher M.
Mauney, <b>Richard Berger</b>, Anna Pietarila Graham, Karen C. Tsai, Brandon
Barker, Alexander Holas, Ann E. Mattsson, Mariam Gogilashvili, Joshua C.
Dolence, Chad D. Meyer, Sriram Swaminarayan, Christoph Junghans
</td></tr>
<tr><th>URL:</th><td><a href="https://doi.org/10.21105/joss.06805" target="_blank">https://doi.org/10.21105/joss.06805</a></td></tr>
</table>

## 2022

<a name="xcap-report-2022"></a>

### Singularity-EOS XCAP Report

<table>
<tr><th>Authors:</th><td>
Peterson, Jeffrey Hammett and Miller, Jonah Maxwell and Pietarila Graham, Anna
Mataleena and Holladay, Daniel Alphin and Mauney, Christopher Michael and
<b>Berger, Richard Felix</b> and Tsai, Karen Chung-Yen
</td></tr>
<tr><th>URL:</th><td><a href="https://doi.org/10.2172/1907763" target="_blank">https://doi.org/10.2172/1907763</a></td></tr>
</table>

### AlphaFold2 Workflow Optimization for High Throughput Predictions in HPC Environment

<table>
<tr><th>Authors:</th><td>
Posada, Edwin Fernando and McGee, Francisco and <b>Berger, Richard</b> and
Dorrell, Mitchell and Lamanna, Jason and Sanielevici, Sergiu and Carnevale,
Vincenzo
</td></tr>
<tr><th>Published in:</th><td>PEARC '22 Proceedings</td></tr>
<tr><th>URL:</th><td><a href="https://doi.org/10.1145/3491418.3535181" target="_blank">https://doi.org/10.1145/3491418.3535181</a></td></tr>
</table>

In this work, we propose a high-throughput implementation that executes
AlphaFold2 efficiently in a High-Performance Computing environment. In this
case, we have tested our proposed workflow with the T1050 CASP14 sequence on
PSC’s Bridges-2 HPC system. The results showed an improvement in
computation-only runtimes and the opportunity to reuse the protein databases
when calculating many structures simultaneously, which would lead to massive
time savings while maximizing the utilization of computing resources.

## 2021

<a name="lammps-paper"></a>

### LAMMPS - A flexible simulation tool for particle-based materials modeling at the atomic, meso, and continuum scales

<table>
<tr><th>Authors:</th><td>Aidan P. Thompson, H. Metin Aktulga, <b>Richard Berger</b>, Dan S. Bolintineanu, W. Michael Brown, Paul S. Crozier, Pieter J. in 't Veld, Axel Kohlmeyer, Stan G. Moore, Trung Dac Nguyen, Ray Shan, Mark Stevens, Julien Tranchida, Christian Trott, Steven J. Plimpton</td></tr>
<tr><th>Published in:</th><td>Computer Physics Communications</td></tr>
<tr><th>URL:</th><td><a href="https://doi.org/10.1016/j.cpc.2021.108171" target="_blank">https://doi.org/10.1016/j.cpc.2021.108171</a></td></tr>
</table>

Since the classical molecular dynamics simulator LAMMPS was released as an open
source code in 2004, it has become a widely-used tool for particle-based
modeling of materials at length scales ranging from atomic to mesoscale to
continuum. Reasons for its popularity are that it provides a wide variety of
particle interaction models for different materials, that it runs on any
platform from a single CPU core to the largest supercomputers with
accelerators, and that it gives users control over simulation details, either
via the input script or by adding code for new interatomic potentials,
constraints, diagnostics, or other features needed for their models. As a
result, hundreds of people have contributed new capabilities to LAMMPS and it
has grown from fifty thousand lines of code in 2004 to a million lines today.
In this paper several of the fundamental algorithms used in LAMMPS are
described along with the design strategies which have made it flexible for both
users and developers. We also highlight some capabilities recently added to the
code which were enabled by this flexibility, including dynamic load balancing,
on-the-fly visualization, magnetic spin dynamics models, and quantum-accuracy
machine learning interatomic potentials.

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
