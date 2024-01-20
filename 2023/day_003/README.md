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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.3 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.24 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.9 | 1.04 ± 0.26 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.3 | 1.5 | 1.04 ± 0.25 |
| mattcl | input-lanjian | 1.1 ± 0.1 | 0.6 | 1.4 | 1.04 ± 0.23 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.8 | 2.3 | 1.38 ± 0.33 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.8 | 2.4 | 1.39 ± 0.32 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.9 | 2.1 | 1.42 ± 0.31 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.6 | 2.6 | 1.42 ± 0.33 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.8 | 2.0 | 1.42 ± 0.32 |
| mikofo | input-mattcl | 12.4 ± 0.4 | 11.3 | 13.3 | 12.00 ± 2.16 |
| mikofo | input-mikofo | 12.4 ± 0.4 | 11.2 | 13.2 | 12.01 ± 2.16 |
| mattcl-ts | input-kcen | 12.5 ± 0.4 | 11.6 | 13.4 | 12.03 ± 2.16 |
| mattcl-ts | input-lanjian | 12.5 ± 0.4 | 11.4 | 13.5 | 12.03 ± 2.17 |
| mikofo | input-kcen | 12.5 ± 0.3 | 11.6 | 13.7 | 12.05 ± 2.16 |
| mikofo | input-lanjian | 12.5 ± 0.3 | 11.5 | 13.3 | 12.06 ± 2.16 |
| mattcl-ts | input-chancalan | 12.5 ± 0.3 | 11.6 | 13.4 | 12.06 ± 2.17 |
| mikofo | input-chancalan | 12.5 ± 0.3 | 11.5 | 13.7 | 12.07 ± 2.17 |
| mattcl-ts | input-mikofo | 12.5 ± 0.4 | 11.5 | 13.4 | 12.07 ± 2.17 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.5 | 13.4 | 12.10 ± 2.18 |
| kcen | input-kcen | 16.3 ± 0.6 | 15.2 | 19.6 | 15.71 ± 2.85 |
| kcen | input-chancalan | 16.3 ± 0.6 | 15.1 | 19.0 | 15.74 ± 2.86 |
| kcen | input-mikofo | 16.3 ± 0.7 | 15.0 | 19.8 | 15.75 ± 2.87 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.2 | 19.2 | 15.77 ± 2.88 |
| kcen | input-mattcl | 16.4 ± 0.5 | 15.5 | 18.1 | 15.79 ± 2.83 |
| pting | input-mattcl | 17.2 ± 0.7 | 16.1 | 20.2 | 16.64 ± 3.02 |
| pting | input-chancalan | 17.3 ± 0.6 | 16.2 | 19.9 | 16.65 ± 3.01 |
| pting | input-mikofo | 17.3 ± 0.5 | 16.5 | 19.8 | 16.68 ± 2.99 |
| pting | input-kcen | 17.3 ± 0.6 | 16.3 | 19.9 | 16.68 ± 3.02 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.2 | 20.8 | 16.68 ± 3.03 |
| mattcl-py | input-chancalan | 17.5 ± 0.7 | 16.4 | 21.0 | 16.92 ± 3.07 |
| mattcl-py | input-kcen | 17.5 ± 0.6 | 16.7 | 20.5 | 16.92 ± 3.06 |
| mattcl-py | input-lanjian | 17.6 ± 0.7 | 16.4 | 20.8 | 16.95 ± 3.08 |
| mattcl-py | input-mattcl | 17.6 ± 0.8 | 16.4 | 20.8 | 16.96 ± 3.11 |
| mattcl-py | input-mikofo | 17.6 ± 0.7 | 16.8 | 20.8 | 16.97 ± 3.08 |
| chancalan | input-chancalan | 21.5 ± 0.5 | 20.7 | 24.4 | 20.75 ± 3.72 |
| chancalan | input-mikofo | 21.5 ± 0.6 | 20.6 | 24.0 | 20.77 ± 3.73 |
| chancalan | input-lanjian | 21.5 ± 0.7 | 20.6 | 24.5 | 20.80 ± 3.75 |
| chancalan | input-kcen | 21.6 ± 0.8 | 20.7 | 25.1 | 20.89 ± 3.79 |
| chancalan | input-mattcl | 21.7 ± 0.9 | 20.6 | 25.0 | 20.95 ± 3.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|