# svg-to-path

## Description:
Converts an SVG path to a list of coordinate points

## Prerequisites:
[Python (preferably 3.9 or above)](https://www.python.org/downloads/)

## How to Use: <br>
Import the file into another python file and use as a package <br>
```python
from plot_points import *

path = svgToPath(svg_file_location)
path.convert()
path.writeToFile(path_file_location)

readPath = readFromPath(path_file_location)
print(readPath)
```

## Built Using:
* re module (regex / parsing svg file)


## License
Distributed under the [GNU GPLv3 License](https://choosealicense.com/licenses/gpl-3.0/). See <code>LICENSE</code> for more information.