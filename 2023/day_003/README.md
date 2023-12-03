# Day 3 benchmarks

[link to problem](https://adventofcode.com/2023/day/3)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 3)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 1.6 ± 0.2 | 0.9 | 2.2 | 1.00 |
| mattcl | input-kcen | 1.6 ± 0.2 | 0.9 | 2.2 | 1.01 ± 0.19 |
| mattcl | input-pting | 1.6 ± 0.2 | 0.8 | 2.2 | 1.04 ± 0.20 |
| mattcl | input-mattcl | 1.7 ± 0.2 | 0.9 | 3.0 | 1.04 ± 0.20 |
| mattcl | input-chancalan | 1.7 ± 0.2 | 0.9 | 2.4 | 1.05 ± 0.20 |
| lanjian | input-mattcl | 1.8 ± 0.2 | 1.1 | 2.2 | 1.12 ± 0.19 |
| lanjian | input-kcen | 1.8 ± 0.2 | 1.1 | 2.3 | 1.13 ± 0.20 |
| lanjian | input-chancalan | 1.8 ± 0.2 | 0.9 | 2.2 | 1.14 ± 0.20 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 1.0 | 2.3 | 1.15 ± 0.21 |
| lanjian | input-pting | 1.8 ± 0.2 | 0.9 | 2.2 | 1.17 ± 0.20 |
| kcen | input-kcen | 19.5 ± 0.7 | 18.1 | 22.7 | 12.29 ± 1.69 |
| kcen | input-mattcl | 19.5 ± 0.5 | 18.5 | 21.7 | 12.32 ± 1.67 |
| kcen | input-chancalan | 19.5 ± 0.6 | 18.6 | 22.3 | 12.34 ± 1.68 |
| kcen | input-pting | 19.7 ± 0.7 | 18.7 | 22.3 | 12.42 ± 1.71 |
| kcen | input-lanjian | 19.8 ± 0.8 | 18.6 | 22.9 | 12.48 ± 1.73 |
| mattcl-py | input-kcen | 21.3 ± 0.6 | 20.5 | 24.2 | 13.45 ± 1.82 |
| mattcl-py | input-mattcl | 21.4 ± 0.8 | 20.0 | 24.4 | 13.51 ± 1.86 |
| mattcl-py | input-chancalan | 21.4 ± 0.7 | 20.4 | 24.6 | 13.51 ± 1.85 |
| mattcl-py | input-lanjian | 21.5 ± 0.8 | 20.5 | 24.5 | 13.56 ± 1.86 |
| mattcl-py | input-pting | 21.5 ± 0.7 | 20.5 | 24.7 | 13.59 ± 1.86 |
| pting | input-lanjian | 23.3 ± 0.7 | 22.2 | 26.7 | 14.71 ± 2.01 |
| pting | input-kcen | 23.3 ± 0.7 | 22.3 | 25.8 | 14.72 ± 2.01 |
| pting | input-chancalan | 23.4 ± 0.8 | 22.0 | 26.5 | 14.77 ± 2.03 |
| pting | input-mattcl | 23.4 ± 0.8 | 22.3 | 26.5 | 14.80 ± 2.04 |
| pting | input-pting | 23.6 ± 0.7 | 22.5 | 26.8 | 14.89 ± 2.03 |
| chancalan | input-mattcl | 26.1 ± 0.6 | 25.2 | 28.5 | 16.51 ± 2.23 |
| chancalan | input-kcen | 26.3 ± 0.9 | 25.1 | 29.3 | 16.61 ± 2.28 |
| chancalan | input-lanjian | 26.3 ± 0.9 | 25.3 | 29.8 | 16.61 ± 2.28 |
| chancalan | input-chancalan | 26.4 ± 1.1 | 25.2 | 30.4 | 16.69 ± 2.33 |
| chancalan | input-pting | 26.5 ± 1.0 | 25.1 | 29.8 | 16.72 ± 2.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|