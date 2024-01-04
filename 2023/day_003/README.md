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
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.5 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.7 | 1.7 | 1.03 ± 0.19 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 2.2 | 1.03 ± 0.25 |
| mattcl | input-mikofo | 1.2 ± 0.2 | 0.7 | 1.8 | 1.04 ± 0.20 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.20 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.9 | 1.16 ± 0.25 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.1 | 1.18 ± 0.24 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.9 | 2.1 | 1.20 ± 0.24 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.7 | 2.0 | 1.21 ± 0.26 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.6 | 1.7 | 1.22 ± 0.24 |
| mikofo | input-kcen | 12.6 ± 0.3 | 11.6 | 13.5 | 10.93 ± 1.61 |
| mikofo | input-mattcl | 12.6 ± 0.3 | 11.6 | 14.0 | 10.95 ± 1.61 |
| mikofo | input-chancalan | 12.6 ± 0.3 | 11.8 | 13.4 | 10.95 ± 1.61 |
| mikofo | input-mikofo | 12.6 ± 0.3 | 11.7 | 13.7 | 10.96 ± 1.62 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.7 | 13.7 | 10.97 ± 1.63 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.8 | 14.2 | 11.00 ± 1.63 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.9 | 13.8 | 11.04 ± 1.63 |
| mattcl-ts | input-mikofo | 12.7 ± 0.3 | 12.0 | 13.7 | 11.06 ± 1.64 |
| mikofo | input-lanjian | 13.0 ± 5.1 | 11.7 | 84.7 | 11.30 ± 4.73 |
| mattcl-ts | input-lanjian | 13.2 ± 4.9 | 12.0 | 67.4 | 11.43 ± 4.54 |
| kcen | input-mattcl | 16.1 ± 0.6 | 15.0 | 19.3 | 13.98 ± 2.11 |
| kcen | input-chancalan | 16.1 ± 0.6 | 15.0 | 18.7 | 13.98 ± 2.11 |
| kcen | input-lanjian | 16.1 ± 0.6 | 15.0 | 19.0 | 14.00 ± 2.11 |
| kcen | input-mikofo | 16.1 ± 0.7 | 14.9 | 18.9 | 14.01 ± 2.13 |
| kcen | input-kcen | 16.3 ± 0.9 | 15.0 | 19.4 | 14.17 ± 2.20 |
| pting | input-mattcl | 17.0 ± 0.6 | 16.1 | 20.1 | 14.80 ± 2.22 |
| pting | input-kcen | 17.1 ± 0.7 | 16.2 | 20.5 | 14.82 ± 2.23 |
| pting | input-lanjian | 17.1 ± 0.6 | 16.3 | 19.8 | 14.85 ± 2.23 |
| pting | input-chancalan | 17.1 ± 0.7 | 16.1 | 20.4 | 14.87 ± 2.25 |
| pting | input-mikofo | 17.3 ± 0.8 | 16.3 | 20.4 | 15.00 ± 2.29 |
| mattcl-py | input-lanjian | 17.4 ± 0.8 | 16.2 | 21.2 | 15.15 ± 2.31 |
| mattcl-py | input-chancalan | 17.5 ± 0.7 | 16.2 | 20.5 | 15.15 ± 2.28 |
| mattcl-py | input-mikofo | 17.5 ± 0.6 | 16.3 | 21.0 | 15.16 ± 2.27 |
| mattcl-py | input-kcen | 17.5 ± 0.6 | 16.2 | 20.1 | 15.16 ± 2.27 |
| mattcl-py | input-mattcl | 17.5 ± 0.7 | 16.1 | 20.9 | 15.17 ± 2.30 |
| chancalan | input-lanjian | 21.3 ± 0.6 | 20.4 | 24.1 | 18.49 ± 2.74 |
| chancalan | input-mattcl | 21.3 ± 0.7 | 20.2 | 24.8 | 18.49 ± 2.76 |
| chancalan | input-mikofo | 21.3 ± 0.5 | 20.5 | 23.4 | 18.49 ± 2.73 |
| chancalan | input-chancalan | 21.3 ± 0.6 | 20.3 | 23.8 | 18.50 ± 2.75 |
| chancalan | input-kcen | 21.4 ± 0.7 | 20.4 | 24.5 | 18.58 ± 2.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|