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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.9 | 1.00 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.22 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.6 | 1.01 ± 0.22 |
| mattcl | input-kcen | 1.2 ± 0.1 | 0.6 | 1.6 | 1.02 ± 0.21 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.9 | 1.02 ± 0.21 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.7 | 1.6 | 1.17 ± 0.25 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.7 | 1.17 ± 0.26 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.8 | 1.9 | 1.19 ± 0.25 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.8 | 2.0 | 1.19 ± 0.26 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.2 | 1.22 ± 0.28 |
| mikofo | input-lanjian | 12.7 ± 0.3 | 11.7 | 13.7 | 11.23 ± 1.85 |
| mikofo | input-mikofo | 12.7 ± 0.3 | 11.7 | 14.3 | 11.26 ± 1.86 |
| mikofo | input-kcen | 12.8 ± 0.3 | 11.8 | 13.8 | 11.27 ± 1.86 |
| mikofo | input-chancalan | 12.8 ± 0.3 | 11.6 | 13.6 | 11.28 ± 1.86 |
| mattcl-ts | input-chancalan | 12.8 ± 0.4 | 11.6 | 13.9 | 11.31 ± 1.87 |
| mattcl-ts | input-mattcl | 12.8 ± 0.4 | 12.0 | 13.7 | 11.32 ± 1.87 |
| mattcl-ts | input-mikofo | 12.8 ± 0.4 | 12.2 | 14.0 | 11.35 ± 1.87 |
| mattcl-ts | input-lanjian | 12.9 ± 0.3 | 11.9 | 13.8 | 11.35 ± 1.87 |
| mattcl-ts | input-kcen | 12.9 ± 0.4 | 11.8 | 13.7 | 11.39 ± 1.88 |
| mikofo | input-mattcl | 13.0 ± 2.5 | 11.9 | 47.4 | 11.48 ± 2.87 |
| kcen | input-mattcl | 16.3 ± 0.5 | 15.0 | 18.2 | 14.36 ± 2.37 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.0 | 19.8 | 14.40 ± 2.43 |
| kcen | input-mikofo | 16.3 ± 0.6 | 15.1 | 19.7 | 14.41 ± 2.42 |
| kcen | input-chancalan | 16.4 ± 0.7 | 15.5 | 20.1 | 14.47 ± 2.44 |
| kcen | input-kcen | 16.4 ± 0.8 | 15.2 | 19.6 | 14.50 ± 2.46 |
| pting | input-kcen | 17.3 ± 0.7 | 16.1 | 20.6 | 15.27 ± 2.56 |
| pting | input-chancalan | 17.4 ± 0.7 | 15.8 | 20.4 | 15.33 ± 2.57 |
| pting | input-mikofo | 17.4 ± 0.8 | 16.2 | 20.6 | 15.36 ± 2.61 |
| pting | input-mattcl | 17.4 ± 1.8 | 16.1 | 38.2 | 15.38 ± 2.97 |
| pting | input-lanjian | 17.4 ± 0.9 | 16.1 | 20.8 | 15.39 ± 2.62 |
| mattcl-py | input-mattcl | 17.5 ± 0.6 | 16.2 | 20.7 | 15.44 ± 2.58 |
| mattcl-py | input-kcen | 17.6 ± 0.7 | 16.6 | 20.6 | 15.51 ± 2.61 |
| mattcl-py | input-chancalan | 17.6 ± 0.6 | 16.6 | 20.5 | 15.52 ± 2.59 |
| mattcl-py | input-lanjian | 17.6 ± 0.8 | 16.6 | 23.2 | 15.56 ± 2.62 |
| mattcl-py | input-mikofo | 17.7 ± 0.9 | 16.8 | 20.9 | 15.67 ± 2.67 |
| chancalan | input-kcen | 21.6 ± 0.8 | 20.5 | 24.4 | 19.10 ± 3.18 |
| chancalan | input-mattcl | 21.6 ± 0.8 | 20.7 | 24.6 | 19.10 ± 3.20 |
| chancalan | input-chancalan | 21.7 ± 0.7 | 20.7 | 24.8 | 19.18 ± 3.19 |
| chancalan | input-mikofo | 21.7 ± 0.8 | 20.7 | 25.0 | 19.19 ± 3.20 |
| chancalan | input-lanjian | 21.8 ± 0.8 | 20.7 | 24.9 | 19.24 ± 3.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|