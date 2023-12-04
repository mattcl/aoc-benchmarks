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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.3 | 1.02 ± 0.38 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.38 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.1 | 1.05 ± 0.37 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.36 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.3 | 1.06 ± 0.35 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.6 | 1.07 ± 0.37 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.09 ± 0.37 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.1 | 1.10 ± 0.37 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.11 ± 0.38 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.3 | 1.13 ± 0.36 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.13 ± 0.38 |
| aspidites | input-aspidites | 13.0 ± 0.5 | 11.4 | 14.2 | 16.27 ± 4.42 |
| aspidites | input-pting | 13.0 ± 0.4 | 12.1 | 14.0 | 16.34 ± 4.43 |
| aspidites | input-mattcl | 13.1 ± 0.4 | 12.1 | 14.2 | 16.37 ± 4.44 |
| aspidites | input-kcen | 13.1 ± 0.5 | 12.2 | 14.6 | 16.37 ± 4.45 |
| aspidites | input-lanjian | 13.1 ± 0.4 | 12.2 | 14.3 | 16.47 ± 4.47 |
| aspidites | input-chancalan | 13.2 ± 0.5 | 12.0 | 14.7 | 16.51 ± 4.49 |
| pting | input-lanjian | 16.4 ± 0.6 | 15.3 | 19.6 | 20.52 ± 5.58 |
| mattcl-py | input-aspidites | 16.4 ± 0.5 | 15.5 | 19.5 | 20.58 ± 5.58 |
| pting | input-pting | 16.4 ± 0.5 | 15.3 | 18.8 | 20.59 ± 5.58 |
| pting | input-mattcl | 16.4 ± 0.5 | 15.3 | 19.2 | 20.61 ± 5.60 |
| pting | input-aspidites | 16.4 ± 0.6 | 15.5 | 19.8 | 20.62 ± 5.61 |
| mattcl-py | input-kcen | 16.5 ± 0.5 | 15.6 | 19.0 | 20.64 ± 5.59 |
| mattcl-py | input-lanjian | 16.5 ± 0.6 | 15.6 | 19.0 | 20.66 ± 5.61 |
| mattcl-py | input-chancalan | 16.5 ± 0.6 | 15.5 | 19.2 | 20.67 ± 5.62 |
| mattcl-py | input-mattcl | 16.5 ± 0.7 | 15.5 | 19.5 | 20.74 ± 5.65 |
| pting | input-kcen | 16.6 ± 0.6 | 15.6 | 19.6 | 20.76 ± 5.65 |
| pting | input-chancalan | 16.6 ± 3.5 | 15.4 | 62.8 | 20.88 ± 7.16 |
| mattcl-py | input-pting | 16.7 ± 3.0 | 15.7 | 56.0 | 20.95 ± 6.79 |
| chancalan | input-mattcl | 17.3 ± 0.7 | 16.3 | 20.7 | 21.74 ± 5.92 |
| chancalan | input-kcen | 17.3 ± 0.6 | 16.3 | 20.7 | 21.74 ± 5.91 |
| chancalan | input-chancalan | 17.4 ± 0.7 | 16.3 | 20.4 | 21.77 ± 5.94 |
| chancalan | input-aspidites | 17.4 ± 0.6 | 16.3 | 19.9 | 21.79 ± 5.92 |
| chancalan | input-lanjian | 17.4 ± 0.8 | 16.3 | 20.6 | 21.80 ± 5.95 |
| chancalan | input-pting | 17.4 ± 0.7 | 16.2 | 20.6 | 21.87 ± 5.96 |
| kcen | input-lanjian | 17.7 ± 0.6 | 17.1 | 20.5 | 22.15 ± 6.01 |
| kcen | input-mattcl | 17.7 ± 0.7 | 16.8 | 21.0 | 22.21 ± 6.04 |
| kcen | input-pting | 17.8 ± 0.7 | 16.9 | 21.2 | 22.27 ± 6.06 |
| kcen | input-aspidites | 17.8 ± 0.7 | 16.9 | 20.7 | 22.28 ± 6.07 |
| kcen | input-chancalan | 17.8 ± 0.7 | 17.2 | 20.9 | 22.35 ± 6.09 |
| kcen | input-kcen | 17.9 ± 0.8 | 16.8 | 20.8 | 22.40 ± 6.12 |
| mikofo | input-kcen | 315.2 ± 2.0 | 312.0 | 318.6 | 395.35 ± 106.56 |
| mikofo | input-aspidites | 315.3 ± 2.0 | 311.5 | 319.0 | 395.39 ± 106.57 |
| mikofo | input-pting | 315.5 ± 2.0 | 312.9 | 319.5 | 395.71 ± 106.66 |
| mikofo | input-chancalan | 315.7 ± 2.9 | 311.3 | 319.7 | 395.90 ± 106.74 |
| mikofo | input-lanjian | 316.9 ± 1.9 | 314.6 | 320.2 | 397.39 ± 107.11 |
| mikofo | input-mattcl | 317.1 ± 1.8 | 314.8 | 319.8 | 397.64 ± 107.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|