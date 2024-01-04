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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.9 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.27 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.27 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.06 ± 0.27 |
| mattcl | input-mikofo | 1.2 ± 0.1 | 0.6 | 1.7 | 1.07 ± 0.26 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.7 | 2.0 | 1.19 ± 0.31 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.8 | 1.9 | 1.21 ± 0.31 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.0 | 1.25 ± 0.33 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.0 | 1.25 ± 0.32 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.7 | 2.0 | 1.28 ± 0.33 |
| mikofo | input-mikofo | 12.6 ± 0.3 | 11.5 | 13.2 | 11.23 ± 2.39 |
| mikofo | input-mattcl | 12.6 ± 0.3 | 11.6 | 13.2 | 11.23 ± 2.39 |
| mikofo | input-kcen | 12.6 ± 0.3 | 11.7 | 13.7 | 11.24 ± 2.39 |
| mikofo | input-lanjian | 12.6 ± 0.3 | 11.8 | 13.5 | 11.24 ± 2.39 |
| mikofo | input-chancalan | 12.6 ± 0.3 | 11.5 | 13.5 | 11.25 ± 2.40 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.8 | 13.8 | 11.31 ± 2.41 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.8 | 13.8 | 11.31 ± 2.41 |
| mattcl-ts | input-lanjian | 12.7 ± 0.4 | 12.0 | 15.7 | 11.37 ± 2.43 |
| mattcl-ts | input-mikofo | 12.7 ± 0.3 | 11.9 | 13.9 | 11.38 ± 2.42 |
| mattcl-ts | input-mattcl | 12.7 ± 0.4 | 12.0 | 14.2 | 11.38 ± 2.43 |
| kcen | input-kcen | 16.2 ± 0.5 | 15.1 | 19.3 | 14.48 ± 3.10 |
| kcen | input-mattcl | 16.2 ± 0.7 | 14.9 | 19.2 | 14.50 ± 3.13 |
| kcen | input-chancalan | 16.3 ± 0.6 | 15.3 | 19.6 | 14.55 ± 3.13 |
| kcen | input-mikofo | 16.4 ± 0.8 | 15.1 | 19.6 | 14.63 ± 3.17 |
| kcen | input-lanjian | 16.5 ± 3.0 | 15.2 | 56.5 | 14.79 ± 4.15 |
| pting | input-mattcl | 17.1 ± 0.6 | 16.1 | 20.3 | 15.30 ± 3.29 |
| pting | input-lanjian | 17.2 ± 0.7 | 16.0 | 20.5 | 15.34 ± 3.30 |
| pting | input-kcen | 17.2 ± 0.7 | 15.8 | 20.0 | 15.38 ± 3.31 |
| pting | input-mikofo | 17.2 ± 0.6 | 16.3 | 20.3 | 15.39 ± 3.31 |
| pting | input-chancalan | 17.3 ± 0.8 | 16.2 | 20.6 | 15.44 ± 3.34 |
| mattcl-py | input-mattcl | 17.4 ± 0.5 | 16.6 | 19.7 | 15.52 ± 3.31 |
| mattcl-py | input-lanjian | 17.4 ± 0.6 | 16.6 | 20.5 | 15.55 ± 3.34 |
| mattcl-py | input-kcen | 17.4 ± 0.6 | 16.1 | 20.5 | 15.60 ± 3.34 |
| mattcl-py | input-chancalan | 17.5 ± 0.6 | 16.3 | 20.6 | 15.61 ± 3.34 |
| mattcl-py | input-mikofo | 17.5 ± 0.5 | 16.6 | 20.5 | 15.63 ± 3.33 |
| chancalan | input-mikofo | 21.4 ± 0.7 | 20.5 | 24.6 | 19.15 ± 4.10 |
| chancalan | input-lanjian | 21.4 ± 0.7 | 20.5 | 24.5 | 19.16 ± 4.10 |
| chancalan | input-kcen | 21.4 ± 0.8 | 20.3 | 25.3 | 19.18 ± 4.11 |
| chancalan | input-chancalan | 21.5 ± 0.6 | 20.2 | 24.3 | 19.21 ± 4.10 |
| chancalan | input-mattcl | 21.6 ± 0.8 | 20.5 | 24.9 | 19.29 ± 4.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|