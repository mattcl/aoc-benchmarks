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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.29 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.8 | 1.05 ± 0.28 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.2 | 1.8 | 1.05 ± 0.30 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.30 |
| mattcl | input-pting | 1.1 ± 0.1 | 0.5 | 1.4 | 1.07 ± 0.27 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.3 | 1.9 | 1.23 ± 0.34 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.6 | 2.0 | 1.26 ± 0.34 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.6 | 2.0 | 1.26 ± 0.33 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.8 | 1.8 | 1.31 ± 0.33 |
| lanjian | input-pting | 1.4 ± 0.2 | 0.6 | 2.1 | 1.32 ± 0.34 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.7 | 2.2 | 1.33 ± 0.35 |
| mattcl-ts | input-lanjian | 12.3 ± 0.3 | 11.5 | 13.3 | 11.92 ± 2.56 |
| mattcl-ts | input-mikofo | 12.3 ± 0.4 | 11.5 | 13.4 | 11.94 ± 2.56 |
| mattcl-ts | input-chancalan | 12.3 ± 0.4 | 11.5 | 13.4 | 11.95 ± 2.57 |
| mattcl-ts | input-mattcl | 12.4 ± 0.4 | 11.5 | 13.4 | 11.95 ± 2.57 |
| mattcl-ts | input-kcen | 12.4 ± 0.3 | 11.5 | 13.3 | 11.97 ± 2.56 |
| mattcl-ts | input-pting | 12.4 ± 0.3 | 11.5 | 13.3 | 12.01 ± 2.57 |
| mikofo | input-lanjian | 12.6 ± 0.3 | 11.6 | 13.4 | 12.20 ± 2.61 |
| mikofo | input-pting | 12.6 ± 0.3 | 11.5 | 13.8 | 12.21 ± 2.62 |
| mikofo | input-mikofo | 12.6 ± 0.3 | 11.6 | 13.6 | 12.21 ± 2.61 |
| mikofo | input-chancalan | 12.6 ± 0.3 | 11.7 | 13.8 | 12.22 ± 2.61 |
| mikofo | input-mattcl | 12.6 ± 0.3 | 11.6 | 13.4 | 12.22 ± 2.61 |
| mikofo | input-kcen | 12.6 ± 0.3 | 11.7 | 13.6 | 12.23 ± 2.61 |
| kcen | input-lanjian | 16.1 ± 0.6 | 14.9 | 19.5 | 15.58 ± 3.36 |
| kcen | input-chancalan | 16.2 ± 0.6 | 15.3 | 19.3 | 15.64 ± 3.38 |
| kcen | input-kcen | 16.2 ± 0.6 | 15.1 | 19.0 | 15.69 ± 3.39 |
| kcen | input-mikofo | 16.2 ± 0.6 | 15.2 | 19.4 | 15.70 ± 3.39 |
| kcen | input-mattcl | 16.3 ± 0.8 | 14.9 | 19.7 | 15.77 ± 3.43 |
| kcen | input-pting | 16.3 ± 0.5 | 15.3 | 18.8 | 15.77 ± 3.39 |
| pting | input-mattcl | 17.0 ± 0.6 | 16.0 | 20.5 | 16.50 ± 3.56 |
| pting | input-kcen | 17.1 ± 0.6 | 16.3 | 20.2 | 16.53 ± 3.56 |
| pting | input-lanjian | 17.1 ± 0.7 | 15.8 | 20.6 | 16.58 ± 3.59 |
| pting | input-pting | 17.1 ± 0.6 | 16.0 | 19.8 | 16.58 ± 3.57 |
| pting | input-chancalan | 17.2 ± 0.7 | 16.3 | 20.5 | 16.62 ± 3.60 |
| pting | input-mikofo | 17.3 ± 0.7 | 16.4 | 20.3 | 16.71 ± 3.62 |
| mattcl-py | input-kcen | 17.3 ± 0.6 | 16.4 | 20.5 | 16.76 ± 3.61 |
| mattcl-py | input-mikofo | 17.4 ± 0.5 | 16.3 | 20.1 | 16.86 ± 3.62 |
| mattcl-py | input-chancalan | 17.4 ± 0.6 | 16.7 | 20.1 | 16.88 ± 3.63 |
| mattcl-py | input-lanjian | 17.4 ± 0.6 | 16.4 | 20.8 | 16.89 ± 3.64 |
| mattcl-py | input-pting | 17.6 ± 1.1 | 16.7 | 28.7 | 17.03 ± 3.77 |
| mattcl-py | input-mattcl | 17.9 ± 5.0 | 16.3 | 80.3 | 17.32 ± 6.04 |
| chancalan | input-pting | 21.4 ± 0.6 | 20.6 | 24.2 | 20.69 ± 4.43 |
| chancalan | input-kcen | 21.4 ± 0.8 | 20.2 | 24.4 | 20.75 ± 4.47 |
| chancalan | input-chancalan | 21.4 ± 0.7 | 20.3 | 25.0 | 20.75 ± 4.47 |
| chancalan | input-lanjian | 21.5 ± 0.7 | 20.7 | 24.1 | 20.78 ± 4.47 |
| chancalan | input-mikofo | 21.5 ± 0.8 | 20.6 | 24.9 | 20.83 ± 4.49 |
| chancalan | input-mattcl | 21.6 ± 2.2 | 20.5 | 46.4 | 20.92 ± 4.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|