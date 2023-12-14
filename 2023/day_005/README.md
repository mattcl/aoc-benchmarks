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
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.5 | 1.00 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.2 | 1.01 ± 0.31 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.32 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.2 | 1.02 ± 0.28 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.04 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.32 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.4 | 1.1 | 1.05 ± 0.28 |
| lanjian | input-pting | 0.9 ± 0.1 | 0.2 | 1.3 | 1.06 ± 0.28 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.07 ± 0.30 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.4 | 13.2 | 14.85 ± 3.28 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.8 | 13.7 | 15.01 ± 3.31 |
| mattcl-ts | input-kcen | 12.8 ± 0.3 | 12.2 | 13.7 | 15.17 ± 3.34 |
| mattcl-ts | input-pting | 12.8 ± 0.4 | 12.0 | 14.0 | 15.23 ± 3.36 |
| mattcl-ts | input-lanjian | 13.7 ± 0.4 | 13.0 | 14.9 | 16.31 ± 3.60 |
| kcen | input-mattcl | 14.9 ± 0.8 | 13.8 | 18.5 | 17.67 ± 3.98 |
| kcen | input-chancalan | 15.0 ± 0.6 | 13.9 | 18.1 | 17.79 ± 3.96 |
| pting | input-mattcl | 15.1 ± 0.6 | 14.1 | 17.6 | 17.92 ± 3.98 |
| chancalan | input-mattcl | 15.1 ± 0.5 | 14.2 | 17.8 | 17.94 ± 3.97 |
| kcen | input-pting | 15.1 ± 0.6 | 13.9 | 17.7 | 17.94 ± 3.99 |
| mattcl-py | input-mattcl | 15.1 ± 0.4 | 14.3 | 17.6 | 17.95 ± 3.96 |
| kcen | input-kcen | 15.2 ± 0.6 | 14.0 | 18.3 | 18.04 ± 4.02 |
| pting | input-chancalan | 15.2 ± 0.6 | 14.2 | 18.6 | 18.09 ± 4.02 |
| pting | input-pting | 15.6 ± 0.7 | 14.5 | 18.4 | 18.53 ± 4.13 |
| chancalan | input-chancalan | 15.8 ± 3.3 | 14.4 | 58.7 | 18.71 ± 5.63 |
| chancalan | input-pting | 15.8 ± 0.6 | 14.7 | 18.2 | 18.75 ± 4.17 |
| mattcl-py | input-chancalan | 15.8 ± 0.8 | 14.9 | 19.2 | 18.77 ± 4.21 |
| pting | input-kcen | 16.0 ± 2.3 | 14.9 | 45.5 | 18.96 ± 4.95 |
| kcen | input-lanjian | 16.0 ± 0.6 | 15.0 | 19.1 | 19.01 ± 4.22 |
| mattcl-py | input-pting | 16.0 ± 1.7 | 14.8 | 38.2 | 19.04 ± 4.65 |
| mattcl-py | input-kcen | 16.0 ± 0.6 | 14.9 | 18.4 | 19.05 ± 4.22 |
| chancalan | input-kcen | 16.1 ± 0.7 | 14.9 | 18.8 | 19.12 ± 4.26 |
| pting | input-lanjian | 17.0 ± 0.6 | 15.8 | 20.3 | 20.15 ± 4.47 |
| chancalan | input-lanjian | 17.3 ± 0.7 | 16.2 | 20.4 | 20.51 ± 4.56 |
| mattcl-py | input-lanjian | 17.6 ± 0.6 | 16.8 | 20.9 | 20.90 ± 4.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|