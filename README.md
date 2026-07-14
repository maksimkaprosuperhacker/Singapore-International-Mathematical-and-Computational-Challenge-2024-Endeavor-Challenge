# SIMC — Proteins Problem (2024 Endeavour Challenge)

My solution to the **SIMC 2024 Endeavour Challenge**, a multi-task computational
problem worked through as part of my preparation for the Singapore International
Mathematical and Computational Challenge (SIMC).

## The problem

The challenge ships a bundle of NumPy arrays (`Data/endeavour.npz`, keyed `task1`
onward), each feeding a sub-task in the official statement
(`SIMC_2024_Endeavour_Challenge.pdf`). Several tasks involve reshaping flattened
vectors into small images (for example 33x33) and reasoning about rotations,
symmetry, and pattern structure.

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

## Related repositories

Part of my SIMC preparation:

- [SIMC — RWA Problem](https://github.com/maksimkaprosuperhacker/SIMC-RWA-Problem) — risk-weighted asset optimisation
- [SIMC — Lizards Problem](https://github.com/maksimkaprosuperhacker/SIMC-Lizards-Problem) — species differentiation by parameter search
- [SIMC — Proteins Problem](https://github.com/maksimkaprosuperhacker/SIMC-Proteins-Problem) — SIMC 2024 Endeavour image and pattern tasks (this repository)
- [Preparation for SIMC 2026](https://github.com/maksimkaprosuperhacker/Preparation-for-SIMC-2026) — all three problems collected together

## Author

- [@maksimkaprosuperhacker](https://github.com/maksimkaprosuperhacker)
