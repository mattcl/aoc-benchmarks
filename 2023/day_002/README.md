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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.0 | 1.5 | 1.00 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.0 | 1.0 | 1.04 ± 0.39 |
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.40 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.39 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.07 ± 0.42 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.5 | 1.08 ± 0.40 |
| lanjian | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.3 | 1.09 ± 0.41 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.10 ± 0.40 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.11 ± 0.42 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.4 | 1.11 ± 0.43 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.4 | 1.0 | 1.11 ± 0.38 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.1 | 1.17 ± 0.39 |
| aspidites | input-pting | 13.0 ± 0.5 | 11.6 | 14.9 | 17.14 ± 5.34 |
| aspidites | input-chancalan | 13.0 ± 0.5 | 12.2 | 14.2 | 17.18 ± 5.36 |
| aspidites | input-lanjian | 13.0 ± 0.5 | 11.9 | 14.4 | 17.22 ± 5.37 |
| aspidites | input-kcen | 13.1 ± 0.4 | 11.7 | 14.7 | 17.25 ± 5.37 |
| aspidites | input-mattcl | 13.1 ± 0.5 | 12.1 | 14.1 | 17.29 ± 5.39 |
| aspidites | input-aspidites | 13.1 ± 0.5 | 12.0 | 14.7 | 17.31 ± 5.40 |
| pting | input-kcen | 16.5 ± 0.6 | 15.4 | 19.6 | 21.76 ± 6.77 |
| pting | input-lanjian | 16.5 ± 0.6 | 15.2 | 19.2 | 21.77 ± 6.78 |
| pting | input-mattcl | 16.5 ± 0.6 | 15.2 | 19.7 | 21.78 ± 6.79 |
| mattcl-py | input-mattcl | 16.5 ± 0.5 | 15.2 | 19.0 | 21.80 ± 6.78 |
| pting | input-pting | 16.5 ± 0.7 | 15.4 | 20.4 | 21.83 ± 6.83 |
| mattcl-py | input-lanjian | 16.5 ± 0.7 | 15.3 | 19.7 | 21.83 ± 6.82 |
| mattcl-py | input-kcen | 16.6 ± 0.6 | 15.6 | 19.5 | 21.94 ± 6.83 |
| pting | input-aspidites | 16.6 ± 0.7 | 15.7 | 19.5 | 21.97 ± 6.85 |
| mattcl-py | input-pting | 16.7 ± 0.6 | 15.8 | 19.4 | 21.98 ± 6.84 |
| mattcl-py | input-aspidites | 16.7 ± 0.8 | 15.6 | 19.5 | 22.00 ± 6.88 |
| mattcl-py | input-chancalan | 16.7 ± 0.7 | 15.7 | 19.6 | 22.03 ± 6.88 |
| pting | input-chancalan | 16.9 ± 4.6 | 15.3 | 74.7 | 22.34 ± 9.21 |
| chancalan | input-mattcl | 17.3 ± 0.6 | 16.6 | 20.3 | 22.90 ± 7.13 |
| chancalan | input-chancalan | 17.4 ± 0.6 | 16.3 | 20.7 | 22.93 ± 7.14 |
| chancalan | input-kcen | 17.4 ± 0.7 | 16.5 | 20.5 | 22.99 ± 7.17 |
| chancalan | input-lanjian | 17.4 ± 0.8 | 16.2 | 20.9 | 23.01 ± 7.20 |
| chancalan | input-aspidites | 17.4 ± 0.6 | 16.1 | 20.5 | 23.03 ± 7.17 |
| chancalan | input-pting | 17.5 ± 0.8 | 16.6 | 20.9 | 23.17 ± 7.24 |
| kcen | input-kcen | 17.8 ± 0.5 | 16.9 | 19.8 | 23.44 ± 7.28 |
| kcen | input-lanjian | 17.8 ± 0.7 | 16.9 | 20.8 | 23.46 ± 7.32 |
| kcen | input-chancalan | 17.8 ± 0.6 | 16.6 | 20.8 | 23.50 ± 7.32 |
| kcen | input-aspidites | 17.9 ± 0.8 | 16.8 | 21.4 | 23.65 ± 7.38 |
| kcen | input-mattcl | 17.9 ± 0.6 | 16.9 | 20.2 | 23.65 ± 7.37 |
| kcen | input-pting | 17.9 ± 0.8 | 17.0 | 21.0 | 23.70 ± 7.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|