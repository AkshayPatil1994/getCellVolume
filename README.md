This utility computes the average cell volume of the computational grid, which can be used to estimate the GCI metrics such as average representative grid size.

## How to compile the code?

Make sure that OpenFOAM is sourced on your current terminal session

1. Copy the code base to the location 
```
OpenFOAM/username-ofversion/applications/utilities/getCellVolume
```

2. Enter the `getCellVolume` directory and compile
```
wmake
```

## Example output from the code

```
Create time

Create mesh for time = 8000


Average cell Volume (V_bar): 1935.2512


Total cell Volume (V): 1.7544206e+10


Average representative length scale (h): 12.461752


ExecutionTime = 2.63 s  ClockTime = 14 s

End
```


