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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.0 | 1.00 |
| mattcl | input-aspidites | 0.7 ± 0.2 | 0.0 | 1.2 | 1.01 ± 0.36 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.0 | 1.01 ± 0.35 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.35 |
| lanjian | input-aspidites | 0.7 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.38 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.0 | 1.0 | 1.02 ± 0.36 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.0 | 1.0 | 1.02 ± 0.39 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.2 | 1.03 ± 0.40 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.1 | 0.9 | 1.04 ± 0.35 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.40 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.3 | 1.06 ± 0.38 |
| mattcl | input-chancalan | 0.8 ± 0.1 | 0.1 | 1.3 | 1.08 ± 0.35 |
| aspidites | input-chancalan | 12.8 ± 0.4 | 12.0 | 13.9 | 17.73 ± 4.94 |
| aspidites | input-pting | 12.9 ± 0.4 | 11.9 | 14.1 | 17.77 ± 4.96 |
| aspidites | input-lanjian | 12.9 ± 0.4 | 12.0 | 14.3 | 17.86 ± 4.99 |
| aspidites | input-aspidites | 13.0 ± 0.5 | 11.7 | 14.2 | 17.89 ± 5.00 |
| aspidites | input-mattcl | 13.0 ± 0.5 | 11.7 | 14.5 | 17.91 ± 5.01 |
| aspidites | input-kcen | 13.0 ± 0.5 | 11.5 | 14.7 | 17.92 ± 5.02 |
| pting | input-chancalan | 16.3 ± 0.6 | 15.3 | 19.5 | 22.43 ± 6.27 |
| pting | input-kcen | 16.3 ± 0.6 | 15.2 | 19.2 | 22.43 ± 6.27 |
| mattcl-py | input-aspidites | 16.3 ± 0.5 | 15.4 | 19.3 | 22.44 ± 6.26 |
| pting | input-aspidites | 16.3 ± 0.6 | 15.4 | 19.6 | 22.46 ± 6.29 |
| mattcl-py | input-chancalan | 16.3 ± 0.6 | 15.4 | 19.8 | 22.50 ± 6.30 |
| mattcl-py | input-mattcl | 16.3 ± 0.6 | 15.4 | 19.4 | 22.50 ± 6.30 |
| pting | input-mattcl | 16.3 ± 0.6 | 15.3 | 18.8 | 22.55 ± 6.31 |
| mattcl-py | input-kcen | 16.3 ± 0.6 | 15.5 | 19.2 | 22.56 ± 6.31 |
| pting | input-lanjian | 16.3 ± 0.7 | 15.2 | 19.6 | 22.56 ± 6.32 |
| pting | input-pting | 16.4 ± 0.7 | 15.5 | 19.3 | 22.59 ± 6.33 |
| mattcl-py | input-lanjian | 16.4 ± 0.7 | 15.4 | 19.8 | 22.68 ± 6.36 |
| mattcl-py | input-pting | 16.5 ± 0.8 | 15.8 | 19.8 | 22.74 ± 6.39 |
| chancalan | input-chancalan | 17.1 ± 0.7 | 16.0 | 20.6 | 23.56 ± 6.60 |
| chancalan | input-aspidites | 17.1 ± 0.6 | 16.3 | 20.0 | 23.61 ± 6.60 |
| chancalan | input-lanjian | 17.1 ± 0.6 | 16.3 | 20.1 | 23.66 ± 6.61 |
| chancalan | input-mattcl | 17.1 ± 0.6 | 16.2 | 19.8 | 23.66 ± 6.61 |
| chancalan | input-pting | 17.2 ± 0.8 | 16.1 | 20.6 | 23.77 ± 6.68 |
| kcen | input-lanjian | 17.4 ± 0.5 | 16.6 | 20.6 | 24.03 ± 6.69 |
| kcen | input-mattcl | 17.5 ± 0.5 | 16.7 | 20.0 | 24.12 ± 6.72 |
| kcen | input-kcen | 17.5 ± 0.7 | 16.7 | 20.6 | 24.17 ± 6.76 |
| kcen | input-aspidites | 17.5 ± 0.6 | 16.4 | 20.8 | 24.18 ± 6.76 |
| chancalan | input-kcen | 17.6 ± 4.1 | 16.0 | 59.8 | 24.27 ± 8.75 |
| kcen | input-chancalan | 17.6 ± 0.9 | 16.3 | 21.1 | 24.34 ± 6.86 |
| kcen | input-pting | 17.7 ± 0.7 | 16.6 | 20.5 | 24.36 ± 6.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|