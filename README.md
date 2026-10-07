# Brighter light felt better. It didn't help us see better.

An interactive write-up of a lighting experiment on visual recognition, by Haritha V A.
Course project for DESC9201 Indoor Environmental Quality, Faculty of Architecture, Design and Planning, University of Sydney.

**Live site:** https://YOUR-USERNAME.github.io/YOUR-REPO/

## The study

252 trials of a Landolt C gap-finding task (64 rings per sheet) under four illuminance levels (20, 80, 320 and 800 lux), using four sheet versions with larger or smaller rings and different contrast. After each trial, participants rated the lighting, task difficulty, effort and their own performance from 1 (good) to 7 (poor).

## Findings

- Lighting rating improved from 4.15 at 20 lux to 2.31 at 800 lux (1 is best).
- Mean score went from 53.8 at 20 lux to 51.1 at 800 lux, out of 64. The spread widened (standard deviation 11.6 to 14.3).
- Score and rating are barely related (r of about 0.10).
- Satisfaction and visual performance are different outcomes, so a brighter room is not automatically a better one for seeing.

Limits: one task, four light levels, student participants, so differences between levels are modest and individual variation is large.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The interactive site. Self-contained: data, images and code are inline. |
| `analysis/lighting_dataset.csv` | The 252-trial dataset. |
| `analysis/Data.ipynb` | Python analysis (pandas, seaborn, statsmodels). |

## Run locally

Open `index.html` in a browser. For the notebook: `pip install pandas seaborn matplotlib statsmodels jupyter`, then open `analysis/Data.ipynb` from the `analysis` folder.

## Contact

Haritha V A, harithaajith8@gmail.com
