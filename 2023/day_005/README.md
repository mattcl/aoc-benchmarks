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
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.35 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.34 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 1.06 ± 0.36 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.06 ± 0.34 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.1 | 1.08 ± 0.34 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.08 ± 0.34 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.0 | 1.08 ± 0.34 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.1 | 1.08 ± 0.35 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.14 ± 0.35 |
| mattcl-ts | input-mattcl | 12.4 ± 2.1 | 11.2 | 41.2 | 15.24 ± 4.71 |
| mattcl-ts | input-chancalan | 12.5 ± 0.4 | 11.5 | 13.7 | 15.35 ± 4.00 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.6 | 13.7 | 15.46 ± 4.03 |
| mattcl-ts | input-pting | 12.9 ± 3.1 | 11.7 | 56.5 | 15.85 ± 5.62 |
| mattcl-ts | input-lanjian | 13.5 ± 0.4 | 12.4 | 14.4 | 16.53 ± 4.31 |
| kcen | input-mattcl | 14.9 ± 0.6 | 13.8 | 17.6 | 18.30 ± 4.81 |
| kcen | input-chancalan | 15.0 ± 0.6 | 14.0 | 18.3 | 18.45 ± 4.83 |
| pting | input-mattcl | 15.1 ± 0.7 | 14.1 | 18.7 | 18.60 ± 4.89 |
| kcen | input-kcen | 15.2 ± 0.5 | 14.2 | 18.0 | 18.63 ± 4.87 |
| kcen | input-pting | 15.2 ± 0.5 | 14.3 | 17.7 | 18.64 ± 4.88 |
| chancalan | input-mattcl | 15.2 ± 0.5 | 14.3 | 17.4 | 18.71 ± 4.89 |
| pting | input-chancalan | 15.4 ± 0.7 | 14.2 | 18.5 | 18.92 ± 4.98 |
| mattcl-py | input-mattcl | 15.4 ± 2.0 | 14.5 | 41.6 | 18.94 ± 5.48 |
| chancalan | input-chancalan | 15.4 ± 0.6 | 14.5 | 18.2 | 18.97 ± 4.96 |
| pting | input-pting | 15.6 ± 0.6 | 14.7 | 18.6 | 19.18 ± 5.02 |
| mattcl-py | input-chancalan | 15.8 ± 0.7 | 14.7 | 18.6 | 19.39 ± 5.09 |
| mattcl-py | input-pting | 15.9 ± 0.7 | 15.0 | 18.9 | 19.60 ± 5.15 |
| chancalan | input-pting | 15.9 ± 0.8 | 14.8 | 19.4 | 19.60 ± 5.17 |
| pting | input-kcen | 16.0 ± 0.7 | 14.9 | 18.8 | 19.64 ± 5.15 |
| kcen | input-lanjian | 16.1 ± 0.7 | 15.0 | 19.4 | 19.74 ± 5.18 |
| chancalan | input-kcen | 16.1 ± 0.6 | 15.0 | 19.5 | 19.81 ± 5.19 |
| mattcl-py | input-kcen | 16.2 ± 0.7 | 15.0 | 18.7 | 19.90 ± 5.24 |
| pting | input-lanjian | 17.1 ± 0.6 | 15.8 | 19.9 | 21.03 ± 5.51 |
| chancalan | input-lanjian | 17.4 ± 0.7 | 16.4 | 20.5 | 21.39 ± 5.61 |
| mattcl-py | input-lanjian | 17.6 ± 0.6 | 16.7 | 20.6 | 21.68 ± 5.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|