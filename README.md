# pycounts_alytow

Calculate word counts in a text file!

## Installation

```bash
$ pip install pycounts_alytow
```
## Usage

`pycounts_alytow` can be used to count words in a text file and plot results
as follows:

```python
from pycounts_alytow.pycounts_alytow import count_words
from pycounts_alytow.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_alytow` was created by Alysen Townsley. It is licensed under the terms of the MIT license.

## Credits

`pycounts_alytow` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
