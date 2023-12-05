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
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.5 | 1.00 ± 0.21 |
| mattcl | input-lanjian | 1.1 ± 0.1 | 0.5 | 1.9 | 1.02 ± 0.21 |
| mattcl | input-chancalan | 1.1 ± 2.9 | 0.3 | 42.4 | 1.02 ± 2.69 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.4 | 1.7 | 1.04 ± 0.24 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.8 | 1.6 | 1.19 ± 0.24 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.8 | 1.6 | 1.21 ± 0.23 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.3 | 1.25 ± 0.27 |
| lanjian | input-pting | 1.4 ± 0.2 | 0.8 | 1.8 | 1.25 ± 0.25 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.8 | 2.1 | 1.34 ± 0.27 |
| mattcl-ts | input-lanjian | 12.2 ± 0.4 | 11.1 | 13.2 | 11.10 ± 1.77 |
| mattcl-ts | input-kcen | 12.2 ± 0.3 | 11.4 | 13.0 | 11.11 ± 1.76 |
| mattcl-ts | input-mattcl | 12.2 ± 0.4 | 11.2 | 13.2 | 11.15 ± 1.78 |
| mattcl-ts | input-chancalan | 12.4 ± 2.7 | 11.2 | 49.7 | 11.28 ± 3.01 |
| mattcl-ts | input-pting | 12.7 ± 3.3 | 11.5 | 51.2 | 11.54 ± 3.51 |
| kcen | input-pting | 16.3 ± 0.6 | 15.2 | 19.2 | 14.84 ± 2.39 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.0 | 19.3 | 14.86 ± 2.41 |
| kcen | input-chancalan | 16.3 ± 0.7 | 15.1 | 19.1 | 14.88 ± 2.41 |
| kcen | input-mattcl | 16.3 ± 0.6 | 15.5 | 19.0 | 14.89 ± 2.40 |
| kcen | input-kcen | 16.5 ± 3.1 | 15.2 | 57.8 | 15.05 ± 3.70 |
| mattcl-py | input-lanjian | 17.6 ± 0.7 | 16.2 | 21.0 | 16.00 ± 2.59 |
| mattcl-py | input-kcen | 17.6 ± 0.7 | 16.8 | 20.8 | 16.02 ± 2.58 |
| mattcl-py | input-pting | 17.7 ± 0.7 | 16.8 | 20.9 | 16.15 ± 2.61 |
| mattcl-py | input-chancalan | 17.8 ± 1.6 | 16.8 | 35.7 | 16.20 ± 2.94 |
| mattcl-py | input-mattcl | 17.8 ± 1.9 | 16.7 | 40.4 | 16.23 ± 3.06 |
| pting | input-lanjian | 18.6 ± 0.6 | 17.4 | 21.5 | 16.94 ± 2.71 |
| pting | input-mattcl | 18.6 ± 0.7 | 17.4 | 21.7 | 16.94 ± 2.72 |
| pting | input-chancalan | 18.6 ± 0.8 | 17.6 | 21.8 | 16.95 ± 2.75 |
| pting | input-pting | 18.7 ± 0.7 | 17.6 | 22.3 | 17.07 ± 2.75 |
| pting | input-kcen | 18.8 ± 0.9 | 17.3 | 21.9 | 17.13 ± 2.80 |
| chancalan | input-kcen | 21.4 ± 0.6 | 20.5 | 24.1 | 19.52 ± 3.10 |
| chancalan | input-chancalan | 21.4 ± 0.5 | 20.5 | 23.9 | 19.54 ± 3.10 |
| chancalan | input-mattcl | 21.5 ± 0.6 | 20.6 | 24.0 | 19.60 ± 3.12 |
| chancalan | input-lanjian | 21.7 ± 0.8 | 20.2 | 24.6 | 19.79 ± 3.18 |
| chancalan | input-pting | 21.8 ± 0.7 | 20.8 | 25.1 | 19.82 ± 3.17 |
| mikofo | input-kcen | 278.5 ± 1.2 | 277.2 | 280.2 | 253.77 ± 39.74 |
| mikofo | input-chancalan | 278.8 ± 2.1 | 275.4 | 282.6 | 254.01 ± 39.81 |
| mikofo | input-pting | 279.1 ± 3.0 | 274.3 | 285.4 | 254.27 ± 39.90 |
| mikofo | input-lanjian | 279.7 ± 2.0 | 276.3 | 282.1 | 254.80 ± 39.93 |
| mikofo | input-mattcl | 282.3 ± 4.3 | 277.4 | 292.3 | 257.15 ± 40.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|