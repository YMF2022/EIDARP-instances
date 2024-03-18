# Instances for the integrated electric dial-a-ride problem (EIDARP)
![badge1](https://img.shields.io/badge/language-julia-blue)

There are 8 instances that each has a dedicated folder. The name of instance folders have the structure of, e.g. *l2-c6-d2-bt2*, where:
- *l*: number of transit lines
- *c*: number of customers
- *d*: number of depots, currently there is one used
- *bt*: number of bus types

The transit network is a cross network:

<img
  src="cross_c3.png"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 900px">

## Files
Each instance folder contains the following files:
- *buses.csv*
- *chargers.csv*
- *customers.csv*
- *depots.csv*
- *tranStops.csv*
- *timetable_line1.csv* and *timetable_line2.csv*
- *other_parameters.csv*
