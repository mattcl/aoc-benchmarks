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
| mattcl | input-mattcl | 0.7 ± 0.3 | 0.1 | 1.1 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.08 ± 0.50 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.1 | 1.09 ± 0.53 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.3 | 1.12 ± 0.50 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.3 | 1.14 ± 0.49 |
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.3 | 1.16 ± 0.51 |
| mattcl | input-chancalan | 0.8 ± 0.1 | 0.1 | 1.1 | 1.17 ± 0.48 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.1 | 1.6 | 1.22 ± 0.53 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.3 | 1.22 ± 0.52 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.7 | 1.22 ± 0.53 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.5 | 1.24 ± 0.52 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.3 | 1.5 | 1.24 ± 0.53 |
| aspidites | input-mattcl | 13.1 ± 0.5 | 11.4 | 14.8 | 18.52 ± 6.95 |
| aspidites | input-aspidites | 13.1 ± 0.5 | 12.1 | 14.8 | 18.52 ± 6.94 |
| aspidites | input-pting | 13.1 ± 0.5 | 11.8 | 15.0 | 18.52 ± 6.94 |
| aspidites | input-lanjian | 13.1 ± 0.4 | 12.3 | 14.8 | 18.56 ± 6.95 |
| aspidites | input-kcen | 13.1 ± 0.5 | 12.1 | 14.8 | 18.56 ± 6.96 |
| aspidites | input-chancalan | 13.2 ± 2.3 | 11.6 | 44.9 | 18.60 ± 7.67 |
| mattcl-py | input-chancalan | 16.6 ± 0.5 | 15.9 | 19.7 | 23.47 ± 8.78 |
| pting | input-aspidites | 16.6 ± 0.7 | 15.5 | 19.8 | 23.51 ± 8.82 |
| pting | input-chancalan | 16.6 ± 0.6 | 15.3 | 19.6 | 23.53 ± 8.82 |
| pting | input-lanjian | 16.6 ± 0.7 | 15.7 | 19.7 | 23.53 ± 8.83 |
| pting | input-kcen | 16.7 ± 0.7 | 15.7 | 19.4 | 23.60 ± 8.86 |
| pting | input-mattcl | 16.7 ± 0.6 | 15.8 | 19.6 | 23.61 ± 8.84 |
| mattcl-py | input-pting | 16.7 ± 0.6 | 15.5 | 19.7 | 23.64 ± 8.86 |
| mattcl-py | input-lanjian | 16.7 ± 0.7 | 15.6 | 20.0 | 23.64 ± 8.87 |
| mattcl-py | input-mattcl | 16.8 ± 0.7 | 15.4 | 20.0 | 23.69 ± 8.89 |
| mattcl-py | input-kcen | 16.8 ± 0.7 | 15.9 | 19.8 | 23.70 ± 8.89 |
| pting | input-pting | 16.8 ± 0.7 | 15.8 | 20.1 | 23.70 ± 8.90 |
| mattcl-py | input-aspidites | 16.8 ± 0.7 | 15.9 | 20.1 | 23.76 ± 8.92 |
| chancalan | input-chancalan | 17.4 ± 0.7 | 16.3 | 20.6 | 24.65 ± 9.24 |
| chancalan | input-kcen | 17.5 ± 0.6 | 16.3 | 20.5 | 24.72 ± 9.27 |
| chancalan | input-mattcl | 17.5 ± 0.7 | 16.5 | 21.3 | 24.75 ± 9.28 |
| chancalan | input-aspidites | 17.5 ± 0.7 | 16.3 | 20.8 | 24.75 ± 9.28 |
| chancalan | input-lanjian | 17.6 ± 0.7 | 16.6 | 21.0 | 24.82 ± 9.31 |
| chancalan | input-pting | 17.6 ± 0.7 | 16.6 | 20.8 | 24.90 ± 9.34 |
| kcen | input-lanjian | 17.9 ± 0.8 | 17.0 | 21.5 | 25.37 ± 9.53 |
| kcen | input-aspidites | 17.9 ± 0.7 | 16.6 | 21.3 | 25.38 ± 9.52 |
| kcen | input-kcen | 18.0 ± 0.8 | 16.8 | 21.2 | 25.46 ± 9.56 |
| kcen | input-chancalan | 18.0 ± 0.8 | 16.6 | 21.7 | 25.47 ± 9.57 |
| kcen | input-mattcl | 18.0 ± 0.7 | 17.2 | 21.7 | 25.51 ± 9.57 |
| kcen | input-pting | 18.1 ± 0.8 | 17.0 | 21.5 | 25.55 ± 9.59 |
| mikofo | input-chancalan | 320.2 ± 2.1 | 317.5 | 323.6 | 452.68 ± 168.87 |
| mikofo | input-mattcl | 320.2 ± 2.5 | 316.3 | 323.3 | 452.73 ± 168.90 |
| mikofo | input-lanjian | 320.6 ± 1.9 | 317.3 | 323.4 | 453.25 ± 169.07 |
| mikofo | input-kcen | 321.0 ± 2.5 | 317.2 | 326.5 | 453.85 ± 169.31 |
| mikofo | input-aspidites | 321.8 ± 2.9 | 318.1 | 327.6 | 454.93 ± 169.73 |
| mikofo | input-pting | 324.8 ± 16.4 | 315.3 | 368.0 | 459.21 ± 172.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|