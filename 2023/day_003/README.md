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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.3 | 1.00 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.3 | 1.3 | 1.01 ± 0.27 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.8 | 1.03 ± 0.28 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.3 | 1.03 ± 0.24 |
| mattcl | input-chancalan | 1.1 ± 0.1 | 0.5 | 1.6 | 1.05 ± 0.24 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 1.7 | 1.36 ± 0.32 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 0.9 | 1.8 | 1.40 ± 0.32 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.9 | 2.1 | 1.42 ± 0.34 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 0.9 | 2.2 | 1.42 ± 0.34 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.8 | 2.2 | 1.44 ± 0.36 |
| mikofo | input-mikofo | 12.5 ± 0.3 | 11.5 | 13.1 | 11.88 ± 2.29 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.7 | 13.4 | 11.89 ± 2.29 |
| mikofo | input-chancalan | 12.6 ± 0.3 | 11.7 | 13.5 | 11.89 ± 2.29 |
| mikofo | input-mattcl | 12.6 ± 0.3 | 11.4 | 13.5 | 11.90 ± 2.30 |
| mikofo | input-lanjian | 12.6 ± 0.3 | 11.5 | 13.5 | 11.90 ± 2.30 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.9 | 13.5 | 11.97 ± 2.31 |
| mattcl-ts | input-mikofo | 12.6 ± 0.3 | 11.5 | 14.0 | 11.97 ± 2.31 |
| mattcl-ts | input-lanjian | 13.2 ± 5.4 | 11.6 | 71.8 | 12.46 ± 5.60 |
| mikofo | input-kcen | 13.2 ± 5.8 | 11.4 | 74.2 | 12.52 ± 6.00 |
| mattcl-ts | input-kcen | 13.3 ± 5.8 | 11.6 | 73.4 | 12.59 ± 6.00 |
| kcen | input-chancalan | 16.2 ± 0.4 | 15.1 | 19.2 | 15.33 ± 2.96 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.3 | 20.1 | 15.40 ± 3.01 |
| kcen | input-kcen | 16.3 ± 0.6 | 15.1 | 19.7 | 15.45 ± 3.02 |
| kcen | input-mikofo | 16.4 ± 0.7 | 15.0 | 19.6 | 15.49 ± 3.04 |
| kcen | input-mattcl | 16.4 ± 0.8 | 15.1 | 19.8 | 15.51 ± 3.06 |
| pting | input-chancalan | 17.3 ± 0.6 | 16.3 | 20.5 | 16.35 ± 3.18 |
| pting | input-kcen | 17.3 ± 0.7 | 16.2 | 20.6 | 16.35 ± 3.19 |
| pting | input-mattcl | 17.3 ± 0.6 | 16.3 | 20.7 | 16.36 ± 3.18 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.1 | 20.7 | 16.42 ± 3.21 |
| pting | input-mikofo | 17.4 ± 0.6 | 16.6 | 20.3 | 16.49 ± 3.21 |
| mattcl-py | input-mattcl | 17.5 ± 0.6 | 16.5 | 20.0 | 16.61 ± 3.22 |
| mattcl-py | input-lanjian | 17.6 ± 0.6 | 16.4 | 20.4 | 16.67 ± 3.24 |
| mattcl-py | input-chancalan | 17.6 ± 0.8 | 16.5 | 21.1 | 16.69 ± 3.27 |
| mattcl-py | input-kcen | 17.7 ± 0.7 | 16.9 | 21.8 | 16.74 ± 3.28 |
| mattcl-py | input-mikofo | 17.7 ± 0.8 | 16.5 | 21.2 | 16.81 ± 3.31 |
| chancalan | input-lanjian | 21.5 ± 0.7 | 20.5 | 24.1 | 20.36 ± 3.95 |
| chancalan | input-mattcl | 21.5 ± 0.9 | 20.4 | 24.9 | 20.40 ± 3.99 |
| chancalan | input-kcen | 21.6 ± 0.7 | 20.4 | 24.6 | 20.46 ± 3.98 |
| chancalan | input-mikofo | 21.6 ± 0.8 | 20.6 | 24.7 | 20.49 ± 3.99 |
| chancalan | input-chancalan | 21.6 ± 0.8 | 20.7 | 25.1 | 20.49 ± 3.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|