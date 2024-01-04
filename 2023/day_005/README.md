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
| mattcl | input-mikofo | 0.8 ± 0.3 | 0.2 | 1.3 | 1.00 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.11 ± 0.43 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.5 | 1.11 ± 0.43 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.2 | 1.11 ± 0.44 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.3 | 1.11 ± 0.42 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.12 ± 0.45 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.3 | 1.14 ± 0.43 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.4 | 1.4 | 1.17 ± 0.43 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.5 | 1.18 ± 0.44 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.2 | 1.21 ± 0.44 |
| mattcl-ts | input-mattcl | 12.5 ± 0.3 | 11.5 | 13.3 | 15.41 ± 5.17 |
| mattcl-ts | input-mikofo | 12.5 ± 0.3 | 11.3 | 13.4 | 15.46 ± 5.19 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.7 | 13.8 | 15.62 ± 5.24 |
| mattcl-ts | input-kcen | 12.8 ± 0.3 | 12.0 | 14.4 | 15.79 ± 5.30 |
| mattcl-ts | input-lanjian | 13.6 ± 0.3 | 12.8 | 14.4 | 16.87 ± 5.66 |
| kcen | input-mattcl | 14.7 ± 0.6 | 13.8 | 17.7 | 18.16 ± 6.13 |
| kcen | input-mikofo | 14.9 ± 3.2 | 13.6 | 59.0 | 18.40 ± 7.31 |
| pting | input-mattcl | 15.0 ± 0.6 | 13.9 | 18.2 | 18.49 ± 6.23 |
| pting | input-mikofo | 15.0 ± 0.5 | 14.0 | 17.7 | 18.50 ± 6.22 |
| kcen | input-chancalan | 15.0 ± 0.6 | 13.9 | 18.2 | 18.52 ± 6.25 |
| mattcl-py | input-mattcl | 15.1 ± 0.5 | 14.1 | 18.3 | 18.72 ± 6.30 |
| chancalan | input-mikofo | 15.2 ± 0.6 | 14.1 | 17.7 | 18.74 ± 6.31 |
| chancalan | input-mattcl | 15.2 ± 0.6 | 14.1 | 18.5 | 18.81 ± 6.34 |
| kcen | input-kcen | 15.2 ± 0.7 | 13.9 | 17.8 | 18.84 ± 6.37 |
| pting | input-chancalan | 15.2 ± 0.6 | 14.2 | 18.2 | 18.85 ± 6.36 |
| chancalan | input-chancalan | 15.3 ± 0.5 | 14.4 | 18.5 | 18.92 ± 6.37 |
| mattcl-py | input-mikofo | 15.3 ± 2.7 | 14.1 | 52.4 | 18.94 ± 7.17 |
| pting | input-kcen | 15.6 ± 0.6 | 14.6 | 18.4 | 19.34 ± 6.52 |
| mattcl-py | input-chancalan | 15.7 ± 0.6 | 14.7 | 18.7 | 19.38 ± 6.54 |
| kcen | input-lanjian | 15.9 ± 0.6 | 14.9 | 18.9 | 19.70 ± 6.64 |
| mattcl-py | input-kcen | 16.0 ± 0.8 | 14.8 | 19.6 | 19.79 ± 6.69 |
| chancalan | input-kcen | 16.1 ± 0.7 | 14.8 | 19.2 | 19.87 ± 6.71 |
| pting | input-lanjian | 16.9 ± 0.7 | 15.8 | 20.3 | 20.90 ± 7.04 |
| chancalan | input-lanjian | 17.1 ± 0.6 | 16.0 | 20.8 | 21.17 ± 7.13 |
| mattcl-py | input-lanjian | 17.7 ± 0.7 | 16.9 | 21.0 | 21.84 ± 7.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|