# Hi, I'm juroc58 👋

**16 · Nuremberg, Germany · Gymnasium year 10 · physics & maths**

---

### Why I built this

My dad and I want to put a Sharp cycloturbine on our roof. So I built a
solver for one first — one week, Python and Numba, heavy AI assistance.

The goal is a real machine, not just a paper: everything in the repository
is oriented toward “can this actually be built on a rooftop?”

### Sharp VAWT Lab

[![tests](https://github.com/juroc58/sharp-vawt-lab/actions/workflows/test.yml/badge.svg)](https://github.com/juroc58/sharp-vawt-lab/actions/workflows/test.yml)

[**sharp-vawt-lab**](https://github.com/juroc58/sharp-vawt-lab) — a 2-D BEM
modelling laboratory for the Sharp cycloturbine: a passive variable-pitch
VAWT using centrifugal-pendulum pitch control (CPPC).

| | |
|---|---|
| **Physics** | DMS induction, dynamic-stall model, curvilinear-flow corrections, Sharp CPPC, Active Lift |
| **Validation status** | Literature comparisons and model-consistency checks; **no experimental validation yet** |
| **Uncertainty** | Saltelli sensitivity study; 14 active inputs, 4,352 runs |
| **Docs** | Derivation, provenance stamps, reproducible result JSONs, and generated README tables |

### What the model says

The most important result is **not** a single Cp number:

- The small Sharp-inspired CPPC rotor is close to a collapse threshold.
  Its UQ result is bimodal: working-branch mean Cp ≈ 0.14, with about 14%
  of samples collapsing.
- A larger, higher-aspect-ratio passive design reaches substantially higher
  model Cp.
- The project compares passive CPPC with fixed-rpm and fair rigid-blade
  baselines, but these are **model comparisons**, not predictions for a
  built machine.

### How I used AI

I wrote the specification, chose the physics, set the validation targets,
and debugged failures. The AI wrote much of the syntax.

The interesting part was not generating code—it was catching the AI’s
convention errors. The first version had the pitch sign flipped and Cp came
out roughly 30× too low. Finding that required understanding the model, not
just reading the code.

### What I work with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Numba](https://img.shields.io/badge/Numba-EE4C2C?style=flat-square&logo=numba&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![FreeCAD](https://img.shields.io/badge/FreeCAD-2E3F53?style=flat-square&logo=freecad&logoColor=white)

### Currently

- Continuing Sharp VAWT Lab: polar database, CAD model, and experimental
  validation plan
- Gymnasium year 10 in Nuremberg
- Interested in physics, maths, and IT

### Contact

[![Email](https://img.shields.io/badge/Email-juroc58%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:juroc58@gmail.com)

---

*“First make it work. Then make it right. Then make it on the roof.”*

[https://github.com/juroc58/sharp-vawt-lab](https://github.com/juroc58/sharp-vawt-lab)
