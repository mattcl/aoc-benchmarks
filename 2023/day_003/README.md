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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.00 ± 0.24 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.3 | 1.4 | 1.02 ± 0.21 |
| lanjian | input-mattcl | 1.6 ± 0.2 | 0.8 | 2.1 | 1.40 ± 0.31 |
| lanjian | input-chancalan | 1.7 ± 0.2 | 0.9 | 2.1 | 1.47 ± 0.29 |
| lanjian | input-kcen | 1.7 ± 0.2 | 0.8 | 2.3 | 1.48 ± 0.31 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 0.8 | 2.2 | 1.49 ± 0.32 |
| lanjian | input-pting | 1.8 ± 0.2 | 1.1 | 2.2 | 1.51 ± 0.31 |
| kcen | input-kcen | 18.8 ± 0.6 | 17.8 | 21.6 | 16.09 ± 2.66 |
| kcen | input-chancalan | 18.8 ± 0.7 | 17.8 | 21.6 | 16.12 ± 2.69 |
| kcen | input-lanjian | 18.9 ± 0.7 | 17.7 | 21.7 | 16.15 ± 2.68 |
| kcen | input-mattcl | 18.9 ± 0.7 | 17.9 | 22.5 | 16.15 ± 2.70 |
| kcen | input-pting | 18.9 ± 0.7 | 17.9 | 22.0 | 16.18 ± 2.69 |
| mattcl-py | input-kcen | 20.8 ± 0.6 | 20.0 | 23.4 | 17.82 ± 2.93 |
| mattcl-py | input-mattcl | 20.9 ± 0.6 | 19.6 | 23.9 | 17.91 ± 2.96 |
| mattcl-py | input-chancalan | 20.9 ± 0.7 | 20.0 | 24.3 | 17.93 ± 2.97 |
| mattcl-py | input-pting | 21.1 ± 0.7 | 19.8 | 23.5 | 18.03 ± 2.99 |
| mattcl-py | input-lanjian | 21.2 ± 2.7 | 20.0 | 52.9 | 18.14 ± 3.76 |
| pting | input-lanjian | 22.9 ± 0.7 | 22.0 | 25.8 | 19.61 ± 3.24 |
| pting | input-mattcl | 22.9 ± 0.8 | 21.8 | 26.4 | 19.64 ± 3.26 |
| pting | input-chancalan | 22.9 ± 0.7 | 21.6 | 25.9 | 19.64 ± 3.25 |
| pting | input-kcen | 23.1 ± 2.8 | 21.8 | 54.0 | 19.75 ± 4.01 |
| pting | input-pting | 23.5 ± 3.0 | 22.4 | 56.7 | 20.12 ± 4.18 |
| chancalan | input-chancalan | 25.7 ± 0.7 | 24.9 | 29.2 | 22.02 ± 3.62 |
| chancalan | input-kcen | 25.8 ± 0.7 | 24.4 | 28.7 | 22.10 ± 3.64 |
| chancalan | input-lanjian | 25.9 ± 0.8 | 25.1 | 29.2 | 22.20 ± 3.66 |
| chancalan | input-mattcl | 26.0 ± 0.8 | 25.0 | 28.7 | 22.28 ± 3.68 |
| chancalan | input-pting | 26.2 ± 0.9 | 25.1 | 29.2 | 22.41 ± 3.71 |
| mikofo | input-chancalan | 314.6 ± 1.7 | 312.4 | 317.1 | 269.45 ± 43.74 |
| mikofo | input-lanjian | 315.4 ± 2.5 | 311.8 | 318.1 | 270.08 ± 43.87 |
| mikofo | input-mattcl | 316.1 ± 2.8 | 311.8 | 320.7 | 270.72 ± 43.98 |
| mikofo | input-pting | 316.6 ± 1.1 | 315.3 | 318.1 | 271.16 ± 44.00 |
| mikofo | input-kcen | 323.4 ± 22.4 | 312.1 | 382.6 | 276.94 ± 48.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|