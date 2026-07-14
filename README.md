# Singapore International Mathematical and Computational Challenge 2024 — Endeavour Challenge

My solution to the **Endeavour Challenge** of the Singapore International Mathematical
and Computational Challenge (SIMC) 2024 — a multi-task computational problem — worked
as part of my preparation for SIMC 2026.

## The problem

The challenge ships a bundle of NumPy arrays (`Data/endeavour.npz`, keyed `task1`
onward), each feeding a sub-task in the official statement
(`SIMC_2024_Endeavour_Challenge.pdf`). Several tasks involve reshaping flattened
vectors into small images (for example 33x33) and reasoning about rotations,
symmetry, and pattern structure, including reconstructing patterns from partial
orientation classes.

## Approach

- `main.py` loads `endeavour.npz`, inspects array shapes, reshapes samples into
  images, and works with rotations and symmetry.
- `first_task.py` through `seventh_task.py` — one script per sub-task.
- `test.py` — scratch checks.

The full reasoning and answers are in `Solution_SIMC_2024.pdf`.

## Structure

```
Code/                    one script per task (first_task.py ... seventh_task.py) plus main.py
Data/
  endeavour.npz          packed arrays, one per task
SIMC_2024_Endeavour_Challenge.pdf   official problem statement
Solution_SIMC_2024.pdf              solution write-up
```

The scripts load `endeavour.npz` by filename, so run them from inside `Data/`
(or adjust the path) to reproduce the results.

## Related

Part of my preparation for the Singapore International Mathematical and Computational
Challenge (SIMC) 2026:

- [Risk-Weighted Assets Optimization](https://github.com/maksimkaprosuperhacker/Risk-Weighted-Assets-Optimization)
- [Species Differentiation of Lizards](https://github.com/maksimkaprosuperhacker/Species-Differentiation-of-Lizards)
- [SIMC 2024 Endeavour Challenge](https://github.com/maksimkaprosuperhacker/Singapore-International-Mathematical-and-Computational-Challenge-2024-Endeavor-Challenge) — this repository
- [IMMC 2026 Wildfire Modeling](https://github.com/maksimkaprosuperhacker/IMMC-2026)

Index: [Preparation for SIMC 2026](https://github.com/maksimkaprosuperhacker/Preparation-for-SIMC-2026)

## Author

- [@maksimkaprosuperhacker](https://github.com/maksimkaprosuperhacker)
