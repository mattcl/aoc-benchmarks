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
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.2 | 1.00 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.3 | 1.01 ± 0.29 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.29 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.29 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.29 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.5 | 1.03 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.6 | 1.04 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.05 ± 0.30 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.06 ± 0.30 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.2 | 1.1 | 1.06 ± 0.28 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.8 | 13.8 | 15.00 ± 3.15 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.8 | 13.7 | 15.17 ± 3.18 |
| mattcl-ts | input-pting | 13.0 ± 0.4 | 12.1 | 14.3 | 15.46 ± 3.25 |
| mattcl-ts | input-kcen | 13.4 ± 3.0 | 12.1 | 41.9 | 15.93 ± 4.88 |
| mattcl-ts | input-lanjian | 13.8 ± 0.3 | 12.9 | 15.0 | 16.45 ± 3.45 |
| kcen | input-mattcl | 15.1 ± 0.7 | 14.2 | 19.2 | 17.95 ± 3.83 |
| pting | input-mattcl | 15.1 ± 0.5 | 13.9 | 18.2 | 17.97 ± 3.78 |
| kcen | input-chancalan | 15.1 ± 0.6 | 13.9 | 18.1 | 18.00 ± 3.81 |
| kcen | input-kcen | 15.3 ± 0.6 | 14.2 | 18.8 | 18.19 ± 3.86 |
| kcen | input-pting | 15.3 ± 0.6 | 14.1 | 18.3 | 18.21 ± 3.86 |
| chancalan | input-mattcl | 15.3 ± 0.7 | 14.3 | 18.5 | 18.29 ± 3.90 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.3 | 18.6 | 18.37 ± 3.89 |
| pting | input-chancalan | 15.5 ± 0.6 | 14.6 | 18.6 | 18.47 ± 3.91 |
| chancalan | input-chancalan | 15.7 ± 0.7 | 14.8 | 18.7 | 18.73 ± 3.98 |
| pting | input-pting | 15.8 ± 0.5 | 14.8 | 18.0 | 18.86 ± 3.97 |
| chancalan | input-pting | 16.0 ± 0.5 | 14.9 | 18.6 | 19.04 ± 4.01 |
| mattcl-py | input-chancalan | 16.0 ± 0.6 | 14.7 | 19.2 | 19.06 ± 4.04 |
| pting | input-kcen | 16.1 ± 0.7 | 15.0 | 19.5 | 19.24 ± 4.10 |
| mattcl-py | input-pting | 16.2 ± 0.6 | 15.3 | 19.5 | 19.33 ± 4.09 |
| mattcl-py | input-kcen | 16.2 ± 0.6 | 15.1 | 19.0 | 19.37 ± 4.09 |
| kcen | input-lanjian | 16.3 ± 0.6 | 15.2 | 19.4 | 19.45 ± 4.12 |
| chancalan | input-kcen | 16.3 ± 0.7 | 15.1 | 19.5 | 19.49 ± 4.13 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.1 | 20.7 | 20.62 ± 4.38 |
| chancalan | input-lanjian | 17.4 ± 0.5 | 16.6 | 20.3 | 20.78 ± 4.36 |
| mattcl-py | input-lanjian | 17.8 ± 0.7 | 16.8 | 21.0 | 21.20 ± 4.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|