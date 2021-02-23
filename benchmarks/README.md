# Running Benchmarks

## GCC

to run

```bash
sim-safe cc1.alpha -O 1stmt.i
```

to test output

```bash
diff 1stmt.s 1stmt.s.ref
```

## ANAGRAM

to run

```bash
sim-safe anagram.alpha words < anagram.in > OUT
```

to test output

```bash
diff OUT anagram.out
```

## GO

to run

```bash
sim-safe go.alpha 50 9 2stone9.in > OUT
```

to test output

```bash
diff OUT go.out
```
