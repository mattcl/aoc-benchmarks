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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.4 | 1.6 | 1.00 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.1 | 1.2 | 1.02 ± 0.24 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.25 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.4 | 1.6 | 1.04 ± 0.27 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.4 | 1.23 ± 0.28 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.5 | 1.5 | 1.24 ± 0.28 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.7 | 1.7 | 1.25 ± 0.30 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.7 | 1.7 | 1.30 ± 0.30 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.6 | 1.8 | 1.32 ± 0.33 |
| kcen | input-lanjian | 16.1 ± 0.6 | 15.2 | 19.0 | 16.71 ± 3.20 |
| kcen | input-mattcl | 16.1 ± 0.6 | 15.0 | 19.1 | 16.74 ± 3.22 |
| kcen | input-chancalan | 16.3 ± 0.8 | 15.0 | 19.9 | 16.92 ± 3.29 |
| kcen | input-pting | 16.3 ± 0.8 | 15.1 | 20.1 | 16.94 ± 3.29 |
| kcen | input-kcen | 16.4 ± 3.3 | 14.9 | 59.8 | 17.02 ± 4.71 |
| mattcl-py | input-lanjian | 17.4 ± 0.6 | 16.1 | 20.6 | 18.05 ± 3.44 |
| mattcl-py | input-pting | 17.4 ± 0.5 | 16.6 | 19.6 | 18.06 ± 3.43 |
| mattcl-py | input-mattcl | 17.4 ± 0.8 | 16.3 | 20.5 | 18.08 ± 3.49 |
| mattcl-py | input-kcen | 17.4 ± 0.6 | 16.5 | 20.8 | 18.08 ± 3.46 |
| mattcl-py | input-chancalan | 17.4 ± 0.6 | 16.4 | 20.2 | 18.13 ± 3.47 |
| pting | input-mattcl | 18.3 ± 0.7 | 17.2 | 21.2 | 19.06 ± 3.65 |
| pting | input-lanjian | 18.3 ± 0.6 | 17.4 | 21.1 | 19.06 ± 3.64 |
| pting | input-pting | 18.5 ± 0.5 | 17.4 | 21.3 | 19.23 ± 3.66 |
| pting | input-kcen | 18.5 ± 0.8 | 17.5 | 21.5 | 19.26 ± 3.72 |
| pting | input-chancalan | 18.6 ± 0.8 | 17.5 | 21.4 | 19.29 ± 3.72 |
| chancalan | input-pting | 21.3 ± 0.5 | 20.6 | 23.7 | 22.14 ± 4.20 |
| chancalan | input-mattcl | 21.3 ± 0.7 | 20.6 | 24.8 | 22.15 ± 4.24 |
| chancalan | input-chancalan | 21.3 ± 0.5 | 20.5 | 24.0 | 22.18 ± 4.20 |
| chancalan | input-kcen | 21.5 ± 0.9 | 20.2 | 24.7 | 22.38 ± 4.31 |
| chancalan | input-lanjian | 22.1 ± 6.2 | 20.6 | 74.3 | 22.99 ± 7.72 |
| mikofo | input-chancalan | 278.3 ± 2.5 | 274.6 | 283.3 | 289.25 ± 54.46 |
| mikofo | input-kcen | 278.6 ± 1.1 | 277.2 | 280.2 | 289.58 ± 54.46 |
| mikofo | input-pting | 278.7 ± 1.7 | 275.3 | 281.5 | 289.68 ± 54.50 |
| mikofo | input-mattcl | 279.7 ± 2.8 | 276.2 | 285.6 | 290.69 ± 54.74 |
| mikofo | input-lanjian | 279.7 ± 2.5 | 275.6 | 283.7 | 290.73 ± 54.73 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|