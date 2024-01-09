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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.25 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.4 | 1.01 ± 0.23 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.23 |
| mattcl | input-mikofo | 1.1 ± 0.1 | 0.6 | 1.7 | 1.06 ± 0.23 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.8 | 2.3 | 1.37 ± 0.32 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.3 | 1.38 ± 0.30 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.1 | 1.38 ± 0.33 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.7 | 2.3 | 1.44 ± 0.33 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 0.9 | 2.4 | 1.50 ± 0.34 |
| mikofo | input-chancalan | 12.9 ± 0.4 | 11.9 | 14.2 | 12.49 ± 2.19 |
| mikofo | input-kcen | 12.9 ± 0.3 | 11.7 | 13.9 | 12.52 ± 2.20 |
| mikofo | input-lanjian | 12.9 ± 0.3 | 11.6 | 14.1 | 12.53 ± 2.20 |
| mikofo | input-mattcl | 12.9 ± 0.3 | 11.9 | 13.8 | 12.54 ± 2.20 |
| mattcl-ts | input-lanjian | 12.9 ± 0.4 | 11.9 | 14.5 | 12.57 ± 2.21 |
| mattcl-ts | input-mattcl | 12.9 ± 0.4 | 12.0 | 14.2 | 12.57 ± 2.21 |
| mattcl-ts | input-chancalan | 13.0 ± 0.4 | 12.0 | 14.6 | 12.58 ± 2.21 |
| mattcl-ts | input-mikofo | 13.0 ± 0.4 | 12.0 | 15.1 | 12.61 ± 2.22 |
| mikofo | input-mikofo | 13.3 ± 4.2 | 12.1 | 72.0 | 12.90 ± 4.64 |
| mattcl-ts | input-kcen | 13.3 ± 4.2 | 12.1 | 71.5 | 12.92 ± 4.61 |
| kcen | input-mattcl | 16.4 ± 0.7 | 15.0 | 19.0 | 15.94 ± 2.84 |
| kcen | input-chancalan | 16.4 ± 0.7 | 15.2 | 19.0 | 15.95 ± 2.84 |
| kcen | input-lanjian | 16.5 ± 0.7 | 15.3 | 20.1 | 15.99 ± 2.86 |
| kcen | input-kcen | 16.5 ± 0.7 | 15.5 | 19.4 | 15.99 ± 2.85 |
| kcen | input-mikofo | 16.5 ± 1.8 | 15.3 | 38.8 | 16.07 ± 3.29 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.4 | 20.9 | 16.87 ± 3.01 |
| pting | input-lanjian | 17.5 ± 0.6 | 16.5 | 20.3 | 16.96 ± 3.00 |
| pting | input-kcen | 17.5 ± 0.7 | 16.3 | 21.0 | 16.99 ± 3.03 |
| pting | input-mikofo | 17.5 ± 0.7 | 16.6 | 20.8 | 17.00 ± 3.02 |
| pting | input-chancalan | 17.5 ± 0.7 | 16.3 | 20.7 | 17.01 ± 3.04 |
| mattcl-py | input-lanjian | 17.5 ± 0.5 | 16.7 | 20.6 | 17.03 ± 2.99 |
| mattcl-py | input-chancalan | 17.6 ± 0.7 | 16.4 | 20.7 | 17.13 ± 3.04 |
| mattcl-py | input-kcen | 17.7 ± 0.8 | 16.6 | 21.0 | 17.18 ± 3.07 |
| mattcl-py | input-mikofo | 17.9 ± 0.9 | 16.3 | 21.0 | 17.37 ± 3.14 |
| mattcl-py | input-mattcl | 18.1 ± 2.3 | 16.9 | 43.0 | 17.58 ± 3.79 |
| chancalan | input-kcen | 21.8 ± 0.7 | 20.6 | 24.5 | 21.12 ± 3.72 |
| chancalan | input-mattcl | 21.8 ± 0.8 | 20.3 | 24.7 | 21.21 ± 3.76 |
| chancalan | input-mikofo | 21.9 ± 1.2 | 20.6 | 32.7 | 21.26 ± 3.87 |
| chancalan | input-chancalan | 21.9 ± 0.7 | 20.9 | 24.4 | 21.30 ± 3.77 |
| chancalan | input-lanjian | 21.9 ± 0.8 | 20.3 | 25.2 | 21.31 ± 3.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|