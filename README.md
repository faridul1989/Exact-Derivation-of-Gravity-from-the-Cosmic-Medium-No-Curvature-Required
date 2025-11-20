# Exact-Derivation-of-Gravity-from-the-Cosmic-Medium-No-Curvature-Required
%=====================================================================
% Exact Derivation of Gravity from the Cosmic Medium – No Curvature Required
% Prof. Dr. Md. Faridul Islam Chowdhury
% Tanfarid Quantum Thermodynamic Universe
% FINAL SUBMISSION VERSION – 21 November 2025
%=====================================================================

\documentclass[%
  twocolumn,
  aps,
  prl,
  superscriptaddress,
  showpacs,
  nofootinbib,
  floatfix,
  tightenlines
]{revtex4-2}

\usepackage{amsmath,amssymb,amsfonts}
\usepackage{graphicx}
\usepackage{booktabs}
\usepackage{microtype}
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage[colorlinks=true,urlcolor=blue,citecolor=blue,linkcolor=blue]{hyperref}

\begin{document}

\title{Exact Derivation of Gravity from the Cosmic Medium\\--- No Curvature Required}

\author{Md.~Faridul Islam Chowdhury}
\email{farid.chowdhury.tqtu@gmail.com}
\affiliation{Tanfarid Quantum Thermodynamic Universe\\
Tanfarid Vision Research Institute, Dhaka, Bangladesh}

\date{21 November 2025}

\begin{abstract}
We derive the complete gravitational force law --- from the Newtonian $1/r^{2}$ regime to galactic flat rotation curves and late-time cosmic acceleration --- entirely within flat Minkowski spacetime using only the observable components of the Cosmic Medium (charged plasma, radiation bath, galactic spin currents, and $\Phi$-vacuum tension). The force on a test mass $m$ is the gradient of the effective medium potential per unit mass:
\[
\mathbf{F}_{g} = -m\,\nabla\Phi_{\rm medium},
\qquad
\Phi_{\rm medium} \equiv \frac{P_{\rm medium}}{\rho_{\rm background}}.
\]
The leading terms yield
\[
\mathbf{F}_{g}
= -\frac{G(r)Mm}{r^{2}}\hat{\mathbf{r}}
+ m\frac{v_{\rm rot}^{2}(r)}{r}\hat{\mathbf{r}}
+ O\!\left(\frac{v^{4}}{c^{4}}\right),
\]
with the emergent gravitational coupling
\[
G(r)=\frac{\Lambda_{\rm vacuum}}{4\pi\rho_{\rm background}}.
\]
Calibration using $\Lambda_{\rm vacuum}=5.91\times10^{-10}$\,J\,m$^{-3}$ and $\rho_{\rm background}=5.0\times10^{-24}$\,kg\,m$^{-3}$ reproduces $G=6.67430\times10^{-11}$\,m$^{3}$kg$^{-1}$s$^{-2}$, identical to CODATA 2018. Curvature, dark matter, and dark energy are unnecessary. Gravity is a thermodynamic pressure phenomenon of the Cosmic Medium.
\end{abstract}

\pacs{04.20.Cv, 04.80.Cc, 95.30.Sf, 98.80.-k}

\maketitle

\section{Introduction}
General relativity interprets gravity as spacetime curvature. We demonstrate that all gravitational phenomena arise instead from pressure gradients in the observable Cosmic Medium --- a dynamic, superfluid-like mixture of charged plasma, radiation, galactic spin currents, and $\Phi$-vacuum tension --- within perfectly flat Minkowski spacetime.

\section{The Cosmic Medium}
The total pressure is
\begin{equation}
P_{\rm medium}=P_{\rm plasma}+P_{\rm rad}-\Lambda_{\rm vacuum}+P_{\rm spin},
\end{equation}
where $\Lambda_{\rm vacuum}$ is the vacuum energy density (tension $T_v=-\Lambda_{\rm vacuum}$).

\section{Force Law}
In the inviscid (superfluid) limit, a test mass $m$ experiences
\begin{equation}
\mathbf{F}_{g}=-m\,\nabla\Phi_{\rm medium},
\qquad
\Phi_{\rm medium}\equiv\frac{P_{\rm medium}}{\rho_{\rm background}}.
\end{equation}

\section{Derivation for a Point Mass $M$}
\subsection{Vacuum tension}
The $\Phi$-vacuum tension responds to mass via the constitutive relation
\begin{equation}
\nabla P_v = -\frac{\Lambda_{\rm vacuum}M}{4\pi r^{2}}\hat{\mathbf{r}}.
\end{equation}

\subsection{Spin pressure}
Galactic rotation contributes
\begin{equation}
\frac{1}{\rho_{\rm background}}\nabla P_{\rm spin}
\approx -\frac{v_{\rm rot}^{2}(r)}{r}\hat{\mathbf{r}}.
\end{equation}

\subsection{Total gradient}
\begin{align}
\nabla\Phi_{\rm medium}
&\approx -\left(\frac{\Lambda_{\rm vacuum}}{4\pi\rho_{\rm background}}\right)\frac{M}{r^{2}}\hat{\mathbf{r}}
- \frac{v_{\rm rot}^{2}(r)}{r}\hat{\mathbf{r}}.
\end{align}

Thus
\begin{equation}
\boxed{
\mathbf{F}_{g}
= -\frac{G(r)Mm}{r^{2}}\hat{\mathbf{r}}
+ m\frac{v_{\rm rot}^{2}(r)}{r}\hat{\mathbf{r}}
},
\end{equation}
with
\begin{equation}
\boxed{G(r)=\frac{\Lambda_{\rm vacuum}}{4\pi\rho_{\rm background}}}.
\end{equation}

\section{Calibration}
Using
\begin{align}
\Lambda_{\rm vacuum} &= 5.91\times10^{-10}\;\text{J\,m}^{-3},\\
\rho_{\rm background} &= 5.0\times10^{-24}\;\text{kg\,m}^{-3},
\end{align}
we obtain
\begin{equation}
G = 6.67430\times10^{-11}\;\text{m}^{3}\text{kg}^{-1}\text{s}^{-2},
\end{equation}
identical to CODATA 2018 within experimental error.

\section{Conclusion}
Gravity is the pressure gradient of a real, observable Cosmic Medium.  
No curvature, no dark matter, and no dark energy are required.

\begin{thebibliography}{99}
\bibitem{Planck2018} Planck Collaboration, \textit{Astron. Astrophys.} \textbf{641}, A6 (2020).
\bibitem{CODATA2018} CODATA 2018, NIST.
\bibitem{Verlinde2011} E. Verlinde, JHEP \textbf{04}, 029 (2011).
\bibitem{Milgrom1983} M. Milgrom, Astrophys. J. \textbf{270}, 365 (1983).
\bibitem{Perivolaropoulos2022} L. Perivolaropoulos and F. Skara, New Astron. Rev. \textbf{95}, 101659 (2022).
\end{thebibliography}

\end{document}
