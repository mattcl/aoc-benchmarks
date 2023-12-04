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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.5 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.4 | 1.05 ± 0.25 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.05 ± 0.26 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.9 | 1.05 ± 0.27 |
| mattcl | input-kcen | 1.2 ± 0.1 | 0.7 | 1.6 | 1.06 ± 0.24 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 0.6 | 2.2 | 1.45 ± 0.35 |
| lanjian | input-kcen | 1.7 ± 0.2 | 1.0 | 2.2 | 1.46 ± 0.35 |
| lanjian | input-chancalan | 1.7 ± 0.2 | 0.8 | 2.2 | 1.48 ± 0.36 |
| lanjian | input-mattcl | 1.7 ± 2.9 | 0.4 | 42.4 | 1.48 ± 2.55 |
| lanjian | input-pting | 1.7 ± 0.2 | 0.8 | 2.3 | 1.50 ± 0.34 |
| kcen | input-kcen | 18.9 ± 0.6 | 17.9 | 21.5 | 16.40 ± 3.26 |
| kcen | input-mattcl | 19.0 ± 0.7 | 18.1 | 22.4 | 16.50 ± 3.29 |
| kcen | input-chancalan | 19.1 ± 0.8 | 18.1 | 22.2 | 16.52 ± 3.30 |
| kcen | input-lanjian | 19.1 ± 0.7 | 18.0 | 21.9 | 16.53 ± 3.30 |
| kcen | input-pting | 19.2 ± 0.8 | 18.1 | 22.3 | 16.61 ± 3.32 |
| mattcl-py | input-lanjian | 21.0 ± 0.7 | 20.1 | 23.6 | 18.23 ± 3.61 |
| mattcl-py | input-mattcl | 21.1 ± 0.5 | 20.0 | 23.7 | 18.29 ± 3.61 |
| mattcl-py | input-chancalan | 21.1 ± 0.7 | 20.0 | 23.9 | 18.30 ± 3.63 |
| mattcl-py | input-kcen | 21.1 ± 0.7 | 20.1 | 24.4 | 18.32 ± 3.64 |
| mattcl-py | input-pting | 21.2 ± 0.6 | 19.9 | 24.1 | 18.37 ± 3.64 |
| pting | input-chancalan | 23.1 ± 0.6 | 22.0 | 25.6 | 20.03 ± 3.95 |
| pting | input-mattcl | 23.2 ± 0.6 | 22.2 | 26.2 | 20.09 ± 3.97 |
| pting | input-lanjian | 23.2 ± 0.7 | 22.3 | 26.8 | 20.13 ± 3.99 |
| pting | input-kcen | 23.2 ± 0.8 | 21.6 | 26.0 | 20.14 ± 4.00 |
| pting | input-pting | 23.5 ± 0.8 | 22.5 | 27.2 | 20.37 ± 4.04 |
| chancalan | input-kcen | 25.9 ± 0.7 | 25.0 | 28.8 | 22.46 ± 4.44 |
| chancalan | input-mattcl | 26.1 ± 0.9 | 24.9 | 29.5 | 22.63 ± 4.49 |
| chancalan | input-chancalan | 26.1 ± 0.9 | 25.1 | 29.4 | 22.64 ± 4.50 |
| chancalan | input-lanjian | 26.1 ± 0.9 | 24.6 | 29.6 | 22.65 ± 4.50 |
| chancalan | input-pting | 26.4 ± 0.9 | 24.9 | 30.0 | 22.92 ± 4.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|