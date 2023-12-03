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
| mattcl | input-kcen | 1.5 ± 0.2 | 0.5 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.1 | 1.01 ± 0.22 |
| mattcl | input-pting | 1.5 ± 0.2 | 0.9 | 2.1 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.6 ± 0.2 | 0.8 | 2.1 | 1.07 ± 0.23 |
| lanjian | input-mattcl | 1.6 ± 0.2 | 0.7 | 2.2 | 1.08 ± 0.24 |
| mattcl | input-chancalan | 1.6 ± 0.2 | 0.8 | 2.6 | 1.09 ± 0.24 |
| lanjian | input-kcen | 1.7 ± 0.2 | 1.0 | 2.3 | 1.14 ± 0.23 |
| lanjian | input-chancalan | 1.8 ± 0.2 | 1.0 | 2.3 | 1.17 ± 0.23 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 0.9 | 2.4 | 1.19 ± 0.23 |
| lanjian | input-pting | 1.8 ± 0.2 | 0.9 | 2.3 | 1.20 ± 0.23 |
| kcen | input-kcen | 19.4 ± 0.7 | 18.1 | 22.2 | 12.95 ± 2.15 |
| kcen | input-pting | 19.4 ± 0.6 | 18.1 | 22.7 | 12.97 ± 2.15 |
| kcen | input-lanjian | 19.4 ± 0.6 | 18.2 | 22.3 | 12.97 ± 2.14 |
| kcen | input-mattcl | 19.5 ± 0.7 | 18.2 | 22.2 | 13.00 ± 2.16 |
| kcen | input-chancalan | 19.7 ± 0.7 | 18.6 | 22.7 | 13.13 ± 2.19 |
| mattcl-py | input-mattcl | 21.1 ± 0.7 | 20.1 | 24.1 | 14.04 ± 2.32 |
| mattcl-py | input-pting | 21.1 ± 0.6 | 20.3 | 24.1 | 14.08 ± 2.32 |
| mattcl-py | input-kcen | 21.1 ± 0.6 | 20.0 | 23.6 | 14.09 ± 2.32 |
| mattcl-py | input-chancalan | 21.1 ± 0.6 | 20.2 | 23.6 | 14.09 ± 2.32 |
| mattcl-py | input-lanjian | 21.2 ± 0.7 | 19.6 | 24.6 | 14.12 ± 2.33 |
| pting | input-kcen | 23.2 ± 0.8 | 22.1 | 26.7 | 15.46 ± 2.57 |
| pting | input-lanjian | 23.2 ± 0.7 | 22.1 | 26.5 | 15.47 ± 2.56 |
| pting | input-mattcl | 23.2 ± 0.8 | 22.1 | 25.9 | 15.49 ± 2.56 |
| pting | input-chancalan | 23.3 ± 0.8 | 22.2 | 26.1 | 15.53 ± 2.57 |
| pting | input-pting | 23.5 ± 0.8 | 22.4 | 26.7 | 15.65 ± 2.59 |
| chancalan | input-mattcl | 26.1 ± 0.7 | 25.0 | 28.7 | 17.39 ± 2.86 |
| chancalan | input-kcen | 26.1 ± 0.8 | 24.9 | 29.3 | 17.42 ± 2.87 |
| chancalan | input-lanjian | 26.1 ± 0.9 | 24.6 | 29.3 | 17.44 ± 2.89 |
| chancalan | input-pting | 26.3 ± 0.8 | 25.0 | 28.6 | 17.55 ± 2.89 |
| chancalan | input-chancalan | 26.4 ± 1.0 | 24.9 | 29.4 | 17.59 ± 2.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|