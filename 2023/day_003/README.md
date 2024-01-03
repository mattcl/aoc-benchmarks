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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.8 | 1.01 ± 0.23 |
| mattcl | input-chancalan | 1.3 ± 0.1 | 0.7 | 1.7 | 1.02 ± 0.20 |
| mattcl | input-mikofo | 1.3 ± 0.2 | 0.7 | 2.0 | 1.03 ± 0.21 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.8 | 1.8 | 1.03 ± 0.21 |
| lanjian | input-chancalan | 1.3 ± 0.4 | 0.5 | 4.7 | 1.07 ± 0.35 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.9 | 1.7 | 1.15 ± 0.24 |
| lanjian | input-mikofo | 1.5 ± 0.2 | 0.9 | 2.3 | 1.18 ± 0.25 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.9 | 2.0 | 1.19 ± 0.26 |
| lanjian | input-kcen | 1.6 ± 0.2 | 1.0 | 2.5 | 1.25 ± 0.27 |
| mikofo | input-lanjian | 12.8 ± 0.3 | 12.0 | 13.8 | 10.23 ± 1.69 |
| mattcl-ts | input-lanjian | 12.9 ± 0.4 | 12.0 | 14.0 | 10.26 ± 1.71 |
| mikofo | input-mikofo | 12.9 ± 0.3 | 12.1 | 13.8 | 10.28 ± 1.70 |
| mikofo | input-chancalan | 12.9 ± 0.3 | 12.0 | 14.0 | 10.29 ± 1.71 |
| mikofo | input-mattcl | 12.9 ± 0.3 | 12.0 | 14.1 | 10.29 ± 1.70 |
| mikofo | input-kcen | 12.9 ± 0.3 | 12.1 | 14.0 | 10.30 ± 1.71 |
| mattcl-ts | input-chancalan | 12.9 ± 0.4 | 12.1 | 14.0 | 10.32 ± 1.71 |
| mattcl-ts | input-mikofo | 13.0 ± 0.4 | 12.1 | 14.0 | 10.37 ± 1.72 |
| mattcl-ts | input-mattcl | 13.0 ± 1.0 | 11.9 | 26.0 | 10.40 ± 1.88 |
| mattcl-ts | input-kcen | 13.6 ± 5.1 | 12.1 | 70.3 | 10.86 ± 4.44 |
| kcen | input-mattcl | 16.4 ± 0.5 | 15.1 | 19.0 | 13.05 ± 2.18 |
| kcen | input-mikofo | 16.4 ± 0.6 | 15.5 | 19.1 | 13.09 ± 2.20 |
| kcen | input-chancalan | 16.5 ± 0.7 | 15.3 | 19.2 | 13.17 ± 2.22 |
| kcen | input-kcen | 16.6 ± 0.8 | 15.1 | 20.0 | 13.20 ± 2.26 |
| kcen | input-lanjian | 16.6 ± 0.7 | 15.1 | 19.1 | 13.20 ± 2.23 |
| pting | input-lanjian | 17.4 ± 0.6 | 16.5 | 20.6 | 13.91 ± 2.33 |
| pting | input-mattcl | 17.5 ± 0.7 | 16.4 | 21.0 | 13.92 ± 2.34 |
| pting | input-chancalan | 17.5 ± 0.7 | 16.5 | 20.8 | 13.93 ± 2.35 |
| pting | input-mikofo | 17.5 ± 0.7 | 16.3 | 20.9 | 13.95 ± 2.36 |
| pting | input-kcen | 17.6 ± 0.8 | 16.5 | 20.8 | 14.01 ± 2.39 |
| mattcl-py | input-mikofo | 17.7 ± 0.6 | 16.5 | 20.7 | 14.09 ± 2.35 |
| mattcl-py | input-chancalan | 17.7 ± 0.6 | 16.6 | 20.5 | 14.12 ± 2.36 |
| mattcl-py | input-mattcl | 17.7 ± 0.8 | 16.8 | 20.8 | 14.13 ± 2.40 |
| mattcl-py | input-kcen | 17.8 ± 0.8 | 16.3 | 20.9 | 14.17 ± 2.41 |
| mattcl-py | input-lanjian | 18.4 ± 5.3 | 16.4 | 65.9 | 14.66 ± 4.85 |
| chancalan | input-mattcl | 21.7 ± 0.8 | 20.7 | 24.9 | 17.31 ± 2.90 |
| chancalan | input-chancalan | 21.8 ± 0.8 | 20.5 | 25.5 | 17.37 ± 2.92 |
| chancalan | input-kcen | 21.8 ± 0.8 | 20.8 | 25.1 | 17.40 ± 2.91 |
| chancalan | input-mikofo | 21.9 ± 0.8 | 20.9 | 25.2 | 17.46 ± 2.94 |
| chancalan | input-lanjian | 21.9 ± 0.9 | 20.8 | 25.3 | 17.47 ± 2.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|