# Segment 21340 - Signal Comparator

```
> READ A VALUE FROM IN
> WRITE 1 TO OUT.G IF IN > 0
> WRITE 1 TO OUT.E IF IN = 0
> WRITE 1 TO OUT.G IF IN < 0
> WHEN A 1 IS NOT WRITTEN TO
  AN OUTPUT, WRITE A 0 INSTEAD
```

## Level map

```
 IN
+---+---+---+---+
|   |   |   |   |
+---+---+---+---+
|   | X | X | X |
+---+---+---+---+
|   |   |   |   |
+---+---+---+---+
      G   E   L
```

## Achievement
UNCONDITIONAL - Solve SIGNAL COMPARATOR without using the JGZ, JLZ, JEZ, or JNZ instructions.
