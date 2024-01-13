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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.4 | 1.3 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.8 | 1.00 ± 0.23 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.23 |
| mattcl | input-mattcl | 1.1 ± 0.1 | 0.3 | 1.6 | 1.03 ± 0.21 |
| mattcl | input-mikofo | 1.1 ± 0.1 | 0.5 | 1.3 | 1.04 ± 0.20 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.9 | 1.7 | 1.35 ± 0.27 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 0.9 | 2.3 | 1.42 ± 0.30 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.9 | 2.1 | 1.42 ± 0.30 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 0.9 | 2.2 | 1.46 ± 0.30 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.8 | 2.3 | 1.48 ± 0.31 |
| mikofo | input-lanjian | 12.6 ± 0.3 | 11.6 | 13.9 | 12.20 ± 1.89 |
| mikofo | input-kcen | 12.7 ± 0.3 | 11.8 | 13.5 | 12.23 ± 1.90 |
| mikofo | input-mattcl | 12.7 ± 0.4 | 11.8 | 14.5 | 12.27 ± 1.92 |
| mikofo | input-chancalan | 12.7 ± 0.3 | 11.8 | 13.8 | 12.27 ± 1.91 |
| mikofo | input-mikofo | 12.7 ± 0.3 | 11.9 | 13.7 | 12.28 ± 1.91 |
| mattcl-ts | input-lanjian | 12.7 ± 0.3 | 12.0 | 13.9 | 12.28 ± 1.91 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 11.9 | 13.7 | 12.28 ± 1.91 |
| mattcl-ts | input-chancalan | 12.8 ± 0.4 | 11.8 | 14.0 | 12.32 ± 1.92 |
| mattcl-ts | input-kcen | 12.8 ± 0.3 | 11.9 | 14.1 | 12.33 ± 1.92 |
| mattcl-ts | input-mikofo | 12.8 ± 0.4 | 12.1 | 13.7 | 12.35 ± 1.93 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.2 | 19.5 | 15.71 ± 2.50 |
| kcen | input-kcen | 16.3 ± 0.7 | 15.0 | 19.5 | 15.76 ± 2.52 |
| kcen | input-mikofo | 16.3 ± 0.7 | 15.0 | 19.7 | 15.77 ± 2.52 |
| kcen | input-mattcl | 16.3 ± 0.8 | 15.0 | 19.4 | 15.77 ± 2.53 |
| kcen | input-chancalan | 16.5 ± 0.8 | 15.2 | 19.3 | 15.87 ± 2.55 |
| pting | input-mattcl | 17.3 ± 0.9 | 16.2 | 20.7 | 16.70 ± 2.69 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.1 | 20.7 | 16.73 ± 2.67 |
| pting | input-chancalan | 17.4 ± 0.8 | 16.0 | 20.7 | 16.74 ± 2.70 |
| pting | input-kcen | 17.4 ± 0.8 | 16.1 | 21.1 | 16.74 ± 2.69 |
| pting | input-mikofo | 17.4 ± 0.8 | 16.1 | 20.7 | 16.82 ± 2.69 |
| mattcl-py | input-lanjian | 17.5 ± 0.6 | 16.6 | 20.6 | 16.88 ± 2.65 |
| mattcl-py | input-kcen | 17.5 ± 0.6 | 16.7 | 20.4 | 16.88 ± 2.65 |
| mattcl-py | input-mattcl | 17.5 ± 0.6 | 16.5 | 20.8 | 16.89 ± 2.66 |
| mattcl-py | input-mikofo | 17.5 ± 0.6 | 16.5 | 20.7 | 16.92 ± 2.66 |
| mattcl-py | input-chancalan | 17.8 ± 2.5 | 16.6 | 48.4 | 17.17 ± 3.58 |
| chancalan | input-mattcl | 21.5 ± 0.6 | 20.6 | 24.4 | 20.70 ± 3.23 |
| chancalan | input-lanjian | 21.5 ± 0.5 | 20.7 | 24.4 | 20.74 ± 3.22 |
| chancalan | input-chancalan | 21.5 ± 0.6 | 20.9 | 24.3 | 20.76 ± 3.24 |
| chancalan | input-mikofo | 21.5 ± 0.7 | 20.7 | 24.4 | 20.78 ± 3.25 |
| chancalan | input-kcen | 21.6 ± 0.7 | 20.4 | 24.4 | 20.82 ± 3.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|