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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.5 | 1.2 | 1.00 ± 0.22 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.9 | 1.01 ± 0.27 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.6 | 1.6 | 1.04 ± 0.20 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.0 | 1.38 ± 0.31 |
| lanjian | input-chancalan | 1.4 ± 0.2 | 0.6 | 2.2 | 1.38 ± 0.32 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.4 | 2.2 | 1.40 ± 0.34 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.7 | 2.2 | 1.41 ± 0.33 |
| lanjian | input-kcen | 1.4 ± 0.2 | 1.0 | 2.1 | 1.43 ± 0.32 |
| mikofo | input-chancalan | 12.8 ± 0.3 | 11.8 | 13.8 | 12.86 ± 2.17 |
| mattcl-ts | input-lanjian | 12.9 ± 0.3 | 12.1 | 13.8 | 12.93 ± 2.18 |
| mikofo | input-mattcl | 12.9 ± 0.4 | 12.0 | 14.2 | 12.93 ± 2.19 |
| mikofo | input-mikofo | 12.9 ± 0.4 | 11.5 | 13.8 | 12.96 ± 2.20 |
| mikofo | input-lanjian | 12.9 ± 0.4 | 11.8 | 13.8 | 12.96 ± 2.19 |
| mikofo | input-kcen | 12.9 ± 0.3 | 12.1 | 13.9 | 12.97 ± 2.19 |
| mattcl-ts | input-kcen | 12.9 ± 0.4 | 12.0 | 14.0 | 12.98 ± 2.20 |
| mattcl-ts | input-mattcl | 12.9 ± 0.4 | 12.1 | 14.0 | 13.00 ± 2.20 |
| mattcl-ts | input-mikofo | 13.0 ± 0.4 | 12.1 | 14.6 | 13.06 ± 2.21 |
| mattcl-ts | input-chancalan | 13.0 ± 0.4 | 12.0 | 13.9 | 13.08 ± 2.21 |
| kcen | input-lanjian | 16.3 ± 0.4 | 15.4 | 18.8 | 16.33 ± 2.76 |
| kcen | input-mattcl | 16.4 ± 0.6 | 15.0 | 19.5 | 16.43 ± 2.81 |
| kcen | input-chancalan | 16.4 ± 0.7 | 15.4 | 19.5 | 16.50 ± 2.83 |
| kcen | input-mikofo | 16.5 ± 0.7 | 15.6 | 20.2 | 16.56 ± 2.85 |
| kcen | input-kcen | 16.9 ± 5.2 | 15.0 | 72.0 | 16.98 ± 5.92 |
| pting | input-chancalan | 17.3 ± 0.6 | 16.5 | 20.1 | 17.42 ± 2.96 |
| pting | input-mikofo | 17.4 ± 0.5 | 16.5 | 20.3 | 17.50 ± 2.97 |
| pting | input-lanjian | 17.5 ± 0.8 | 16.4 | 20.9 | 17.56 ± 3.03 |
| pting | input-mattcl | 17.5 ± 0.8 | 16.4 | 20.8 | 17.56 ± 3.03 |
| mattcl-py | input-mikofo | 17.5 ± 0.5 | 16.4 | 20.6 | 17.58 ± 2.98 |
| pting | input-kcen | 17.5 ± 0.8 | 16.2 | 20.5 | 17.58 ± 3.04 |
| mattcl-py | input-lanjian | 17.6 ± 0.6 | 16.5 | 21.1 | 17.64 ± 3.01 |
| mattcl-py | input-chancalan | 17.6 ± 0.7 | 16.8 | 20.8 | 17.69 ± 3.03 |
| mattcl-py | input-kcen | 17.6 ± 0.7 | 16.7 | 20.8 | 17.72 ± 3.04 |
| mattcl-py | input-mattcl | 17.6 ± 0.7 | 16.5 | 21.0 | 17.73 ± 3.04 |
| chancalan | input-mattcl | 21.7 ± 0.8 | 20.7 | 24.4 | 21.82 ± 3.73 |
| chancalan | input-lanjian | 21.7 ± 0.7 | 20.8 | 24.5 | 21.84 ± 3.70 |
| chancalan | input-chancalan | 21.9 ± 0.8 | 20.8 | 25.4 | 21.97 ± 3.76 |
| chancalan | input-mikofo | 22.0 ± 0.8 | 21.0 | 25.6 | 22.07 ± 3.76 |
| chancalan | input-kcen | 22.3 ± 3.9 | 20.4 | 57.0 | 22.41 ± 5.40 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-mikofo|<pre>528819</pre>|<pre>80403602</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|