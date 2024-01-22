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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.8 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.6 | 1.3 | 1.01 ± 0.25 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.5 | 1.6 | 1.03 ± 0.25 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.5 | 2.6 | 1.06 ± 0.27 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 2.1 | 1.06 ± 0.27 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.8 | 2.0 | 1.39 ± 0.33 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.5 | 1.39 ± 0.34 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 0.8 | 2.2 | 1.41 ± 0.34 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 1.0 | 2.2 | 1.47 ± 0.35 |
| lanjian | input-lanjian | 1.6 ± 0.2 | 0.9 | 2.3 | 1.48 ± 0.36 |
| mikofo | input-chancalan | 12.7 ± 0.3 | 11.6 | 13.9 | 12.10 ± 2.45 |
| mikofo | input-kcen | 12.7 ± 0.3 | 11.7 | 13.6 | 12.11 ± 2.46 |
| mikofo | input-lanjian | 12.8 ± 0.3 | 12.1 | 13.8 | 12.14 ± 2.46 |
| mikofo | input-mattcl | 12.8 ± 0.3 | 11.9 | 13.7 | 12.14 ± 2.46 |
| mikofo | input-mikofo | 12.8 ± 0.4 | 11.8 | 15.1 | 12.17 ± 2.47 |
| mattcl-ts | input-kcen | 12.8 ± 0.4 | 11.9 | 14.6 | 12.18 ± 2.48 |
| mattcl-ts | input-lanjian | 12.8 ± 0.4 | 12.0 | 13.8 | 12.19 ± 2.47 |
| mattcl-ts | input-chancalan | 12.8 ± 0.3 | 12.0 | 14.0 | 12.20 ± 2.47 |
| mattcl-ts | input-mattcl | 12.9 ± 0.4 | 12.0 | 14.6 | 12.25 ± 2.49 |
| mattcl-ts | input-mikofo | 12.9 ± 0.4 | 12.1 | 14.2 | 12.30 ± 2.50 |
| kcen | input-mikofo | 16.3 ± 0.6 | 15.2 | 18.9 | 15.52 ± 3.17 |
| kcen | input-chancalan | 16.4 ± 0.5 | 15.5 | 18.8 | 15.55 ± 3.17 |
| kcen | input-lanjian | 16.4 ± 0.6 | 15.4 | 19.8 | 15.58 ± 3.19 |
| kcen | input-mattcl | 16.5 ± 0.6 | 15.3 | 19.7 | 15.66 ± 3.21 |
| kcen | input-kcen | 16.6 ± 0.8 | 15.2 | 19.8 | 15.75 ± 3.27 |
| pting | input-lanjian | 17.3 ± 0.6 | 16.0 | 20.1 | 16.43 ± 3.36 |
| pting | input-chancalan | 17.4 ± 0.7 | 16.1 | 20.6 | 16.50 ± 3.38 |
| pting | input-kcen | 17.5 ± 0.7 | 16.4 | 20.5 | 16.61 ± 3.40 |
| pting | input-mattcl | 17.5 ± 0.6 | 16.3 | 20.2 | 16.62 ± 3.39 |
| pting | input-mikofo | 17.5 ± 0.8 | 16.7 | 20.7 | 16.65 ± 3.43 |
| mattcl-py | input-lanjian | 17.5 ± 0.6 | 16.3 | 20.0 | 16.67 ± 3.40 |
| mattcl-py | input-kcen | 17.6 ± 0.7 | 16.2 | 20.2 | 16.74 ± 3.42 |
| mattcl-py | input-mattcl | 17.6 ± 0.6 | 17.0 | 20.8 | 16.77 ± 3.42 |
| mattcl-py | input-chancalan | 17.6 ± 0.6 | 16.4 | 20.8 | 16.77 ± 3.42 |
| mattcl-py | input-mikofo | 17.7 ± 0.6 | 16.4 | 20.0 | 16.79 ± 3.42 |
| chancalan | input-mattcl | 21.6 ± 0.7 | 20.7 | 24.2 | 20.56 ± 4.18 |
| chancalan | input-mikofo | 21.6 ± 0.6 | 20.7 | 24.0 | 20.58 ± 4.17 |
| chancalan | input-kcen | 21.6 ± 0.7 | 20.7 | 24.3 | 20.59 ± 4.19 |
| chancalan | input-chancalan | 21.8 ± 0.7 | 20.7 | 24.6 | 20.71 ± 4.22 |
| chancalan | input-lanjian | 21.8 ± 0.7 | 20.7 | 25.0 | 20.72 ± 4.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|