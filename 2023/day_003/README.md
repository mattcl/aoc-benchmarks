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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.2 | 1.6 | 1.05 ± 0.29 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.29 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.06 ± 0.29 |
| mattcl | input-kcen | 1.2 ± 0.1 | 0.6 | 1.6 | 1.07 ± 0.27 |
| lanjian | input-mattcl | 1.4 ± 0.3 | 0.7 | 1.9 | 1.30 ± 0.39 |
| lanjian | input-kcen | 1.6 ± 0.2 | 0.8 | 2.3 | 1.48 ± 0.39 |
| lanjian | input-chancalan | 1.6 ± 0.2 | 0.8 | 2.0 | 1.50 ± 0.39 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 1.0 | 2.3 | 1.54 ± 0.39 |
| lanjian | input-pting | 1.7 ± 0.2 | 0.8 | 2.6 | 1.55 ± 0.39 |
| kcen | input-kcen | 18.8 ± 0.7 | 17.7 | 21.5 | 17.22 ± 3.85 |
| kcen | input-mattcl | 18.9 ± 0.8 | 17.8 | 21.9 | 17.25 ± 3.86 |
| kcen | input-pting | 18.9 ± 0.8 | 17.9 | 22.1 | 17.28 ± 3.87 |
| kcen | input-chancalan | 18.9 ± 0.8 | 17.9 | 22.3 | 17.28 ± 3.87 |
| kcen | input-lanjian | 18.9 ± 0.8 | 17.8 | 22.3 | 17.30 ± 3.88 |
| mattcl-py | input-lanjian | 20.8 ± 0.7 | 20.0 | 23.6 | 19.02 ± 4.23 |
| mattcl-py | input-mattcl | 20.8 ± 0.5 | 20.1 | 24.0 | 19.06 ± 4.22 |
| mattcl-py | input-pting | 20.9 ± 0.6 | 20.0 | 23.5 | 19.16 ± 4.26 |
| mattcl-py | input-chancalan | 21.0 ± 0.8 | 20.0 | 24.5 | 19.19 ± 4.28 |
| mattcl-py | input-kcen | 21.0 ± 1.2 | 20.1 | 30.9 | 19.25 ± 4.37 |
| pting | input-kcen | 22.8 ± 0.6 | 21.8 | 26.1 | 20.83 ± 4.61 |
| pting | input-lanjian | 22.8 ± 0.7 | 22.0 | 25.6 | 20.89 ± 4.65 |
| pting | input-mattcl | 22.9 ± 0.9 | 21.9 | 26.4 | 20.95 ± 4.68 |
| pting | input-chancalan | 22.9 ± 0.8 | 21.7 | 26.1 | 21.00 ± 4.68 |
| pting | input-pting | 23.2 ± 0.8 | 22.0 | 26.4 | 21.21 ± 4.73 |
| chancalan | input-kcen | 25.8 ± 0.7 | 24.8 | 29.0 | 23.64 ± 5.25 |
| chancalan | input-lanjian | 25.9 ± 0.8 | 24.9 | 28.7 | 23.67 ± 5.26 |
| chancalan | input-mattcl | 25.9 ± 0.7 | 24.5 | 28.0 | 23.67 ± 5.25 |
| chancalan | input-chancalan | 26.0 ± 0.8 | 24.9 | 28.6 | 23.75 ± 5.28 |
| chancalan | input-pting | 26.0 ± 0.7 | 24.9 | 28.4 | 23.78 ± 5.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|