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
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.3 | 1.4 | 1.00 |
| lanjian | input-mikofo | 1.0 ± 0.2 | 0.5 | 1.6 | 1.06 ± 0.29 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.7 | 1.07 ± 0.29 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.7 | 1.07 ± 0.31 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.7 | 1.07 ± 0.30 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.4 | 1.2 | 1.08 ± 0.28 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.7 | 1.08 ± 0.31 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 1.10 ± 0.30 |
| lanjian | input-chancalan | 1.0 ± 0.1 | 0.3 | 1.5 | 1.10 ± 0.29 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.12 ± 0.31 |
| mattcl-ts | input-mikofo | 12.7 ± 0.3 | 11.7 | 13.5 | 13.50 ± 3.07 |
| mattcl-ts | input-mattcl | 12.7 ± 0.4 | 11.6 | 14.3 | 13.55 ± 3.09 |
| mattcl-ts | input-chancalan | 12.9 ± 0.4 | 12.1 | 14.5 | 13.74 ± 3.13 |
| mattcl-ts | input-kcen | 13.1 ± 0.4 | 12.2 | 14.5 | 13.92 ± 3.17 |
| mattcl-ts | input-lanjian | 14.0 ± 0.4 | 13.0 | 15.2 | 14.86 ± 3.38 |
| kcen | input-mikofo | 15.1 ± 0.6 | 14.2 | 17.7 | 16.00 ± 3.67 |
| kcen | input-mattcl | 15.1 ± 0.5 | 13.9 | 18.3 | 16.03 ± 3.67 |
| kcen | input-chancalan | 15.2 ± 0.5 | 14.3 | 17.7 | 16.15 ± 3.69 |
| pting | input-mikofo | 15.3 ± 0.5 | 14.3 | 18.2 | 16.21 ± 3.71 |
| pting | input-mattcl | 15.3 ± 0.6 | 14.0 | 18.8 | 16.24 ± 3.73 |
| chancalan | input-mikofo | 15.4 ± 0.7 | 14.2 | 18.7 | 16.38 ± 3.77 |
| chancalan | input-mattcl | 15.4 ± 0.7 | 14.5 | 18.9 | 16.40 ± 3.77 |
| mattcl-py | input-mattcl | 15.5 ± 0.7 | 14.5 | 18.8 | 16.51 ± 3.81 |
| mattcl-py | input-mikofo | 15.6 ± 0.7 | 14.2 | 18.7 | 16.54 ± 3.80 |
| kcen | input-kcen | 15.6 ± 0.7 | 14.4 | 19.2 | 16.55 ± 3.82 |
| chancalan | input-chancalan | 15.8 ± 0.7 | 14.5 | 19.5 | 16.74 ± 3.86 |
| pting | input-chancalan | 15.8 ± 2.6 | 14.4 | 49.3 | 16.76 ± 4.66 |
| mattcl-py | input-chancalan | 16.1 ± 0.7 | 14.6 | 18.7 | 17.14 ± 3.95 |
| pting | input-kcen | 16.1 ± 0.7 | 14.9 | 19.5 | 17.16 ± 3.94 |
| mattcl-py | input-kcen | 16.3 ± 0.6 | 15.0 | 19.1 | 17.33 ± 3.97 |
| kcen | input-lanjian | 16.4 ± 0.7 | 15.1 | 19.4 | 17.38 ± 3.99 |
| chancalan | input-kcen | 16.4 ± 0.6 | 15.2 | 19.4 | 17.39 ± 3.99 |
| pting | input-lanjian | 17.3 ± 0.6 | 16.4 | 20.3 | 18.43 ± 4.22 |
| chancalan | input-lanjian | 17.6 ± 0.7 | 16.2 | 20.7 | 18.67 ± 4.28 |
| mattcl-py | input-lanjian | 18.3 ± 2.7 | 16.6 | 51.2 | 19.47 ± 5.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|