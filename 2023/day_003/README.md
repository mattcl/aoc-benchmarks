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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.19 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.20 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.19 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.9 | 1.03 ± 0.20 |
| lanjian | input-mattcl | 1.7 ± 0.2 | 0.7 | 2.1 | 1.41 ± 0.26 |
| lanjian | input-kcen | 1.7 ± 0.2 | 0.9 | 2.4 | 1.41 ± 0.26 |
| lanjian | input-pting | 1.8 ± 0.2 | 1.0 | 2.3 | 1.43 ± 0.27 |
| lanjian | input-chancalan | 1.8 ± 0.2 | 0.9 | 2.3 | 1.43 ± 0.26 |
| lanjian | input-lanjian | 1.8 ± 0.2 | 1.0 | 2.3 | 1.46 ± 0.25 |
| kcen | input-chancalan | 19.0 ± 0.6 | 17.9 | 21.8 | 15.33 ± 2.25 |
| kcen | input-mattcl | 19.3 ± 0.8 | 17.8 | 21.9 | 15.53 ± 2.31 |
| kcen | input-pting | 19.3 ± 0.8 | 18.2 | 22.5 | 15.57 ± 2.32 |
| kcen | input-lanjian | 19.3 ± 0.8 | 17.9 | 22.2 | 15.57 ± 2.33 |
| kcen | input-kcen | 19.4 ± 1.6 | 17.8 | 36.2 | 15.61 ± 2.60 |
| mattcl-py | input-chancalan | 21.1 ± 0.5 | 20.3 | 24.8 | 17.05 ± 2.47 |
| mattcl-py | input-lanjian | 21.2 ± 0.7 | 20.3 | 24.2 | 17.06 ± 2.51 |
| mattcl-py | input-kcen | 21.2 ± 0.6 | 20.2 | 23.9 | 17.13 ± 2.50 |
| mattcl-py | input-mattcl | 21.3 ± 0.8 | 20.4 | 25.0 | 17.15 ± 2.54 |
| mattcl-py | input-pting | 21.3 ± 0.7 | 19.9 | 24.6 | 17.15 ± 2.52 |
| pting | input-kcen | 23.2 ± 0.7 | 21.7 | 26.2 | 18.70 ± 2.73 |
| pting | input-mattcl | 23.4 ± 0.8 | 22.1 | 26.1 | 18.84 ± 2.77 |
| pting | input-chancalan | 23.4 ± 0.8 | 22.3 | 26.6 | 18.85 ± 2.77 |
| pting | input-lanjian | 23.4 ± 0.8 | 22.5 | 26.6 | 18.88 ± 2.79 |
| pting | input-pting | 23.5 ± 0.7 | 22.4 | 26.3 | 18.96 ± 2.78 |
| chancalan | input-kcen | 26.1 ± 0.8 | 25.2 | 29.0 | 21.06 ± 3.08 |
| chancalan | input-chancalan | 26.1 ± 0.8 | 25.1 | 29.6 | 21.07 ± 3.09 |
| chancalan | input-lanjian | 26.2 ± 0.7 | 25.0 | 28.8 | 21.09 ± 3.07 |
| chancalan | input-mattcl | 26.5 ± 1.0 | 25.2 | 29.7 | 21.35 ± 3.16 |
| chancalan | input-pting | 26.6 ± 1.0 | 25.3 | 29.9 | 21.44 ± 3.18 |
| mikofo | input-lanjian | 319.6 ± 2.7 | 315.5 | 322.7 | 257.72 ± 37.00 |
| mikofo | input-chancalan | 320.3 ± 3.1 | 316.2 | 325.1 | 258.28 ± 37.09 |
| mikofo | input-mattcl | 320.8 ± 2.2 | 316.8 | 322.7 | 258.65 ± 37.10 |
| mikofo | input-pting | 321.1 ± 2.0 | 317.8 | 323.9 | 258.92 ± 37.14 |
| mikofo | input-kcen | 321.7 ± 1.8 | 318.1 | 323.9 | 259.42 ± 37.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|