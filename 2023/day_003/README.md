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
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.3 | 0.4 | 1.6 | 1.01 ± 0.27 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.23 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.7 | 2.0 | 1.09 ± 0.23 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.10 ± 0.22 |
| lanjian | input-chancalan | 1.7 ± 0.3 | 0.6 | 2.0 | 1.42 ± 0.31 |
| lanjian | input-pting | 1.7 ± 0.3 | 0.8 | 2.2 | 1.43 ± 0.33 |
| lanjian | input-mattcl | 1.7 ± 0.2 | 1.1 | 2.3 | 1.46 ± 0.29 |
| lanjian | input-kcen | 1.8 ± 4.9 | 0.5 | 70.4 | 1.50 ± 4.17 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 1.0 | 2.3 | 1.52 ± 0.28 |
| kcen | input-kcen | 18.9 ± 0.8 | 17.9 | 23.9 | 16.04 ± 2.65 |
| kcen | input-lanjian | 18.9 ± 0.8 | 18.0 | 22.6 | 16.05 ± 2.65 |
| kcen | input-chancalan | 18.9 ± 0.7 | 18.1 | 22.1 | 16.07 ± 2.64 |
| kcen | input-pting | 18.9 ± 0.7 | 17.8 | 21.6 | 16.11 ± 2.63 |
| kcen | input-mattcl | 19.0 ± 0.8 | 17.8 | 22.2 | 16.15 ± 2.67 |
| mattcl-py | input-chancalan | 20.9 ± 0.7 | 19.7 | 23.4 | 17.75 ± 2.89 |
| mattcl-py | input-kcen | 20.9 ± 0.7 | 20.0 | 24.3 | 17.80 ± 2.90 |
| mattcl-py | input-mattcl | 20.9 ± 1.2 | 19.9 | 33.5 | 17.81 ± 3.02 |
| mattcl-py | input-lanjian | 20.9 ± 0.7 | 19.8 | 24.1 | 17.83 ± 2.90 |
| mattcl-py | input-pting | 21.1 ± 0.8 | 20.1 | 24.4 | 17.99 ± 2.96 |
| pting | input-lanjian | 22.9 ± 0.6 | 22.0 | 25.5 | 19.46 ± 3.15 |
| pting | input-chancalan | 22.9 ± 0.7 | 21.9 | 26.8 | 19.50 ± 3.17 |
| pting | input-kcen | 22.9 ± 0.8 | 21.8 | 26.2 | 19.50 ± 3.18 |
| pting | input-mattcl | 22.9 ± 0.7 | 22.1 | 26.4 | 19.51 ± 3.17 |
| pting | input-pting | 23.2 ± 0.7 | 22.0 | 26.3 | 19.73 ± 3.20 |
| chancalan | input-kcen | 25.9 ± 0.7 | 24.9 | 28.8 | 22.02 ± 3.57 |
| chancalan | input-mattcl | 25.9 ± 0.7 | 25.1 | 28.5 | 22.02 ± 3.56 |
| chancalan | input-lanjian | 26.0 ± 0.7 | 24.7 | 29.0 | 22.09 ± 3.58 |
| chancalan | input-chancalan | 26.0 ± 0.8 | 25.0 | 29.1 | 22.12 ± 3.60 |
| chancalan | input-pting | 26.1 ± 0.7 | 25.0 | 28.5 | 22.22 ± 3.60 |
| mikofo | input-chancalan | 316.6 ± 1.3 | 315.3 | 318.8 | 269.41 ± 42.99 |
| mikofo | input-kcen | 316.8 ± 2.1 | 312.6 | 319.6 | 269.55 ± 43.03 |
| mikofo | input-pting | 317.8 ± 2.4 | 313.0 | 321.1 | 270.38 ± 43.18 |
| mikofo | input-mattcl | 317.8 ± 1.7 | 315.1 | 319.7 | 270.45 ± 43.16 |
| mikofo | input-lanjian | 319.0 ± 2.4 | 313.9 | 321.7 | 271.45 ± 43.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|