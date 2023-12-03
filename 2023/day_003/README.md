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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.6 | 1.01 ± 0.23 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.22 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.22 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.9 | 1.06 ± 0.23 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.6 | 2.1 | 1.31 ± 0.31 |
| lanjian | input-kcen | 1.5 ± 0.3 | 0.7 | 2.1 | 1.36 ± 0.34 |
| lanjian | input-pting | 1.6 ± 0.3 | 0.6 | 2.2 | 1.41 ± 0.34 |
| lanjian | input-chancalan | 1.6 ± 0.2 | 0.8 | 2.2 | 1.42 ± 0.32 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 0.9 | 2.2 | 1.47 ± 0.32 |
| kcen | input-mattcl | 19.1 ± 0.6 | 18.2 | 22.6 | 16.88 ± 2.90 |
| kcen | input-lanjian | 19.1 ± 0.7 | 18.1 | 22.2 | 16.90 ± 2.92 |
| kcen | input-pting | 19.2 ± 0.5 | 18.4 | 20.9 | 16.97 ± 2.90 |
| kcen | input-kcen | 19.2 ± 0.7 | 17.9 | 22.2 | 16.98 ± 2.95 |
| kcen | input-chancalan | 19.3 ± 2.4 | 18.3 | 47.8 | 17.09 ± 3.57 |
| mattcl-py | input-kcen | 20.8 ± 0.6 | 19.9 | 23.6 | 18.39 ± 3.16 |
| mattcl-py | input-mattcl | 20.8 ± 0.7 | 19.9 | 23.9 | 18.42 ± 3.17 |
| mattcl-py | input-lanjian | 20.8 ± 0.7 | 19.8 | 23.9 | 18.43 ± 3.17 |
| mattcl-py | input-chancalan | 20.9 ± 0.7 | 19.7 | 24.2 | 18.47 ± 3.18 |
| mattcl-py | input-pting | 21.0 ± 0.7 | 20.0 | 23.5 | 18.61 ± 3.20 |
| pting | input-lanjian | 22.7 ± 0.7 | 21.7 | 25.8 | 20.13 ± 3.45 |
| pting | input-kcen | 22.8 ± 0.7 | 21.7 | 25.8 | 20.21 ± 3.47 |
| pting | input-chancalan | 22.9 ± 0.8 | 22.0 | 25.7 | 20.28 ± 3.49 |
| pting | input-mattcl | 22.9 ± 0.9 | 21.9 | 26.5 | 20.31 ± 3.52 |
| pting | input-pting | 23.0 ± 0.7 | 21.9 | 26.0 | 20.39 ± 3.50 |
| chancalan | input-mattcl | 25.7 ± 0.6 | 24.4 | 28.2 | 22.78 ± 3.89 |
| chancalan | input-lanjian | 25.8 ± 0.7 | 25.1 | 29.2 | 22.86 ± 3.91 |
| chancalan | input-kcen | 25.8 ± 0.7 | 24.9 | 28.6 | 22.87 ± 3.92 |
| chancalan | input-pting | 25.9 ± 0.6 | 25.1 | 29.0 | 22.88 ± 3.91 |
| chancalan | input-chancalan | 26.3 ± 4.9 | 25.0 | 78.1 | 23.24 ± 5.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|