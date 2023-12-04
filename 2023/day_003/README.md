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
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.6 | 1.01 ± 0.22 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.4 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.6 | 1.5 | 1.03 ± 0.20 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.1 | 1.06 ± 0.24 |
| lanjian | input-mattcl | 1.6 ± 0.2 | 0.6 | 2.2 | 1.37 ± 0.28 |
| lanjian | input-kcen | 1.7 ± 0.2 | 0.9 | 2.2 | 1.40 ± 0.27 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 0.8 | 2.3 | 1.43 ± 0.29 |
| lanjian | input-pting | 1.7 ± 0.2 | 0.9 | 2.3 | 1.45 ± 0.28 |
| lanjian | input-chancalan | 1.7 ± 0.2 | 0.9 | 2.2 | 1.45 ± 0.29 |
| kcen | input-mattcl | 19.1 ± 0.6 | 17.7 | 22.0 | 15.93 ± 2.46 |
| kcen | input-chancalan | 19.3 ± 0.8 | 18.1 | 22.5 | 16.09 ± 2.53 |
| kcen | input-kcen | 19.3 ± 0.8 | 18.2 | 22.6 | 16.09 ± 2.52 |
| kcen | input-pting | 19.3 ± 0.7 | 17.8 | 21.9 | 16.17 ± 2.52 |
| kcen | input-lanjian | 19.5 ± 2.8 | 17.9 | 53.4 | 16.26 ± 3.41 |
| mattcl-py | input-mattcl | 21.1 ± 0.6 | 20.2 | 24.1 | 17.63 ± 2.73 |
| mattcl-py | input-lanjian | 21.2 ± 0.7 | 20.1 | 24.5 | 17.75 ± 2.76 |
| mattcl-py | input-chancalan | 21.3 ± 0.7 | 20.2 | 24.3 | 17.77 ± 2.75 |
| mattcl-py | input-pting | 21.3 ± 0.7 | 20.1 | 24.2 | 17.79 ± 2.76 |
| mattcl-py | input-kcen | 21.4 ± 0.8 | 20.2 | 24.4 | 17.85 ± 2.80 |
| pting | input-chancalan | 23.2 ± 0.6 | 22.3 | 26.0 | 19.42 ± 2.99 |
| pting | input-mattcl | 23.3 ± 0.9 | 22.1 | 26.6 | 19.45 ± 3.04 |
| pting | input-lanjian | 23.4 ± 0.8 | 22.2 | 26.4 | 19.57 ± 3.04 |
| pting | input-kcen | 23.4 ± 0.8 | 22.3 | 26.9 | 19.58 ± 3.05 |
| pting | input-pting | 23.5 ± 1.0 | 21.9 | 26.6 | 19.66 ± 3.09 |
| chancalan | input-chancalan | 26.3 ± 1.0 | 25.2 | 29.4 | 22.00 ± 3.43 |
| chancalan | input-lanjian | 26.4 ± 0.9 | 25.2 | 29.4 | 22.04 ± 3.42 |
| chancalan | input-kcen | 26.4 ± 1.0 | 25.3 | 29.8 | 22.06 ± 3.44 |
| chancalan | input-mattcl | 26.4 ± 0.9 | 25.1 | 29.3 | 22.09 ± 3.43 |
| chancalan | input-pting | 26.4 ± 0.9 | 25.2 | 28.9 | 22.10 ± 3.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|