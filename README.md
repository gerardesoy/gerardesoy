# Gerard Esoy

Civil engineering student specializing in computational mechanics, structural analysis automation, and numerical methods. Focused on building deterministic engineering software that bridges theoretical mechanics and production web systems.

---

## Projects & Systems

### Beam Solver
**Production Web Application** — [beamsolver.app](https://beamsolver.app)

A hybrid symbolic-numeric structural mechanics engine designed for complex, non-prismatic, and compound beam systems.

- **Formulation:** Coupled Macaulay singularity functions with a 1D Direct Stiffness Method (DSM) using cubic Hermite interpolation.
- **Kinematics:** Dual-rotation degree-of-freedom splitting at internal hinges ($M=0$) preserving matrix bandedness without static condensation.
- **Non-Prismatic Continuity:** Exact piecewise boundary value integration across variable flexural rigidity ($EI$) zones via a $2N \times 2N$ linear continuity system.
- **Reporting:** Headless LaTeX/Cairo vector export pipeline generating publication-ready step-by-step mathematical derivations.

### Soil Classifier (USCS)
**Open Source Library** — [gerardesoy/soil-classifier-USCS-](https://github.com/gerardesoy/soil-classifier-USCS-)

Automated geotechnical soil classification implementing ASTM D2487 standards. Handles complex boundary soils, dual-symbol logic, and plasticity chart boundary zones (CL-ML).

---

## Technical Focus

- **Mechanics & Mathematics:** Euler-Bernoulli beam theory, Finite Element Analysis (1D DSM), singularity functions, boundary value problems, matrix structural analysis.
- **Computation:** Python, SymPy, NumPy, SciPy, FastAPI.
- **Frontend & Graphics:** TypeScript, Next.js, Cairo graphics, KaTeX / LaTeX.

---
