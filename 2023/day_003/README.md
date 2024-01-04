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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.9 | 1.02 ± 0.21 |
| mattcl | input-mikofo | 1.3 ± 0.2 | 0.4 | 1.8 | 1.04 ± 0.20 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.7 | 2.0 | 1.04 ± 0.21 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.8 | 1.04 ± 0.20 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.1 | 1.16 ± 0.24 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 0.5 | 2.1 | 1.17 ± 0.25 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 0.8 | 1.8 | 1.17 ± 0.24 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.8 | 2.1 | 1.18 ± 0.26 |
| lanjian | input-lanjian | 1.6 ± 0.2 | 0.8 | 2.3 | 1.27 ± 0.27 |
| mikofo | input-mikofo | 12.9 ± 0.3 | 12.1 | 13.8 | 10.19 ± 1.61 |
| mikofo | input-kcen | 12.9 ± 0.4 | 12.0 | 14.7 | 10.19 ± 1.62 |
| mikofo | input-mattcl | 12.9 ± 0.4 | 12.0 | 14.5 | 10.20 ± 1.62 |
| mattcl-ts | input-mattcl | 12.9 ± 0.4 | 12.1 | 13.8 | 10.21 ± 1.62 |
| mattcl-ts | input-lanjian | 13.0 ± 0.3 | 12.2 | 13.9 | 10.23 ± 1.62 |
| mattcl-ts | input-kcen | 13.0 ± 0.4 | 12.1 | 13.9 | 10.23 ± 1.62 |
| mikofo | input-chancalan | 13.0 ± 0.6 | 11.9 | 19.2 | 10.25 ± 1.66 |
| mattcl-ts | input-chancalan | 13.0 ± 0.4 | 12.2 | 13.8 | 10.28 ± 1.63 |
| mattcl-ts | input-mikofo | 13.0 ± 0.4 | 12.1 | 13.9 | 10.29 ± 1.63 |
| mikofo | input-lanjian | 13.5 ± 5.0 | 12.1 | 68.9 | 10.61 ± 4.27 |
| kcen | input-kcen | 16.4 ± 0.6 | 15.7 | 19.8 | 12.95 ± 2.07 |
| kcen | input-mattcl | 16.4 ± 0.5 | 15.4 | 19.0 | 12.96 ± 2.07 |
| kcen | input-chancalan | 16.5 ± 0.6 | 15.1 | 19.5 | 12.99 ± 2.09 |
| kcen | input-mikofo | 16.5 ± 0.8 | 15.2 | 19.7 | 13.01 ± 2.12 |
| kcen | input-lanjian | 16.5 ± 0.8 | 15.4 | 19.6 | 13.05 ± 2.13 |
| pting | input-chancalan | 17.4 ± 0.6 | 16.3 | 20.4 | 13.71 ± 2.20 |
| pting | input-lanjian | 17.4 ± 0.6 | 16.5 | 20.8 | 13.73 ± 2.20 |
| pting | input-mikofo | 17.5 ± 0.6 | 16.4 | 20.4 | 13.81 ± 2.22 |
| pting | input-kcen | 17.6 ± 0.8 | 16.2 | 20.4 | 13.86 ± 2.27 |
| mattcl-py | input-mattcl | 17.7 ± 0.6 | 16.7 | 20.6 | 13.93 ± 2.23 |
| pting | input-mattcl | 17.7 ± 0.8 | 16.1 | 21.0 | 13.94 ± 2.28 |
| mattcl-py | input-kcen | 17.7 ± 0.7 | 16.2 | 21.1 | 13.95 ± 2.25 |
| mattcl-py | input-chancalan | 17.7 ± 0.7 | 16.6 | 21.4 | 13.96 ± 2.26 |
| mattcl-py | input-mikofo | 17.8 ± 0.8 | 16.4 | 21.1 | 14.04 ± 2.29 |
| mattcl-py | input-lanjian | 18.4 ± 3.4 | 16.8 | 47.4 | 14.50 ± 3.54 |
| chancalan | input-kcen | 21.6 ± 0.7 | 20.7 | 24.1 | 17.08 ± 2.73 |
| chancalan | input-mattcl | 21.7 ± 0.8 | 20.6 | 24.6 | 17.14 ± 2.75 |
| chancalan | input-mikofo | 21.8 ± 0.8 | 20.9 | 25.2 | 17.22 ± 2.76 |
| chancalan | input-lanjian | 21.8 ± 0.8 | 20.7 | 25.1 | 17.22 ± 2.77 |
| chancalan | input-chancalan | 21.9 ± 0.9 | 20.8 | 25.2 | 17.24 ± 2.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|