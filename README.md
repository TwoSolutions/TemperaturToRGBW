[![PyPI version](https://badge.fury.io/py/temp-to-rgbw.svg)](https://badge.fury.io/py/temp-to-rgbw)
# TemperatureToRGBW
Convert a Kelvin Temperature to RGBW

Install:

pip install temp-to-rgbw

Usage:
```python
from temptorgbw_pkg import TemperatureToRGBW
r,g,b,w = TemperatureToRGBW.kelvin_to_rgbw(temperature)
```
Note: Any temperature smaller then 1000 will be capped to 1000 and any temperature bigger then 40000 will be capped to 40000
