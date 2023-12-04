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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.23 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 1.8 | 1.03 ± 0.23 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.7 | 1.04 ± 0.24 |
| mattcl | input-chancalan | 1.4 ± 0.2 | 0.8 | 2.2 | 1.10 ± 0.26 |
| lanjian | input-kcen | 1.7 ± 0.2 | 0.7 | 2.5 | 1.40 ± 0.32 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 0.8 | 2.3 | 1.40 ± 0.31 |
| lanjian | input-pting | 1.8 ± 0.2 | 0.8 | 2.1 | 1.44 ± 0.32 |
| lanjian | input-mattcl | 1.8 ± 0.3 | 1.0 | 2.5 | 1.45 ± 0.33 |
| lanjian | input-chancalan | 1.8 ± 0.2 | 1.0 | 2.2 | 1.46 ± 0.31 |
| kcen | input-kcen | 18.9 ± 0.6 | 17.9 | 21.6 | 15.25 ± 2.75 |
| kcen | input-lanjian | 19.0 ± 0.7 | 17.7 | 22.0 | 15.30 ± 2.78 |
| kcen | input-mattcl | 19.0 ± 0.7 | 18.1 | 21.8 | 15.31 ± 2.78 |
| kcen | input-pting | 19.0 ± 0.6 | 17.9 | 21.6 | 15.34 ± 2.76 |
| kcen | input-chancalan | 19.1 ± 0.8 | 18.0 | 22.0 | 15.38 ± 2.80 |
| mattcl-py | input-mattcl | 21.0 ± 0.6 | 20.1 | 23.4 | 16.96 ± 3.05 |
| mattcl-py | input-kcen | 21.0 ± 0.6 | 20.0 | 23.7 | 16.98 ± 3.06 |
| mattcl-py | input-lanjian | 21.1 ± 0.6 | 20.0 | 24.0 | 16.98 ± 3.06 |
| mattcl-py | input-chancalan | 21.2 ± 0.7 | 20.2 | 24.6 | 17.09 ± 3.09 |
| mattcl-py | input-pting | 21.2 ± 0.7 | 20.1 | 24.2 | 17.11 ± 3.09 |
| pting | input-mattcl | 23.0 ± 0.6 | 22.0 | 25.9 | 18.56 ± 3.33 |
| pting | input-lanjian | 23.0 ± 0.6 | 22.2 | 25.9 | 18.58 ± 3.33 |
| pting | input-chancalan | 23.2 ± 0.8 | 22.1 | 26.1 | 18.69 ± 3.38 |
| pting | input-kcen | 23.3 ± 0.9 | 21.9 | 26.6 | 18.78 ± 3.42 |
| pting | input-pting | 23.5 ± 0.8 | 22.4 | 26.8 | 18.93 ± 3.42 |
| chancalan | input-mattcl | 26.1 ± 0.7 | 25.1 | 29.1 | 21.06 ± 3.78 |
| chancalan | input-lanjian | 26.1 ± 0.7 | 25.4 | 29.2 | 21.07 ± 3.78 |
| chancalan | input-kcen | 26.2 ± 0.9 | 25.0 | 28.9 | 21.12 ± 3.82 |
| chancalan | input-chancalan | 26.2 ± 0.9 | 25.1 | 29.3 | 21.13 ± 3.82 |
| chancalan | input-pting | 26.3 ± 0.9 | 25.4 | 29.3 | 21.23 ± 3.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|