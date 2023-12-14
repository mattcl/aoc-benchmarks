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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.31 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.33 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.2 | 1.1 | 1.06 ± 0.29 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.4 | 1.06 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.2 | 1.07 ± 0.33 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.3 | 1.1 | 1.07 ± 0.31 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.3 | 1.0 | 1.08 ± 0.29 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.4 | 1.6 | 1.08 ± 0.31 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.2 | 1.10 ± 0.29 |
| mattcl-ts | input-mattcl | 12.6 ± 0.4 | 11.3 | 13.8 | 15.72 ± 3.56 |
| mattcl-ts | input-chancalan | 12.8 ± 0.4 | 12.0 | 14.5 | 16.05 ± 3.63 |
| mattcl-ts | input-kcen | 13.0 ± 0.3 | 12.3 | 13.9 | 16.19 ± 3.65 |
| mattcl-ts | input-pting | 13.0 ± 0.4 | 11.9 | 13.9 | 16.22 ± 3.66 |
| mattcl-ts | input-lanjian | 13.9 ± 0.3 | 13.0 | 14.9 | 17.31 ± 3.90 |
| kcen | input-mattcl | 15.0 ± 0.7 | 13.9 | 17.9 | 18.75 ± 4.29 |
| kcen | input-chancalan | 15.1 ± 0.6 | 14.0 | 18.3 | 18.87 ± 4.29 |
| pting | input-mattcl | 15.1 ± 0.6 | 14.0 | 17.9 | 18.92 ± 4.29 |
| kcen | input-pting | 15.3 ± 0.6 | 14.2 | 18.2 | 19.06 ± 4.33 |
| chancalan | input-mattcl | 15.3 ± 0.6 | 14.0 | 17.9 | 19.07 ± 4.33 |
| kcen | input-kcen | 15.3 ± 0.6 | 14.1 | 18.1 | 19.14 ± 4.35 |
| mattcl-py | input-mattcl | 15.5 ± 0.7 | 14.3 | 18.3 | 19.42 ± 4.44 |
| chancalan | input-chancalan | 15.7 ± 0.8 | 14.6 | 19.3 | 19.66 ± 4.51 |
| pting | input-chancalan | 15.8 ± 3.7 | 14.4 | 56.1 | 19.75 ± 6.37 |
| pting | input-pting | 15.9 ± 0.7 | 14.9 | 19.1 | 19.89 ± 4.54 |
| mattcl-py | input-chancalan | 16.0 ± 0.6 | 14.8 | 19.3 | 19.94 ± 4.54 |
| chancalan | input-pting | 16.0 ± 0.6 | 14.7 | 19.0 | 19.97 ± 4.54 |
| pting | input-kcen | 16.1 ± 0.7 | 15.1 | 19.3 | 20.13 ± 4.59 |
| kcen | input-lanjian | 16.2 ± 0.6 | 14.8 | 19.1 | 20.18 ± 4.58 |
| mattcl-py | input-pting | 16.3 ± 0.7 | 15.0 | 19.3 | 20.33 ± 4.64 |
| mattcl-py | input-kcen | 16.3 ± 0.7 | 15.0 | 19.5 | 20.37 ± 4.66 |
| chancalan | input-kcen | 16.4 ± 3.3 | 14.9 | 60.3 | 20.54 ± 6.19 |
| pting | input-lanjian | 17.2 ± 0.7 | 15.9 | 20.2 | 21.43 ± 4.88 |
| chancalan | input-lanjian | 17.5 ± 0.8 | 16.2 | 20.6 | 21.83 ± 4.98 |
| mattcl-py | input-lanjian | 17.8 ± 0.6 | 16.5 | 20.8 | 22.19 ± 5.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|