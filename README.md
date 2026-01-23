# Python Refresher Labs – M1 Data Science, Centrale Lille

This repository collects my lab work from the **Python Refresher / Python and Tools for Research** course in **M1 Data Science** (first year of the Master's program) at Centrale Lille (2025-2026).

The labs focus on the Python ecosystem used in data science: environment management, project structure, testing, scientific computing, data analysis, visualization, code acceleration, and parallel computing.

---

## Course overview

| Area | Topics |
| --- | --- |
| Python tooling | Environments, package management, project structure, notebooks, code quality tools |
| Scientific computing | NumPy, SciPy, random variables, linear algebra, Fourier transforms |
| Data analysis | Pandas, Titanic dataset cleaning, feature handling, basic model training |
| Visualization | Matplotlib and Seaborn |
| Testing | `unittest`, `pytest`, fixtures, small package examples |
| Performance | Profiling, Cython, Numba, compiled extensions |
| Parallel computing | `multiprocessing`, Dask arrays, delayed tasks, distributed execution |

---

## Repository structure

```
python-labs/
├── lab1_python_environment_basics/
│   ├── main.ipynb
│   ├── README.md
│   ├── examples/
│   ├── src/tutorial/
│   └── tests/
├── lab2_numpy_pandas_matplotlib/
│   ├── main.ipynb
│   ├── data/
│   └── samples.npy
├── lab3_titanic_dataset_fourier_transform/
│   └── main.ipynb
├── lab4_cython_numba/
│   ├── main.ipynb
│   ├── data/
│   ├── example_cy/
│   └── example_np_cy/
├── lab5_seaborn_dask_multiprocessing/
│   └── main.ipynb
├── README.md
└── requirements.txt
```

Each lab folder contains the completed Jupyter notebook and any supporting data, scripts, tests, or compiled-code examples provided or produced for the assignment. The original course instructions are preserved inside the notebooks where applicable.

---

## Lab index

| Folder | Contents |
| --- | --- |
| `lab1_python_environment_basics/` | Environment setup, project structure, command-line basics, toy package, examples, and `unittest`/`pytest` tests |
| `lab2_numpy_pandas_matplotlib/` | NumPy, SciPy, Pandas, h5py, Matplotlib, sample data, and array data |
| `lab3_titanic_dataset_fourier_transform/` | Titanic data handling, exploratory analysis, feature preparation, Fourier transforms, image filtering, and convolution |
| `lab4_cython_numba/` | K-nearest neighbors classification, scikit-learn comparison, Cython examples, Numba acceleration, and benchmark data |
| `lab5_seaborn_dask_multiprocessing/` | Seaborn visualization, Markov chain simulation, multiprocessing, Dask arrays, delayed computation, and distributed execution |

---

## Technologies

- Python
- NumPy, SciPy, Pandas, h5py
- Matplotlib, Seaborn
- Scikit-learn
- Pillow
- Jupyter Notebook / JupyterLab
- Cython, Numba
- Dask, multiprocessing
- `unittest`, `pytest`
- Black, pylint, isort, pre-commit

---

## Skills demonstrated

- Managing Python environments and dependencies
- Structuring small Python projects and packages
- Writing and running unit tests
- Using NumPy and SciPy for numerical computing
- Cleaning and analyzing data with Pandas
- Producing visualizations with Matplotlib and Seaborn
- Applying basic machine learning workflows with scikit-learn
- Working with image-processing and Fourier-transform workflows
- Profiling and accelerating Python code with Cython and Numba
- Running parallel computations with multiprocessing and Dask
- Maintaining reproducible notebook-based lab work

---

## Author

Danila Pechenev

M1 Data Science – Centrale Lille
