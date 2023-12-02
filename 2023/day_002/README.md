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
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.31 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.1 | 1.2 | 1.06 ± 0.29 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.4 | 1.2 | 1.07 ± 0.28 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.3 | 1.08 ± 0.32 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.4 | 1.5 | 1.09 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.2 | 1.1 | 1.09 ± 0.28 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.6 | 1.09 ± 0.33 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.1 | 1.2 | 1.10 ± 0.32 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.7 | 1.15 ± 0.35 |
| pting | input-lanjian | 16.3 ± 0.6 | 15.3 | 19.6 | 20.61 ± 4.52 |
| pting | input-mattcl | 16.4 ± 1.1 | 15.2 | 29.6 | 20.67 ± 4.69 |
| mattcl-py | input-chancalan | 16.4 ± 0.5 | 15.5 | 18.7 | 20.68 ± 4.51 |
| pting | input-kcen | 16.4 ± 0.7 | 15.4 | 19.6 | 20.68 ± 4.56 |
| mattcl-py | input-kcen | 16.4 ± 0.6 | 15.5 | 19.0 | 20.69 ± 4.52 |
| pting | input-chancalan | 16.4 ± 0.7 | 15.2 | 19.5 | 20.72 ± 4.55 |
| mattcl-py | input-mattcl | 16.5 ± 0.7 | 15.5 | 19.5 | 20.76 ± 4.56 |
| mattcl-py | input-lanjian | 16.5 ± 0.6 | 15.5 | 19.8 | 20.81 ± 4.57 |
| pting | input-pting | 16.5 ± 0.7 | 15.3 | 19.5 | 20.82 ± 4.59 |
| mattcl-py | input-pting | 16.5 ± 0.7 | 15.4 | 19.4 | 20.87 ± 4.59 |
| chancalan | input-chancalan | 17.2 ± 0.7 | 16.2 | 20.6 | 21.70 ± 4.76 |
| chancalan | input-pting | 17.2 ± 0.5 | 16.4 | 20.3 | 21.75 ± 4.73 |
| chancalan | input-mattcl | 17.2 ± 0.7 | 16.3 | 20.7 | 21.77 ± 4.79 |
| chancalan | input-kcen | 17.3 ± 0.7 | 16.5 | 20.2 | 21.83 ± 4.80 |
| chancalan | input-lanjian | 17.3 ± 0.7 | 16.4 | 20.1 | 21.85 ± 4.80 |
| kcen | input-chancalan | 17.6 ± 0.5 | 16.4 | 19.7 | 22.17 ± 4.83 |
| kcen | input-lanjian | 17.6 ± 0.7 | 16.9 | 21.2 | 22.20 ± 4.87 |
| kcen | input-kcen | 17.6 ± 0.6 | 17.0 | 20.7 | 22.23 ± 4.87 |
| kcen | input-pting | 17.8 ± 0.8 | 17.0 | 20.7 | 22.41 ± 4.94 |
| kcen | input-mattcl | 17.8 ± 0.8 | 16.9 | 20.7 | 22.43 ± 4.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|