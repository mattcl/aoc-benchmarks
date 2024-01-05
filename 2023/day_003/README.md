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
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 1.2 ± 0.2 | 0.2 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.24 |
| mattcl | input-mikofo | 1.2 ± 0.1 | 0.7 | 1.9 | 1.03 ± 0.23 |
| mattcl | input-chancalan | 1.2 ± 0.1 | 0.4 | 1.7 | 1.04 ± 0.22 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 2.0 | 1.05 ± 0.27 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 1.9 | 1.18 ± 0.27 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.6 | 2.0 | 1.18 ± 0.28 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.7 | 2.0 | 1.20 ± 0.27 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.7 | 2.0 | 1.20 ± 0.29 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.8 | 2.3 | 1.32 ± 0.31 |
| mikofo | input-chancalan | 12.8 ± 0.4 | 11.8 | 14.9 | 11.04 ± 2.06 |
| mikofo | input-kcen | 12.8 ± 0.3 | 12.2 | 13.8 | 11.05 ± 2.06 |
| mikofo | input-mikofo | 12.8 ± 0.4 | 11.7 | 14.0 | 11.07 ± 2.06 |
| mattcl-ts | input-mattcl | 12.8 ± 0.4 | 12.1 | 14.8 | 11.07 ± 2.06 |
| mikofo | input-mattcl | 12.8 ± 0.4 | 11.6 | 13.8 | 11.07 ± 2.06 |
| mikofo | input-lanjian | 12.9 ± 0.4 | 12.2 | 14.6 | 11.09 ± 2.07 |
| mattcl-ts | input-lanjian | 12.9 ± 0.3 | 12.0 | 14.3 | 11.09 ± 2.06 |
| mattcl-ts | input-kcen | 12.9 ± 0.4 | 11.9 | 14.2 | 11.13 ± 2.08 |
| mattcl-ts | input-chancalan | 13.0 ± 0.4 | 12.1 | 14.5 | 11.17 ± 2.08 |
| mattcl-ts | input-mikofo | 13.3 ± 4.1 | 12.2 | 62.7 | 11.48 ± 4.12 |
| kcen | input-mikofo | 16.4 ± 0.6 | 15.1 | 19.5 | 14.10 ± 2.65 |
| kcen | input-lanjian | 16.4 ± 0.7 | 15.6 | 19.5 | 14.15 ± 2.67 |
| kcen | input-chancalan | 16.5 ± 0.8 | 15.0 | 19.6 | 14.19 ± 2.71 |
| kcen | input-kcen | 16.5 ± 0.8 | 15.1 | 20.4 | 14.19 ± 2.71 |
| kcen | input-mattcl | 16.8 ± 3.3 | 15.2 | 56.1 | 14.51 ± 3.87 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.0 | 20.6 | 15.01 ± 2.83 |
| pting | input-kcen | 17.4 ± 0.7 | 16.5 | 20.6 | 15.03 ± 2.84 |
| pting | input-chancalan | 17.5 ± 0.7 | 16.2 | 20.6 | 15.08 ± 2.84 |
| pting | input-mikofo | 17.6 ± 0.8 | 16.8 | 20.6 | 15.13 ± 2.87 |
| mattcl-py | input-mattcl | 17.6 ± 0.7 | 16.3 | 20.4 | 15.17 ± 2.86 |
| mattcl-py | input-kcen | 17.6 ± 0.6 | 16.8 | 20.6 | 15.18 ± 2.84 |
| mattcl-py | input-lanjian | 17.7 ± 0.9 | 16.5 | 22.0 | 15.24 ± 2.90 |
| mattcl-py | input-mikofo | 17.7 ± 0.8 | 16.9 | 21.1 | 15.25 ± 2.89 |
| mattcl-py | input-chancalan | 17.7 ± 0.7 | 16.7 | 20.6 | 15.28 ± 2.88 |
| pting | input-mattcl | 18.0 ± 5.9 | 16.2 | 72.7 | 15.49 ± 5.81 |
| chancalan | input-lanjian | 21.6 ± 0.6 | 20.2 | 24.7 | 18.63 ± 3.46 |
| chancalan | input-mattcl | 21.7 ± 0.7 | 20.6 | 24.8 | 18.69 ± 3.50 |
| chancalan | input-kcen | 21.7 ± 0.7 | 20.3 | 24.5 | 18.73 ± 3.51 |
| chancalan | input-chancalan | 21.8 ± 0.8 | 20.7 | 24.8 | 18.82 ± 3.53 |
| chancalan | input-mikofo | 21.9 ± 0.9 | 20.8 | 25.2 | 18.86 ± 3.57 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|