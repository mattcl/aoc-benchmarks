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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.4 | 1.01 ± 0.29 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.27 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.8 | 1.04 ± 0.27 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.5 | 1.9 | 1.08 ± 0.29 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.6 | 1.9 | 1.41 ± 0.36 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.5 | 2.1 | 1.43 ± 0.36 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.3 | 1.44 ± 0.38 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.3 | 1.54 ± 0.38 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 0.7 | 2.3 | 1.57 ± 0.40 |
| mikofo | input-mattcl | 12.8 ± 0.3 | 12.0 | 13.6 | 13.18 ± 2.66 |
| mikofo | input-mikofo | 12.8 ± 0.4 | 11.6 | 13.8 | 13.24 ± 2.67 |
| mikofo | input-kcen | 12.8 ± 0.3 | 12.2 | 13.7 | 13.25 ± 2.67 |
| mikofo | input-chancalan | 12.8 ± 0.4 | 12.0 | 15.1 | 13.25 ± 2.68 |
| mikofo | input-lanjian | 12.9 ± 0.3 | 11.8 | 13.9 | 13.29 ± 2.68 |
| mattcl-ts | input-chancalan | 12.9 ± 0.3 | 12.2 | 13.9 | 13.35 ± 2.69 |
| mattcl-ts | input-mikofo | 12.9 ± 0.4 | 12.0 | 13.9 | 13.35 ± 2.70 |
| mattcl-ts | input-mattcl | 12.9 ± 0.4 | 11.9 | 13.9 | 13.35 ± 2.70 |
| mattcl-ts | input-kcen | 12.9 ± 0.4 | 12.0 | 14.2 | 13.36 ± 2.70 |
| mattcl-ts | input-lanjian | 12.9 ± 0.4 | 12.1 | 14.2 | 13.38 ± 2.70 |
| kcen | input-kcen | 16.3 ± 0.8 | 15.0 | 19.7 | 16.89 ± 3.47 |
| kcen | input-mattcl | 16.4 ± 0.6 | 15.3 | 19.3 | 16.96 ± 3.46 |
| kcen | input-lanjian | 16.4 ± 0.7 | 15.2 | 19.2 | 16.96 ± 3.47 |
| kcen | input-chancalan | 16.5 ± 0.8 | 15.3 | 19.7 | 17.05 ± 3.50 |
| kcen | input-mikofo | 16.5 ± 1.5 | 15.0 | 34.2 | 17.05 ± 3.75 |
| pting | input-chancalan | 17.3 ± 0.4 | 16.2 | 19.5 | 17.87 ± 3.60 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.0 | 21.0 | 17.95 ± 3.67 |
| pting | input-mattcl | 17.4 ± 0.6 | 16.1 | 20.6 | 17.99 ± 3.66 |
| pting | input-kcen | 17.5 ± 0.8 | 16.5 | 21.0 | 18.10 ± 3.71 |
| mattcl-py | input-lanjian | 17.5 ± 0.6 | 16.4 | 20.8 | 18.12 ± 3.69 |
| mattcl-py | input-mattcl | 17.5 ± 0.6 | 16.6 | 20.5 | 18.13 ± 3.68 |
| mattcl-py | input-chancalan | 17.6 ± 0.7 | 16.8 | 20.8 | 18.21 ± 3.72 |
| mattcl-py | input-kcen | 17.7 ± 0.7 | 16.6 | 20.7 | 18.24 ± 3.72 |
| pting | input-mikofo | 17.7 ± 1.9 | 16.4 | 39.9 | 18.31 ± 4.14 |
| mattcl-py | input-mikofo | 17.7 ± 0.8 | 16.4 | 20.6 | 18.34 ± 3.76 |
| chancalan | input-mikofo | 21.7 ± 0.7 | 20.8 | 24.5 | 22.43 ± 4.55 |
| chancalan | input-lanjian | 21.7 ± 0.8 | 20.8 | 24.7 | 22.47 ± 4.57 |
| chancalan | input-chancalan | 21.8 ± 0.7 | 20.7 | 25.3 | 22.51 ± 4.57 |
| chancalan | input-mattcl | 21.8 ± 0.8 | 20.6 | 25.2 | 22.53 ± 4.59 |
| chancalan | input-kcen | 21.9 ± 1.0 | 20.5 | 29.8 | 22.59 ± 4.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|