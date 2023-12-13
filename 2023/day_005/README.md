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
| lanjian | input-kcen | 0.9 ± 0.2 | 0.3 | 1.7 | 1.00 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.34 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.1 | 1.04 ± 0.30 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 1.05 ± 0.31 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.5 | 1.1 | 1.06 ± 0.29 |
| lanjian | input-pting | 0.9 ± 0.1 | 0.3 | 1.5 | 1.07 ± 0.30 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.5 | 1.1 | 1.08 ± 0.28 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.4 | 1.08 ± 0.31 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.4 | 1.1 | 1.10 ± 0.31 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.4 | 13.5 | 14.25 ± 3.41 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.7 | 13.7 | 14.48 ± 3.46 |
| mattcl-ts | input-pting | 12.8 ± 0.3 | 11.9 | 13.8 | 14.64 ± 3.50 |
| mattcl-ts | input-kcen | 12.8 ± 0.3 | 12.0 | 13.7 | 14.66 ± 3.50 |
| mattcl-ts | input-lanjian | 13.7 ± 0.3 | 12.8 | 15.5 | 15.63 ± 3.73 |
| kcen | input-mattcl | 15.1 ± 0.5 | 14.2 | 17.6 | 17.24 ± 4.14 |
| pting | input-mattcl | 15.2 ± 0.6 | 14.0 | 17.9 | 17.40 ± 4.18 |
| kcen | input-chancalan | 15.2 ± 0.6 | 14.1 | 18.2 | 17.41 ± 4.19 |
| kcen | input-pting | 15.3 ± 0.8 | 14.1 | 19.4 | 17.50 ± 4.25 |
| chancalan | input-mattcl | 15.3 ± 0.5 | 14.5 | 18.1 | 17.54 ± 4.20 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.3 | 18.3 | 17.65 ± 4.24 |
| pting | input-chancalan | 15.7 ± 0.7 | 14.4 | 18.5 | 17.91 ± 4.33 |
| chancalan | input-chancalan | 15.7 ± 0.7 | 14.4 | 18.7 | 18.00 ± 4.36 |
| pting | input-pting | 15.9 ± 0.7 | 14.7 | 20.2 | 18.14 ± 4.38 |
| kcen | input-kcen | 15.9 ± 4.4 | 14.2 | 57.1 | 18.24 ± 6.61 |
| mattcl-py | input-chancalan | 16.0 ± 0.6 | 14.8 | 18.7 | 18.26 ± 4.39 |
| chancalan | input-pting | 16.0 ± 0.6 | 14.8 | 19.1 | 18.30 ± 4.41 |
| pting | input-kcen | 16.0 ± 0.6 | 14.8 | 18.9 | 18.34 ± 4.40 |
| mattcl-py | input-pting | 16.2 ± 0.7 | 15.0 | 18.9 | 18.50 ± 4.46 |
| mattcl-py | input-kcen | 16.2 ± 0.6 | 14.9 | 18.9 | 18.57 ± 4.47 |
| chancalan | input-kcen | 16.4 ± 0.8 | 15.2 | 19.8 | 18.70 ± 4.53 |
| kcen | input-lanjian | 16.4 ± 0.6 | 15.3 | 20.0 | 18.72 ± 4.51 |
| chancalan | input-lanjian | 17.6 ± 0.6 | 16.7 | 20.3 | 20.08 ± 4.81 |
| pting | input-lanjian | 17.6 ± 3.5 | 16.0 | 61.5 | 20.14 ± 6.21 |
| mattcl-py | input-lanjian | 17.9 ± 0.7 | 16.8 | 20.8 | 20.48 ± 4.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|