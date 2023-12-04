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
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 ± 0.34 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.34 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.03 ± 0.36 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.31 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.06 ± 0.34 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.32 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.1 | 1.4 | 1.07 ± 0.31 |
| lanjian | input-aspidites | 0.8 ± 0.2 | 0.2 | 1.3 | 1.09 ± 0.33 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.09 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.3 | 1.0 | 1.09 ± 0.30 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.2 | 1.3 | 1.16 ± 0.32 |
| aspidites | input-kcen | 13.0 ± 0.4 | 12.0 | 14.1 | 16.70 ± 3.91 |
| aspidites | input-mattcl | 13.0 ± 0.5 | 12.0 | 14.7 | 16.75 ± 3.92 |
| aspidites | input-pting | 13.0 ± 0.5 | 11.9 | 14.2 | 16.77 ± 3.93 |
| aspidites | input-chancalan | 13.0 ± 0.5 | 11.9 | 14.4 | 16.78 ± 3.94 |
| aspidites | input-lanjian | 13.0 ± 0.4 | 12.2 | 14.3 | 16.79 ± 3.93 |
| aspidites | input-aspidites | 13.0 ± 0.4 | 12.1 | 14.3 | 16.79 ± 3.93 |
| pting | input-kcen | 16.3 ± 0.5 | 15.6 | 18.7 | 20.98 ± 4.90 |
| pting | input-aspidites | 16.4 ± 0.6 | 15.2 | 19.5 | 21.04 ± 4.92 |
| pting | input-lanjian | 16.4 ± 0.6 | 15.3 | 19.1 | 21.05 ± 4.94 |
| mattcl-py | input-pting | 16.4 ± 0.6 | 15.5 | 19.6 | 21.09 ± 4.94 |
| mattcl-py | input-chancalan | 16.4 ± 0.6 | 15.5 | 19.2 | 21.11 ± 4.95 |
| mattcl-py | input-mattcl | 16.4 ± 0.5 | 15.6 | 18.6 | 21.13 ± 4.93 |
| mattcl-py | input-aspidites | 16.5 ± 0.6 | 15.8 | 19.2 | 21.19 ± 4.96 |
| mattcl-py | input-lanjian | 16.5 ± 0.7 | 15.4 | 19.5 | 21.21 ± 4.99 |
| pting | input-mattcl | 16.5 ± 0.8 | 15.5 | 19.4 | 21.26 ± 5.03 |
| pting | input-pting | 16.6 ± 2.7 | 15.4 | 51.1 | 21.33 ± 6.02 |
| mattcl-py | input-kcen | 16.6 ± 2.1 | 15.6 | 43.1 | 21.41 ± 5.63 |
| pting | input-chancalan | 16.7 ± 3.6 | 15.4 | 52.3 | 21.50 ± 6.76 |
| chancalan | input-aspidites | 17.2 ± 0.5 | 16.3 | 20.1 | 22.09 ± 5.16 |
| chancalan | input-kcen | 17.2 ± 0.6 | 16.2 | 20.3 | 22.11 ± 5.18 |
| chancalan | input-lanjian | 17.3 ± 0.7 | 16.1 | 20.8 | 22.23 ± 5.22 |
| chancalan | input-pting | 17.3 ± 0.7 | 16.1 | 19.7 | 22.27 ± 5.23 |
| chancalan | input-chancalan | 17.3 ± 3.1 | 16.1 | 56.0 | 22.30 ± 6.49 |
| chancalan | input-mattcl | 17.4 ± 0.7 | 16.3 | 20.7 | 22.32 ± 5.26 |
| kcen | input-lanjian | 17.6 ± 0.6 | 17.0 | 21.0 | 22.62 ± 5.30 |
| kcen | input-chancalan | 17.6 ± 0.6 | 16.9 | 20.6 | 22.70 ± 5.32 |
| kcen | input-aspidites | 17.7 ± 0.7 | 16.8 | 20.7 | 22.72 ± 5.34 |
| kcen | input-pting | 17.7 ± 0.7 | 17.1 | 21.1 | 22.82 ± 5.36 |
| kcen | input-kcen | 17.7 ± 0.8 | 16.8 | 21.0 | 22.83 ± 5.38 |
| kcen | input-mattcl | 17.8 ± 0.8 | 16.7 | 21.0 | 22.84 ± 5.39 |
| mikofo | input-kcen | 314.6 ± 1.4 | 312.6 | 316.6 | 404.76 ± 93.71 |
| mikofo | input-pting | 314.7 ± 0.9 | 313.3 | 316.1 | 404.86 ± 93.72 |
| mikofo | input-aspidites | 314.8 ± 1.8 | 311.3 | 317.4 | 404.97 ± 93.77 |
| mikofo | input-mattcl | 314.9 ± 1.5 | 312.7 | 317.3 | 405.17 ± 93.81 |
| mikofo | input-lanjian | 315.2 ± 3.0 | 312.8 | 322.3 | 405.47 ± 93.93 |
| mikofo | input-chancalan | 315.3 ± 1.8 | 312.4 | 317.9 | 405.69 ± 93.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|