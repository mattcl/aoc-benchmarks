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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.8 | 1.00 ± 0.29 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.27 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 1.7 | 1.05 ± 0.27 |
| mattcl | input-mattcl | 1.1 ± 0.1 | 0.5 | 1.6 | 1.06 ± 0.26 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.2 | 1.40 ± 0.35 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.8 | 2.0 | 1.40 ± 0.34 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.6 | 2.3 | 1.46 ± 0.38 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 0.8 | 2.5 | 1.48 ± 0.38 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.1 | 1.49 ± 0.37 |
| mikofo | input-chancalan | 12.8 ± 0.3 | 11.9 | 13.8 | 12.59 ± 2.60 |
| mikofo | input-lanjian | 12.8 ± 0.3 | 12.0 | 13.6 | 12.61 ± 2.60 |
| mikofo | input-mattcl | 12.8 ± 0.3 | 11.9 | 13.7 | 12.62 ± 2.60 |
| mikofo | input-mikofo | 12.8 ± 0.3 | 12.0 | 13.7 | 12.63 ± 2.61 |
| mikofo | input-kcen | 12.8 ± 0.4 | 11.7 | 14.0 | 12.64 ± 2.61 |
| mattcl-ts | input-chancalan | 12.9 ± 0.4 | 11.8 | 14.0 | 12.68 ± 2.62 |
| mattcl-ts | input-mikofo | 12.9 ± 0.4 | 12.1 | 13.9 | 12.71 ± 2.63 |
| mattcl-ts | input-lanjian | 12.9 ± 0.4 | 12.0 | 14.0 | 12.73 ± 2.63 |
| mattcl-ts | input-mattcl | 12.9 ± 0.3 | 11.9 | 13.8 | 12.73 ± 2.63 |
| mattcl-ts | input-kcen | 13.0 ± 0.4 | 11.9 | 14.2 | 12.76 ± 2.64 |
| kcen | input-mattcl | 16.4 ± 0.6 | 15.3 | 19.7 | 16.11 ± 3.36 |
| kcen | input-mikofo | 16.4 ± 0.6 | 15.4 | 19.3 | 16.15 ± 3.36 |
| kcen | input-kcen | 16.5 ± 0.7 | 15.3 | 19.5 | 16.21 ± 3.38 |
| kcen | input-chancalan | 16.5 ± 0.6 | 15.3 | 19.4 | 16.22 ± 3.38 |
| kcen | input-lanjian | 16.8 ± 4.3 | 14.9 | 54.7 | 16.59 ± 5.47 |
| pting | input-kcen | 17.4 ± 0.7 | 16.0 | 20.4 | 17.11 ± 3.57 |
| pting | input-chancalan | 17.4 ± 0.6 | 16.1 | 20.6 | 17.11 ± 3.55 |
| pting | input-lanjian | 17.4 ± 0.6 | 16.2 | 20.1 | 17.13 ± 3.56 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.4 | 20.7 | 17.16 ± 3.59 |
| pting | input-mikofo | 17.5 ± 0.6 | 16.4 | 20.4 | 17.19 ± 3.57 |
| mattcl-py | input-mattcl | 17.6 ± 0.7 | 16.3 | 20.5 | 17.31 ± 3.61 |
| mattcl-py | input-lanjian | 17.6 ± 0.7 | 16.7 | 21.0 | 17.33 ± 3.62 |
| mattcl-py | input-kcen | 17.6 ± 0.6 | 16.3 | 20.1 | 17.35 ± 3.60 |
| mattcl-py | input-mikofo | 17.7 ± 0.7 | 16.3 | 20.6 | 17.40 ± 3.63 |
| mattcl-py | input-chancalan | 17.7 ± 0.7 | 16.6 | 20.8 | 17.41 ± 3.64 |
| chancalan | input-kcen | 21.7 ± 0.6 | 20.7 | 24.4 | 21.38 ± 4.42 |
| chancalan | input-mattcl | 21.8 ± 0.7 | 20.8 | 24.9 | 21.43 ± 4.45 |
| chancalan | input-mikofo | 21.8 ± 0.8 | 20.7 | 24.8 | 21.44 ± 4.46 |
| chancalan | input-chancalan | 21.8 ± 0.8 | 20.8 | 24.5 | 21.46 ± 4.46 |
| chancalan | input-lanjian | 21.8 ± 0.8 | 20.7 | 24.7 | 21.50 ± 4.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|