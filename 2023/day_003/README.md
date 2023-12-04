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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.6 | 1.4 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.4 | 1.6 | 1.01 ± 0.19 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 2.1 | 1.04 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 2.0 | 1.04 ± 0.21 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.7 | 1.8 | 1.08 ± 0.21 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.8 | 2.0 | 1.35 ± 0.27 |
| lanjian | input-chancalan | 1.6 ± 0.2 | 0.8 | 2.2 | 1.36 ± 0.27 |
| lanjian | input-pting | 1.6 ± 0.3 | 0.6 | 2.2 | 1.41 ± 0.32 |
| lanjian | input-mattcl | 1.7 ± 0.2 | 0.8 | 2.1 | 1.44 ± 0.27 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 0.8 | 2.1 | 1.46 ± 0.26 |
| kcen | input-kcen | 18.6 ± 0.6 | 17.6 | 21.7 | 16.21 ± 2.22 |
| kcen | input-chancalan | 18.7 ± 0.7 | 17.6 | 22.0 | 16.27 ± 2.25 |
| kcen | input-mattcl | 18.7 ± 0.6 | 18.0 | 21.5 | 16.30 ± 2.24 |
| kcen | input-lanjian | 18.8 ± 0.6 | 18.1 | 21.4 | 16.37 ± 2.26 |
| kcen | input-pting | 18.9 ± 0.8 | 17.8 | 22.2 | 16.44 ± 2.31 |
| mattcl-py | input-chancalan | 20.8 ± 0.7 | 19.9 | 24.2 | 18.08 ± 2.48 |
| mattcl-py | input-lanjian | 20.8 ± 0.7 | 19.8 | 24.0 | 18.12 ± 2.49 |
| mattcl-py | input-mattcl | 20.8 ± 0.6 | 19.5 | 23.1 | 18.13 ± 2.48 |
| mattcl-py | input-pting | 20.9 ± 0.6 | 19.8 | 24.3 | 18.16 ± 2.47 |
| mattcl-py | input-kcen | 21.1 ± 2.2 | 19.7 | 45.3 | 18.34 ± 3.09 |
| pting | input-mattcl | 22.7 ± 0.6 | 22.0 | 25.8 | 19.77 ± 2.69 |
| pting | input-lanjian | 22.7 ± 0.6 | 21.8 | 25.5 | 19.79 ± 2.70 |
| pting | input-kcen | 22.8 ± 0.7 | 21.8 | 25.7 | 19.86 ± 2.73 |
| pting | input-chancalan | 22.9 ± 0.7 | 21.8 | 25.4 | 19.90 ± 2.73 |
| pting | input-pting | 23.2 ± 0.7 | 22.3 | 25.9 | 20.16 ± 2.76 |
| chancalan | input-mattcl | 25.8 ± 0.9 | 24.9 | 28.8 | 22.44 ± 3.09 |
| chancalan | input-chancalan | 25.8 ± 0.8 | 24.8 | 28.8 | 22.47 ± 3.07 |
| chancalan | input-lanjian | 25.8 ± 0.8 | 24.9 | 29.0 | 22.47 ± 3.08 |
| chancalan | input-kcen | 25.9 ± 0.9 | 24.8 | 28.5 | 22.55 ± 3.10 |
| chancalan | input-pting | 25.9 ± 0.8 | 24.9 | 28.9 | 22.57 ± 3.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|