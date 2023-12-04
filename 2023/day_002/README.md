# Day 2 benchmarks

[link to problem](https://adventofcode.com/2023/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [aspidites](https://github.com/aspidites/aoc2023) (haskell)
- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.7 ± 0.2 | 0.0 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.0 | 1.02 ± 0.44 |
| mattcl | input-chancalan | 0.7 ± 0.2 | 0.0 | 1.0 | 1.05 ± 0.44 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.43 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.0 | 2.0 | 1.06 ± 0.49 |
| mattcl | input-aspidites | 0.7 ± 0.2 | 0.1 | 1.2 | 1.07 ± 0.45 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.07 ± 0.46 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.0 | 1.0 | 1.09 ± 0.46 |
| lanjian | input-aspidites | 0.8 ± 0.2 | 0.0 | 1.2 | 1.12 ± 0.47 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.0 | 1.0 | 1.12 ± 0.47 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.12 ± 0.47 |
| lanjian | input-pting | 0.9 ± 3.2 | 0.0 | 46.0 | 1.31 ± 4.66 |
| aspidites | input-pting | 12.8 ± 0.5 | 12.0 | 14.3 | 18.52 ± 6.36 |
| aspidites | input-lanjian | 12.9 ± 0.4 | 11.9 | 14.0 | 18.57 ± 6.37 |
| aspidites | input-kcen | 12.9 ± 0.5 | 11.8 | 14.6 | 18.66 ± 6.41 |
| aspidites | input-chancalan | 12.9 ± 0.4 | 12.0 | 14.7 | 18.67 ± 6.41 |
| aspidites | input-aspidites | 13.0 ± 0.5 | 12.1 | 14.4 | 18.72 ± 6.43 |
| aspidites | input-mattcl | 13.0 ± 0.4 | 11.9 | 14.4 | 18.75 ± 6.43 |
| pting | input-lanjian | 16.2 ± 0.4 | 15.3 | 19.6 | 23.38 ± 8.01 |
| pting | input-mattcl | 16.2 ± 0.5 | 15.3 | 20.0 | 23.40 ± 8.03 |
| pting | input-pting | 16.3 ± 0.5 | 15.4 | 19.8 | 23.47 ± 8.05 |
| pting | input-aspidites | 16.3 ± 0.5 | 15.4 | 19.6 | 23.48 ± 8.06 |
| pting | input-chancalan | 16.3 ± 0.6 | 15.2 | 19.0 | 23.51 ± 8.08 |
| mattcl-py | input-mattcl | 16.3 ± 0.5 | 15.7 | 18.8 | 23.56 ± 8.09 |
| mattcl-py | input-lanjian | 16.4 ± 0.7 | 15.3 | 19.5 | 23.57 ± 8.11 |
| mattcl-py | input-aspidites | 16.4 ± 0.6 | 15.4 | 19.2 | 23.61 ± 8.11 |
| mattcl-py | input-kcen | 16.4 ± 0.6 | 15.5 | 19.2 | 23.63 ± 8.12 |
| mattcl-py | input-pting | 16.5 ± 0.6 | 15.7 | 19.4 | 23.72 ± 8.15 |
| pting | input-kcen | 16.5 ± 3.1 | 15.2 | 56.1 | 23.79 ± 9.25 |
| mattcl-py | input-chancalan | 16.5 ± 1.9 | 15.3 | 40.0 | 23.83 ± 8.57 |
| chancalan | input-aspidites | 17.0 ± 0.6 | 16.1 | 20.3 | 24.56 ± 8.44 |
| chancalan | input-lanjian | 17.1 ± 0.5 | 16.0 | 19.7 | 24.59 ± 8.43 |
| chancalan | input-mattcl | 17.1 ± 0.7 | 16.0 | 20.5 | 24.72 ± 8.51 |
| chancalan | input-chancalan | 17.1 ± 0.7 | 16.3 | 20.6 | 24.72 ± 8.51 |
| chancalan | input-pting | 17.2 ± 0.5 | 16.1 | 20.0 | 24.73 ± 8.47 |
| chancalan | input-kcen | 17.2 ± 0.6 | 16.2 | 20.0 | 24.76 ± 8.50 |
| kcen | input-aspidites | 17.5 ± 0.5 | 16.6 | 20.3 | 25.22 ± 8.65 |
| kcen | input-mattcl | 17.5 ± 0.5 | 16.9 | 21.0 | 25.27 ± 8.67 |
| kcen | input-lanjian | 17.5 ± 0.6 | 16.5 | 20.3 | 25.27 ± 8.67 |
| kcen | input-kcen | 17.6 ± 0.7 | 16.8 | 20.8 | 25.31 ± 8.71 |
| kcen | input-chancalan | 17.6 ± 0.7 | 16.6 | 20.9 | 25.36 ± 8.72 |
| kcen | input-pting | 17.6 ± 0.7 | 16.9 | 21.3 | 25.41 ± 8.74 |
| mikofo | input-lanjian | 313.8 ± 2.4 | 310.5 | 316.4 | 452.33 ± 154.54 |
| mikofo | input-kcen | 313.9 ± 1.8 | 311.6 | 316.9 | 452.56 ± 154.60 |
| mikofo | input-aspidites | 313.9 ± 2.2 | 311.2 | 317.3 | 452.57 ± 154.62 |
| mikofo | input-chancalan | 314.0 ± 1.7 | 312.0 | 316.4 | 452.75 ± 154.66 |
| mikofo | input-mattcl | 314.3 ± 1.3 | 311.6 | 316.1 | 453.16 ± 154.80 |
| mikofo | input-pting | 314.4 ± 1.7 | 312.1 | 317.6 | 453.31 ± 154.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|