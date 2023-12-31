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
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.01 ± 0.19 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.5 | 2.0 | 1.01 ± 0.21 |
| mattcl | input-mikofo | 1.3 ± 0.2 | 0.8 | 1.8 | 1.02 ± 0.19 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.8 | 1.03 ± 0.19 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.6 | 2.2 | 1.05 ± 0.22 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.9 | 1.8 | 1.15 ± 0.22 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 0.8 | 2.2 | 1.18 ± 0.24 |
| lanjian | input-chancalan | 1.6 ± 0.2 | 1.0 | 2.3 | 1.18 ± 0.23 |
| lanjian | input-kcen | 1.6 ± 0.2 | 1.0 | 2.1 | 1.19 ± 0.21 |
| lanjian | input-lanjian | 1.6 ± 0.2 | 1.0 | 2.4 | 1.20 ± 0.23 |
| lanjian | input-pting | 1.6 ± 0.2 | 0.9 | 2.4 | 1.24 ± 0.26 |
| mikofo | input-mattcl | 12.9 ± 0.4 | 11.9 | 14.1 | 9.86 ± 1.42 |
| mikofo | input-lanjian | 12.9 ± 0.3 | 12.1 | 13.9 | 9.87 ± 1.41 |
| mikofo | input-mikofo | 13.0 ± 0.4 | 12.0 | 14.6 | 9.88 ± 1.42 |
| mikofo | input-chancalan | 13.0 ± 0.4 | 12.3 | 14.8 | 9.89 ± 1.42 |
| mikofo | input-kcen | 13.0 ± 0.3 | 11.8 | 13.7 | 9.89 ± 1.42 |
| mattcl-ts | input-pting | 13.0 ± 0.4 | 12.3 | 14.1 | 9.93 ± 1.43 |
| mattcl-ts | input-mattcl | 13.0 ± 0.4 | 11.9 | 13.8 | 9.93 ± 1.43 |
| mattcl-ts | input-kcen | 13.0 ± 0.4 | 12.1 | 14.7 | 9.93 ± 1.43 |
| mattcl-ts | input-chancalan | 13.0 ± 0.3 | 12.1 | 14.1 | 9.95 ± 1.43 |
| mattcl-ts | input-lanjian | 13.1 ± 0.4 | 12.2 | 14.2 | 9.98 ± 1.43 |
| mattcl-ts | input-mikofo | 13.1 ± 0.4 | 12.1 | 15.3 | 10.02 ± 1.45 |
| mikofo | input-pting | 13.3 ± 4.0 | 11.7 | 63.3 | 10.14 ± 3.38 |
| kcen | input-lanjian | 16.5 ± 0.5 | 15.4 | 18.9 | 12.61 ± 1.82 |
| kcen | input-kcen | 16.6 ± 0.6 | 15.1 | 19.5 | 12.62 ± 1.84 |
| kcen | input-pting | 16.6 ± 0.6 | 15.2 | 19.6 | 12.63 ± 1.84 |
| kcen | input-mattcl | 16.6 ± 0.7 | 15.6 | 19.8 | 12.67 ± 1.87 |
| kcen | input-chancalan | 16.6 ± 0.7 | 15.2 | 19.6 | 12.67 ± 1.87 |
| kcen | input-mikofo | 16.8 ± 3.3 | 15.2 | 59.2 | 12.82 ± 3.07 |
| pting | input-mattcl | 17.5 ± 0.6 | 16.0 | 20.4 | 13.35 ± 1.93 |
| pting | input-chancalan | 17.5 ± 0.6 | 16.6 | 20.5 | 13.39 ± 1.94 |
| pting | input-mikofo | 17.6 ± 0.7 | 16.7 | 20.4 | 13.46 ± 1.97 |
| pting | input-lanjian | 17.7 ± 0.8 | 16.5 | 21.3 | 13.47 ± 1.99 |
| mattcl-py | input-mikofo | 17.7 ± 0.6 | 16.5 | 21.0 | 13.50 ± 1.96 |
| pting | input-pting | 17.7 ± 0.6 | 16.8 | 20.6 | 13.50 ± 1.95 |
| mattcl-py | input-lanjian | 17.8 ± 0.7 | 16.6 | 20.6 | 13.54 ± 1.99 |
| mattcl-py | input-chancalan | 17.8 ± 0.7 | 16.4 | 21.0 | 13.58 ± 1.99 |
| mattcl-py | input-pting | 17.8 ± 0.5 | 16.9 | 20.1 | 13.58 ± 1.95 |
| pting | input-kcen | 17.8 ± 3.0 | 16.6 | 54.6 | 13.60 ± 2.96 |
| mattcl-py | input-kcen | 17.8 ± 0.7 | 16.7 | 20.8 | 13.61 ± 2.00 |
| mattcl-py | input-mattcl | 17.9 ± 0.8 | 16.7 | 21.0 | 13.63 ± 2.00 |
| chancalan | input-kcen | 21.8 ± 0.7 | 20.5 | 25.4 | 16.63 ± 2.41 |
| chancalan | input-mattcl | 21.9 ± 0.7 | 20.5 | 24.6 | 16.70 ± 2.42 |
| chancalan | input-pting | 21.9 ± 0.7 | 20.6 | 24.8 | 16.70 ± 2.41 |
| chancalan | input-mikofo | 21.9 ± 0.7 | 20.9 | 24.9 | 16.72 ± 2.41 |
| chancalan | input-chancalan | 22.1 ± 0.6 | 20.7 | 24.5 | 16.82 ± 2.42 |
| chancalan | input-lanjian | 22.2 ± 3.1 | 20.9 | 57.5 | 16.96 ± 3.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|