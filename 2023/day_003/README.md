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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.24 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.24 |
| mattcl | input-pting | 1.1 ± 0.1 | 0.3 | 1.7 | 1.04 ± 0.23 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.8 | 1.05 ± 0.24 |
| lanjian | input-mattcl | 1.5 ± 0.3 | 0.6 | 2.1 | 1.40 ± 0.34 |
| lanjian | input-kcen | 1.6 ± 0.3 | 0.8 | 2.1 | 1.47 ± 0.36 |
| lanjian | input-chancalan | 1.6 ± 0.3 | 0.5 | 2.1 | 1.47 ± 0.37 |
| lanjian | input-lanjian | 1.6 ± 0.2 | 0.7 | 2.1 | 1.51 ± 0.34 |
| lanjian | input-pting | 1.7 ± 0.2 | 0.9 | 2.1 | 1.55 ± 0.34 |
| kcen | input-mattcl | 18.7 ± 0.6 | 17.8 | 21.5 | 17.48 ± 3.13 |
| kcen | input-lanjian | 18.7 ± 0.7 | 17.6 | 21.7 | 17.51 ± 3.16 |
| kcen | input-kcen | 18.7 ± 0.8 | 17.7 | 21.5 | 17.53 ± 3.16 |
| kcen | input-chancalan | 18.7 ± 0.8 | 17.7 | 22.0 | 17.54 ± 3.18 |
| kcen | input-pting | 18.8 ± 0.7 | 17.5 | 21.8 | 17.58 ± 3.17 |
| mattcl-py | input-chancalan | 20.6 ± 0.7 | 19.7 | 24.1 | 19.30 ± 3.46 |
| mattcl-py | input-lanjian | 20.6 ± 0.5 | 19.7 | 23.7 | 19.31 ± 3.43 |
| mattcl-py | input-kcen | 20.8 ± 0.7 | 19.8 | 23.4 | 19.45 ± 3.49 |
| mattcl-py | input-mattcl | 20.8 ± 0.8 | 19.4 | 24.3 | 19.46 ± 3.51 |
| mattcl-py | input-pting | 21.0 ± 0.7 | 19.9 | 24.0 | 19.62 ± 3.52 |
| pting | input-chancalan | 22.7 ± 0.7 | 21.9 | 26.5 | 21.26 ± 3.80 |
| pting | input-kcen | 22.7 ± 0.6 | 21.9 | 26.5 | 21.26 ± 3.79 |
| pting | input-mattcl | 22.8 ± 0.7 | 21.7 | 25.3 | 21.29 ± 3.81 |
| pting | input-lanjian | 22.9 ± 0.9 | 21.7 | 26.4 | 21.44 ± 3.87 |
| pting | input-pting | 23.4 ± 3.4 | 22.0 | 60.1 | 21.89 ± 4.97 |
| chancalan | input-kcen | 25.7 ± 0.7 | 24.7 | 28.3 | 24.00 ± 4.28 |
| chancalan | input-lanjian | 25.7 ± 0.7 | 24.9 | 28.7 | 24.04 ± 4.28 |
| chancalan | input-chancalan | 25.7 ± 0.7 | 24.6 | 29.1 | 24.06 ± 4.29 |
| chancalan | input-mattcl | 25.9 ± 0.8 | 24.8 | 29.0 | 24.20 ± 4.33 |
| chancalan | input-pting | 26.0 ± 1.2 | 24.6 | 36.3 | 24.32 ± 4.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|