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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.9 | 1.01 ± 0.20 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.9 | 1.02 ± 0.20 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.4 | 1.4 | 1.02 ± 0.19 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.6 | 1.03 ± 0.20 |
| lanjian | input-kcen | 1.6 ± 0.2 | 0.9 | 2.1 | 1.42 ± 0.27 |
| lanjian | input-mattcl | 1.6 ± 0.2 | 0.8 | 2.1 | 1.43 ± 0.27 |
| lanjian | input-chancalan | 1.6 ± 0.2 | 0.9 | 2.1 | 1.43 ± 0.27 |
| lanjian | input-pting | 1.7 ± 0.2 | 0.8 | 2.1 | 1.45 ± 0.28 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 0.9 | 2.2 | 1.49 ± 0.26 |
| kcen | input-kcen | 18.7 ± 0.6 | 17.7 | 21.7 | 16.37 ± 2.32 |
| kcen | input-chancalan | 18.8 ± 0.7 | 17.6 | 21.9 | 16.44 ± 2.37 |
| kcen | input-mattcl | 18.8 ± 0.7 | 17.8 | 21.8 | 16.46 ± 2.36 |
| kcen | input-lanjian | 18.8 ± 0.6 | 18.0 | 22.0 | 16.52 ± 2.35 |
| kcen | input-pting | 18.9 ± 0.7 | 18.0 | 22.0 | 16.55 ± 2.37 |
| mattcl-py | input-chancalan | 20.9 ± 0.7 | 20.1 | 23.8 | 18.32 ± 2.61 |
| mattcl-py | input-kcen | 20.9 ± 0.6 | 20.2 | 24.2 | 18.33 ± 2.60 |
| mattcl-py | input-lanjian | 21.0 ± 1.6 | 19.5 | 38.6 | 18.37 ± 2.91 |
| mattcl-py | input-pting | 21.0 ± 0.7 | 20.0 | 23.5 | 18.40 ± 2.61 |
| mattcl-py | input-mattcl | 21.0 ± 0.7 | 19.8 | 24.3 | 18.44 ± 2.63 |
| pting | input-mattcl | 22.9 ± 0.7 | 22.0 | 25.9 | 20.06 ± 2.84 |
| pting | input-kcen | 23.0 ± 0.8 | 21.8 | 25.5 | 20.12 ± 2.86 |
| pting | input-chancalan | 23.0 ± 0.9 | 21.9 | 26.5 | 20.15 ± 2.89 |
| pting | input-lanjian | 23.0 ± 0.8 | 22.0 | 26.2 | 20.16 ± 2.88 |
| pting | input-pting | 23.2 ± 0.8 | 22.1 | 26.1 | 20.34 ± 2.89 |
| chancalan | input-mattcl | 25.9 ± 0.7 | 24.9 | 28.7 | 22.70 ± 3.20 |
| chancalan | input-pting | 25.9 ± 0.6 | 25.0 | 29.1 | 22.70 ± 3.19 |
| chancalan | input-kcen | 26.0 ± 0.9 | 25.0 | 28.9 | 22.80 ± 3.26 |
| chancalan | input-chancalan | 26.1 ± 1.1 | 24.6 | 31.2 | 22.83 ± 3.30 |
| chancalan | input-lanjian | 26.2 ± 1.1 | 25.0 | 34.0 | 22.94 ± 3.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|