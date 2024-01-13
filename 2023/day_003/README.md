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
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.7 | 1.01 ± 0.23 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.8 | 1.02 ± 0.23 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.24 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.24 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.6 | 2.1 | 1.35 ± 0.32 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.2 | 1.37 ± 0.30 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.8 | 2.0 | 1.37 ± 0.30 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.7 | 2.0 | 1.37 ± 0.29 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.8 | 2.3 | 1.42 ± 0.32 |
| mikofo | input-kcen | 12.8 ± 0.3 | 12.1 | 13.6 | 12.29 ± 2.08 |
| mikofo | input-lanjian | 12.8 ± 0.3 | 11.9 | 13.7 | 12.35 ± 2.09 |
| mikofo | input-chancalan | 12.8 ± 0.3 | 12.1 | 14.3 | 12.35 ± 2.10 |
| mikofo | input-mattcl | 12.8 ± 0.3 | 12.1 | 13.7 | 12.35 ± 2.09 |
| mattcl-ts | input-lanjian | 12.8 ± 0.4 | 11.8 | 13.9 | 12.37 ± 2.11 |
| mikofo | input-mikofo | 12.9 ± 0.3 | 11.9 | 13.6 | 12.38 ± 2.10 |
| mattcl-ts | input-kcen | 12.9 ± 0.4 | 11.8 | 13.7 | 12.43 ± 2.11 |
| mattcl-ts | input-mattcl | 12.9 ± 0.4 | 12.2 | 14.1 | 12.45 ± 2.11 |
| mattcl-ts | input-chancalan | 12.9 ± 0.4 | 11.9 | 14.0 | 12.46 ± 2.12 |
| mattcl-ts | input-mikofo | 13.0 ± 0.3 | 12.2 | 13.7 | 12.48 ± 2.12 |
| kcen | input-mattcl | 16.3 ± 0.6 | 14.9 | 18.9 | 15.68 ± 2.68 |
| kcen | input-kcen | 16.4 ± 0.6 | 15.6 | 19.6 | 15.76 ± 2.70 |
| kcen | input-mikofo | 16.4 ± 0.6 | 15.3 | 19.8 | 15.77 ± 2.71 |
| kcen | input-chancalan | 16.4 ± 0.7 | 15.0 | 19.8 | 15.80 ± 2.74 |
| kcen | input-lanjian | 16.4 ± 0.6 | 15.3 | 18.6 | 15.81 ± 2.71 |
| pting | input-chancalan | 17.4 ± 0.6 | 16.4 | 20.1 | 16.76 ± 2.86 |
| pting | input-mikofo | 17.4 ± 0.6 | 16.2 | 20.8 | 16.79 ± 2.86 |
| pting | input-kcen | 17.5 ± 0.8 | 16.3 | 20.3 | 16.83 ± 2.92 |
| pting | input-lanjian | 17.5 ± 0.7 | 16.6 | 20.6 | 16.83 ± 2.90 |
| mattcl-py | input-mattcl | 17.5 ± 0.6 | 16.5 | 20.8 | 16.86 ± 2.88 |
| mattcl-py | input-lanjian | 17.6 ± 0.6 | 16.7 | 20.9 | 16.91 ± 2.89 |
| mattcl-py | input-kcen | 17.6 ± 0.7 | 16.9 | 20.8 | 16.99 ± 2.92 |
| mattcl-py | input-mikofo | 17.7 ± 0.8 | 16.7 | 20.9 | 17.03 ± 2.94 |
| mattcl-py | input-chancalan | 17.7 ± 0.8 | 16.7 | 21.1 | 17.04 ± 2.95 |
| pting | input-mattcl | 17.9 ± 3.7 | 16.4 | 54.1 | 17.21 ± 4.56 |
| chancalan | input-kcen | 21.5 ± 0.6 | 20.6 | 25.1 | 20.72 ± 3.53 |
| chancalan | input-mattcl | 21.6 ± 0.6 | 20.2 | 24.5 | 20.84 ± 3.54 |
| chancalan | input-chancalan | 21.7 ± 0.6 | 20.8 | 24.7 | 20.94 ± 3.56 |
| chancalan | input-lanjian | 21.8 ± 0.8 | 20.8 | 25.3 | 21.02 ± 3.61 |
| chancalan | input-mikofo | 22.2 ± 4.4 | 20.8 | 72.9 | 21.35 ± 5.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|