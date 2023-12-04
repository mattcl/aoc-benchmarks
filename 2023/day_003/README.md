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
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.23 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 1.7 | 1.03 ± 0.22 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.9 | 1.04 ± 0.23 |
| lanjian | input-chancalan | 1.7 ± 0.3 | 0.9 | 2.4 | 1.40 ± 0.32 |
| lanjian | input-kcen | 1.7 ± 0.3 | 0.8 | 2.5 | 1.43 ± 0.33 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 0.7 | 2.3 | 1.44 ± 0.32 |
| lanjian | input-mattcl | 1.7 ± 0.2 | 1.1 | 2.4 | 1.45 ± 0.31 |
| lanjian | input-pting | 1.8 ± 0.2 | 0.8 | 2.2 | 1.46 ± 0.30 |
| kcen | input-lanjian | 19.1 ± 0.7 | 17.9 | 22.3 | 15.98 ± 2.80 |
| kcen | input-chancalan | 19.2 ± 0.6 | 18.2 | 22.3 | 15.99 ± 2.79 |
| kcen | input-pting | 19.2 ± 0.7 | 18.1 | 21.9 | 16.01 ± 2.81 |
| kcen | input-kcen | 19.2 ± 0.7 | 18.1 | 21.7 | 16.02 ± 2.81 |
| kcen | input-mattcl | 19.4 ± 2.6 | 17.9 | 50.2 | 16.21 ± 3.54 |
| mattcl-py | input-lanjian | 21.0 ± 0.5 | 20.2 | 23.6 | 17.54 ± 3.04 |
| mattcl-py | input-kcen | 21.1 ± 0.6 | 20.3 | 24.0 | 17.61 ± 3.06 |
| mattcl-py | input-mattcl | 21.1 ± 0.5 | 20.3 | 23.3 | 17.64 ± 3.06 |
| mattcl-py | input-chancalan | 21.3 ± 0.7 | 20.1 | 24.3 | 17.77 ± 3.11 |
| mattcl-py | input-pting | 21.3 ± 0.7 | 20.2 | 24.3 | 17.80 ± 3.11 |
| pting | input-lanjian | 23.1 ± 0.6 | 21.8 | 25.4 | 19.26 ± 3.34 |
| pting | input-chancalan | 23.2 ± 0.6 | 22.2 | 25.5 | 19.38 ± 3.36 |
| pting | input-kcen | 23.4 ± 0.9 | 22.2 | 26.6 | 19.49 ± 3.43 |
| pting | input-mattcl | 23.4 ± 0.7 | 22.6 | 26.6 | 19.57 ± 3.41 |
| pting | input-pting | 23.6 ± 1.7 | 22.4 | 40.1 | 19.73 ± 3.68 |
| chancalan | input-chancalan | 26.1 ± 0.8 | 25.0 | 29.6 | 21.82 ± 3.80 |
| chancalan | input-mattcl | 26.3 ± 0.9 | 25.2 | 29.5 | 21.91 ± 3.84 |
| chancalan | input-kcen | 26.3 ± 0.9 | 24.8 | 29.7 | 21.97 ± 3.85 |
| chancalan | input-lanjian | 26.4 ± 0.9 | 25.2 | 29.8 | 22.06 ± 3.87 |
| chancalan | input-pting | 26.5 ± 0.9 | 25.2 | 29.6 | 22.15 ± 3.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|