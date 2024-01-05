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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.1 | 0.6 | 1.4 | 1.05 ± 0.25 |
| mattcl | input-mikofo | 1.2 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.27 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 2.0 | 1.06 ± 0.27 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.7 | 1.6 | 1.07 ± 0.25 |
| lanjian | input-kcen | 1.3 ± 2.6 | 0.4 | 37.2 | 1.19 ± 2.29 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.6 | 1.7 | 1.21 ± 0.29 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.7 | 1.9 | 1.24 ± 0.31 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.8 | 2.0 | 1.26 ± 0.31 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.1 | 1.28 ± 0.31 |
| mikofo | input-lanjian | 12.6 ± 0.3 | 11.7 | 13.7 | 11.16 ± 2.27 |
| mikofo | input-kcen | 12.6 ± 0.3 | 11.8 | 13.6 | 11.16 ± 2.27 |
| mikofo | input-chancalan | 12.7 ± 0.3 | 11.8 | 13.7 | 11.20 ± 2.28 |
| mikofo | input-mattcl | 12.7 ± 0.3 | 11.8 | 14.7 | 11.21 ± 2.29 |
| mattcl-ts | input-lanjian | 12.7 ± 0.3 | 11.8 | 13.7 | 11.21 ± 2.29 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 11.7 | 14.7 | 11.21 ± 2.29 |
| mikofo | input-mikofo | 12.7 ± 0.3 | 11.7 | 13.6 | 11.22 ± 2.28 |
| mattcl-ts | input-mikofo | 12.7 ± 0.3 | 11.9 | 13.6 | 11.26 ± 2.30 |
| mattcl-ts | input-kcen | 12.7 ± 0.4 | 11.6 | 13.9 | 11.26 ± 2.30 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 12.0 | 13.8 | 11.27 ± 2.30 |
| kcen | input-mattcl | 16.1 ± 0.6 | 14.9 | 18.6 | 14.26 ± 2.93 |
| kcen | input-mikofo | 16.2 ± 0.6 | 15.1 | 19.6 | 14.35 ± 2.96 |
| kcen | input-chancalan | 16.2 ± 0.6 | 15.1 | 19.3 | 14.35 ± 2.95 |
| kcen | input-lanjian | 16.2 ± 0.7 | 15.1 | 19.0 | 14.36 ± 2.96 |
| kcen | input-kcen | 16.5 ± 3.1 | 14.9 | 48.9 | 14.62 ± 4.06 |
| pting | input-chancalan | 17.1 ± 0.6 | 16.3 | 20.1 | 15.16 ± 3.12 |
| pting | input-lanjian | 17.1 ± 0.6 | 16.0 | 20.7 | 15.17 ± 3.12 |
| pting | input-kcen | 17.2 ± 0.6 | 16.1 | 20.5 | 15.18 ± 3.13 |
| pting | input-mikofo | 17.3 ± 0.7 | 16.0 | 20.6 | 15.29 ± 3.16 |
| mattcl-py | input-lanjian | 17.4 ± 0.7 | 16.6 | 20.7 | 15.44 ± 3.19 |
| mattcl-py | input-chancalan | 17.5 ± 0.7 | 16.4 | 20.5 | 15.46 ± 3.19 |
| mattcl-py | input-mattcl | 17.5 ± 0.7 | 16.4 | 20.4 | 15.49 ± 3.19 |
| pting | input-mattcl | 17.5 ± 3.0 | 16.2 | 55.8 | 15.51 ± 4.13 |
| mattcl-py | input-mikofo | 17.5 ± 0.6 | 16.8 | 20.5 | 15.52 ± 3.18 |
| mattcl-py | input-kcen | 17.6 ± 0.8 | 16.4 | 22.5 | 15.55 ± 3.22 |
| chancalan | input-mikofo | 21.4 ± 0.6 | 20.2 | 24.2 | 18.93 ± 3.87 |
| chancalan | input-chancalan | 21.4 ± 0.7 | 20.3 | 24.4 | 18.94 ± 3.88 |
| chancalan | input-kcen | 21.4 ± 0.7 | 20.4 | 23.6 | 18.94 ± 3.88 |
| chancalan | input-mattcl | 21.5 ± 0.9 | 20.3 | 24.4 | 19.00 ± 3.92 |
| chancalan | input-lanjian | 21.5 ± 0.8 | 20.3 | 24.7 | 19.01 ± 3.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|