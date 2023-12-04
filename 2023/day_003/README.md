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
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.6 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.1 | 0.6 | 1.6 | 1.01 ± 0.20 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.22 |
| mattcl | input-mattcl | 1.1 ± 0.1 | 0.6 | 1.3 | 1.02 ± 0.18 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.8 | 1.07 ± 0.22 |
| lanjian | input-kcen | 1.6 ± 0.2 | 0.7 | 2.1 | 1.40 ± 0.30 |
| lanjian | input-chancalan | 1.6 ± 0.2 | 0.8 | 2.1 | 1.42 ± 0.30 |
| lanjian | input-mattcl | 1.6 ± 0.2 | 0.7 | 2.1 | 1.43 ± 0.29 |
| lanjian | input-lanjian | 1.6 ± 0.3 | 0.8 | 2.1 | 1.45 ± 0.31 |
| lanjian | input-pting | 1.6 ± 0.2 | 0.8 | 2.1 | 1.48 ± 0.29 |
| kcen | input-kcen | 18.7 ± 0.6 | 17.7 | 21.2 | 16.73 ± 2.47 |
| kcen | input-chancalan | 18.7 ± 0.7 | 17.6 | 22.1 | 16.75 ± 2.49 |
| kcen | input-lanjian | 18.7 ± 0.7 | 17.6 | 21.2 | 16.76 ± 2.49 |
| kcen | input-mattcl | 18.8 ± 0.8 | 17.8 | 21.7 | 16.83 ± 2.53 |
| kcen | input-pting | 18.8 ± 0.8 | 17.9 | 22.0 | 16.83 ± 2.52 |
| mattcl-py | input-lanjian | 20.6 ± 0.6 | 19.8 | 24.0 | 18.50 ± 2.72 |
| mattcl-py | input-chancalan | 20.8 ± 0.8 | 19.7 | 24.2 | 18.61 ± 2.77 |
| mattcl-py | input-kcen | 20.8 ± 0.8 | 20.0 | 24.4 | 18.65 ± 2.78 |
| mattcl-py | input-pting | 20.8 ± 0.7 | 19.7 | 24.2 | 18.69 ± 2.77 |
| mattcl-py | input-mattcl | 20.9 ± 0.8 | 19.9 | 23.8 | 18.77 ± 2.81 |
| pting | input-mattcl | 22.6 ± 0.5 | 21.7 | 24.6 | 20.26 ± 2.95 |
| pting | input-lanjian | 22.7 ± 0.6 | 21.9 | 25.4 | 20.32 ± 2.99 |
| pting | input-chancalan | 22.9 ± 0.8 | 21.7 | 26.1 | 20.53 ± 3.06 |
| pting | input-pting | 23.0 ± 0.7 | 22.0 | 26.6 | 20.63 ± 3.05 |
| pting | input-kcen | 23.2 ± 4.1 | 21.5 | 65.5 | 20.80 ± 4.73 |
| chancalan | input-lanjian | 25.7 ± 0.7 | 24.4 | 28.3 | 23.05 ± 3.39 |
| chancalan | input-kcen | 25.7 ± 0.8 | 24.8 | 28.6 | 23.07 ± 3.40 |
| chancalan | input-mattcl | 25.8 ± 1.0 | 24.7 | 28.8 | 23.12 ± 3.45 |
| chancalan | input-chancalan | 25.8 ± 0.9 | 24.4 | 29.0 | 23.14 ± 3.43 |
| chancalan | input-pting | 25.8 ± 0.8 | 24.6 | 28.8 | 23.14 ± 3.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|