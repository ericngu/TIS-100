# Segment 22280 - Signal Multiplexer

```
> READ VALUES FROM 1N.A AND IN.B
> READ A VALUE FROM IN.S
> WRITE IN.A WHEN IN.S = -1
> WRITE IN.B WHEN IN.S = 1
> WRITE IN.A * IN.B WHEN IN.S = 0
```

## Level map

```
      A   S   B
+---+---+---+---+
|   |   |   |   |
+---+---+---+---+
|   |   |   |   |
+---+---+---+---+
| X |   |   |   |
+---+---+---+---+
         OUT
```

