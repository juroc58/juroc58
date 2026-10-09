# Hi, I'm juroc58 👋

**16 · Nuremberg, Germany · Gymnasium year 10 · physics & maths**

---

### Why I built this

My dad and I want to put a Sharp cycloturbine on our roof. So I built a
solver for one first — one week, Python and Numba, heavy AI assistance.

The goal is a real machine, not a paper. Everything in the repo is
oriented toward "can this actually be built on a rooftop."

### Sharp VAWT Lab

[![tests](https://github.com/juroc58/sharp-vawt-lab/actions/workflows/test.yml/badge.svg)](https://github.com/juroc58/sharp-vawt-lab/actions/workflows/test.yml)

[**sharp-vawt-lab**](https://github.com/juroc58/sharp-vawt-lab) — a validated
2D BEM solver for the Sharp cycloturbine (passive variable-pitch VAWT).

| | |
|---|---|
| **Physics** | DMS induction, MIT dynamic stall, Adams curvature, Sharp CPPC, Active Lift |
| **Validation** | Ham 1979 (Cp = 0.49), Bayly-Kentfield (Cp = 0.36) |
| **Uncertainty** | 8-parameter Latin hypercube + Spearman sensitivity |
| **Tests** | 26 pytest, CI green on every push |
| **Docs** | 647-line derivation with source-paper references |

### How I used AI

I wrote the specification, chose the physics, set the validation targets,
and debugged the failures. The AI wrote most of the syntax.

The interesting part wasn't the code — it was catching the AI's own
convention errors. The first version had the pitch sign flipped and Cp
came out 30× too low. Finding that bug required understanding the model,
not reading the code.

### What I work with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Numba](https://img.shields.io/badge/Numba-00A3E0?style=flat-square&logo=numba&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![FreeCAD](https://img.shields.io/badge/FreeCAD-2E3F53?style=flat-square&logo=freecad&logoColor=white)

### Currently

- Continuing work on the Sharp VAWT Lab (polar database, CAD model)
- Gymnasium year 10 in Nuremberg
- Interested in physics, maths and IT

### Contact

[![Email](https://img.shields.io/badge/Email-juroc58%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:juroc58@gmail.com)

---

*"First make it work. Then make it right. Then make it on the roof."*
