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
| mattcl | input-chancalan | 0.7 ± 0.2 | 0.0 | 1.0 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.0 | 1.6 | 1.15 ± 0.52 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.15 ± 0.50 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.0 | 1.0 | 1.16 ± 0.53 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.4 | 1.18 ± 0.54 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.0 | 1.5 | 1.20 ± 0.51 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.0 | 1.3 | 1.21 ± 0.53 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.3 | 1.3 | 1.23 ± 0.50 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.26 ± 0.52 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.1 | 1.0 | 1.26 ± 0.50 |
| mattcl-py | input-chancalan | 16.6 ± 0.6 | 15.3 | 19.7 | 25.32 ± 9.08 |
| mattcl-py | input-lanjian | 16.6 ± 0.6 | 15.4 | 19.5 | 25.35 ± 9.08 |
| mattcl-py | input-mattcl | 16.7 ± 0.6 | 15.7 | 19.6 | 25.49 ± 9.13 |
| mattcl-py | input-kcen | 16.7 ± 0.6 | 15.3 | 19.0 | 25.51 ± 9.14 |
| mattcl-py | input-pting | 16.9 ± 0.7 | 15.6 | 19.8 | 25.70 ± 9.22 |
| chancalan | input-chancalan | 17.4 ± 0.7 | 16.4 | 20.6 | 26.51 ± 9.51 |
| chancalan | input-kcen | 17.4 ± 0.6 | 16.3 | 20.6 | 26.52 ± 9.51 |
| chancalan | input-lanjian | 17.4 ± 0.8 | 16.1 | 20.9 | 26.53 ± 9.53 |
| pting | input-chancalan | 17.5 ± 0.7 | 16.6 | 20.5 | 26.61 ± 9.54 |
| chancalan | input-mattcl | 17.5 ± 0.7 | 16.4 | 20.6 | 26.61 ± 9.55 |
| pting | input-lanjian | 17.5 ± 0.6 | 16.5 | 20.4 | 26.63 ± 9.54 |
| pting | input-mattcl | 17.5 ± 0.6 | 16.6 | 20.4 | 26.71 ± 9.56 |
| pting | input-kcen | 17.5 ± 0.7 | 16.4 | 20.6 | 26.72 ± 9.59 |
| chancalan | input-pting | 17.6 ± 0.6 | 16.3 | 20.7 | 26.75 ± 9.59 |
| pting | input-pting | 17.6 ± 0.7 | 16.7 | 20.7 | 26.82 ± 9.62 |
| kcen | input-kcen | 17.8 ± 0.6 | 16.8 | 21.0 | 27.16 ± 9.73 |
| kcen | input-lanjian | 17.9 ± 0.8 | 16.8 | 21.2 | 27.21 ± 9.77 |
| kcen | input-mattcl | 17.9 ± 0.7 | 16.9 | 21.3 | 27.33 ± 9.80 |
| kcen | input-chancalan | 18.0 ± 1.8 | 16.9 | 38.7 | 27.46 ± 10.17 |
| kcen | input-pting | 18.1 ± 0.7 | 17.3 | 21.1 | 27.57 ± 9.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|