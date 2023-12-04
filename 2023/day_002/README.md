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
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.4 | 1.00 ± 0.34 |
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 ± 0.33 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.4 | 1.02 ± 0.33 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.6 | 1.05 ± 0.36 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.3 | 1.3 | 1.05 ± 0.31 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.07 ± 0.33 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.3 | 1.3 | 1.08 ± 0.30 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.2 | 1.09 ± 0.34 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.09 ± 0.34 |
| lanjian | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.3 | 1.09 ± 0.32 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.0 | 1.13 ± 0.31 |
| aspidites | input-aspidites | 13.0 ± 0.4 | 11.9 | 14.7 | 16.64 ± 3.84 |
| aspidites | input-mattcl | 13.0 ± 0.4 | 11.5 | 14.0 | 16.66 ± 3.85 |
| aspidites | input-kcen | 13.0 ± 0.5 | 12.0 | 14.5 | 16.70 ± 3.87 |
| aspidites | input-chancalan | 13.0 ± 0.5 | 11.7 | 14.7 | 16.72 ± 3.87 |
| aspidites | input-pting | 13.1 ± 0.5 | 12.2 | 15.2 | 16.84 ± 3.90 |
| aspidites | input-lanjian | 13.2 ± 0.4 | 12.2 | 14.5 | 16.88 ± 3.90 |
| pting | input-aspidites | 16.5 ± 0.7 | 15.3 | 19.7 | 21.17 ± 4.92 |
| mattcl-py | input-pting | 16.6 ± 0.5 | 15.5 | 19.1 | 21.26 ± 4.91 |
| mattcl-py | input-mattcl | 16.6 ± 0.5 | 15.7 | 19.8 | 21.31 ± 4.92 |
| pting | input-kcen | 16.7 ± 0.7 | 15.8 | 20.4 | 21.38 ± 4.98 |
| mattcl-py | input-chancalan | 16.7 ± 0.6 | 15.3 | 19.5 | 21.39 ± 4.96 |
| pting | input-chancalan | 16.7 ± 0.8 | 15.7 | 20.2 | 21.40 ± 5.00 |
| mattcl-py | input-aspidites | 16.7 ± 0.7 | 15.7 | 20.6 | 21.40 ± 4.98 |
| pting | input-pting | 16.7 ± 0.7 | 15.8 | 19.9 | 21.41 ± 4.97 |
| pting | input-mattcl | 16.7 ± 0.7 | 15.6 | 20.4 | 21.41 ± 4.99 |
| mattcl-py | input-kcen | 16.7 ± 0.7 | 15.9 | 19.8 | 21.45 ± 4.99 |
| pting | input-lanjian | 16.8 ± 1.7 | 15.4 | 37.7 | 21.51 ± 5.39 |
| mattcl-py | input-lanjian | 16.8 ± 0.8 | 15.7 | 20.0 | 21.53 ± 5.04 |
| chancalan | input-chancalan | 17.4 ± 0.7 | 16.0 | 20.7 | 22.37 ± 5.19 |
| chancalan | input-kcen | 17.4 ± 0.6 | 16.6 | 20.2 | 22.38 ± 5.17 |
| chancalan | input-lanjian | 17.5 ± 0.8 | 16.1 | 20.8 | 22.39 ± 5.21 |
| chancalan | input-pting | 17.5 ± 0.7 | 16.6 | 20.7 | 22.40 ± 5.21 |
| chancalan | input-aspidites | 17.5 ± 0.7 | 16.2 | 20.8 | 22.41 ± 5.20 |
| chancalan | input-mattcl | 17.5 ± 0.7 | 16.7 | 20.9 | 22.44 ± 5.20 |
| kcen | input-aspidites | 17.9 ± 0.8 | 17.0 | 21.5 | 22.93 ± 5.34 |
| kcen | input-chancalan | 17.9 ± 0.6 | 16.9 | 21.0 | 22.94 ± 5.30 |
| kcen | input-lanjian | 17.9 ± 0.6 | 17.0 | 20.8 | 23.02 ± 5.33 |
| kcen | input-mattcl | 18.0 ± 0.8 | 17.0 | 21.5 | 23.06 ± 5.36 |
| kcen | input-kcen | 18.0 ± 0.8 | 17.1 | 21.5 | 23.13 ± 5.39 |
| kcen | input-pting | 18.1 ± 0.9 | 17.1 | 21.3 | 23.19 ± 5.43 |
| mikofo | input-aspidites | 320.2 ± 2.8 | 316.4 | 323.5 | 410.63 ± 93.99 |
| mikofo | input-lanjian | 320.6 ± 2.5 | 317.1 | 324.3 | 411.20 ± 94.11 |
| mikofo | input-chancalan | 320.9 ± 2.1 | 317.7 | 323.1 | 411.51 ± 94.16 |
| mikofo | input-kcen | 320.9 ± 1.6 | 317.2 | 322.8 | 411.53 ± 94.15 |
| mikofo | input-mattcl | 321.7 ± 3.0 | 318.4 | 326.9 | 412.53 ± 94.43 |
| mikofo | input-pting | 322.0 ± 2.6 | 317.4 | 325.5 | 412.96 ± 94.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|