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
| mattcl | input-chancalan | 1.3 ± 0.1 | 0.7 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.7 | 1.00 ± 0.17 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.7 | 1.00 ± 0.16 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 2.0 | 1.01 ± 0.19 |
| mattcl | input-mikofo | 1.3 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.18 |
| lanjian | input-kcen | 1.4 ± 0.3 | 0.6 | 2.2 | 1.12 ± 0.24 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.6 | 2.2 | 1.16 ± 0.21 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 0.8 | 1.7 | 1.16 ± 0.20 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.9 | 2.1 | 1.18 ± 0.22 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 1.0 | 2.3 | 1.19 ± 0.20 |
| mikofo | input-chancalan | 12.6 ± 0.3 | 11.5 | 13.5 | 10.09 ± 1.14 |
| mattcl-ts | input-lanjian | 12.6 ± 0.4 | 11.7 | 13.5 | 10.09 ± 1.15 |
| mikofo | input-lanjian | 12.6 ± 0.3 | 11.6 | 13.7 | 10.10 ± 1.14 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.8 | 13.8 | 10.12 ± 1.15 |
| mattcl-ts | input-mikofo | 12.7 ± 0.3 | 11.8 | 13.4 | 10.12 ± 1.15 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.6 | 13.6 | 10.13 ± 1.16 |
| mikofo | input-mattcl | 12.7 ± 0.2 | 12.0 | 13.5 | 10.13 ± 1.14 |
| mikofo | input-mikofo | 12.7 ± 0.3 | 11.8 | 13.6 | 10.16 ± 1.16 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 11.7 | 13.7 | 10.16 ± 1.16 |
| mikofo | input-kcen | 12.9 ± 2.9 | 11.6 | 53.9 | 10.30 ± 2.61 |
| kcen | input-kcen | 16.4 ± 0.6 | 15.4 | 19.7 | 13.12 ± 1.54 |
| kcen | input-lanjian | 16.4 ± 0.5 | 15.2 | 19.0 | 13.12 ± 1.52 |
| kcen | input-mattcl | 16.4 ± 0.7 | 15.6 | 19.8 | 13.14 ± 1.56 |
| kcen | input-mikofo | 16.5 ± 0.6 | 15.4 | 19.7 | 13.16 ± 1.54 |
| kcen | input-chancalan | 16.5 ± 0.7 | 15.1 | 19.7 | 13.23 ± 1.58 |
| pting | input-mattcl | 17.3 ± 0.6 | 16.3 | 20.7 | 13.86 ± 1.62 |
| pting | input-kcen | 17.4 ± 0.7 | 16.2 | 21.6 | 13.93 ± 1.66 |
| pting | input-chancalan | 17.4 ± 0.6 | 16.5 | 20.3 | 13.94 ± 1.62 |
| pting | input-mikofo | 17.4 ± 0.7 | 16.1 | 20.3 | 13.95 ± 1.64 |
| pting | input-lanjian | 17.5 ± 0.7 | 16.2 | 20.1 | 13.99 ± 1.64 |
| mattcl-py | input-mattcl | 17.6 ± 0.7 | 16.8 | 20.9 | 14.07 ± 1.65 |
| mattcl-py | input-lanjian | 17.7 ± 0.7 | 16.5 | 20.4 | 14.12 ± 1.68 |
| mattcl-py | input-kcen | 17.7 ± 0.6 | 16.8 | 21.0 | 14.15 ± 1.64 |
| mattcl-py | input-mikofo | 17.7 ± 0.7 | 16.6 | 20.9 | 14.15 ± 1.67 |
| mattcl-py | input-chancalan | 17.8 ± 0.8 | 16.7 | 21.3 | 14.26 ± 1.70 |
| chancalan | input-chancalan | 21.6 ± 0.5 | 20.7 | 24.2 | 17.28 ± 1.96 |
| chancalan | input-lanjian | 21.8 ± 0.8 | 20.6 | 24.8 | 17.41 ± 2.04 |
| chancalan | input-kcen | 21.8 ± 0.8 | 20.8 | 24.3 | 17.43 ± 2.03 |
| chancalan | input-mikofo | 21.8 ± 0.6 | 20.8 | 24.6 | 17.45 ± 2.00 |
| chancalan | input-mattcl | 21.8 ± 0.8 | 20.7 | 24.6 | 17.47 ± 2.05 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|