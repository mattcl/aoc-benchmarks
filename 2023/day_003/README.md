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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.4 | 1.2 | 1.01 ± 0.24 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.2 | 1.6 | 1.02 ± 0.24 |
| mattcl | input-mikofo | 1.0 ± 0.1 | 0.5 | 1.6 | 1.04 ± 0.23 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.7 | 2.1 | 1.41 ± 0.34 |
| lanjian | input-kcen | 1.3 ± 0.2 | 1.0 | 1.8 | 1.41 ± 0.32 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.5 | 1.6 | 1.41 ± 0.33 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.8 | 1.9 | 1.43 ± 0.32 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.4 | 1.46 ± 0.35 |
| mikofo | input-mattcl | 12.6 ± 0.3 | 11.7 | 13.5 | 13.15 ± 2.40 |
| mikofo | input-kcen | 12.6 ± 0.3 | 11.7 | 13.5 | 13.16 ± 2.40 |
| mikofo | input-chancalan | 12.6 ± 0.3 | 11.5 | 13.8 | 13.16 ± 2.41 |
| mikofo | input-mikofo | 12.6 ± 0.3 | 11.9 | 13.7 | 13.19 ± 2.41 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 11.9 | 13.5 | 13.22 ± 2.41 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.8 | 13.6 | 13.23 ± 2.42 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.9 | 13.5 | 13.30 ± 2.43 |
| mattcl-ts | input-mikofo | 12.8 ± 0.3 | 12.0 | 13.8 | 13.32 ± 2.44 |
| mikofo | input-lanjian | 12.8 ± 2.1 | 11.8 | 42.6 | 13.34 ± 3.29 |
| mattcl-ts | input-lanjian | 13.1 ± 5.1 | 11.9 | 84.5 | 13.65 ± 5.86 |
| kcen | input-mattcl | 16.0 ± 0.6 | 14.9 | 19.0 | 16.75 ± 3.09 |
| kcen | input-kcen | 16.1 ± 0.6 | 15.0 | 19.8 | 16.84 ± 3.11 |
| kcen | input-chancalan | 16.1 ± 0.6 | 15.0 | 19.5 | 16.87 ± 3.13 |
| kcen | input-mikofo | 16.1 ± 0.6 | 15.3 | 19.2 | 16.87 ± 3.13 |
| kcen | input-lanjian | 16.3 ± 0.8 | 15.0 | 19.4 | 17.03 ± 3.18 |
| pting | input-kcen | 17.0 ± 0.6 | 15.8 | 19.6 | 17.74 ± 3.28 |
| pting | input-lanjian | 17.0 ± 0.7 | 15.9 | 20.2 | 17.79 ± 3.31 |
| pting | input-mattcl | 17.0 ± 0.6 | 15.9 | 19.9 | 17.81 ± 3.29 |
| pting | input-mikofo | 17.0 ± 0.5 | 16.1 | 19.6 | 17.81 ± 3.27 |
| pting | input-chancalan | 17.1 ± 0.7 | 16.1 | 20.2 | 17.91 ± 3.33 |
| mattcl-py | input-kcen | 17.4 ± 0.7 | 16.4 | 20.7 | 18.15 ± 3.36 |
| mattcl-py | input-mattcl | 17.4 ± 0.7 | 16.3 | 20.5 | 18.19 ± 3.39 |
| mattcl-py | input-chancalan | 17.4 ± 0.6 | 16.4 | 21.1 | 18.21 ± 3.36 |
| mattcl-py | input-mikofo | 17.5 ± 0.8 | 16.5 | 21.1 | 18.31 ± 3.41 |
| mattcl-py | input-lanjian | 17.6 ± 3.2 | 16.4 | 58.0 | 18.34 ± 4.72 |
| chancalan | input-kcen | 21.2 ± 0.5 | 20.6 | 24.5 | 22.14 ± 4.04 |
| chancalan | input-mikofo | 21.3 ± 0.5 | 20.5 | 23.4 | 22.21 ± 4.06 |
| chancalan | input-mattcl | 21.3 ± 0.6 | 20.4 | 24.2 | 22.24 ± 4.09 |
| chancalan | input-lanjian | 21.3 ± 0.6 | 20.5 | 24.6 | 22.25 ± 4.08 |
| chancalan | input-chancalan | 21.4 ± 0.6 | 20.2 | 24.5 | 22.37 ± 4.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|