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
| mattcl | input-mikofo | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.00 ± 0.19 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.20 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.20 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.20 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.7 | 1.7 | 1.04 ± 0.19 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.5 | 1.8 | 1.15 ± 0.24 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.6 | 2.1 | 1.17 ± 0.24 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.8 | 2.1 | 1.17 ± 0.25 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 1.9 | 1.18 ± 0.23 |
| lanjian | input-pting | 1.5 ± 0.2 | 0.8 | 2.2 | 1.27 ± 0.26 |
| lanjian | input-lanjian | 1.6 ± 0.2 | 0.9 | 2.3 | 1.33 ± 0.28 |
| mikofo | input-chancalan | 12.8 ± 0.3 | 11.7 | 13.7 | 10.57 ± 1.56 |
| mikofo | input-kcen | 12.8 ± 0.3 | 11.9 | 13.6 | 10.63 ± 1.57 |
| mikofo | input-mattcl | 12.9 ± 0.3 | 12.0 | 13.8 | 10.65 ± 1.57 |
| mikofo | input-lanjian | 12.9 ± 0.3 | 11.9 | 13.8 | 10.67 ± 1.58 |
| mattcl-ts | input-chancalan | 12.9 ± 0.4 | 12.0 | 14.0 | 10.68 ± 1.58 |
| mikofo | input-pting | 12.9 ± 0.4 | 11.8 | 14.3 | 10.68 ± 1.58 |
| mikofo | input-mikofo | 12.9 ± 0.3 | 12.0 | 13.7 | 10.68 ± 1.57 |
| mattcl-ts | input-lanjian | 12.9 ± 0.3 | 12.2 | 13.8 | 10.70 ± 1.58 |
| mattcl-ts | input-kcen | 12.9 ± 0.4 | 11.9 | 14.0 | 10.70 ± 1.59 |
| mattcl-ts | input-mattcl | 12.9 ± 0.4 | 12.0 | 14.4 | 10.71 ± 1.59 |
| mattcl-ts | input-mikofo | 13.0 ± 0.4 | 12.0 | 14.3 | 10.74 ± 1.60 |
| mattcl-ts | input-pting | 13.0 ± 0.4 | 12.1 | 14.1 | 10.76 ± 1.60 |
| kcen | input-mattcl | 16.3 ± 0.5 | 15.1 | 18.1 | 13.47 ± 1.99 |
| kcen | input-lanjian | 16.4 ± 0.7 | 15.1 | 20.1 | 13.55 ± 2.06 |
| kcen | input-chancalan | 16.4 ± 0.7 | 15.3 | 19.5 | 13.62 ± 2.05 |
| kcen | input-mikofo | 16.4 ± 0.7 | 15.2 | 20.1 | 13.63 ± 2.06 |
| kcen | input-pting | 16.5 ± 0.7 | 15.4 | 19.5 | 13.63 ± 2.06 |
| kcen | input-kcen | 16.5 ± 0.7 | 15.6 | 19.8 | 13.66 ± 2.06 |
| pting | input-mattcl | 17.4 ± 0.6 | 16.1 | 21.1 | 14.38 ± 2.16 |
| pting | input-lanjian | 17.4 ± 0.6 | 16.0 | 20.6 | 14.41 ± 2.14 |
| pting | input-mikofo | 17.4 ± 0.7 | 16.3 | 20.9 | 14.44 ± 2.18 |
| pting | input-chancalan | 17.4 ± 0.6 | 16.2 | 20.4 | 14.45 ± 2.17 |
| pting | input-pting | 17.5 ± 0.6 | 16.1 | 20.9 | 14.50 ± 2.17 |
| mattcl-py | input-kcen | 17.5 ± 0.5 | 16.6 | 20.6 | 14.53 ± 2.15 |
| mattcl-py | input-chancalan | 17.6 ± 0.6 | 16.9 | 20.5 | 14.58 ± 2.17 |
| mattcl-py | input-lanjian | 17.6 ± 0.6 | 16.8 | 20.3 | 14.61 ± 2.18 |
| mattcl-py | input-mattcl | 17.7 ± 0.7 | 16.5 | 21.1 | 14.63 ± 2.20 |
| pting | input-kcen | 17.7 ± 2.8 | 16.2 | 53.2 | 14.66 ± 3.18 |
| mattcl-py | input-pting | 17.7 ± 0.7 | 16.6 | 21.2 | 14.67 ± 2.22 |
| mattcl-py | input-mikofo | 18.3 ± 4.2 | 16.8 | 55.1 | 15.20 ± 4.10 |
| chancalan | input-mattcl | 21.7 ± 0.5 | 20.9 | 24.6 | 17.97 ± 2.65 |
| chancalan | input-kcen | 21.8 ± 0.8 | 20.5 | 25.0 | 18.02 ± 2.70 |
| chancalan | input-mikofo | 21.8 ± 0.7 | 20.6 | 24.9 | 18.05 ± 2.68 |
| chancalan | input-lanjian | 21.8 ± 0.8 | 20.8 | 24.9 | 18.07 ± 2.71 |
| chancalan | input-pting | 22.0 ± 0.8 | 20.9 | 25.5 | 18.19 ± 2.72 |
| chancalan | input-chancalan | 22.4 ± 3.9 | 20.5 | 54.9 | 18.52 ± 4.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|