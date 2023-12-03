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
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.0 | 1.0 | 1.01 ± 0.35 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.0 | 1.0 | 1.03 ± 0.34 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.0 | 1.3 | 1.04 ± 0.41 |
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.4 | 1.04 ± 0.34 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.05 ± 0.34 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.1 | 1.1 | 1.07 ± 0.32 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.3 | 1.07 ± 0.35 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.3 | 1.08 ± 0.36 |
| lanjian | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.4 | 1.09 ± 0.35 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.0 | 1.6 | 1.12 ± 0.36 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.4 | 1.12 ± 0.35 |
| aspidites | input-aspidites | 12.9 ± 0.5 | 12.0 | 14.1 | 17.31 ± 4.22 |
| aspidites | input-kcen | 13.0 ± 0.5 | 12.0 | 14.3 | 17.32 ± 4.23 |
| aspidites | input-mattcl | 13.0 ± 0.4 | 12.0 | 14.0 | 17.33 ± 4.22 |
| aspidites | input-lanjian | 13.0 ± 0.4 | 12.0 | 14.5 | 17.40 ± 4.24 |
| aspidites | input-pting | 13.0 ± 0.4 | 12.0 | 14.3 | 17.43 ± 4.25 |
| aspidites | input-chancalan | 13.1 ± 0.4 | 12.2 | 14.7 | 17.50 ± 4.27 |
| pting | input-lanjian | 16.3 ± 0.7 | 15.2 | 19.4 | 21.78 ± 5.34 |
| pting | input-aspidites | 16.3 ± 0.5 | 15.3 | 19.7 | 21.79 ± 5.31 |
| pting | input-chancalan | 16.3 ± 0.6 | 15.4 | 19.5 | 21.83 ± 5.33 |
| mattcl-py | input-chancalan | 16.3 ± 0.5 | 15.4 | 19.0 | 21.84 ± 5.32 |
| mattcl-py | input-lanjian | 16.3 ± 0.5 | 15.4 | 18.6 | 21.86 ± 5.32 |
| mattcl-py | input-aspidites | 16.4 ± 0.6 | 15.3 | 19.4 | 21.87 ± 5.34 |
| pting | input-pting | 16.4 ± 0.6 | 15.5 | 19.4 | 21.89 ± 5.35 |
| pting | input-mattcl | 16.4 ± 0.7 | 15.5 | 19.5 | 21.90 ± 5.36 |
| mattcl-py | input-pting | 16.4 ± 0.6 | 15.4 | 19.8 | 21.90 ± 5.35 |
| mattcl-py | input-kcen | 16.4 ± 0.7 | 15.3 | 19.6 | 21.91 ± 5.36 |
| mattcl-py | input-mattcl | 16.4 ± 0.6 | 15.3 | 19.1 | 21.93 ± 5.35 |
| pting | input-kcen | 16.5 ± 0.8 | 15.4 | 19.6 | 22.00 ± 5.42 |
| chancalan | input-kcen | 17.1 ± 0.7 | 16.2 | 20.0 | 22.89 ± 5.60 |
| chancalan | input-aspidites | 17.1 ± 0.7 | 16.0 | 19.8 | 22.91 ± 5.60 |
| chancalan | input-mattcl | 17.2 ± 0.7 | 16.1 | 20.3 | 22.94 ± 5.62 |
| chancalan | input-pting | 17.2 ± 0.5 | 16.2 | 20.1 | 22.94 ± 5.58 |
| chancalan | input-lanjian | 17.2 ± 0.6 | 16.0 | 20.4 | 22.99 ± 5.61 |
| chancalan | input-chancalan | 17.6 ± 4.0 | 16.2 | 58.4 | 23.48 ± 7.78 |
| kcen | input-lanjian | 17.6 ± 0.5 | 16.8 | 20.3 | 23.49 ± 5.72 |
| kcen | input-mattcl | 17.6 ± 0.8 | 16.6 | 22.1 | 23.56 ± 5.78 |
| kcen | input-kcen | 17.6 ± 0.7 | 16.6 | 20.7 | 23.58 ± 5.77 |
| kcen | input-chancalan | 17.7 ± 0.8 | 16.7 | 20.5 | 23.66 ± 5.81 |
| kcen | input-aspidites | 17.7 ± 0.7 | 16.8 | 20.7 | 23.68 ± 5.80 |
| kcen | input-pting | 17.7 ± 0.8 | 16.9 | 21.1 | 23.72 ± 5.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|