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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.5 | 1.6 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 1.1 ± 0.1 | 0.5 | 1.3 | 1.03 ± 0.21 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.8 | 1.04 ± 0.25 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.8 | 1.04 ± 0.24 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.7 | 2.0 | 1.21 ± 0.28 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.4 | 2.1 | 1.22 ± 0.31 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.5 | 1.9 | 1.22 ± 0.28 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 2.0 | 1.23 ± 0.28 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 1.9 | 1.23 ± 0.28 |
| mikofo | input-lanjian | 12.7 ± 0.3 | 11.7 | 13.4 | 11.41 ± 2.05 |
| mikofo | input-kcen | 12.7 ± 0.3 | 11.8 | 13.6 | 11.44 ± 2.06 |
| mattcl-ts | input-lanjian | 12.8 ± 0.4 | 11.7 | 13.7 | 11.46 ± 2.07 |
| mikofo | input-mattcl | 12.8 ± 0.3 | 12.0 | 13.7 | 11.48 ± 2.06 |
| mattcl-ts | input-chancalan | 12.8 ± 0.4 | 11.9 | 14.0 | 11.50 ± 2.07 |
| mattcl-ts | input-kcen | 12.8 ± 0.4 | 11.5 | 13.9 | 11.51 ± 2.08 |
| mikofo | input-mikofo | 12.8 ± 0.3 | 12.0 | 13.9 | 11.51 ± 2.07 |
| mattcl-ts | input-mattcl | 12.9 ± 0.4 | 12.1 | 13.7 | 11.57 ± 2.08 |
| mattcl-ts | input-mikofo | 12.9 ± 0.3 | 12.0 | 13.8 | 11.59 ± 2.08 |
| mikofo | input-chancalan | 13.3 ± 4.2 | 12.3 | 56.8 | 11.90 ± 4.35 |
| kcen | input-kcen | 16.3 ± 0.7 | 14.9 | 19.8 | 14.60 ± 2.67 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.0 | 20.1 | 14.61 ± 2.67 |
| kcen | input-mattcl | 16.3 ± 0.5 | 15.1 | 19.4 | 14.62 ± 2.64 |
| kcen | input-chancalan | 16.4 ± 0.8 | 15.4 | 19.8 | 14.72 ± 2.71 |
| kcen | input-mikofo | 17.1 ± 4.8 | 15.4 | 62.2 | 15.38 ± 5.10 |
| pting | input-mikofo | 17.2 ± 0.4 | 16.1 | 19.5 | 15.45 ± 2.78 |
| pting | input-kcen | 17.3 ± 0.6 | 16.1 | 20.1 | 15.51 ± 2.81 |
| pting | input-chancalan | 17.3 ± 0.7 | 16.2 | 20.4 | 15.54 ± 2.83 |
| pting | input-lanjian | 17.3 ± 0.6 | 16.3 | 20.4 | 15.55 ± 2.81 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.3 | 20.2 | 15.60 ± 2.85 |
| mattcl-py | input-mikofo | 17.5 ± 0.6 | 16.9 | 20.6 | 15.74 ± 2.85 |
| mattcl-py | input-lanjian | 17.6 ± 0.7 | 16.5 | 20.4 | 15.76 ± 2.88 |
| mattcl-py | input-mattcl | 17.6 ± 0.7 | 16.2 | 20.6 | 15.77 ± 2.87 |
| mattcl-py | input-chancalan | 17.7 ± 0.7 | 16.6 | 20.9 | 15.84 ± 2.90 |
| mattcl-py | input-kcen | 17.8 ± 3.0 | 16.4 | 55.9 | 15.99 ± 3.95 |
| chancalan | input-kcen | 21.6 ± 0.8 | 20.1 | 24.7 | 19.37 ± 3.52 |
| chancalan | input-mikofo | 21.7 ± 0.7 | 20.6 | 24.7 | 19.43 ± 3.51 |
| chancalan | input-lanjian | 21.7 ± 0.7 | 20.8 | 24.4 | 19.47 ± 3.52 |
| chancalan | input-mattcl | 21.7 ± 0.7 | 20.6 | 24.7 | 19.51 ± 3.54 |
| chancalan | input-chancalan | 22.3 ± 3.8 | 20.8 | 58.5 | 20.00 ± 4.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|