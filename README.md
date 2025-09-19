# Computational Geometry

This repository contains implementations of various computational geometry algorithms and data structures in Python. The focus is on clarity and educational value, making it suitable for learning and experimentation.

## Environment setup for reproducibility

This repository uses Astral's `uv` as the main Python package and project manager. You can find more about `uv` in: https://docs.astral.sh/uv/.

If you have `uv` installed in your machine, you can run `uv sync` inside the repository directory. This will install the needed libraries. This repository uses the release version of Python 3.13, so bear in mind that you'll need to have this Python version installed, luckily, `uv` is also able to install and manage Python versions (https://docs.astral.sh/uv/guides/install-python/).

## Folder structure

This repository will have 2 main folders:

1. `assignments`: Here, you'll have access to my Jupyter Notebook codes and reports that were delivered to the professor as a way to grade my performance on the course.
2. `lessons`: This folder will contain the material shared by the professor on its lectures during the semester.

If the setup is correctly executed, every `.ipynb` notebook under assignments should work seamlessly with the "Run All" command that Jupyter provides. Some exercises will require simulation parts and for that I'll be using the `multiprocessing` library from Python, to achieve faster simulation times when running multiple benchmarks and executions. I'll try to push my assignments with simulations configured to run for only a few steps, to ensure nothing will take more than a few seconds in each cell.

## Assignments

As of right now, we're in the middle of the semester (30-august-2025). The list of assignments available are:

- Assignment 1: Minimum Circle. Calculate the minimum enclosing circle for a cloud of points using 2 different $O(n)$ techniques.
  - Code: [Jupyter Notebook](assignments/01_minimum_circle/minimum_circle.ipynb).
  - Report: [Report](assignments/01_minimum_circle/README.md).

- Assignment 2: Polygon Triangulation. Implement the Ear Clipping algorithm to triangulate simple polygons.
  - Code: [Jupyter Notebook](assignments/02_polygon_triangulation/polygon_triangulation.ipynb).
  - Report: [Report](assignments/02_polygon_triangulation/README.md).

## Markdown over $\LaTeX$

I'm personally a fan of using Markdown for documentation, notes and reports because of its simplicity, readability and ease of use. While $\LaTeX$ is powerful for typesetting complex mathematical formulas, Markdown strikes a good balance between ease of use and functionality for most documentation needs. Also, both export in PDF and are great for versioning with git, so, please, don't get angry just because I'm doing academic work with Markdown over $\LaTeX$.

Thanks, GG.
