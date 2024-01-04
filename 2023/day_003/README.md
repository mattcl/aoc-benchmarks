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
| mattcl | input-mikofo | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.23 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.22 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.9 | 1.02 ± 0.26 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.7 | 1.04 ± 0.21 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.7 | 2.0 | 1.17 ± 0.25 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.5 | 1.9 | 1.17 ± 0.26 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.6 | 2.0 | 1.20 ± 0.26 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.1 | 1.20 ± 0.26 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.0 | 1.24 ± 0.26 |
| mattcl-ts | input-lanjian | 12.5 ± 0.4 | 11.6 | 13.7 | 10.78 ± 1.73 |
| mikofo | input-mattcl | 12.5 ± 0.3 | 11.5 | 13.5 | 10.78 ± 1.73 |
| mattcl-ts | input-chancalan | 12.5 ± 0.4 | 11.5 | 14.1 | 10.79 ± 1.74 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.6 | 13.7 | 10.79 ± 1.74 |
| mattcl-ts | input-kcen | 12.5 ± 0.4 | 11.4 | 13.4 | 10.79 ± 1.74 |
| mikofo | input-lanjian | 12.5 ± 0.3 | 11.3 | 13.2 | 10.81 ± 1.73 |
| mattcl-ts | input-mikofo | 12.5 ± 0.3 | 11.8 | 13.2 | 10.82 ± 1.74 |
| mikofo | input-chancalan | 12.5 ± 0.3 | 11.6 | 13.2 | 10.82 ± 1.73 |
| mikofo | input-mikofo | 12.5 ± 0.3 | 11.7 | 14.2 | 10.83 ± 1.74 |
| mikofo | input-kcen | 12.8 ± 3.6 | 11.2 | 51.5 | 11.08 ± 3.59 |
| kcen | input-mattcl | 16.1 ± 0.5 | 14.9 | 19.0 | 13.93 ± 2.25 |
| kcen | input-lanjian | 16.1 ± 0.6 | 15.1 | 18.9 | 13.93 ± 2.27 |
| kcen | input-chancalan | 16.1 ± 0.7 | 15.0 | 19.5 | 13.95 ± 2.28 |
| kcen | input-mikofo | 16.2 ± 0.7 | 15.1 | 18.9 | 13.99 ± 2.30 |
| kcen | input-kcen | 16.2 ± 0.7 | 15.4 | 19.4 | 14.04 ± 2.31 |
| pting | input-chancalan | 17.1 ± 0.6 | 16.2 | 20.1 | 14.73 ± 2.40 |
| pting | input-mattcl | 17.1 ± 0.7 | 16.1 | 20.6 | 14.76 ± 2.42 |
| pting | input-kcen | 17.1 ± 0.7 | 15.9 | 20.6 | 14.80 ± 2.43 |
| pting | input-lanjian | 17.1 ± 0.7 | 15.8 | 20.8 | 14.80 ± 2.42 |
| pting | input-mikofo | 17.1 ± 0.7 | 16.4 | 20.7 | 14.81 ± 2.43 |
| mattcl-py | input-lanjian | 17.4 ± 0.6 | 16.4 | 20.9 | 15.00 ± 2.43 |
| mattcl-py | input-mattcl | 17.5 ± 0.7 | 16.5 | 21.6 | 15.10 ± 2.46 |
| mattcl-py | input-chancalan | 17.5 ± 0.7 | 16.5 | 20.7 | 15.11 ± 2.46 |
| mattcl-py | input-mikofo | 17.5 ± 0.8 | 16.4 | 20.8 | 15.14 ± 2.48 |
| mattcl-py | input-kcen | 17.5 ± 0.7 | 16.3 | 21.0 | 15.14 ± 2.48 |
| chancalan | input-mattcl | 21.2 ± 0.6 | 20.3 | 24.8 | 18.35 ± 2.96 |
| chancalan | input-chancalan | 21.4 ± 0.7 | 20.1 | 24.4 | 18.46 ± 2.99 |
| chancalan | input-kcen | 21.4 ± 0.7 | 20.4 | 24.6 | 18.50 ± 3.00 |
| chancalan | input-lanjian | 21.4 ± 0.7 | 20.5 | 24.1 | 18.50 ± 2.99 |
| chancalan | input-mikofo | 21.4 ± 0.7 | 20.2 | 24.6 | 18.53 ± 3.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|