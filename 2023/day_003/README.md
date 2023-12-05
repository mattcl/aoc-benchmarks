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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.9 | 1.02 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 2.0 | 1.03 ± 0.25 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.6 | 2.1 | 1.03 ± 0.25 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.7 | 1.7 | 1.04 ± 0.22 |
| lanjian | input-kcen | 1.7 ± 0.3 | 0.7 | 2.2 | 1.39 ± 0.34 |
| lanjian | input-lanjian | 1.7 ± 0.2 | 0.8 | 2.3 | 1.43 ± 0.32 |
| lanjian | input-chancalan | 1.7 ± 0.2 | 0.8 | 2.3 | 1.46 ± 0.32 |
| lanjian | input-pting | 1.7 ± 0.2 | 0.9 | 2.2 | 1.46 ± 0.31 |
| lanjian | input-mattcl | 1.7 ± 0.2 | 1.0 | 2.3 | 1.47 ± 0.30 |
| kcen | input-chancalan | 19.1 ± 0.6 | 18.2 | 22.2 | 16.14 ± 2.93 |
| kcen | input-kcen | 19.2 ± 0.7 | 17.8 | 22.0 | 16.16 ± 2.95 |
| kcen | input-lanjian | 19.3 ± 0.8 | 18.2 | 22.1 | 16.29 ± 2.98 |
| kcen | input-mattcl | 19.3 ± 0.9 | 17.8 | 22.8 | 16.30 ± 3.01 |
| kcen | input-pting | 19.4 ± 0.8 | 18.0 | 22.9 | 16.35 ± 3.00 |
| mattcl-py | input-kcen | 21.2 ± 0.6 | 20.2 | 24.6 | 17.85 ± 3.23 |
| mattcl-py | input-mattcl | 21.2 ± 0.8 | 19.9 | 24.5 | 17.85 ± 3.27 |
| mattcl-py | input-pting | 21.2 ± 0.6 | 20.3 | 24.1 | 17.86 ± 3.23 |
| mattcl-py | input-chancalan | 21.2 ± 0.7 | 20.2 | 24.3 | 17.90 ± 3.26 |
| mattcl-py | input-lanjian | 21.3 ± 0.7 | 20.2 | 24.3 | 17.93 ± 3.26 |
| pting | input-mattcl | 23.3 ± 0.8 | 22.0 | 26.5 | 19.67 ± 3.59 |
| pting | input-chancalan | 23.3 ± 0.9 | 22.2 | 26.4 | 19.68 ± 3.59 |
| pting | input-kcen | 23.4 ± 0.8 | 21.8 | 26.4 | 19.71 ± 3.59 |
| pting | input-pting | 23.6 ± 0.8 | 22.5 | 26.7 | 19.87 ± 3.62 |
| pting | input-lanjian | 24.2 ± 5.5 | 22.2 | 63.9 | 20.38 ± 5.90 |
| chancalan | input-kcen | 26.2 ± 0.7 | 25.2 | 29.3 | 22.12 ± 4.01 |
| chancalan | input-chancalan | 26.3 ± 0.9 | 25.1 | 29.8 | 22.16 ± 4.03 |
| chancalan | input-lanjian | 26.3 ± 0.9 | 25.0 | 29.5 | 22.17 ± 4.04 |
| chancalan | input-mattcl | 26.4 ± 1.0 | 25.0 | 29.0 | 22.23 ± 4.06 |
| chancalan | input-pting | 26.6 ± 0.9 | 25.4 | 29.6 | 22.44 ± 4.09 |
| mikofo | input-mattcl | 319.9 ± 2.2 | 316.9 | 323.6 | 269.73 ± 48.29 |
| mikofo | input-pting | 321.1 ± 3.0 | 317.5 | 325.1 | 270.74 ± 48.50 |
| mikofo | input-chancalan | 321.3 ± 2.1 | 317.7 | 324.2 | 270.96 ± 48.51 |
| mikofo | input-kcen | 321.5 ± 2.5 | 319.2 | 327.1 | 271.13 ± 48.55 |
| mikofo | input-lanjian | 321.7 ± 1.5 | 319.8 | 323.8 | 271.24 ± 48.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|