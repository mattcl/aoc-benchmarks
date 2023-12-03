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
| mattcl | input-pting | 1.4 ± 0.2 | 0.6 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.6 | 1.7 | 1.01 ± 0.23 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.1 | 1.03 ± 0.22 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.1 | 1.04 ± 0.23 |
| mattcl | input-chancalan | 1.4 ± 0.2 | 0.6 | 1.9 | 1.06 ± 0.25 |
| lanjian | input-pting | 1.5 ± 0.2 | 0.7 | 2.0 | 1.11 ± 0.25 |
| lanjian | input-chancalan | 1.6 ± 0.2 | 0.7 | 2.1 | 1.16 ± 0.25 |
| lanjian | input-lanjian | 1.6 ± 0.2 | 0.8 | 2.1 | 1.17 ± 0.26 |
| lanjian | input-kcen | 1.6 ± 0.2 | 0.8 | 2.0 | 1.18 ± 0.25 |
| lanjian | input-mattcl | 1.6 ± 0.2 | 0.8 | 2.0 | 1.20 ± 0.25 |
| kcen | input-mattcl | 19.3 ± 0.6 | 18.0 | 22.3 | 14.15 ± 2.46 |
| kcen | input-lanjian | 19.3 ± 0.6 | 18.1 | 21.8 | 14.16 ± 2.46 |
| kcen | input-chancalan | 19.4 ± 0.7 | 18.4 | 22.5 | 14.21 ± 2.47 |
| kcen | input-pting | 19.5 ± 0.7 | 18.2 | 23.1 | 14.28 ± 2.49 |
| kcen | input-kcen | 19.5 ± 1.8 | 18.4 | 39.4 | 14.28 ± 2.76 |
| mattcl-py | input-kcen | 21.1 ± 0.7 | 19.9 | 24.2 | 15.46 ± 2.68 |
| mattcl-py | input-lanjian | 21.1 ± 0.5 | 20.2 | 23.2 | 15.46 ± 2.67 |
| mattcl-py | input-chancalan | 21.1 ± 0.6 | 20.2 | 24.3 | 15.49 ± 2.68 |
| mattcl-py | input-mattcl | 21.2 ± 0.5 | 20.0 | 23.7 | 15.53 ± 2.67 |
| mattcl-py | input-pting | 21.2 ± 0.6 | 20.3 | 24.3 | 15.56 ± 2.69 |
| pting | input-kcen | 23.0 ± 0.7 | 21.9 | 25.7 | 16.86 ± 2.92 |
| pting | input-lanjian | 23.1 ± 0.8 | 21.8 | 26.7 | 16.96 ± 2.95 |
| pting | input-chancalan | 23.2 ± 0.8 | 21.7 | 26.4 | 16.99 ± 2.95 |
| pting | input-pting | 23.3 ± 0.7 | 22.0 | 26.0 | 17.10 ± 2.96 |
| pting | input-mattcl | 23.4 ± 4.4 | 22.0 | 70.7 | 17.13 ± 4.37 |
| chancalan | input-kcen | 25.8 ± 0.7 | 24.6 | 29.5 | 18.95 ± 3.27 |
| chancalan | input-mattcl | 26.0 ± 1.0 | 24.5 | 29.2 | 19.06 ± 3.33 |
| chancalan | input-lanjian | 26.2 ± 0.9 | 25.1 | 29.4 | 19.17 ± 3.34 |
| chancalan | input-pting | 26.2 ± 0.9 | 25.1 | 29.3 | 19.20 ± 3.34 |
| chancalan | input-chancalan | 26.2 ± 1.0 | 24.6 | 29.5 | 19.24 ± 3.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|