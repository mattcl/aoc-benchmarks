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
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.03 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.03 ± 0.32 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.32 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.2 | 1.05 ± 0.32 |
| lanjian | input-pting | 0.8 ± 0.1 | 0.3 | 1.3 | 1.06 ± 0.30 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.4 | 1.06 ± 0.34 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.2 | 1.0 | 1.07 ± 0.30 |
| lanjian | input-kcen | 0.8 ± 0.1 | 0.2 | 1.1 | 1.07 ± 0.31 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.2 | 1.5 | 1.07 ± 0.31 |
| mattcl-ts | input-mattcl | 12.4 ± 0.4 | 11.2 | 13.4 | 15.97 ± 3.77 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.8 | 13.7 | 16.21 ± 3.82 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 12.1 | 13.7 | 16.36 ± 3.86 |
| mattcl-ts | input-pting | 12.8 ± 0.4 | 11.9 | 13.6 | 16.48 ± 3.89 |
| mattcl-ts | input-lanjian | 13.6 ± 0.4 | 12.7 | 14.5 | 17.51 ± 4.14 |
| kcen | input-mattcl | 14.8 ± 0.5 | 13.7 | 17.5 | 18.99 ± 4.51 |
| kcen | input-chancalan | 15.0 ± 0.6 | 13.9 | 17.9 | 19.32 ± 4.60 |
| chancalan | input-mattcl | 15.1 ± 0.5 | 14.1 | 17.6 | 19.40 ± 4.60 |
| pting | input-mattcl | 15.1 ± 0.7 | 14.0 | 18.3 | 19.42 ± 4.64 |
| kcen | input-kcen | 15.1 ± 0.6 | 14.1 | 18.2 | 19.46 ± 4.63 |
| pting | input-chancalan | 15.2 ± 0.5 | 14.3 | 18.2 | 19.50 ± 4.61 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.2 | 18.5 | 19.53 ± 4.65 |
| kcen | input-pting | 15.2 ± 2.1 | 14.0 | 43.2 | 19.60 ± 5.31 |
| chancalan | input-chancalan | 15.4 ± 0.6 | 14.5 | 18.5 | 19.81 ± 4.71 |
| pting | input-pting | 15.7 ± 0.8 | 14.5 | 19.1 | 20.17 ± 4.83 |
| mattcl-py | input-chancalan | 15.7 ± 0.7 | 14.6 | 18.5 | 20.19 ± 4.81 |
| chancalan | input-pting | 15.9 ± 0.7 | 14.7 | 18.6 | 20.44 ± 4.88 |
| pting | input-kcen | 16.0 ± 0.8 | 14.8 | 19.2 | 20.54 ± 4.92 |
| mattcl-py | input-pting | 16.0 ± 0.8 | 14.8 | 19.2 | 20.59 ± 4.93 |
| kcen | input-lanjian | 16.1 ± 0.7 | 14.9 | 18.9 | 20.70 ± 4.94 |
| chancalan | input-kcen | 16.1 ± 0.7 | 14.9 | 18.7 | 20.73 ± 4.94 |
| mattcl-py | input-kcen | 16.1 ± 0.8 | 14.9 | 19.6 | 20.73 ± 4.98 |
| pting | input-lanjian | 17.0 ± 0.5 | 16.2 | 19.5 | 21.84 ± 5.16 |
| chancalan | input-lanjian | 17.3 ± 0.8 | 16.2 | 20.5 | 22.28 ± 5.32 |
| mattcl-py | input-lanjian | 17.7 ± 0.8 | 16.8 | 23.2 | 22.74 ± 5.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|