# Day 5 benchmarks

[link to problem](https://adventofcode.com/2023/day/5)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 5)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.10 ± 0.47 |
| lanjian | input-mattcl | 0.8 ± 2.7 | 0.1 | 39.1 | 1.15 ± 3.79 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.15 ± 0.45 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.16 ± 0.45 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.4 | 1.17 ± 0.45 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.3 | 1.2 | 1.18 ± 0.44 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.1 | 1.19 ± 0.44 |
| lanjian | input-pting | 0.9 ± 0.1 | 0.2 | 1.0 | 1.19 ± 0.44 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.4 | 1.23 ± 0.46 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.6 | 13.5 | 17.26 ± 5.73 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.9 | 13.8 | 17.48 ± 5.80 |
| mattcl-ts | input-kcen | 12.8 ± 0.3 | 12.1 | 13.6 | 17.67 ± 5.85 |
| mattcl-ts | input-pting | 12.8 ± 0.3 | 12.1 | 13.7 | 17.71 ± 5.87 |
| mattcl-ts | input-lanjian | 13.7 ± 0.4 | 12.9 | 15.0 | 18.95 ± 6.28 |
| kcen | input-mattcl | 14.7 ± 0.6 | 13.7 | 18.2 | 20.34 ± 6.77 |
| pting | input-mattcl | 15.1 ± 0.6 | 14.0 | 17.7 | 20.80 ± 6.92 |
| kcen | input-chancalan | 15.1 ± 0.8 | 13.9 | 18.2 | 20.81 ± 6.96 |
| kcen | input-kcen | 15.2 ± 0.6 | 14.1 | 18.4 | 20.92 ± 6.96 |
| chancalan | input-mattcl | 15.2 ± 0.7 | 14.1 | 18.2 | 21.01 ± 7.01 |
| pting | input-chancalan | 15.3 ± 0.6 | 14.2 | 18.6 | 21.11 ± 7.02 |
| kcen | input-pting | 15.4 ± 3.1 | 14.1 | 57.0 | 21.24 ± 8.23 |
| chancalan | input-chancalan | 15.5 ± 0.6 | 14.4 | 18.4 | 21.32 ± 7.10 |
| pting | input-pting | 15.6 ± 0.7 | 14.8 | 18.8 | 21.53 ± 7.18 |
| mattcl-py | input-mattcl | 15.7 ± 4.8 | 14.2 | 73.5 | 21.67 ± 9.77 |
| chancalan | input-pting | 15.8 ± 0.7 | 14.7 | 19.4 | 21.85 ± 7.29 |
| pting | input-kcen | 15.9 ± 0.6 | 14.9 | 18.7 | 21.86 ± 7.28 |
| mattcl-py | input-chancalan | 15.9 ± 0.9 | 14.7 | 19.4 | 21.91 ± 7.34 |
| mattcl-py | input-pting | 16.0 ± 0.6 | 14.9 | 18.9 | 22.05 ± 7.34 |
| kcen | input-lanjian | 16.1 ± 0.7 | 15.0 | 19.0 | 22.16 ± 7.38 |
| chancalan | input-kcen | 16.2 ± 0.6 | 14.9 | 19.3 | 22.29 ± 7.42 |
| mattcl-py | input-kcen | 16.2 ± 0.8 | 15.0 | 19.5 | 22.39 ± 7.48 |
| pting | input-lanjian | 17.0 ± 0.7 | 15.9 | 20.4 | 23.48 ± 7.82 |
| chancalan | input-lanjian | 17.3 ± 0.6 | 16.1 | 20.2 | 23.87 ± 7.93 |
| mattcl-py | input-lanjian | 17.7 ± 0.7 | 16.7 | 20.8 | 24.39 ± 8.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|