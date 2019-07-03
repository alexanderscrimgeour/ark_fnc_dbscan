# fnc_dbscan.sqf

This sqf function performs [Density-based spatial clustering of applications with noise](https://en.wikipedia.org/wiki/DBSCAN) (DBSCAN). 

## Usage

To use this function call `[units, eps, minPts, markers] call fnc_dbscan;`

| Argument | Type |Description |
|-|-|-|
| `units` | array\<object\> | The array of objects you wish to pass to the clustering algorithm.
| `eps` | number | The radius used in checking for `minPts` |
| `minPts` | number | The minimum number of neighbours required to be considered a cluster |
| `markers` | boolean | If true, places a marker on each `units` with their cluster. Black triangles are outliers. |