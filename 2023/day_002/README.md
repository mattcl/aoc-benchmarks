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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.2 | 1.01 ± 0.33 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.33 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.3 | 1.5 | 1.02 ± 0.32 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.4 | 1.5 | 1.02 ± 0.31 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.3 | 1.5 | 1.03 ± 0.32 |
| mattcl | input-aspidites | 0.8 ± 0.1 | 0.2 | 1.1 | 1.04 ± 0.29 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.33 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.1 | 1.6 | 1.06 ± 0.34 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.6 | 1.08 ± 0.32 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.1 | 1.2 | 1.09 ± 0.31 |
| lanjian | input-pting | 0.9 ± 0.1 | 0.3 | 1.1 | 1.09 ± 0.31 |
| aspidites | input-chancalan | 13.0 ± 0.4 | 12.1 | 14.4 | 16.20 ± 3.76 |
| aspidites | input-lanjian | 13.0 ± 0.4 | 12.1 | 14.4 | 16.21 ± 3.77 |
| aspidites | input-mattcl | 13.1 ± 0.4 | 12.2 | 14.6 | 16.23 ± 3.78 |
| aspidites | input-aspidites | 13.1 ± 0.5 | 12.0 | 14.6 | 16.27 ± 3.79 |
| aspidites | input-pting | 13.1 ± 0.4 | 11.9 | 14.8 | 16.29 ± 3.79 |
| aspidites | input-kcen | 13.1 ± 0.5 | 12.1 | 14.7 | 16.30 ± 3.80 |
| pting | input-kcen | 16.5 ± 0.5 | 15.6 | 19.1 | 20.47 ± 4.76 |
| pting | input-chancalan | 16.5 ± 0.6 | 15.5 | 19.7 | 20.53 ± 4.80 |
| mattcl-py | input-lanjian | 16.5 ± 0.6 | 15.3 | 19.5 | 20.55 ± 4.79 |
| pting | input-lanjian | 16.6 ± 0.7 | 15.3 | 19.6 | 20.56 ± 4.82 |
| mattcl-py | input-chancalan | 16.6 ± 0.5 | 15.6 | 19.6 | 20.58 ± 4.79 |
| mattcl-py | input-pting | 16.6 ± 0.6 | 15.2 | 19.7 | 20.58 ± 4.79 |
| pting | input-mattcl | 16.6 ± 0.7 | 15.2 | 19.8 | 20.61 ± 4.83 |
| mattcl-py | input-kcen | 16.6 ± 0.7 | 15.5 | 20.3 | 20.62 ± 4.82 |
| pting | input-aspidites | 16.6 ± 0.7 | 15.6 | 19.4 | 20.62 ± 4.82 |
| pting | input-pting | 16.6 ± 0.5 | 15.9 | 19.7 | 20.64 ± 4.80 |
| mattcl-py | input-mattcl | 16.6 ± 0.7 | 15.5 | 20.0 | 20.65 ± 4.83 |
| mattcl-py | input-aspidites | 16.8 ± 0.8 | 15.7 | 20.3 | 20.86 ± 4.91 |
| chancalan | input-lanjian | 17.4 ± 0.7 | 16.1 | 20.5 | 21.59 ± 5.05 |
| chancalan | input-pting | 17.4 ± 0.6 | 16.6 | 20.7 | 21.60 ± 5.04 |
| chancalan | input-aspidites | 17.4 ± 0.7 | 16.0 | 20.6 | 21.63 ± 5.06 |
| chancalan | input-mattcl | 17.5 ± 0.8 | 16.4 | 20.6 | 21.69 ± 5.09 |
| chancalan | input-chancalan | 17.5 ± 0.8 | 16.5 | 21.0 | 21.70 ± 5.09 |
| chancalan | input-kcen | 17.5 ± 0.6 | 16.3 | 20.6 | 21.73 ± 5.06 |
| kcen | input-mattcl | 17.8 ± 0.7 | 16.5 | 21.3 | 22.12 ± 5.18 |
| kcen | input-lanjian | 17.8 ± 0.9 | 16.8 | 21.5 | 22.16 ± 5.21 |
| kcen | input-kcen | 18.0 ± 0.8 | 16.9 | 21.2 | 22.30 ± 5.22 |
| kcen | input-aspidites | 18.1 ± 2.3 | 17.0 | 45.7 | 22.43 ± 5.89 |
| kcen | input-chancalan | 18.1 ± 1.0 | 16.7 | 21.4 | 22.46 ± 5.31 |
| kcen | input-pting | 18.3 ± 3.0 | 17.1 | 56.5 | 22.68 ± 6.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|