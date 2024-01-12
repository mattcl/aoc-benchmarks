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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.29 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.3 | 1.4 | 1.02 ± 0.29 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.28 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.4 | 1.1 | 1.02 ± 0.28 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.29 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.4 | 1.05 ± 0.30 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.5 | 1.07 ± 0.30 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.4 | 1.07 ± 0.28 |
| lanjian | input-mattcl | 1.0 ± 0.1 | 0.3 | 1.1 | 1.08 ± 0.26 |
| mattcl-ts | input-mattcl | 12.6 ± 0.4 | 11.6 | 13.8 | 13.82 ± 2.88 |
| mattcl-ts | input-mikofo | 12.7 ± 0.4 | 11.5 | 13.9 | 13.87 ± 2.89 |
| mattcl-ts | input-chancalan | 12.8 ± 0.4 | 11.9 | 13.8 | 14.01 ± 2.92 |
| mattcl-ts | input-kcen | 13.0 ± 0.4 | 12.1 | 13.9 | 14.24 ± 2.97 |
| mattcl-ts | input-lanjian | 14.0 ± 0.4 | 13.0 | 15.0 | 15.29 ± 3.18 |
| kcen | input-mattcl | 15.0 ± 0.5 | 13.9 | 17.8 | 16.47 ± 3.44 |
| kcen | input-mikofo | 15.1 ± 0.7 | 13.9 | 18.1 | 16.53 ± 3.49 |
| kcen | input-chancalan | 15.2 ± 0.7 | 14.1 | 18.7 | 16.66 ± 3.51 |
| pting | input-mikofo | 15.2 ± 0.6 | 14.0 | 17.7 | 16.68 ± 3.49 |
| pting | input-mattcl | 15.2 ± 0.7 | 14.2 | 18.6 | 16.71 ± 3.52 |
| kcen | input-kcen | 15.3 ± 0.6 | 14.3 | 18.0 | 16.79 ± 3.52 |
| chancalan | input-mikofo | 15.3 ± 0.5 | 14.3 | 17.9 | 16.80 ± 3.52 |
| mattcl-py | input-mikofo | 15.5 ± 0.6 | 14.2 | 19.7 | 16.95 ± 3.56 |
| mattcl-py | input-mattcl | 15.5 ± 0.7 | 14.5 | 18.6 | 17.00 ± 3.58 |
| pting | input-chancalan | 15.6 ± 0.7 | 14.4 | 18.6 | 17.13 ± 3.61 |
| chancalan | input-chancalan | 15.7 ± 0.6 | 14.4 | 19.0 | 17.22 ± 3.62 |
| chancalan | input-mattcl | 16.0 ± 5.0 | 14.2 | 67.3 | 17.49 ± 6.53 |
| mattcl-py | input-chancalan | 16.2 ± 0.9 | 14.9 | 19.6 | 17.71 ± 3.77 |
| pting | input-kcen | 16.2 ± 0.6 | 15.0 | 18.8 | 17.78 ± 3.73 |
| kcen | input-lanjian | 16.3 ± 0.6 | 15.0 | 19.6 | 17.82 ± 3.73 |
| chancalan | input-kcen | 16.4 ± 0.7 | 15.0 | 19.6 | 17.94 ± 3.77 |
| mattcl-py | input-kcen | 16.4 ± 0.8 | 14.9 | 19.4 | 18.00 ± 3.81 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.2 | 20.2 | 19.07 ± 4.00 |
| chancalan | input-lanjian | 17.6 ± 0.8 | 16.4 | 20.9 | 19.26 ± 4.06 |
| mattcl-py | input-lanjian | 17.9 ± 0.8 | 17.1 | 20.8 | 19.66 ± 4.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|