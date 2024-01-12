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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.6 | 1.7 | 1.00 ± 0.20 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.21 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.23 |
| mattcl | input-mattcl | 1.1 ± 0.1 | 0.6 | 1.7 | 1.01 ± 0.18 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 0.5 | 2.3 | 1.32 ± 0.29 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.9 | 1.7 | 1.32 ± 0.26 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.2 | 1.35 ± 0.28 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.8 | 2.3 | 1.39 ± 0.28 |
| lanjian | input-mikofo | 1.6 ± 0.2 | 0.8 | 2.6 | 1.42 ± 0.29 |
| mikofo | input-lanjian | 12.8 ± 0.3 | 12.0 | 13.6 | 11.58 ± 1.69 |
| mikofo | input-chancalan | 12.8 ± 0.3 | 12.0 | 13.9 | 11.59 ± 1.70 |
| mikofo | input-kcen | 12.8 ± 0.3 | 11.8 | 13.9 | 11.60 ± 1.70 |
| mikofo | input-mattcl | 12.9 ± 0.3 | 11.9 | 14.7 | 11.62 ± 1.71 |
| mikofo | input-mikofo | 12.9 ± 0.3 | 12.0 | 13.7 | 11.63 ± 1.70 |
| mattcl-ts | input-chancalan | 12.9 ± 0.4 | 12.0 | 13.8 | 11.66 ± 1.72 |
| mattcl-ts | input-lanjian | 12.9 ± 0.4 | 12.0 | 14.5 | 11.68 ± 1.72 |
| mattcl-ts | input-kcen | 12.9 ± 0.4 | 11.8 | 13.9 | 11.70 ± 1.72 |
| mattcl-ts | input-mattcl | 12.9 ± 0.4 | 12.0 | 14.8 | 11.71 ± 1.72 |
| mattcl-ts | input-mikofo | 13.0 ± 0.4 | 12.2 | 13.9 | 11.75 ± 1.73 |
| kcen | input-mattcl | 16.4 ± 0.7 | 15.1 | 19.5 | 14.83 ± 2.24 |
| kcen | input-kcen | 16.4 ± 0.8 | 15.0 | 19.7 | 14.84 ± 2.25 |
| kcen | input-lanjian | 16.5 ± 0.7 | 15.3 | 19.2 | 14.89 ± 2.23 |
| kcen | input-chancalan | 16.5 ± 0.7 | 15.1 | 19.6 | 14.91 ± 2.26 |
| kcen | input-mikofo | 16.5 ± 0.7 | 15.3 | 19.5 | 14.94 ± 2.25 |
| pting | input-lanjian | 17.4 ± 0.6 | 16.2 | 20.8 | 15.72 ± 2.33 |
| pting | input-kcen | 17.4 ± 0.7 | 16.3 | 22.5 | 15.76 ± 2.37 |
| pting | input-mattcl | 17.5 ± 0.7 | 16.6 | 21.0 | 15.82 ± 2.38 |
| mattcl-py | input-chancalan | 17.6 ± 0.6 | 16.4 | 20.6 | 15.90 ± 2.35 |
| mattcl-py | input-lanjian | 17.6 ± 0.6 | 16.6 | 20.5 | 15.90 ± 2.37 |
| mattcl-py | input-mikofo | 17.6 ± 0.6 | 16.4 | 20.5 | 15.95 ± 2.37 |
| mattcl-py | input-mattcl | 17.7 ± 0.8 | 16.7 | 21.2 | 15.96 ± 2.41 |
| mattcl-py | input-kcen | 17.7 ± 0.8 | 16.5 | 20.5 | 16.00 ± 2.41 |
| pting | input-chancalan | 17.7 ± 3.5 | 16.5 | 62.3 | 16.01 ± 3.91 |
| pting | input-mikofo | 17.8 ± 3.1 | 16.5 | 57.8 | 16.06 ± 3.66 |
| chancalan | input-mattcl | 21.6 ± 0.8 | 20.2 | 25.1 | 19.52 ± 2.92 |
| chancalan | input-chancalan | 21.7 ± 0.6 | 20.8 | 24.6 | 19.61 ± 2.88 |
| chancalan | input-kcen | 21.7 ± 0.7 | 20.7 | 25.1 | 19.62 ± 2.91 |
| chancalan | input-mikofo | 21.9 ± 0.8 | 20.6 | 25.5 | 19.79 ± 2.95 |
| chancalan | input-lanjian | 21.9 ± 0.9 | 20.4 | 25.3 | 19.80 ± 2.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|