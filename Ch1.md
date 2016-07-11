1.4
---
Example 1:
```mathematica
f = #^3 - 7 #^2 + 28 &
Plot[f[x], {x, -10, 10}, PlotRange -> {-10, 10}]
```
Example 3:
```mathematica
f = 1/(2 - #) &
Plot[f[x], {x, -10, 10}, PlotRange -> {-10, 10}]
```
