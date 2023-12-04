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
| mattcl | input-chancalan | 0.7 ± 0.2 | 0.0 | 1.1 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.08 ± 0.45 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.0 | 1.0 | 1.09 ± 0.45 |
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.3 | 1.10 ± 0.46 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.10 ± 0.46 |
| lanjian | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.0 | 1.10 ± 0.47 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.1 | 1.12 ± 0.48 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.0 | 1.13 ± 0.44 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.14 ± 0.45 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.2 | 1.15 ± 0.47 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.17 ± 0.48 |
| lanjian | input-pting | 0.9 ± 0.1 | 0.4 | 1.2 | 1.24 ± 0.47 |
| aspidites | input-chancalan | 12.9 ± 0.6 | 11.5 | 14.4 | 18.04 ± 6.32 |
| aspidites | input-mattcl | 13.0 ± 0.5 | 11.8 | 14.3 | 18.13 ± 6.33 |
| aspidites | input-kcen | 13.0 ± 0.4 | 11.9 | 14.6 | 18.20 ± 6.34 |
| aspidites | input-aspidites | 13.0 ± 0.4 | 11.9 | 14.3 | 18.20 ± 6.34 |
| aspidites | input-pting | 13.0 ± 2.7 | 10.9 | 50.2 | 18.23 ± 7.39 |
| aspidites | input-lanjian | 13.1 ± 0.5 | 11.5 | 14.4 | 18.31 ± 6.39 |
| mattcl-py | input-aspidites | 16.3 ± 0.5 | 15.4 | 19.3 | 22.79 ± 7.94 |
| pting | input-chancalan | 16.3 ± 0.5 | 15.2 | 18.9 | 22.81 ± 7.94 |
| mattcl-py | input-lanjian | 16.3 ± 0.5 | 15.4 | 18.8 | 22.84 ± 7.95 |
| pting | input-pting | 16.4 ± 0.7 | 15.4 | 19.7 | 22.92 ± 8.01 |
| pting | input-mattcl | 16.4 ± 0.6 | 15.4 | 19.6 | 22.92 ± 8.00 |
| mattcl-py | input-kcen | 16.4 ± 0.6 | 15.5 | 19.4 | 22.97 ± 8.01 |
| mattcl-py | input-chancalan | 16.4 ± 0.6 | 15.3 | 19.7 | 22.97 ± 8.02 |
| mattcl-py | input-pting | 16.5 ± 0.6 | 15.6 | 19.6 | 23.00 ± 8.02 |
| pting | input-lanjian | 16.5 ± 0.8 | 15.3 | 19.9 | 23.04 ± 8.08 |
| pting | input-kcen | 16.5 ± 0.8 | 15.4 | 19.3 | 23.06 ± 8.08 |
| mattcl-py | input-mattcl | 16.5 ± 0.7 | 15.3 | 19.5 | 23.07 ± 8.07 |
| pting | input-aspidites | 16.7 ± 3.2 | 15.6 | 59.0 | 23.36 ± 9.28 |
| chancalan | input-chancalan | 17.2 ± 0.8 | 16.3 | 20.7 | 24.04 ± 8.41 |
| chancalan | input-kcen | 17.2 ± 0.6 | 16.2 | 20.5 | 24.11 ± 8.41 |
| chancalan | input-lanjian | 17.3 ± 0.7 | 16.2 | 20.4 | 24.13 ± 8.43 |
| chancalan | input-mattcl | 17.3 ± 0.7 | 16.0 | 20.8 | 24.17 ± 8.45 |
| chancalan | input-aspidites | 17.3 ± 0.7 | 16.3 | 20.6 | 24.20 ± 8.45 |
| chancalan | input-pting | 17.3 ± 0.6 | 16.3 | 20.4 | 24.23 ± 8.45 |
| kcen | input-lanjian | 17.6 ± 0.6 | 17.0 | 20.5 | 24.59 ± 8.58 |
| kcen | input-kcen | 17.6 ± 0.6 | 16.7 | 20.7 | 24.60 ± 8.58 |
| kcen | input-chancalan | 17.7 ± 0.7 | 16.6 | 21.1 | 24.68 ± 8.62 |
| kcen | input-mattcl | 17.7 ± 0.7 | 16.8 | 20.7 | 24.73 ± 8.64 |
| kcen | input-aspidites | 17.7 ± 0.7 | 17.0 | 20.8 | 24.75 ± 8.65 |
| kcen | input-pting | 17.7 ± 0.6 | 16.8 | 20.5 | 24.77 ± 8.64 |
| mikofo | input-chancalan | 314.4 ± 1.5 | 311.2 | 315.3 | 439.39 ± 152.52 |
| mikofo | input-kcen | 315.6 ± 1.6 | 312.6 | 317.3 | 441.12 ± 153.12 |
| mikofo | input-aspidites | 315.6 ± 2.0 | 313.3 | 318.7 | 441.15 ± 153.14 |
| mikofo | input-lanjian | 316.3 ± 1.6 | 314.0 | 318.6 | 442.10 ± 153.46 |
| mikofo | input-mattcl | 316.4 ± 1.7 | 314.6 | 319.7 | 442.21 ± 153.50 |
| mikofo | input-pting | 316.8 ± 2.2 | 313.4 | 319.9 | 442.75 ± 153.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|