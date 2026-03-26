# iNeuron Assignments Repository

This repository collects a set of Python and general programming assignments completed as Jupyter notebooks, along with a small supporting Python module. The materials appear to be organized as individual submission files for iNeuron coursework and cover Python basics, standard library usage, files, object-oriented programming, and introductory programming exercises.

## Repository Contents

### Assignment notebooks
The root of the repository contains **29 Jupyter notebooks**:

- `Assignment_1.ipynb` through `Assignment_25.ipynb`
- `Assignment 18.ipynb` and `Assignment 21.ipynb` (saved with spaces in the filename)
- `Advance Assignment.ipynb`
- `Programming_assignment_1.ipynb`
- `Programming_assignment_2.ipynb`
- `Programming _Assignment_3.ipynb`

These notebooks include question-and-answer style work on topics such as:

- Python fundamentals: values, variables, Boolean types, lists, dictionaries, strings, and functions
- File handling and paths
- Regular expressions
- Common standard-library modules
- Object-oriented programming concepts
- Introductory programming practice problems

### Python module
- `zoo.py` contains a simple helper function:
  - `hours()` returns the string `Open 9-5 daily`

### Other directories
- `Live_Class/` exists in the repository and can be used for additional live class material.

## Suggested Setup

To review the notebooks locally, install Jupyter in a Python environment:

```bash
python -m venv .venv
source .venv/bin/activate
pip install notebook
jupyter notebook
```

Then open any of the notebook files from the Jupyter interface.

## Working With This Repository

### Run the Python module
You can test the included module from the command line:

```bash
python -c "import zoo; print(zoo.hours())"
```

### Open a notebook
If you prefer JupyterLab, you can use:

```bash
pip install jupyterlab
jupyter lab
```

## Notes

- File naming is not fully uniform: some notebooks use underscores and others include spaces.
- Most of the repository content is notebook-based, so version diffs may be larger than for plain `.py` files.
- If you want a cleaner long-term structure, consider grouping notebooks into folders such as `assignments/`, `programming_assignments/`, and `advanced_assignments/`.

## Quick Index of Notebook Topics

| File | First listed prompt/topic |
| --- | --- |
| `Advance Assignment.ipynb` | Relationship between classes and modules |
| `Assignment_1.ipynb` | Values vs. expressions |
| `Assignment_2.ipynb` | Boolean data type |
| `Assignment_3.ipynb` | Advantages of functions |
| `Assignment_4.ipynb` | Meaning of `[]` |
| `Assignment_5.ipynb` | Empty dictionaries |
| `Assignment_6.ipynb` | Escape characters |
| `Assignment_7.ipynb` | Regex object generation |
| `Assignment_8.ipynb` | PyInputPlus and the standard library |
| `Assignment_9.ipynb` | Relative paths |
| `Assignment_10.ipynb` | `shutil.copy()` vs `shutil.copytree()` |
| `Assignment_11.ipynb` | Assertion example |
| `Assignment_12.ipynb` | `PdfFileReader()` / `PdfFileWriter()` modes |
| `Assignment_13.ipynb` | Excel vs. CSV |
| `Assignment_14.ipynb` | RGBA |
| `Assignment_15.ipynb` | Seconds in an hour |
| `Assignment_16.ipynb` | `years_list` exercise |
| `Assignment_17.ipynb` | Conditional logic exercise |
| `Assignment 18.ipynb` | Create and import `zoo.py` |
| `Assignment_19.ipynb` | `Thing` class exercise |
| `Assignment_20.ipynb` | Write `test.txt` |
| `Assignment 21.ipynb` | Write current date to `today.txt` |
| `Assignment_22.ipynb` | Explain code result |
| `Assignment_23.ipynb` | Explain code result and why |
| `Assignment_24.ipynb` | `def` vs. `lambda` |
| `Assignment_25.ipynb` | List comprehension brackets vs. parentheses |
| `Programming_assignment_1.ipynb` | Print `Hello Python` |
| `Programming_assignment_2.ipynb` | Kilometers to miles |
| `Programming _Assignment_3.ipynb` | Positive/negative/zero check |


