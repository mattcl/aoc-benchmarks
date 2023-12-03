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
| mattcl | input-pting | 1.4 ± 0.2 | 0.7 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 1.7 | 1.01 ± 0.18 |
| mattcl | input-kcen | 1.4 ± 0.1 | 0.7 | 1.9 | 1.02 ± 0.17 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.6 | 2.2 | 1.03 ± 0.19 |
| mattcl | input-chancalan | 1.5 ± 0.2 | 0.7 | 2.3 | 1.07 ± 0.22 |
| lanjian | input-mattcl | 1.8 ± 0.2 | 1.1 | 2.5 | 1.29 ± 0.23 |
| lanjian | input-kcen | 1.9 ± 0.2 | 1.1 | 2.4 | 1.33 ± 0.24 |
| lanjian | input-lanjian | 1.9 ± 0.2 | 1.1 | 2.5 | 1.36 ± 0.25 |
| lanjian | input-chancalan | 1.9 ± 0.2 | 1.0 | 2.5 | 1.37 ± 0.24 |
| lanjian | input-pting | 2.0 ± 0.2 | 1.1 | 2.4 | 1.39 ± 0.23 |
| kcen | input-mattcl | 19.6 ± 0.6 | 18.7 | 22.5 | 13.98 ± 1.92 |
| kcen | input-pting | 19.7 ± 0.6 | 18.5 | 22.9 | 14.02 ± 1.94 |
| kcen | input-kcen | 19.7 ± 0.6 | 18.6 | 23.1 | 14.02 ± 1.94 |
| kcen | input-lanjian | 19.7 ± 0.6 | 18.8 | 22.6 | 14.03 ± 1.93 |
| kcen | input-chancalan | 19.8 ± 0.7 | 19.0 | 22.8 | 14.11 ± 1.96 |
| mattcl-py | input-lanjian | 21.3 ± 0.8 | 20.3 | 24.6 | 15.13 ± 2.11 |
| mattcl-py | input-chancalan | 21.3 ± 0.5 | 20.3 | 23.6 | 15.14 ± 2.07 |
| mattcl-py | input-mattcl | 21.4 ± 0.7 | 20.5 | 25.3 | 15.22 ± 2.10 |
| mattcl-py | input-kcen | 21.4 ± 0.7 | 19.8 | 24.5 | 15.25 ± 2.12 |
| mattcl-py | input-pting | 21.4 ± 0.6 | 20.5 | 24.5 | 15.27 ± 2.10 |
| pting | input-lanjian | 23.4 ± 0.7 | 22.1 | 26.0 | 16.63 ± 2.29 |
| pting | input-mattcl | 23.4 ± 0.7 | 22.3 | 26.4 | 16.63 ± 2.29 |
| pting | input-chancalan | 23.4 ± 0.8 | 22.4 | 27.1 | 16.68 ± 2.31 |
| pting | input-pting | 23.6 ± 0.6 | 22.7 | 26.6 | 16.82 ± 2.30 |
| pting | input-kcen | 23.6 ± 0.8 | 22.4 | 26.6 | 16.84 ± 2.34 |
| chancalan | input-kcen | 26.2 ± 0.7 | 25.3 | 29.0 | 18.66 ± 2.56 |
| chancalan | input-mattcl | 26.3 ± 0.8 | 25.0 | 29.1 | 18.69 ± 2.58 |
| chancalan | input-lanjian | 26.5 ± 0.9 | 25.2 | 28.9 | 18.85 ± 2.61 |
| chancalan | input-chancalan | 26.6 ± 1.0 | 25.4 | 29.5 | 18.95 ± 2.65 |
| chancalan | input-pting | 26.6 ± 0.9 | 25.5 | 29.3 | 18.97 ± 2.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|