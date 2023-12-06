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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.4 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.3 | 1.04 ± 0.26 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.8 | 1.06 ± 0.26 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.5 | 1.6 | 1.07 ± 0.25 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.8 | 1.08 ± 0.27 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.8 | 1.24 ± 0.30 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.5 | 1.8 | 1.27 ± 0.31 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.7 | 2.0 | 1.28 ± 0.30 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.7 | 1.29 ± 0.31 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.7 | 1.9 | 1.33 ± 0.32 |
| mattcl-ts | input-chancalan | 12.1 ± 0.4 | 11.2 | 13.3 | 11.96 ± 2.28 |
| mattcl-ts | input-kcen | 12.1 ± 0.3 | 11.3 | 12.9 | 11.98 ± 2.28 |
| mattcl-ts | input-mattcl | 12.2 ± 0.4 | 11.2 | 13.4 | 12.03 ± 2.29 |
| mattcl-ts | input-pting | 12.4 ± 3.3 | 11.0 | 58.4 | 12.25 ± 3.99 |
| mattcl-ts | input-lanjian | 12.5 ± 3.9 | 11.5 | 66.9 | 12.34 ± 4.49 |
| kcen | input-kcen | 16.2 ± 0.5 | 15.1 | 18.6 | 15.99 ± 3.05 |
| kcen | input-pting | 16.2 ± 0.6 | 15.1 | 19.3 | 16.00 ± 3.07 |
| kcen | input-mattcl | 16.2 ± 0.7 | 15.1 | 18.9 | 16.00 ± 3.08 |
| kcen | input-lanjian | 16.2 ± 0.6 | 15.2 | 18.9 | 16.01 ± 3.06 |
| kcen | input-chancalan | 16.2 ± 0.6 | 15.0 | 18.7 | 16.02 ± 3.07 |
| mattcl-py | input-kcen | 17.4 ± 0.7 | 16.3 | 20.6 | 17.21 ± 3.31 |
| mattcl-py | input-lanjian | 17.4 ± 0.7 | 16.2 | 20.3 | 17.24 ± 3.32 |
| mattcl-py | input-chancalan | 17.5 ± 0.7 | 16.4 | 20.7 | 17.27 ± 3.33 |
| mattcl-py | input-mattcl | 17.5 ± 0.7 | 16.4 | 20.6 | 17.29 ± 3.32 |
| mattcl-py | input-pting | 17.6 ± 0.8 | 16.5 | 21.3 | 17.38 ± 3.37 |
| pting | input-kcen | 18.4 ± 0.6 | 17.5 | 21.1 | 18.20 ± 3.47 |
| pting | input-mattcl | 18.4 ± 0.6 | 17.5 | 21.8 | 18.21 ± 3.48 |
| pting | input-lanjian | 18.5 ± 0.7 | 17.5 | 21.6 | 18.27 ± 3.50 |
| pting | input-chancalan | 18.5 ± 0.7 | 17.3 | 21.4 | 18.30 ± 3.51 |
| pting | input-pting | 18.6 ± 0.6 | 17.5 | 21.7 | 18.35 ± 3.51 |
| chancalan | input-kcen | 21.3 ± 0.6 | 20.6 | 24.5 | 21.11 ± 4.02 |
| chancalan | input-mattcl | 21.4 ± 0.7 | 20.2 | 24.3 | 21.16 ± 4.04 |
| chancalan | input-chancalan | 21.4 ± 0.7 | 20.5 | 25.4 | 21.18 ± 4.05 |
| chancalan | input-lanjian | 21.4 ± 0.7 | 20.3 | 24.1 | 21.19 ± 4.04 |
| chancalan | input-pting | 21.5 ± 0.6 | 20.5 | 24.9 | 21.24 ± 4.04 |
| mikofo | input-kcen | 31.3 ± 0.5 | 30.2 | 32.0 | 30.92 ± 5.83 |
| mikofo | input-chancalan | 31.3 ± 0.5 | 30.2 | 32.2 | 30.94 ± 5.84 |
| mikofo | input-mattcl | 31.4 ± 0.4 | 30.5 | 32.3 | 31.03 ± 5.85 |
| mikofo | input-pting | 31.4 ± 0.4 | 30.6 | 32.1 | 31.06 ± 5.85 |
| mikofo | input-lanjian | 31.5 ± 0.5 | 30.1 | 32.8 | 31.11 ± 5.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>538046</pre>|<pre>81709807</pre>|
|input-kcen|<pre>519444</pre>|<pre>74528807</pre>|
|input-lanjian|<pre>531561</pre>|<pre>83279367</pre>|
|input-mattcl|<pre>526404</pre>|<pre>84399773</pre>|
|input-pting|<pre>535078</pre>|<pre>75312571</pre>|