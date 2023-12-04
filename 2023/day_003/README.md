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
| mattcl | input-lanjian | 1.2 ± 0.3 | 0.4 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.8 | 1.04 ± 0.28 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.9 | 1.05 ± 0.31 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 1.5 | 1.06 ± 0.27 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 2.0 | 1.08 ± 0.28 |
| lanjian | input-chancalan | 1.6 ± 0.2 | 0.8 | 2.3 | 1.41 ± 0.37 |
| lanjian | input-mattcl | 1.7 ± 0.2 | 0.9 | 2.3 | 1.48 ± 0.39 |
| lanjian | input-kcen | 1.8 ± 0.2 | 1.2 | 2.3 | 1.50 ± 0.37 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 0.9 | 2.2 | 1.51 ± 0.37 |
| lanjian | input-pting | 1.8 ± 0.1 | 1.2 | 2.2 | 1.53 ± 0.35 |
| kcen | input-chancalan | 18.9 ± 0.6 | 17.7 | 22.0 | 16.22 ± 3.61 |
| kcen | input-kcen | 19.0 ± 1.5 | 17.7 | 35.2 | 16.31 ± 3.82 |
| kcen | input-mattcl | 19.1 ± 0.8 | 17.8 | 22.3 | 16.33 ± 3.66 |
| kcen | input-lanjian | 19.1 ± 0.8 | 17.8 | 22.3 | 16.35 ± 3.66 |
| kcen | input-pting | 19.1 ± 0.5 | 18.2 | 21.8 | 16.38 ± 3.63 |
| mattcl-py | input-mattcl | 21.1 ± 0.7 | 19.8 | 23.7 | 18.05 ± 4.02 |
| mattcl-py | input-pting | 21.1 ± 0.7 | 20.2 | 24.5 | 18.07 ± 4.02 |
| mattcl-py | input-lanjian | 21.1 ± 0.7 | 20.1 | 24.4 | 18.09 ± 4.03 |
| mattcl-py | input-kcen | 21.1 ± 0.8 | 20.3 | 24.3 | 18.09 ± 4.04 |
| mattcl-py | input-chancalan | 21.7 ± 4.7 | 19.9 | 75.4 | 18.62 ± 5.75 |
| pting | input-chancalan | 23.1 ± 0.7 | 22.1 | 25.8 | 19.81 ± 4.40 |
| pting | input-kcen | 23.3 ± 0.7 | 22.2 | 25.8 | 19.92 ± 4.42 |
| pting | input-mattcl | 23.3 ± 0.7 | 22.3 | 26.4 | 19.94 ± 4.43 |
| pting | input-lanjian | 23.4 ± 0.8 | 21.9 | 26.9 | 20.01 ± 4.46 |
| pting | input-pting | 23.7 ± 3.2 | 22.3 | 57.7 | 20.26 ± 5.23 |
| chancalan | input-chancalan | 25.9 ± 0.7 | 25.2 | 29.0 | 22.22 ± 4.93 |
| chancalan | input-mattcl | 26.0 ± 0.8 | 25.1 | 29.3 | 22.30 ± 4.96 |
| chancalan | input-lanjian | 26.2 ± 0.9 | 25.1 | 29.5 | 22.41 ± 4.99 |
| chancalan | input-kcen | 26.2 ± 0.9 | 25.0 | 29.4 | 22.43 ± 5.00 |
| chancalan | input-pting | 26.5 ± 1.0 | 25.0 | 30.8 | 22.65 ± 5.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|