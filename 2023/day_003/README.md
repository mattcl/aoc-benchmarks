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
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.4 | 2.0 | 1.00 |
| mattcl | input-chancalan | 1.5 ± 0.2 | 0.7 | 2.1 | 1.07 ± 0.24 |
| mattcl | input-pting | 1.5 ± 0.2 | 0.8 | 2.2 | 1.07 ± 0.25 |
| mattcl | input-kcen | 1.5 ± 0.2 | 0.8 | 2.4 | 1.07 ± 0.25 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 0.7 | 2.2 | 1.12 ± 0.25 |
| lanjian | input-kcen | 1.6 ± 0.3 | 0.8 | 2.3 | 1.13 ± 0.26 |
| lanjian | input-chancalan | 1.6 ± 0.2 | 0.8 | 2.3 | 1.14 ± 0.26 |
| lanjian | input-mattcl | 1.6 ± 0.3 | 0.8 | 2.2 | 1.16 ± 0.28 |
| lanjian | input-pting | 1.7 ± 0.2 | 0.9 | 2.3 | 1.21 ± 0.25 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 0.9 | 2.2 | 1.22 ± 0.25 |
| kcen | input-kcen | 19.3 ± 0.7 | 18.4 | 22.3 | 14.08 ± 2.28 |
| kcen | input-chancalan | 19.4 ± 0.8 | 18.3 | 22.0 | 14.11 ± 2.30 |
| kcen | input-lanjian | 19.4 ± 0.7 | 18.4 | 22.1 | 14.12 ± 2.29 |
| kcen | input-mattcl | 19.4 ± 0.8 | 18.0 | 22.8 | 14.14 ± 2.31 |
| kcen | input-pting | 19.4 ± 0.7 | 18.1 | 22.5 | 14.14 ± 2.30 |
| mattcl-py | input-mattcl | 22.1 ± 0.6 | 20.7 | 25.0 | 16.06 ± 2.59 |
| mattcl-py | input-lanjian | 22.2 ± 0.7 | 21.2 | 25.1 | 16.15 ± 2.60 |
| mattcl-py | input-chancalan | 22.2 ± 0.7 | 21.1 | 24.7 | 16.16 ± 2.60 |
| mattcl-py | input-pting | 22.2 ± 0.6 | 21.2 | 25.2 | 16.17 ± 2.60 |
| mattcl-py | input-kcen | 22.2 ± 1.0 | 20.9 | 25.7 | 16.19 ± 2.66 |
| pting | input-mattcl | 23.0 ± 0.8 | 21.9 | 25.7 | 16.73 ± 2.71 |
| pting | input-kcen | 23.0 ± 0.7 | 22.1 | 25.9 | 16.77 ± 2.70 |
| pting | input-pting | 23.2 ± 0.7 | 21.9 | 26.8 | 16.88 ± 2.72 |
| pting | input-chancalan | 23.2 ± 0.7 | 22.2 | 26.6 | 16.89 ± 2.72 |
| pting | input-lanjian | 23.3 ± 0.8 | 21.9 | 26.1 | 16.99 ± 2.75 |
| chancalan | input-chancalan | 26.0 ± 0.8 | 24.9 | 28.9 | 18.91 ± 3.04 |
| chancalan | input-mattcl | 26.0 ± 0.9 | 24.6 | 29.2 | 18.94 ± 3.07 |
| chancalan | input-lanjian | 26.1 ± 0.7 | 24.9 | 28.6 | 18.97 ± 3.05 |
| chancalan | input-pting | 26.2 ± 0.9 | 25.2 | 29.1 | 19.08 ± 3.09 |
| chancalan | input-kcen | 26.2 ± 0.9 | 25.0 | 28.6 | 19.08 ± 3.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|