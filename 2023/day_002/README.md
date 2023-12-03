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
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.4 | 1.01 ± 0.32 |
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.4 | 1.01 ± 0.32 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.4 | 1.03 ± 0.33 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.3 | 1.1 | 1.06 ± 0.32 |
| lanjian | input-aspidites | 0.8 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.32 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.33 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.4 | 1.3 | 1.07 ± 0.30 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.08 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.5 | 1.0 | 1.09 ± 0.28 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.0 | 1.09 ± 0.33 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.2 | 1.10 ± 0.31 |
| aspidites | input-lanjian | 13.0 ± 0.4 | 12.0 | 14.4 | 16.32 ± 3.83 |
| aspidites | input-aspidites | 13.0 ± 0.5 | 11.6 | 14.1 | 16.38 ± 3.85 |
| aspidites | input-chancalan | 13.0 ± 0.5 | 12.1 | 14.5 | 16.41 ± 3.86 |
| aspidites | input-mattcl | 13.0 ± 0.5 | 11.9 | 14.7 | 16.42 ± 3.86 |
| aspidites | input-pting | 13.0 ± 0.4 | 12.1 | 14.4 | 16.42 ± 3.86 |
| aspidites | input-kcen | 13.1 ± 0.5 | 12.0 | 14.7 | 16.52 ± 3.88 |
| pting | input-pting | 16.3 ± 0.5 | 15.5 | 19.6 | 20.57 ± 4.83 |
| pting | input-lanjian | 16.3 ± 0.6 | 15.4 | 19.4 | 20.57 ± 4.85 |
| pting | input-kcen | 16.3 ± 0.6 | 15.6 | 19.0 | 20.58 ± 4.84 |
| mattcl-py | input-kcen | 16.4 ± 0.6 | 15.5 | 19.7 | 20.59 ± 4.84 |
| pting | input-mattcl | 16.4 ± 0.6 | 15.4 | 19.6 | 20.62 ± 4.86 |
| mattcl-py | input-mattcl | 16.4 ± 0.5 | 15.7 | 19.0 | 20.63 ± 4.84 |
| pting | input-chancalan | 16.4 ± 0.8 | 15.4 | 19.7 | 20.67 ± 4.90 |
| mattcl-py | input-pting | 16.4 ± 0.7 | 15.4 | 19.8 | 20.68 ± 4.89 |
| pting | input-aspidites | 16.5 ± 0.7 | 15.5 | 19.6 | 20.72 ± 4.90 |
| mattcl-py | input-chancalan | 16.5 ± 0.6 | 15.3 | 19.3 | 20.73 ± 4.88 |
| mattcl-py | input-lanjian | 16.5 ± 2.1 | 15.5 | 43.5 | 20.81 ± 5.52 |
| mattcl-py | input-aspidites | 16.6 ± 1.4 | 15.5 | 33.3 | 20.87 ± 5.17 |
| chancalan | input-mattcl | 17.1 ± 0.6 | 16.1 | 20.5 | 21.58 ± 5.08 |
| chancalan | input-aspidites | 17.2 ± 0.6 | 16.4 | 20.4 | 21.61 ± 5.08 |
| chancalan | input-kcen | 17.2 ± 0.7 | 16.0 | 19.9 | 21.62 ± 5.10 |
| chancalan | input-lanjian | 17.2 ± 0.7 | 16.0 | 20.2 | 21.62 ± 5.11 |
| chancalan | input-chancalan | 17.2 ± 0.7 | 15.9 | 20.6 | 21.66 ± 5.12 |
| chancalan | input-pting | 17.5 ± 2.4 | 16.5 | 47.6 | 21.99 ± 5.94 |
| kcen | input-lanjian | 17.5 ± 0.6 | 16.6 | 20.8 | 22.09 ± 5.19 |
| kcen | input-chancalan | 17.6 ± 0.8 | 16.5 | 20.7 | 22.21 ± 5.25 |
| kcen | input-kcen | 17.6 ± 0.7 | 16.7 | 20.9 | 22.22 ± 5.24 |
| kcen | input-aspidites | 17.7 ± 0.8 | 16.7 | 21.2 | 22.24 ± 5.26 |
| kcen | input-pting | 17.7 ± 0.7 | 16.9 | 20.6 | 22.27 ± 5.26 |
| kcen | input-mattcl | 17.7 ± 0.7 | 17.0 | 20.7 | 22.28 ± 5.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|