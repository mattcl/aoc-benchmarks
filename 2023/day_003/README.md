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
| mattcl | input-mikofo | 1.2 ± 0.2 | 0.5 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.24 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.6 | 1.02 ± 0.23 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.8 | 1.7 | 1.03 ± 0.21 |
| mattcl | input-chancalan | 1.2 ± 0.1 | 0.6 | 1.7 | 1.05 ± 0.21 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.6 | 2.1 | 1.17 ± 0.27 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.5 | 2.2 | 1.18 ± 0.28 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.6 | 2.0 | 1.18 ± 0.26 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 1.8 | 1.22 ± 0.27 |
| lanjian | input-chancalan | 1.5 ± 0.2 | 0.8 | 2.3 | 1.28 ± 0.28 |
| mikofo | input-chancalan | 12.7 ± 0.4 | 11.6 | 14.4 | 10.83 ± 1.86 |
| mikofo | input-mikofo | 12.8 ± 0.3 | 11.9 | 13.6 | 10.88 ± 1.86 |
| mattcl-ts | input-lanjian | 12.8 ± 0.4 | 11.7 | 13.9 | 10.88 ± 1.87 |
| mikofo | input-lanjian | 12.8 ± 0.3 | 12.2 | 13.7 | 10.91 ± 1.87 |
| mikofo | input-kcen | 12.8 ± 0.3 | 12.2 | 13.7 | 10.91 ± 1.87 |
| mikofo | input-mattcl | 12.8 ± 0.3 | 12.0 | 14.9 | 10.91 ± 1.87 |
| mattcl-ts | input-mikofo | 12.8 ± 0.3 | 12.1 | 13.7 | 10.92 ± 1.87 |
| mattcl-ts | input-chancalan | 12.8 ± 0.4 | 11.8 | 13.9 | 10.93 ± 1.88 |
| mattcl-ts | input-mattcl | 12.9 ± 0.4 | 11.9 | 14.0 | 10.96 ± 1.88 |
| mattcl-ts | input-kcen | 12.9 ± 0.4 | 11.9 | 13.8 | 10.97 ± 1.89 |
| kcen | input-mikofo | 16.4 ± 0.6 | 15.2 | 19.5 | 13.95 ± 2.42 |
| kcen | input-kcen | 16.4 ± 0.7 | 15.1 | 19.7 | 13.96 ± 2.43 |
| kcen | input-lanjian | 16.4 ± 0.6 | 15.5 | 19.3 | 13.99 ± 2.42 |
| kcen | input-chancalan | 16.5 ± 0.6 | 15.0 | 18.8 | 14.02 ± 2.43 |
| kcen | input-mattcl | 16.5 ± 0.8 | 15.0 | 19.4 | 14.05 ± 2.47 |
| pting | input-mattcl | 17.3 ± 0.5 | 16.1 | 20.1 | 14.71 ± 2.53 |
| pting | input-mikofo | 17.4 ± 0.6 | 16.4 | 20.3 | 14.84 ± 2.57 |
| pting | input-lanjian | 17.5 ± 0.6 | 16.4 | 20.4 | 14.87 ± 2.58 |
| pting | input-chancalan | 17.5 ± 0.7 | 16.3 | 20.6 | 14.87 ± 2.59 |
| pting | input-kcen | 17.6 ± 0.7 | 16.2 | 20.7 | 14.97 ± 2.62 |
| mattcl-py | input-mattcl | 17.6 ± 0.6 | 16.9 | 20.7 | 15.00 ± 2.60 |
| mattcl-py | input-chancalan | 17.6 ± 0.7 | 16.7 | 21.5 | 15.01 ± 2.62 |
| mattcl-py | input-kcen | 17.6 ± 0.7 | 16.5 | 20.4 | 15.03 ± 2.61 |
| mattcl-py | input-lanjian | 17.7 ± 0.8 | 16.2 | 20.7 | 15.08 ± 2.65 |
| mattcl-py | input-mikofo | 17.7 ± 0.7 | 16.9 | 20.8 | 15.09 ± 2.63 |
| chancalan | input-mattcl | 21.7 ± 0.9 | 20.7 | 25.3 | 18.52 ± 3.22 |
| chancalan | input-kcen | 21.8 ± 0.8 | 20.4 | 24.6 | 18.53 ± 3.22 |
| chancalan | input-chancalan | 21.8 ± 0.7 | 20.6 | 25.2 | 18.55 ± 3.20 |
| chancalan | input-mikofo | 21.8 ± 0.7 | 20.3 | 25.2 | 18.56 ± 3.21 |
| chancalan | input-lanjian | 21.8 ± 0.8 | 20.7 | 25.4 | 18.58 ± 3.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|