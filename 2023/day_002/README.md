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
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.29 |
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.28 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.32 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.5 | 1.05 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.6 | 1.06 ± 0.29 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.08 ± 0.31 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.08 ± 0.31 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.5 | 1.4 | 1.09 ± 0.29 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.4 | 1.9 | 1.10 ± 0.32 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.4 | 1.8 | 1.13 ± 0.30 |
| aspidites | input-kcen | 13.0 ± 0.5 | 11.8 | 14.2 | 14.78 ± 3.13 |
| aspidites | input-aspidites | 13.1 ± 0.5 | 12.1 | 14.6 | 14.95 ± 3.17 |
| aspidites | input-mattcl | 13.1 ± 0.4 | 12.2 | 14.5 | 14.97 ± 3.16 |
| aspidites | input-lanjian | 13.2 ± 0.4 | 12.2 | 14.6 | 15.02 ± 3.18 |
| aspidites | input-chancalan | 13.2 ± 0.4 | 12.1 | 15.1 | 15.02 ± 3.17 |
| aspidites | input-pting | 13.2 ± 0.5 | 11.8 | 14.6 | 15.06 ± 3.20 |
| mattcl-py | input-mattcl | 16.4 ± 0.5 | 15.6 | 19.1 | 18.77 ± 3.96 |
| pting | input-mattcl | 16.5 ± 0.5 | 15.5 | 18.9 | 18.78 ± 3.97 |
| pting | input-lanjian | 16.5 ± 0.6 | 15.7 | 19.1 | 18.81 ± 3.99 |
| pting | input-aspidites | 16.5 ± 0.7 | 15.4 | 19.5 | 18.81 ± 4.00 |
| pting | input-pting | 16.5 ± 0.6 | 15.5 | 20.2 | 18.81 ± 3.99 |
| pting | input-kcen | 16.5 ± 0.6 | 15.5 | 19.4 | 18.85 ± 4.00 |
| mattcl-py | input-pting | 16.5 ± 0.6 | 15.6 | 20.0 | 18.85 ± 4.00 |
| pting | input-chancalan | 16.5 ± 0.6 | 15.4 | 19.2 | 18.85 ± 3.99 |
| mattcl-py | input-aspidites | 16.5 ± 0.6 | 15.4 | 19.6 | 18.86 ± 4.00 |
| mattcl-py | input-chancalan | 16.6 ± 0.7 | 15.5 | 19.5 | 18.98 ± 4.04 |
| mattcl-py | input-lanjian | 16.6 ± 0.8 | 15.6 | 19.8 | 18.98 ± 4.06 |
| mattcl-py | input-kcen | 16.7 ± 0.8 | 15.8 | 19.8 | 19.06 ± 4.08 |
| chancalan | input-aspidites | 17.2 ± 0.5 | 16.4 | 20.0 | 19.67 ± 4.15 |
| chancalan | input-lanjian | 17.3 ± 0.7 | 16.3 | 20.2 | 19.77 ± 4.19 |
| chancalan | input-mattcl | 17.3 ± 0.6 | 16.4 | 20.1 | 19.79 ± 4.19 |
| chancalan | input-kcen | 17.4 ± 0.7 | 16.3 | 20.2 | 19.86 ± 4.22 |
| chancalan | input-pting | 17.6 ± 1.8 | 16.4 | 38.4 | 20.04 ± 4.64 |
| kcen | input-chancalan | 17.7 ± 0.5 | 16.7 | 20.7 | 20.17 ± 4.25 |
| kcen | input-mattcl | 17.7 ± 0.5 | 17.0 | 20.3 | 20.18 ± 4.25 |
| chancalan | input-chancalan | 17.7 ± 4.4 | 16.2 | 59.4 | 20.19 ± 6.55 |
| kcen | input-lanjian | 17.7 ± 0.7 | 16.9 | 20.9 | 20.22 ± 4.30 |
| kcen | input-aspidites | 17.7 ± 0.6 | 16.7 | 20.9 | 20.24 ± 4.29 |
| kcen | input-kcen | 17.7 ± 0.6 | 17.0 | 20.4 | 20.24 ± 4.28 |
| kcen | input-pting | 18.0 ± 1.7 | 16.7 | 37.9 | 20.49 ± 4.71 |
| mikofo | input-mattcl | 314.5 ± 1.7 | 312.6 | 317.5 | 358.92 ± 74.94 |
| mikofo | input-chancalan | 315.1 ± 2.2 | 311.1 | 317.7 | 359.56 ± 75.09 |
| mikofo | input-aspidites | 315.1 ± 1.0 | 312.7 | 316.0 | 359.57 ± 75.06 |
| mikofo | input-lanjian | 315.2 ± 1.5 | 313.3 | 318.2 | 359.73 ± 75.11 |
| mikofo | input-kcen | 315.4 ± 1.7 | 313.5 | 318.3 | 359.96 ± 75.16 |
| mikofo | input-pting | 316.5 ± 2.5 | 312.6 | 320.7 | 361.24 ± 75.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|