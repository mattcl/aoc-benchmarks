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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.8 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.7 | 1.01 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 1.6 | 1.02 ± 0.20 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.7 | 1.03 ± 0.19 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 1.7 | 1.04 ± 0.20 |
| lanjian | input-mattcl | 1.6 ± 0.3 | 0.9 | 2.2 | 1.35 ± 0.29 |
| lanjian | input-kcen | 1.6 ± 0.2 | 0.9 | 2.3 | 1.35 ± 0.28 |
| lanjian | input-chancalan | 1.7 ± 0.3 | 0.8 | 2.3 | 1.40 ± 0.29 |
| lanjian | input-pting | 1.7 ± 0.2 | 1.1 | 2.1 | 1.42 ± 0.27 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 1.0 | 2.3 | 1.43 ± 0.28 |
| kcen | input-mattcl | 18.9 ± 0.7 | 17.9 | 22.0 | 15.66 ± 2.37 |
| kcen | input-kcen | 18.9 ± 0.7 | 18.1 | 22.1 | 15.70 ± 2.39 |
| kcen | input-chancalan | 18.9 ± 0.7 | 18.0 | 22.1 | 15.72 ± 2.38 |
| kcen | input-lanjian | 19.0 ± 0.7 | 18.1 | 21.8 | 15.74 ± 2.40 |
| kcen | input-pting | 19.0 ± 0.7 | 17.9 | 22.0 | 15.77 ± 2.39 |
| mattcl-py | input-kcen | 21.1 ± 0.7 | 20.1 | 23.9 | 17.49 ± 2.65 |
| mattcl-py | input-chancalan | 21.1 ± 0.7 | 20.1 | 24.5 | 17.49 ± 2.64 |
| mattcl-py | input-lanjian | 21.1 ± 0.7 | 20.3 | 23.7 | 17.49 ± 2.63 |
| mattcl-py | input-pting | 21.1 ± 0.5 | 20.0 | 23.7 | 17.50 ± 2.61 |
| mattcl-py | input-mattcl | 21.1 ± 0.7 | 20.0 | 24.2 | 17.54 ± 2.65 |
| pting | input-kcen | 23.1 ± 0.7 | 22.0 | 25.9 | 19.15 ± 2.89 |
| pting | input-mattcl | 23.1 ± 0.8 | 21.9 | 26.5 | 19.17 ± 2.89 |
| pting | input-chancalan | 23.2 ± 0.8 | 22.1 | 26.6 | 19.22 ± 2.92 |
| pting | input-lanjian | 23.3 ± 0.9 | 22.3 | 25.9 | 19.31 ± 2.94 |
| pting | input-pting | 23.4 ± 0.8 | 22.1 | 26.7 | 19.44 ± 2.95 |
| chancalan | input-mattcl | 26.0 ± 0.7 | 25.0 | 28.6 | 21.55 ± 3.22 |
| chancalan | input-lanjian | 26.0 ± 0.7 | 25.2 | 29.1 | 21.58 ± 3.23 |
| chancalan | input-kcen | 26.0 ± 0.8 | 24.9 | 28.8 | 21.61 ± 3.25 |
| chancalan | input-chancalan | 26.1 ± 0.7 | 25.1 | 28.9 | 21.66 ± 3.25 |
| chancalan | input-pting | 26.8 ± 3.0 | 25.6 | 49.2 | 22.25 ± 4.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|