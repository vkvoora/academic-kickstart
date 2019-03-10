+++
title = "Methods of Electronic Structure Theory"
	
# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""
+++
*Graduate course, Spring 2019*
{{% toc %}} 

## Goals
This course aims to  develop a quantitative understanding of chemical binding.  Aspects of covalent and non-covalent bonding will be covered. At the end, the students should be able to understand the approximations that go into various quantum chemistry methods, and be able to assess their use in their own routine research. 

## Assignments
### [Assignment 0]({{< ref path="0.md" >}})
### [Assignment 1]({{< ref path="1.md" >}})

### Assignment 2

*(Due 21/03/2019)* 

2.1 Consider a system (for example, a molecule) consisting of two electrons of different spins that equally populate two different orbitals (whose spatial wavefunctions are given by $\psi\_1$ and $\psi_2$). 
a) Construct the two possible Slate determinants and obtain their expectation value of the energy. 
b) Check that these Slater determinants are not suitable approximate wave functions of such a system [Hint: are they pure spin states?]
c) Which wavefunctions would be suitable approximate wavefunctions? [Hint: try to diagonalize the $S^2$ matrix]
d) What is the energy expectation value of such functions, and which one of them will be more stable? (10 pts)

2.2 For the minimal basis H$\_2$, i.e. a the many-body basis consisting of the two singlet wavefunctions (
$\vert \Phi_0 \rangle = \vert 1 \bar{1} \vert$
, $\vert \Phi\_{1 \bar 1}^{2 \bar 2} \rangle = \vert 2 \bar 2\vert$, where $\vert . \vert$ denotes a Slater determinant, 
$\vert 1 \rangle = \vert  \sigma\_g1s \alpha \rangle$, 
$\vert \bar 1 \rangle = \vert  \sigma\_g1s \beta \rangle$,
$\vert 2 \rangle = \vert  \sigma\_u1s \alpha \rangle$, and
$\vert \bar 2 \rangle = \vert  \sigma\_u1s \beta \rangle$ ), 
show that the full CI Hamiltonian matrix  
$$\mathbf{H} = \begin{pmatrix} 
\langle 1 \vert h \vert  1 \rangle + \langle \bar 1 \vert h \vert  \bar 1 \rangle
+ \langle 1\bar 1 \vert \vert  1\bar 1 \rangle  
&
 \langle 1 \bar 1 \vert \vert 2 \bar 2 \rangle \newline
\langle 2 \bar 2 \vert \vert 1 \bar 1 \rangle &
\langle 2 \vert h \vert  2 \rangle + \langle \bar 2 \vert h \vert  \bar 2 \rangle
+ \langle 2\bar 2 \vert \vert  2\bar 2 \rangle  \newline
\end{pmatrix}$$
and show that it is Hermitian. Show this result without (and with) using Slater-Condon rules. By integrating out spin, show that 
$$\mathbf{H} = \begin{pmatrix} 
2 h\_{11} + J\_{11} & J\_{12} \newline
J\_{21}  &  2 h\_{22} + J\_{22} \newline
\end{pmatrix} \;\text{. (15pts)}$$. 

2.3 Show that the Hartree products
$$
\Psi\_a(\mathbf r\_1, \mathbf r\_2) = \psi\_1(\mathbf r\_1)\alpha(s\_1) \psi\_2(\mathbf r_2)\beta(s_2) $$
$$ \Psi\_b(\mathbf r\_1, \mathbf r\_2) = \psi\_1(\mathbf r\_1)\alpha(s\_1) \psi\_2(\mathbf r_2)\alpha(s_2) $$
a) are uncorrelated and b) have the same energy as that of the antisymmetrized form of $\Psi\_a$, i.e
$$ \psi\_1(\mathbf r\_1)\alpha(s\_1) \psi\_2(\mathbf r_2)\beta(s_2) -
\psi\_2(\mathbf r\_1)\beta(s\_1) \psi\_1(\mathbf r_2)\alpha(s_2)\;\text{. (5pts)}$$. 




<!-- $\vert \sigma\_g1s \bar{\sigma\_g1s}  \rangle$ and $\vert \Phi_2 \rangle = \vert \sigma\_u1s \bar{\sigma\_u1s}  \rangle$), --> 




<!-- $$\begin{eqnarray} 
y &=& 1+1   \\\\\\
&=& 2 
\end{eqnarray}$$ -->



 <!-- ## Lecture Summary -->

 <!--  ### Chapter 1 -->

<!-- ## Corrections -->

<!-- {{% staticref "files/smallsyl.pdf" "newtab" %}} Syllabus {{% /staticref %}} -->

<!-- This is inline: $\mathbf{y} = \mathbf{X}\boldsymbol\beta + \boldsymbol\varepsilon$ -->


## Central Topics

-   Many-body problem and electron correlation

-   Concept of potential energy surface

-   Theories of chemical bonding

-   Mean-field and semi-empirical methods

-   Approximate ab initio methods for electron correlation

-   Introductory density functional theory

-   Molecular properties

-   Intermolecular interactions



## Suggested books


1.  Attila Szabo and Neil S. Ostlund, *Modern Quantum Chemistry*,
    Dover, 1996.

2.  Frank Jensen, *Introduction to Computational Chemistry*, Wiley, 3rd
    ed., 2007.

3.  Roy McWeeny, *Methods of molecular quantum mechanics*, Academic
    Press, 2nd ed., 1992.

4.  Trygve Helgaker, Paul Jørgensen, and Jeppe Olsen, *Molecular
    electronic-structure theory*, Wiley, 2000.

5.  Anthony J. Stone, *Theory of Intermolecular Forces*, Oxford
    University Press, 2nd ed., 2013.	

6.  Eberhard Engel, Reiner M. Dreizler, *Density Functional Theory: An
    Advanced Course*, Springer Berlin Heidelberg, 2011.

## Course Info

**Prerequisites:** Linear algebra and basic quantum chemistry.

**Grading Policy:** Weekly assignments (30%), Midterm (30%), Final
(40%).

**Venue:** AG80\
**Hours:** Tue 10:00 am -- 11:15 am,\
Thu 11:15 am -- 12:30 pm\
**Office Hours:** WF 2--3 pm or set-up an appointment via email\
\
**Instructor:** Vamsee Voora\
Email: <vamsee.voora@tifr.res.in>\
Office: NMR 104\
***The first lecture is on Jan 22nd (Tuesday)***

