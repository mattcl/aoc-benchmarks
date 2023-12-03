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
| mattcl | input-chancalan | 1.5 ± 0.2 | 0.8 | 2.0 | 1.00 |
| mattcl | input-kcen | 1.6 ± 0.3 | 0.6 | 2.3 | 1.02 ± 0.23 |
| mattcl | input-mattcl | 1.6 ± 0.3 | 0.8 | 2.4 | 1.04 ± 0.23 |
| mattcl | input-lanjian | 1.6 ± 0.2 | 0.9 | 2.4 | 1.06 ± 0.22 |
| lanjian | input-kcen | 1.7 ± 0.3 | 0.7 | 2.3 | 1.11 ± 0.23 |
| mattcl | input-pting | 1.7 ± 0.3 | 0.8 | 2.4 | 1.11 ± 0.23 |
| lanjian | input-chancalan | 1.7 ± 0.2 | 0.8 | 2.3 | 1.12 ± 0.21 |
| lanjian | input-mattcl | 1.7 ± 0.2 | 1.0 | 2.3 | 1.14 ± 0.22 |
| lanjian | input-pting | 1.8 ± 0.2 | 1.0 | 2.2 | 1.16 ± 0.20 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 1.0 | 2.6 | 1.17 ± 0.21 |
| kcen | input-mattcl | 19.5 ± 0.6 | 18.5 | 22.6 | 12.70 ± 1.78 |
| kcen | input-lanjian | 19.5 ± 0.6 | 18.6 | 22.2 | 12.74 ± 1.78 |
| kcen | input-pting | 19.6 ± 0.7 | 18.6 | 22.9 | 12.78 ± 1.80 |
| kcen | input-chancalan | 19.6 ± 0.8 | 18.5 | 22.9 | 12.78 ± 1.81 |
| kcen | input-kcen | 19.6 ± 0.8 | 18.6 | 22.8 | 12.81 ± 1.82 |
| mattcl-py | input-chancalan | 22.6 ± 0.7 | 21.5 | 26.0 | 14.74 ± 2.07 |
| mattcl-py | input-kcen | 22.6 ± 0.8 | 21.1 | 26.0 | 14.77 ± 2.08 |
| mattcl-py | input-lanjian | 22.6 ± 1.7 | 21.2 | 40.6 | 14.78 ± 2.30 |
| mattcl-py | input-mattcl | 22.7 ± 0.8 | 21.4 | 25.5 | 14.79 ± 2.08 |
| mattcl-py | input-pting | 22.7 ± 0.8 | 21.8 | 26.0 | 14.83 ± 2.08 |
| pting | input-lanjian | 23.2 ± 0.8 | 22.2 | 25.9 | 15.14 ± 2.12 |
| pting | input-chancalan | 23.2 ± 0.8 | 22.0 | 26.7 | 15.15 ± 2.13 |
| pting | input-kcen | 23.2 ± 0.9 | 22.2 | 26.6 | 15.17 ± 2.15 |
| pting | input-mattcl | 23.2 ± 0.8 | 22.2 | 26.5 | 15.17 ± 2.13 |
| pting | input-pting | 23.3 ± 0.6 | 22.1 | 26.4 | 15.24 ± 2.12 |
| chancalan | input-lanjian | 26.0 ± 0.6 | 25.1 | 28.9 | 17.00 ± 2.35 |
| chancalan | input-mattcl | 26.1 ± 0.8 | 24.9 | 29.3 | 17.04 ± 2.39 |
| chancalan | input-kcen | 26.2 ± 0.9 | 25.0 | 29.4 | 17.08 ± 2.40 |
| chancalan | input-chancalan | 26.2 ± 0.7 | 25.3 | 29.3 | 17.09 ± 2.38 |
| chancalan | input-pting | 26.4 ± 0.9 | 25.3 | 29.6 | 17.24 ± 2.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|