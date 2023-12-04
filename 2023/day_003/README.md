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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.7 | 1.01 ± 0.20 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.8 | 2.1 | 1.04 ± 0.20 |
| mattcl | input-chancalan | 1.3 ± 0.1 | 0.7 | 1.8 | 1.04 ± 0.19 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.8 | 2.0 | 1.08 ± 0.21 |
| lanjian | input-kcen | 1.8 ± 0.2 | 1.0 | 2.5 | 1.41 ± 0.28 |
| lanjian | input-chancalan | 1.8 ± 0.2 | 1.0 | 2.3 | 1.42 ± 0.28 |
| lanjian | input-mattcl | 1.8 ± 0.2 | 1.1 | 2.4 | 1.43 ± 0.28 |
| lanjian | input-pting | 1.8 ± 0.2 | 1.0 | 2.4 | 1.43 ± 0.27 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 0.9 | 2.3 | 1.44 ± 0.29 |
| kcen | input-mattcl | 19.0 ± 0.6 | 18.0 | 22.4 | 15.01 ± 2.25 |
| kcen | input-kcen | 19.0 ± 0.7 | 18.2 | 22.1 | 15.02 ± 2.27 |
| kcen | input-lanjian | 19.0 ± 0.6 | 18.1 | 22.2 | 15.04 ± 2.26 |
| kcen | input-chancalan | 19.0 ± 0.7 | 17.9 | 22.0 | 15.09 ± 2.28 |
| kcen | input-pting | 19.1 ± 0.8 | 18.0 | 22.6 | 15.10 ± 2.29 |
| mattcl-py | input-chancalan | 21.0 ± 0.5 | 20.3 | 24.0 | 16.66 ± 2.47 |
| mattcl-py | input-lanjian | 21.1 ± 0.7 | 20.0 | 23.7 | 16.68 ± 2.50 |
| mattcl-py | input-kcen | 21.1 ± 0.7 | 20.1 | 23.7 | 16.74 ± 2.51 |
| mattcl-py | input-mattcl | 21.3 ± 1.7 | 20.0 | 40.1 | 16.85 ± 2.81 |
| mattcl-py | input-pting | 21.4 ± 2.4 | 20.3 | 48.1 | 16.93 ± 3.11 |
| pting | input-kcen | 23.0 ± 0.6 | 22.0 | 25.7 | 18.22 ± 2.71 |
| pting | input-chancalan | 23.1 ± 0.6 | 21.9 | 25.7 | 18.28 ± 2.72 |
| pting | input-mattcl | 23.1 ± 0.8 | 22.0 | 26.2 | 18.28 ± 2.74 |
| pting | input-lanjian | 23.1 ± 0.8 | 22.2 | 26.4 | 18.33 ± 2.75 |
| pting | input-pting | 23.2 ± 0.6 | 22.2 | 26.0 | 18.39 ± 2.73 |
| chancalan | input-chancalan | 26.1 ± 0.6 | 24.8 | 28.8 | 20.64 ± 3.07 |
| chancalan | input-kcen | 26.1 ± 0.8 | 25.4 | 29.2 | 20.69 ± 3.09 |
| chancalan | input-pting | 26.1 ± 0.7 | 25.2 | 29.2 | 20.70 ± 3.09 |
| chancalan | input-mattcl | 26.2 ± 0.9 | 25.0 | 29.0 | 20.71 ± 3.11 |
| chancalan | input-lanjian | 26.2 ± 0.9 | 25.2 | 29.4 | 20.75 ± 3.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|