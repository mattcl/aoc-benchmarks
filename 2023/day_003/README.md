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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 2.1 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.7 | 1.04 ± 0.23 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.5 | 1.9 | 1.09 ± 0.26 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.6 | 2.2 | 1.12 ± 0.27 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.1 | 1.13 ± 0.25 |
| lanjian | input-kcen | 1.7 ± 0.2 | 1.0 | 2.3 | 1.41 ± 0.32 |
| lanjian | input-mattcl | 1.7 ± 0.2 | 1.1 | 2.4 | 1.45 ± 0.33 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 1.0 | 2.4 | 1.45 ± 0.31 |
| lanjian | input-pting | 1.8 ± 0.2 | 1.0 | 2.2 | 1.47 ± 0.31 |
| lanjian | input-chancalan | 1.9 ± 4.1 | 0.5 | 59.1 | 1.54 ± 3.40 |
| kcen | input-chancalan | 18.9 ± 0.7 | 17.8 | 21.8 | 15.67 ± 2.93 |
| kcen | input-mattcl | 19.1 ± 0.8 | 18.1 | 22.3 | 15.83 ± 2.97 |
| kcen | input-lanjian | 19.1 ± 0.8 | 18.1 | 22.3 | 15.87 ± 2.98 |
| kcen | input-kcen | 19.1 ± 0.8 | 18.0 | 22.1 | 15.88 ± 2.99 |
| kcen | input-pting | 19.1 ± 0.6 | 18.1 | 21.7 | 15.90 ± 2.96 |
| mattcl-py | input-mattcl | 21.0 ± 0.7 | 19.7 | 24.2 | 17.43 ± 3.25 |
| mattcl-py | input-kcen | 21.0 ± 0.7 | 19.7 | 24.3 | 17.47 ± 3.25 |
| mattcl-py | input-lanjian | 21.1 ± 0.7 | 20.2 | 24.5 | 17.56 ± 3.28 |
| mattcl-py | input-chancalan | 21.2 ± 0.8 | 20.2 | 24.5 | 17.59 ± 3.29 |
| mattcl-py | input-pting | 21.3 ± 0.8 | 20.1 | 24.9 | 17.71 ± 3.31 |
| pting | input-mattcl | 23.1 ± 0.7 | 21.8 | 26.5 | 19.19 ± 3.57 |
| pting | input-lanjian | 23.2 ± 0.8 | 22.2 | 26.7 | 19.27 ± 3.60 |
| pting | input-kcen | 23.2 ± 0.7 | 22.1 | 26.6 | 19.29 ± 3.59 |
| pting | input-chancalan | 23.4 ± 0.8 | 22.2 | 26.7 | 19.40 ± 3.62 |
| pting | input-pting | 23.5 ± 0.7 | 22.5 | 26.4 | 19.49 ± 3.62 |
| chancalan | input-chancalan | 26.0 ± 0.8 | 24.8 | 29.4 | 21.59 ± 4.01 |
| chancalan | input-mattcl | 26.1 ± 0.9 | 24.9 | 29.5 | 21.69 ± 4.05 |
| chancalan | input-kcen | 26.1 ± 0.9 | 25.2 | 29.5 | 21.72 ± 4.06 |
| chancalan | input-lanjian | 26.2 ± 0.8 | 25.1 | 29.2 | 21.72 ± 4.04 |
| chancalan | input-pting | 26.2 ± 0.7 | 25.0 | 29.6 | 21.74 ± 4.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|