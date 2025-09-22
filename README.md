# Week 1 — GitHub & Version Control Assignment

This repo is a starter pack for the Week 1 exercise: create a plot from `mammal_teeth.csv` and submit your work via a branch on GitHub.

## Files

- `week1_plot.py` — Python script that loads `mammal_teeth.csv` and saves `mammal_teeth_scatterplot.png`.
- `mammal_teeth.csv` — CSV file containing mammal teeth data.
- `README.md` — This file.

## Instructions (Quick Start)

1. **(Once)** Create and activate a conda environment:

   ```bash
   conda create -n HMB491_env python=3.11 -y
   conda activate HMB491_env
   conda install pandas matplotlib
   ```
2. Run the script (edit the title name or pass `--name`):

   ```bash
   python week1_plot.py --name "Your Name"
   ```
3. The script writes `mammal_teeth_scatterplot.png` to this folder.

## Suggested Branch Flow

- Create a fork of this repo, `github_id/HMB491_week1` (replace `github_id` with your GitHub username).
- In your fork, create a branch named: `graded_question`
- Switch over to the solution branch and complete the assignment
- Commit your changes and push the branch to your fork.
- Submit the **URL of your branch** on Quercus.
