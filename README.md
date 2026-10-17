# Data Science Studies

A collection of notebooks I created while taking courses to learn data science with Python, NumPy and Pandas (from [Alura](https://www.alura.com.br/)'s Data Science track).

## Contents

| Folder | Course | Topics |
|---|---|---|
| [`01-python-primeiros-passos`](01-python-primeiros-passos) | Python for Data Science: first steps | Variables, strings, user input, conditionals, loops, lists and dictionaries, plus practice exercises. |
| [`02-python-funcoes-estruturas-excecoes`](02-python-funcoes-estruturas-excecoes) | Python for Data Science: functions, data structures and exceptions | Libraries, functions (including `lambda` and `map`), list and dict comprehensions, exception handling, plus practice exercises. |
| [`03-numpy`](03-numpy) | NumPy | Apple price time series across 5 cities: array slicing, missing values and least-squares linear regression. Challenge on orange vs. grapefruit diameter and weight. |
| [`04-pandas-conhecendo-a-biblioteca`](04-pandas-conhecendo-a-biblioteca) | Pandas: getting to know the library | Exploratory analysis of a Rio de Janeiro rental dataset: grouping, null handling, filtering, new columns and charts, plus each lesson's challenges. |
| [`05-pandas-io`](05-pandas-io) | Pandas: input and output formats | Reading and writing CSV, Excel, Google Sheets and JSON from an API, including `json_normalize`. Uses CO₂ emissions and Brazilian public health (SUS) data. |

The notebooks are written in Portuguese.

## Running

The notebooks were built in Google Colab and load their data from URLs. To open one in Colab, replace `github.com` with `githubtocolab.com` in the file's URL.

To run locally:

```bash
pip install numpy pandas matplotlib openpyxl requests
jupyter notebook
```

Some cells use `input()` and wait for you to type a value.

## Credits

Exercise prompts, explanatory text and datasets come from Alura's courses ([alura-cursos](https://github.com/alura-cursos)). The solution code is my own.
