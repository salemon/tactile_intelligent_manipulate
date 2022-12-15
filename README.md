 [![Python Package using Conda](https://github.com/salemon/tactile_intelligent_manipulate/actions/workflows/python-package-conda.yml/badge.svg)](https://github.com/salemon/tactile_intelligent_manipulate/actions/workflows/python-package-conda.yml) <br/>
 
# Tactile Intelligent Manipulate

## Marker Tracking Algorithm

## Requirement

* opencv
* pybind11
* numpy

```
pip3 install pybind11 numpy opencv-python
```

## Example

```
make
python3 src/tracking/src/tracking.py
```

### Shear force test
* **Pink arrow**: the marker is out of boundary/not detected, but can be inferred from surrounding flow (assume same first derivative)

![](src/tracking/results/shear_flow.gif)

### Twist force test
![](src/tracking/results/twist_flow.gif)


## Configuration

Configuration based on different marker settings (marker number/color/size/interval)