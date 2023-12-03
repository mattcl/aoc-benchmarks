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
| mattcl | input-chancalan | 1.4 ± 0.2 | 0.8 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.1 | 1.00 ± 0.20 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.0 | 1.01 ± 0.23 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.2 | 1.02 ± 0.21 |
| mattcl | input-pting | 1.5 ± 0.2 | 0.7 | 2.0 | 1.05 ± 0.23 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.2 | 1.09 ± 0.23 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 0.8 | 2.2 | 1.11 ± 0.23 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.7 | 2.2 | 1.11 ± 0.24 |
| lanjian | input-pting | 1.6 ± 0.2 | 0.8 | 2.2 | 1.16 ± 0.23 |
| lanjian | input-lanjian | 1.6 ± 0.2 | 0.7 | 2.2 | 1.19 ± 0.24 |
| kcen | input-kcen | 19.0 ± 0.6 | 18.4 | 22.0 | 13.73 ± 2.00 |
| kcen | input-lanjian | 19.1 ± 0.8 | 18.0 | 22.1 | 13.80 ± 2.04 |
| kcen | input-chancalan | 19.2 ± 0.7 | 18.1 | 22.2 | 13.84 ± 2.04 |
| kcen | input-pting | 19.2 ± 0.6 | 18.5 | 22.8 | 13.87 ± 2.03 |
| kcen | input-mattcl | 19.5 ± 3.7 | 18.1 | 63.6 | 14.10 ± 3.33 |
| mattcl-py | input-mattcl | 21.0 ± 0.6 | 20.0 | 24.0 | 15.14 ± 2.21 |
| mattcl-py | input-chancalan | 21.0 ± 0.5 | 20.1 | 23.9 | 15.16 ± 2.20 |
| mattcl-py | input-lanjian | 21.1 ± 0.7 | 20.2 | 24.1 | 15.20 ± 2.22 |
| mattcl-py | input-pting | 21.2 ± 0.8 | 20.3 | 24.5 | 15.29 ± 2.25 |
| mattcl-py | input-kcen | 21.2 ± 0.7 | 20.1 | 24.1 | 15.29 ± 2.25 |
| pting | input-lanjian | 22.8 ± 0.7 | 21.5 | 25.6 | 16.46 ± 2.41 |
| pting | input-chancalan | 22.8 ± 0.6 | 21.6 | 25.7 | 16.49 ± 2.40 |
| pting | input-mattcl | 22.8 ± 0.8 | 21.8 | 25.5 | 16.49 ± 2.42 |
| pting | input-kcen | 22.9 ± 0.8 | 21.8 | 26.0 | 16.54 ± 2.44 |
| pting | input-pting | 23.1 ± 0.7 | 22.0 | 25.6 | 16.66 ± 2.43 |
| chancalan | input-mattcl | 25.7 ± 0.6 | 24.8 | 28.9 | 18.56 ± 2.69 |
| chancalan | input-kcen | 25.8 ± 0.7 | 24.9 | 28.8 | 18.60 ± 2.71 |
| chancalan | input-lanjian | 25.9 ± 0.7 | 24.9 | 28.9 | 18.66 ± 2.71 |
| chancalan | input-chancalan | 25.9 ± 0.8 | 24.5 | 28.7 | 18.69 ± 2.73 |
| chancalan | input-pting | 26.0 ± 0.7 | 25.2 | 29.0 | 18.75 ± 2.73 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|