# Python start for Applied Artificial Intelligence

This folder provides a self-contained Python introduction for **Applied Artificial Intelligence (AAI)**. It is designed for a mixed audience: some students may be opening Python for the first time, while others already write production code.

The notebooks therefore use a layered approach. The main path teaches the concepts needed later in the course, optional sections offer extra context, and short **Your turn** exercises let you change or complete a few lines yourself. Exercises intentionally contain no solutions.

## Recommended order

| Notebook | Purpose | Relative importance |
|---|---|---|
| `00_01_Recap_Basics.ipynb` | Python syntax, types, collections, control flow, functions, errors, and optional language features | Essential for beginners. Useful as a reference for everyone |
| `00_02_OOP.ipynb` | Minimal object-oriented programming needed to understand class-based library APIs | Short orientation |
| `00_03_Pandas.ipynb` | Loading, inspecting, cleaning, transforming, grouping, joining, and reshaping tables | Essential throughout AAI |
| `00_04_Numpy.ipynb` | Arrays, vectorization, broadcasting, axes, random numbers, and linear algebra | Essential for numerical and ML work |
| `00_05_Plotting.ipynb` | Reusable Matplotlib and Seaborn workflows for exploration and communication | Essential for analysis and reporting |

Work through the notebooks in order if you are new to Python. Experienced students can use the headings as a checklist and focus on unfamiliar sections.

## Requirements

The environment and Git setup PDFs are available in `Environment_Setup_Guides/`.

## Exercises

Exercise cells are tagged `exercise` and marked with `# TODO`. They are deliberately small and independent of later examples. Replace `None`, modify the indicated expression, or add the requested lines. No solutions are included, so discuss uncertain results with fellow students or in the discussion/exercise.

## Synthetic dataset

`data/aai_student_data.csv` contains 69 entirely fictional student records generated deterministically for these tutorials. The rows do **not** describe real students, courses, grades, or behavior at the University of Bayreuth or anywhere else. Intentional missing values support data-cleaning exercises.

## Style and attribution

All explanations and examples in these notebooks were created for this AAI course. Some section titles and the broad introductory ordering were inspired by the [W3Schools Python Tutorial](https://www.w3schools.com/python/). This attribution concerns the outline only. The instructional text, code, exercises, and synthetic data are original to this repository.

## Further documentation

- [Official Python tutorial](https://docs.python.org/3/tutorial/)
- [NumPy user guide](https://numpy.org/doc/stable/user/)
- [Pandas user guide](https://pandas.pydata.org/docs/user_guide/index.html)
- [Matplotlib tutorials](https://matplotlib.org/stable/tutorials/index.html)
- [Seaborn tutorial](https://seaborn.pydata.org/tutorial.html)
