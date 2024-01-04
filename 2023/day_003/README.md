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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.00 |
| mattcl | input-mikofo | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.23 |
| mattcl | input-chancalan | 1.2 ± 0.1 | 0.7 | 1.7 | 1.02 ± 0.18 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.22 |
| lanjian | input-kcen | 1.3 ± 0.3 | 0.4 | 2.1 | 1.08 ± 0.31 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.7 | 1.9 | 1.15 ± 0.24 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 1.7 | 1.17 ± 0.22 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.8 | 2.1 | 1.18 ± 0.25 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.9 | 2.2 | 1.21 ± 0.24 |
| mikofo | input-lanjian | 12.8 ± 0.3 | 12.0 | 14.0 | 10.55 ± 1.53 |
| mikofo | input-mattcl | 12.9 ± 0.3 | 11.8 | 13.9 | 10.58 ± 1.54 |
| mikofo | input-mikofo | 12.9 ± 0.3 | 12.1 | 14.7 | 10.58 ± 1.54 |
| mikofo | input-chancalan | 12.9 ± 0.4 | 11.9 | 14.6 | 10.58 ± 1.54 |
| mattcl-ts | input-chancalan | 12.9 ± 0.3 | 12.0 | 13.7 | 10.60 ± 1.54 |
| mikofo | input-kcen | 12.9 ± 0.3 | 12.1 | 13.8 | 10.61 ± 1.54 |
| mattcl-ts | input-lanjian | 12.9 ± 0.4 | 12.0 | 14.0 | 10.62 ± 1.55 |
| mattcl-ts | input-kcen | 13.0 ± 0.3 | 12.0 | 13.9 | 10.66 ± 1.55 |
| mattcl-ts | input-mattcl | 13.3 ± 4.1 | 12.1 | 70.4 | 10.93 ± 3.70 |
| mattcl-ts | input-mikofo | 13.8 ± 7.3 | 12.1 | 93.0 | 11.33 ± 6.20 |
| kcen | input-kcen | 16.4 ± 0.6 | 15.3 | 19.4 | 13.50 ± 1.98 |
| kcen | input-lanjian | 16.4 ± 0.7 | 14.9 | 19.2 | 13.53 ± 2.03 |
| kcen | input-chancalan | 16.5 ± 0.7 | 15.1 | 19.7 | 13.54 ± 2.02 |
| kcen | input-mikofo | 16.5 ± 0.7 | 15.3 | 19.6 | 13.55 ± 2.02 |
| kcen | input-mattcl | 16.7 ± 3.7 | 15.2 | 51.4 | 13.77 ± 3.61 |
| pting | input-mikofo | 17.3 ± 0.5 | 16.2 | 19.4 | 14.24 ± 2.08 |
| pting | input-kcen | 17.4 ± 0.8 | 16.3 | 20.6 | 14.32 ± 2.14 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.2 | 21.8 | 14.35 ± 2.13 |
| pting | input-chancalan | 17.5 ± 0.7 | 16.6 | 20.2 | 14.37 ± 2.12 |
| pting | input-mattcl | 17.5 ± 0.7 | 16.3 | 20.6 | 14.38 ± 2.14 |
| mattcl-py | input-lanjian | 17.5 ± 0.6 | 16.2 | 19.9 | 14.42 ± 2.12 |
| mattcl-py | input-kcen | 17.6 ± 0.7 | 16.6 | 20.3 | 14.52 ± 2.15 |
| mattcl-py | input-chancalan | 17.7 ± 0.7 | 16.6 | 20.8 | 14.53 ± 2.15 |
| mattcl-py | input-mikofo | 17.7 ± 0.7 | 16.6 | 20.6 | 14.57 ± 2.16 |
| mattcl-py | input-mattcl | 18.4 ± 5.4 | 16.5 | 67.1 | 15.10 ± 4.94 |
| chancalan | input-kcen | 21.6 ± 0.7 | 20.7 | 24.5 | 17.79 ± 2.60 |
| chancalan | input-lanjian | 21.8 ± 0.9 | 20.7 | 25.0 | 17.92 ± 2.66 |
| chancalan | input-chancalan | 21.8 ± 0.8 | 20.3 | 24.9 | 17.93 ± 2.65 |
| chancalan | input-mattcl | 21.9 ± 1.0 | 20.6 | 28.2 | 17.98 ± 2.69 |
| chancalan | input-mikofo | 21.9 ± 0.8 | 20.8 | 24.7 | 18.01 ± 2.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|