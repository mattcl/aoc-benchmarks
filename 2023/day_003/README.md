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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 2.0 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.6 | 1.02 ± 0.23 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.7 | 1.7 | 1.02 ± 0.24 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.25 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 2.0 | 1.06 ± 0.24 |
| lanjian | input-kcen | 1.7 ± 0.3 | 0.9 | 2.3 | 1.42 ± 0.34 |
| lanjian | input-pting | 1.7 ± 0.2 | 0.9 | 2.3 | 1.45 ± 0.33 |
| lanjian | input-chancalan | 1.7 ± 0.2 | 0.9 | 2.4 | 1.48 ± 0.33 |
| lanjian | input-mattcl | 1.7 ± 0.2 | 0.8 | 2.3 | 1.48 ± 0.33 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 1.0 | 2.3 | 1.51 ± 0.33 |
| kcen | input-chancalan | 19.0 ± 0.5 | 18.2 | 21.9 | 16.23 ± 2.98 |
| kcen | input-pting | 19.0 ± 0.6 | 18.2 | 21.6 | 16.28 ± 2.99 |
| kcen | input-lanjian | 19.0 ± 0.6 | 18.1 | 22.0 | 16.28 ± 3.00 |
| kcen | input-mattcl | 19.1 ± 0.7 | 17.7 | 21.9 | 16.32 ± 3.02 |
| kcen | input-kcen | 19.1 ± 0.7 | 18.0 | 22.8 | 16.33 ± 3.02 |
| mattcl-py | input-mattcl | 21.1 ± 0.8 | 20.1 | 24.1 | 18.05 ± 3.34 |
| mattcl-py | input-pting | 21.1 ± 0.6 | 19.9 | 24.1 | 18.07 ± 3.32 |
| mattcl-py | input-chancalan | 21.1 ± 0.9 | 19.7 | 26.3 | 18.08 ± 3.36 |
| mattcl-py | input-lanjian | 21.1 ± 0.7 | 19.7 | 24.2 | 18.08 ± 3.33 |
| mattcl-py | input-kcen | 21.2 ± 0.7 | 20.1 | 23.9 | 18.16 ± 3.35 |
| pting | input-kcen | 23.1 ± 0.8 | 21.8 | 26.4 | 19.75 ± 3.65 |
| pting | input-mattcl | 23.2 ± 0.8 | 21.6 | 26.0 | 19.85 ± 3.67 |
| pting | input-lanjian | 23.2 ± 0.7 | 22.2 | 25.9 | 19.85 ± 3.65 |
| pting | input-chancalan | 23.4 ± 1.3 | 21.8 | 34.0 | 20.02 ± 3.79 |
| pting | input-pting | 23.5 ± 0.8 | 22.4 | 26.6 | 20.10 ± 3.71 |
| chancalan | input-kcen | 26.1 ± 0.8 | 24.6 | 28.9 | 22.31 ± 4.10 |
| chancalan | input-lanjian | 26.1 ± 0.8 | 25.1 | 29.5 | 22.34 ± 4.11 |
| chancalan | input-pting | 26.1 ± 0.7 | 24.9 | 28.9 | 22.35 ± 4.10 |
| chancalan | input-chancalan | 26.2 ± 0.8 | 25.1 | 29.4 | 22.40 ± 4.12 |
| chancalan | input-mattcl | 26.2 ± 0.9 | 25.0 | 29.0 | 22.42 ± 4.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|