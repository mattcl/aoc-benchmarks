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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.1 | 0.7 | 1.8 | 1.00 ± 0.18 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.0 | 1.02 ± 0.22 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.6 | 1.8 | 1.02 ± 0.20 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 2.1 | 1.03 ± 0.21 |
| lanjian | input-chancalan | 1.7 ± 0.3 | 0.9 | 2.3 | 1.36 ± 0.27 |
| lanjian | input-pting | 1.8 ± 0.2 | 0.9 | 2.2 | 1.39 ± 0.26 |
| lanjian | input-kcen | 1.8 ± 0.3 | 0.9 | 2.5 | 1.40 ± 0.28 |
| lanjian | input-mattcl | 1.8 ± 0.3 | 1.0 | 2.4 | 1.41 ± 0.28 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 0.9 | 2.2 | 1.42 ± 0.26 |
| kcen | input-mattcl | 18.9 ± 0.5 | 18.0 | 21.8 | 14.89 ± 2.02 |
| kcen | input-lanjian | 18.9 ± 0.7 | 17.9 | 22.0 | 14.95 ± 2.06 |
| kcen | input-chancalan | 19.0 ± 0.7 | 18.1 | 22.1 | 15.00 ± 2.07 |
| kcen | input-kcen | 19.0 ± 0.8 | 18.0 | 22.0 | 15.01 ± 2.10 |
| kcen | input-pting | 19.4 ± 3.5 | 18.0 | 58.5 | 15.28 ± 3.42 |
| mattcl-py | input-lanjian | 20.9 ± 0.6 | 19.7 | 24.0 | 16.50 ± 2.24 |
| mattcl-py | input-chancalan | 21.0 ± 0.5 | 20.2 | 23.9 | 16.61 ± 2.25 |
| mattcl-py | input-mattcl | 21.1 ± 0.7 | 19.7 | 24.0 | 16.62 ± 2.28 |
| mattcl-py | input-kcen | 21.1 ± 0.7 | 20.1 | 24.0 | 16.63 ± 2.28 |
| mattcl-py | input-pting | 21.1 ± 0.7 | 20.3 | 24.1 | 16.69 ± 2.28 |
| pting | input-mattcl | 22.9 ± 0.6 | 21.8 | 25.4 | 18.11 ± 2.45 |
| pting | input-kcen | 23.0 ± 0.6 | 22.1 | 25.6 | 18.16 ± 2.46 |
| pting | input-lanjian | 23.1 ± 0.8 | 22.0 | 25.9 | 18.21 ± 2.49 |
| pting | input-chancalan | 23.1 ± 0.7 | 22.1 | 26.0 | 18.23 ± 2.48 |
| pting | input-pting | 23.1 ± 0.6 | 22.0 | 25.9 | 18.26 ± 2.47 |
| chancalan | input-lanjian | 25.9 ± 0.6 | 25.1 | 28.1 | 20.43 ± 2.75 |
| chancalan | input-mattcl | 26.0 ± 0.8 | 25.0 | 29.1 | 20.53 ± 2.80 |
| chancalan | input-chancalan | 26.1 ± 0.8 | 25.1 | 29.1 | 20.60 ± 2.81 |
| chancalan | input-kcen | 26.2 ± 1.0 | 24.7 | 29.6 | 20.70 ± 2.86 |
| chancalan | input-pting | 26.3 ± 0.9 | 25.2 | 29.2 | 20.77 ± 2.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|