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
| mattcl | input-mikofo | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.9 | 1.02 ± 0.20 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.8 | 1.02 ± 0.20 |
| mattcl | input-mattcl | 1.3 ± 0.1 | 0.5 | 1.8 | 1.03 ± 0.19 |
| mattcl | input-chancalan | 1.3 ± 0.1 | 0.8 | 1.6 | 1.03 ± 0.18 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 0.7 | 2.1 | 1.17 ± 0.24 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.1 | 1.17 ± 0.24 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 0.5 | 1.9 | 1.18 ± 0.23 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.9 | 1.7 | 1.19 ± 0.23 |
| lanjian | input-lanjian | 1.6 ± 0.2 | 0.9 | 2.3 | 1.25 ± 0.26 |
| mikofo | input-mattcl | 12.8 ± 0.3 | 11.8 | 13.7 | 10.17 ± 1.54 |
| mikofo | input-kcen | 12.9 ± 0.3 | 12.1 | 13.8 | 10.21 ± 1.54 |
| mikofo | input-lanjian | 12.9 ± 0.3 | 12.0 | 13.9 | 10.23 ± 1.55 |
| mikofo | input-mikofo | 12.9 ± 0.4 | 11.8 | 13.7 | 10.23 ± 1.55 |
| mattcl-ts | input-lanjian | 13.0 ± 0.4 | 12.1 | 14.3 | 10.27 ± 1.56 |
| mattcl-ts | input-mattcl | 13.0 ± 0.4 | 12.0 | 14.6 | 10.28 ± 1.56 |
| mattcl-ts | input-chancalan | 13.0 ± 0.3 | 12.0 | 14.0 | 10.29 ± 1.56 |
| mattcl-ts | input-kcen | 13.0 ± 0.4 | 12.0 | 14.5 | 10.31 ± 1.57 |
| mattcl-ts | input-mikofo | 13.1 ± 0.4 | 12.1 | 15.0 | 10.34 ± 1.58 |
| mikofo | input-chancalan | 13.1 ± 3.6 | 11.8 | 63.1 | 10.41 ± 3.23 |
| kcen | input-kcen | 16.4 ± 0.6 | 15.1 | 19.6 | 13.01 ± 2.00 |
| kcen | input-mattcl | 16.5 ± 0.7 | 15.2 | 19.4 | 13.04 ± 2.02 |
| kcen | input-lanjian | 16.5 ± 0.7 | 15.2 | 19.7 | 13.06 ± 2.02 |
| kcen | input-chancalan | 16.6 ± 0.8 | 15.1 | 19.8 | 13.18 ± 2.07 |
| kcen | input-mikofo | 16.7 ± 2.1 | 15.5 | 43.1 | 13.19 ± 2.56 |
| pting | input-mattcl | 17.5 ± 0.7 | 16.6 | 20.9 | 13.86 ± 2.14 |
| pting | input-kcen | 17.5 ± 0.7 | 16.4 | 20.8 | 13.88 ± 2.15 |
| pting | input-lanjian | 17.5 ± 0.7 | 16.2 | 20.7 | 13.88 ± 2.15 |
| pting | input-mikofo | 17.5 ± 0.7 | 16.3 | 20.6 | 13.89 ± 2.15 |
| pting | input-chancalan | 17.6 ± 0.8 | 16.3 | 20.7 | 13.95 ± 2.17 |
| mattcl-py | input-lanjian | 17.6 ± 0.6 | 16.8 | 20.8 | 13.98 ± 2.14 |
| mattcl-py | input-mattcl | 17.7 ± 0.6 | 16.7 | 20.7 | 14.04 ± 2.16 |
| mattcl-py | input-kcen | 17.8 ± 0.8 | 16.7 | 20.9 | 14.08 ± 2.19 |
| mattcl-py | input-chancalan | 17.8 ± 0.7 | 16.7 | 21.2 | 14.10 ± 2.18 |
| mattcl-py | input-mikofo | 18.0 ± 1.6 | 16.8 | 36.6 | 14.23 ± 2.49 |
| chancalan | input-mattcl | 21.7 ± 0.7 | 20.7 | 25.2 | 17.20 ± 2.62 |
| chancalan | input-kcen | 21.8 ± 0.7 | 20.4 | 25.1 | 17.25 ± 2.64 |
| chancalan | input-lanjian | 21.8 ± 0.6 | 21.0 | 24.4 | 17.28 ± 2.62 |
| chancalan | input-chancalan | 21.9 ± 0.8 | 20.7 | 24.9 | 17.34 ± 2.67 |
| chancalan | input-mikofo | 21.9 ± 0.7 | 20.8 | 25.1 | 17.35 ± 2.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|