# MS1

<<<<<<< HEAD
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Mesnage-Org/PGFinder/master?urlpath=tree/pgfinder-demo.ipynb)
=======
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Mesnage-Org/Mass-Spec-MS1-Analysis/jupyter?filepath=ms1-demo.ipynb)
>>>>>>> parent of cbb58c2 (rename ms1 to pgfinder)
## Installation

Install [miniconda](https://docs.conda.io/en/latest/miniconda.html) (it also works with [anaconda](https://docs.anaconda.com/anaconda/install/), but we do not need the extra packages). With conda installed, run the following commands to create the virtual environment and activate it:

```
conda env create -f environment.yml
conda activate ms1
```
## Usage

```
python demo.py
```

## Testing

To run tests:

```
pytest
```

The tests check output against an [expected baseline](data/baseline_output.csv). To recreate this (e.g. in response to improvements to the scientific "correctness" of the code ouput), use:

```
python make_baseline.py
```

and replace the exisiting file.

**This software is licensed as specified by the [GPL License](COPYING) and [LGPL License](COPYING.LESSER).**