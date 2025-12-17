
# **Sadhya Padmanabhan**

**Undergraduate Researcher | Computational & Theoretical Physics**

**BTech Metallurgy & Materials Engineering, IIT Madras (2023–2027)**  
Aspiring **Computational Astrophysicist**

---


## **Research Focus**

I am an undergraduate engineering student with a strong interest in **computational and theoretical physics**, particularly in **transport phenomena and astrophysical fluid dynamics**. My work emphasizes **deriving models from first principles**, implementing **numerical solvers from scratch**, and performing **systematic validation and convergence analysis**.
---

## **Technical Capabilities**

- **Programming:** Python, C, Java  

- **Scientific Computing:** NumPy, SciPy, SymPy, Pandas, Numba;  
  **Astrophysical data analysis:** Astropy for FITS I/O, image handling, and metadata (WCS) processing; experience working with **ALMA interferometric imaging products** (e.g., HL Tau Band 6).

- **Numerical Methods:** Monte Carlo methods, MCMC, Finite Element Method (FEM), FTCS, Crank–Nicolson schemes  

- **Scientific Workflow:** Git/GitHub, Jupyter Notebooks  

- **Scientific Writing:** LaTeX for reports, derivations, and publication-quality figures


---
## **Selected Projects**

---

### **1. Comparative Study of 1D Spin Diffusion Solvers**  
*Analytical, Finite Element, and Monte Carlo Approaches*

A controlled benchmark study of deterministic and stochastic solvers for the steady-state 1D spin diffusion equation, focusing on **accuracy, convergence, and computational cost**.

**Core contributions**
- Derived and implemented the **closed-form analytical solution** as a benchmark
- Implemented a **Finite Element Method (FEM)** solver from the weak form using linear elements and sparse matrix assembly
- Developed custom **Monte Carlo particle-hopping algorithms** ($N>10^6$ particles) to validate deterministic PDE solvers.
- Performed explicit **statistical vs. systematic error decomposition**
- Verified theoretical convergence laws:  
  - FEM: \( \mathcal{O}(h^2) \)  
  - MC: \( \mathcal{O}(N^{-1/2}) \)

**Implementation**
- Python with **NumPy**, **SciPy**, **SymPy**
- Sparse solvers via `scipy.sparse`
- Convergence and error pipelines with reproducible workflows
- Visualization using **Matplotlib**
- Analysis notebooks in **Jupyter**
- Version control with **Git/GitHub**


---

### **2. Viscous Evolution of Thin Accretion Disks**  
*Explicit and Implicit Finite Difference Methods with Observational Comparison*

A numerical study of the time-dependent viscous evolution of thin, axisymmetric accretion disks, derived from the vertically integrated Navier–Stokes equations and compared against **ALMA observations**.

**Core contributions**
- Derived the surface density evolution equation from mass and angular-momentum conservation
- Implemented an explicit **FTCS scheme** with stability analysis
- Developed an **unconditionally stable Crank–Nicolson solver** in conservative flux form
- Verified mass conservation and long-timescale numerical stability
- Reproduced the theoretical temperature scaling  
  \( T \propto R^{-3/4} \)

**Observational interface**
- Worked with **FITS data** using **Astropy**
- Compared simulated surface density structures with **ALMA HL Tau Band 6** observations
- Established qualitative consistency between viscous ring spreading and observed disk morphology

**Implementation**
- Python with **NumPy**, **SciPy**, sparse linear solvers
- FITS and ALMA data handling via **Astropy**
- Visualization using **Matplotlib**
- Full derivations and documentation prepared in **LaTeX**






---

## **Contact**

📧 Email: *mm23b080@smail.iitm.ac.in*


---





