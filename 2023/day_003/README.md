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
| mattcl | input-kcen | 0.9 ± 0.3 | 0.2 | 1.6 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.2 | 1.08 ± 0.36 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.6 | 1.08 ± 0.37 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.7 | 1.09 ± 0.38 |
| mattcl | input-mikofo | 1.0 ± 0.1 | 0.4 | 1.7 | 1.12 ± 0.36 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.4 | 1.6 | 1.39 ± 0.51 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.6 | 2.0 | 1.51 ± 0.49 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.8 | 2.1 | 1.54 ± 0.50 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.0 | 1.55 ± 0.50 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.8 | 2.1 | 1.58 ± 0.51 |
| mattcl-ts | input-kcen | 12.1 ± 0.4 | 10.9 | 13.4 | 13.14 ± 3.77 |
| mattcl-ts | input-lanjian | 12.1 ± 0.4 | 11.1 | 13.6 | 13.14 ± 3.77 |
| mattcl-ts | input-mattcl | 12.1 ± 0.4 | 11.2 | 13.0 | 13.17 ± 3.77 |
| mattcl-ts | input-chancalan | 12.1 ± 0.4 | 11.0 | 13.2 | 13.19 ± 3.78 |
| mikofo | input-chancalan | 12.1 ± 0.4 | 11.0 | 13.0 | 13.19 ± 3.78 |
| mikofo | input-kcen | 12.1 ± 0.4 | 11.0 | 13.2 | 13.22 ± 3.79 |
| mikofo | input-mattcl | 12.1 ± 0.4 | 10.9 | 13.1 | 13.23 ± 3.79 |
| mattcl-ts | input-mikofo | 12.2 ± 0.4 | 11.2 | 13.2 | 13.27 ± 3.80 |
| mikofo | input-mikofo | 12.2 ± 0.4 | 11.1 | 13.2 | 13.28 ± 3.80 |
| mikofo | input-lanjian | 12.2 ± 0.4 | 10.9 | 13.2 | 13.29 ± 3.81 |
| kcen | input-chancalan | 16.2 ± 0.7 | 14.9 | 19.1 | 17.67 ± 5.08 |
| kcen | input-kcen | 16.3 ± 0.7 | 15.0 | 19.5 | 17.79 ± 5.13 |
| kcen | input-mikofo | 16.3 ± 0.7 | 15.1 | 19.8 | 17.81 ± 5.12 |
| kcen | input-mattcl | 16.4 ± 0.8 | 15.1 | 19.8 | 17.88 ± 5.16 |
| kcen | input-lanjian | 16.5 ± 0.8 | 15.2 | 19.3 | 17.96 ± 5.18 |
| pting | input-mikofo | 17.4 ± 0.6 | 16.4 | 20.6 | 18.92 ± 5.43 |
| pting | input-chancalan | 17.4 ± 0.8 | 16.3 | 20.7 | 18.92 ± 5.45 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.1 | 20.6 | 18.95 ± 5.44 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.5 | 20.8 | 18.99 ± 5.46 |
| pting | input-kcen | 17.4 ± 0.7 | 16.2 | 20.5 | 19.01 ± 5.46 |
| mattcl-py | input-lanjian | 17.5 ± 0.7 | 16.2 | 20.8 | 19.10 ± 5.48 |
| mattcl-py | input-kcen | 17.5 ± 0.6 | 16.6 | 20.2 | 19.10 ± 5.47 |
| mattcl-py | input-mattcl | 17.6 ± 0.7 | 16.6 | 20.8 | 19.17 ± 5.50 |
| mattcl-py | input-chancalan | 17.6 ± 0.6 | 16.8 | 20.3 | 19.17 ± 5.50 |
| mattcl-py | input-mikofo | 17.6 ± 0.7 | 16.8 | 21.1 | 19.19 ± 5.51 |
| chancalan | input-kcen | 21.6 ± 0.7 | 20.6 | 24.7 | 23.52 ± 6.73 |
| chancalan | input-mattcl | 21.6 ± 0.8 | 20.1 | 24.7 | 23.54 ± 6.75 |
| chancalan | input-chancalan | 21.7 ± 0.8 | 20.3 | 24.7 | 23.68 ± 6.79 |
| chancalan | input-lanjian | 21.7 ± 0.7 | 20.7 | 24.6 | 23.70 ± 6.79 |
| chancalan | input-mikofo | 21.8 ± 0.8 | 20.7 | 25.3 | 23.75 ± 6.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|