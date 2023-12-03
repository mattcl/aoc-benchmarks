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
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.4 | 1.02 ± 0.37 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.36 |
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.4 | 1.04 ± 0.35 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.9 | 1.04 ± 0.40 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.05 ± 0.35 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.34 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.36 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.2 | 1.09 ± 0.35 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.5 | 1.09 ± 0.37 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.10 ± 0.34 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.13 ± 0.37 |
| aspidites | input-pting | 13.0 ± 0.4 | 11.9 | 14.3 | 16.07 ± 4.25 |
| aspidites | input-chancalan | 13.1 ± 0.4 | 12.2 | 14.2 | 16.09 ± 4.25 |
| aspidites | input-mattcl | 13.1 ± 0.5 | 12.0 | 14.8 | 16.11 ± 4.27 |
| aspidites | input-aspidites | 13.1 ± 0.5 | 12.1 | 14.2 | 16.11 ± 4.26 |
| aspidites | input-lanjian | 13.1 ± 0.5 | 12.0 | 14.7 | 16.12 ± 4.27 |
| aspidites | input-kcen | 13.1 ± 0.5 | 12.3 | 14.7 | 16.15 ± 4.27 |
| pting | input-mattcl | 16.3 ± 0.5 | 15.5 | 19.3 | 20.12 ± 5.31 |
| mattcl-py | input-kcen | 16.3 ± 0.4 | 15.7 | 19.4 | 20.15 ± 5.30 |
| pting | input-aspidites | 16.4 ± 0.5 | 15.3 | 18.8 | 20.16 ± 5.32 |
| pting | input-pting | 16.4 ± 0.5 | 15.3 | 19.4 | 20.18 ± 5.33 |
| pting | input-lanjian | 16.4 ± 0.6 | 15.4 | 20.0 | 20.18 ± 5.34 |
| mattcl-py | input-mattcl | 16.4 ± 0.5 | 15.6 | 18.9 | 20.20 ± 5.33 |
| mattcl-py | input-lanjian | 16.4 ± 0.6 | 15.4 | 19.6 | 20.21 ± 5.34 |
| mattcl-py | input-aspidites | 16.4 ± 0.5 | 15.5 | 18.8 | 20.22 ± 5.34 |
| mattcl-py | input-chancalan | 16.4 ± 0.6 | 15.6 | 19.7 | 20.22 ± 5.35 |
| mattcl-py | input-pting | 16.4 ± 0.6 | 15.4 | 19.6 | 20.25 ± 5.36 |
| pting | input-kcen | 16.4 ± 0.7 | 15.2 | 18.8 | 20.28 ± 5.38 |
| pting | input-chancalan | 16.6 ± 2.8 | 15.3 | 51.2 | 20.52 ± 6.37 |
| chancalan | input-aspidites | 17.2 ± 0.6 | 16.3 | 20.2 | 21.22 ± 5.61 |
| chancalan | input-chancalan | 17.2 ± 0.7 | 16.1 | 20.6 | 21.23 ± 5.63 |
| chancalan | input-kcen | 17.2 ± 0.6 | 16.2 | 20.1 | 21.23 ± 5.61 |
| chancalan | input-mattcl | 17.3 ± 0.6 | 16.4 | 20.7 | 21.34 ± 5.65 |
| chancalan | input-lanjian | 17.3 ± 0.7 | 16.3 | 20.2 | 21.34 ± 5.66 |
| chancalan | input-pting | 17.3 ± 0.7 | 16.4 | 20.7 | 21.35 ± 5.65 |
| kcen | input-mattcl | 17.6 ± 0.6 | 16.8 | 21.2 | 21.70 ± 5.73 |
| kcen | input-aspidites | 17.6 ± 0.6 | 16.9 | 20.7 | 21.71 ± 5.74 |
| kcen | input-kcen | 17.7 ± 0.6 | 16.8 | 20.4 | 21.77 ± 5.76 |
| kcen | input-chancalan | 17.7 ± 0.7 | 17.0 | 20.6 | 21.81 ± 5.78 |
| kcen | input-lanjian | 17.7 ± 0.8 | 16.9 | 20.6 | 21.86 ± 5.81 |
| kcen | input-pting | 17.8 ± 0.7 | 16.9 | 20.6 | 21.95 ± 5.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|