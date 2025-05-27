## Physics 215 Project
Author: Kelvin Bartilad
Topic: Classifying leaves using Dynamic Time Warping and Shapelets Transformation

## How to replicate the work
1. Clone this repo.
2. Recreate the environment by navigating to the `scripts` directory and type `conda env create -f environment.yml` in the terminal.
3. Activate the environment and run `classify_leaves.ipynb` to reproduce the figures. It should run but you won't see the full page unless you also install Quarto (https://quarto.org/docs/get-started/)
4. If you have Quarto, type `quarto preview classify_leaves.ipynb` in the terminal to get a preview of the page. Else type `quarto render classify_leaves.ipynb --to html` to get a local render of the webpage.
5. Open `classify_leaves.html` in the `scripts` directory to see the page rendered using Quarto.
6. Figures are saved in the `results` directory