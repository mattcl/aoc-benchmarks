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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-mikofo | 1.3 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.21 |
| mattcl | input-kcen | 1.3 ± 0.1 | 0.7 | 1.7 | 1.04 ± 0.19 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.7 | 1.7 | 1.04 ± 0.20 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 2.0 | 1.18 ± 0.23 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.7 | 2.2 | 1.18 ± 0.24 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.2 | 1.18 ± 0.24 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 0.8 | 2.0 | 1.21 ± 0.23 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.8 | 2.2 | 1.21 ± 0.24 |
| mikofo | input-chancalan | 12.7 ± 0.3 | 11.9 | 13.8 | 10.39 ± 1.54 |
| mikofo | input-mikofo | 12.7 ± 0.3 | 11.8 | 14.4 | 10.39 ± 1.54 |
| mikofo | input-kcen | 12.7 ± 0.3 | 11.8 | 13.7 | 10.42 ± 1.54 |
| mikofo | input-lanjian | 12.8 ± 0.3 | 11.9 | 13.8 | 10.43 ± 1.54 |
| mattcl-ts | input-lanjian | 12.8 ± 0.3 | 12.2 | 13.9 | 10.43 ± 1.54 |
| mattcl-ts | input-kcen | 12.8 ± 0.3 | 11.9 | 13.7 | 10.44 ± 1.54 |
| mattcl-ts | input-mikofo | 12.8 ± 0.4 | 11.7 | 14.2 | 10.46 ± 1.55 |
| mattcl-ts | input-mattcl | 12.8 ± 0.3 | 11.9 | 13.7 | 10.47 ± 1.55 |
| mikofo | input-mattcl | 13.0 ± 2.9 | 11.9 | 54.2 | 10.63 ± 2.87 |
| mattcl-ts | input-chancalan | 13.3 ± 4.7 | 12.1 | 64.1 | 10.84 ± 4.16 |
| kcen | input-mikofo | 16.3 ± 0.7 | 15.1 | 19.3 | 13.31 ± 2.03 |
| kcen | input-kcen | 16.3 ± 0.5 | 15.2 | 18.9 | 13.32 ± 1.98 |
| kcen | input-mattcl | 16.3 ± 0.8 | 15.2 | 19.8 | 13.36 ± 2.05 |
| kcen | input-lanjian | 16.4 ± 0.7 | 15.3 | 19.8 | 13.38 ± 2.04 |
| kcen | input-chancalan | 16.4 ± 0.7 | 15.0 | 19.6 | 13.43 ± 2.05 |
| pting | input-mattcl | 17.3 ± 0.6 | 16.2 | 20.5 | 14.11 ± 2.12 |
| pting | input-chancalan | 17.3 ± 0.6 | 16.2 | 20.1 | 14.17 ± 2.13 |
| pting | input-kcen | 17.3 ± 0.8 | 16.2 | 20.8 | 14.18 ± 2.18 |
| pting | input-lanjian | 17.4 ± 0.8 | 16.2 | 20.7 | 14.22 ± 2.17 |
| mattcl-py | input-kcen | 17.6 ± 0.6 | 16.4 | 20.8 | 14.35 ± 2.14 |
| mattcl-py | input-lanjian | 17.6 ± 0.6 | 16.5 | 20.4 | 14.35 ± 2.15 |
| mattcl-py | input-mattcl | 17.6 ± 0.8 | 16.3 | 20.8 | 14.36 ± 2.19 |
| mattcl-py | input-mikofo | 17.7 ± 0.7 | 16.4 | 20.8 | 14.46 ± 2.19 |
| mattcl-py | input-chancalan | 17.7 ± 1.2 | 16.4 | 30.5 | 14.47 ± 2.34 |
| pting | input-mikofo | 17.9 ± 5.1 | 16.1 | 64.7 | 14.67 ± 4.67 |
| chancalan | input-mattcl | 21.4 ± 0.6 | 20.6 | 24.2 | 17.54 ± 2.60 |
| chancalan | input-kcen | 21.5 ± 0.7 | 20.2 | 24.3 | 17.60 ± 2.62 |
| chancalan | input-lanjian | 21.6 ± 0.8 | 20.4 | 24.4 | 17.65 ± 2.65 |
| chancalan | input-mikofo | 21.6 ± 0.8 | 20.8 | 24.5 | 17.70 ± 2.65 |
| chancalan | input-chancalan | 21.9 ± 2.4 | 20.9 | 48.9 | 17.92 ± 3.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|