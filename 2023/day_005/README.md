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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.4 | 1.00 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 ± 0.29 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.29 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.7 | 1.01 ± 0.31 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.1 | 1.01 ± 0.30 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.5 | 1.03 ± 0.30 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.04 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.5 | 1.07 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.4 | 1.1 | 1.07 ± 0.27 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.6 | 1.07 ± 0.28 |
| mattcl-ts | input-mikofo | 12.6 ± 0.3 | 11.5 | 14.3 | 14.55 ± 3.11 |
| mattcl-ts | input-mattcl | 12.7 ± 0.4 | 11.6 | 14.0 | 14.59 ± 3.12 |
| mattcl-ts | input-chancalan | 12.8 ± 0.3 | 11.8 | 13.6 | 14.77 ± 3.16 |
| mattcl-ts | input-kcen | 13.2 ± 2.7 | 12.3 | 50.0 | 15.20 ± 4.44 |
| mattcl-ts | input-lanjian | 13.9 ± 0.4 | 12.9 | 15.2 | 16.01 ± 3.43 |
| kcen | input-mikofo | 14.9 ± 0.6 | 13.7 | 18.0 | 17.22 ± 3.71 |
| kcen | input-mattcl | 15.0 ± 0.6 | 13.8 | 17.7 | 17.27 ± 3.72 |
| kcen | input-chancalan | 15.0 ± 0.5 | 13.8 | 17.5 | 17.31 ± 3.71 |
| pting | input-mattcl | 15.1 ± 0.6 | 13.8 | 18.8 | 17.45 ± 3.76 |
| pting | input-mikofo | 15.2 ± 0.7 | 14.1 | 18.4 | 17.51 ± 3.79 |
| chancalan | input-mattcl | 15.3 ± 0.6 | 14.5 | 18.5 | 17.66 ± 3.80 |
| kcen | input-kcen | 15.3 ± 0.7 | 14.4 | 18.4 | 17.68 ± 3.83 |
| chancalan | input-mikofo | 15.4 ± 0.8 | 14.4 | 18.3 | 17.74 ± 3.86 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.1 | 18.6 | 17.74 ± 3.83 |
| mattcl-py | input-mikofo | 15.5 ± 0.8 | 14.2 | 18.6 | 17.85 ± 3.89 |
| pting | input-chancalan | 15.5 ± 0.7 | 14.5 | 18.7 | 17.85 ± 3.86 |
| chancalan | input-chancalan | 15.7 ± 0.8 | 14.6 | 18.7 | 18.14 ± 3.95 |
| mattcl-py | input-chancalan | 15.9 ± 0.7 | 14.7 | 19.3 | 18.31 ± 3.96 |
| chancalan | input-kcen | 16.2 ± 0.6 | 14.8 | 18.5 | 18.64 ± 4.01 |
| kcen | input-lanjian | 16.3 ± 0.6 | 15.3 | 19.0 | 18.79 ± 4.05 |
| pting | input-kcen | 16.3 ± 2.5 | 15.0 | 48.7 | 18.83 ± 4.94 |
| mattcl-py | input-kcen | 16.5 ± 2.8 | 15.4 | 52.5 | 18.98 ± 5.14 |
| pting | input-lanjian | 17.3 ± 0.6 | 15.9 | 19.9 | 19.92 ± 4.27 |
| chancalan | input-lanjian | 17.5 ± 0.7 | 16.5 | 21.0 | 20.22 ± 4.36 |
| mattcl-py | input-lanjian | 17.7 ± 0.6 | 16.9 | 20.9 | 20.45 ± 4.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|