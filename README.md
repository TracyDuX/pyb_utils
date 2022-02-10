# pyb_utils: utilities for PyBullet

This is a collection of utilities I've found useful for working with PyBullet,
including:
* Collision detection: conveniently set up shortest distance computations and
  collision checking between arbitrary objects in arbitrary configurations with
  PyBullet. See the accompanying [blog post](https://adamheins.com/blog/collision-detection-pybullet).
* Ghost objects: add purely visual objects to the simulation, optionally
  attached to another body.
* Camera: virtual camera from which to get RGBA, depth, segmentation, and point
  cloud data. Also provides video recording using OpenCV.

## Install and run
This package requires **Python 3.7+**.

### From source
Clone the repo:
```bash
git clone https://github.com/adamheins/collision-detection-pybullet
cd collision-detection-pybullet
```

Install using [poetry](https://python-poetry.org/):
```bash
poetry install
poetry run python scripts/collision_detection_example.py  # for example
```

Or using pip:
```bash
python -m pip install .
```

### Directly from GitHub
```
python -m pip install git+https://github.com/adamheins/pyb_utils
```

## Usage and examples
You can find example scripts demonstrating all of this package's utilities in
the `scripts/` directory.

## License
MIT
