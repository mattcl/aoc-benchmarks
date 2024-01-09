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
| lanjian | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.4 | 1.00 ± 0.26 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.24 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.24 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.23 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 1.4 | 1.02 ± 0.23 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.25 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.5 | 1.03 ± 0.24 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.4 | 1.06 ± 0.24 |
| lanjian | input-lanjian | 1.1 ± 0.1 | 0.5 | 1.8 | 1.09 ± 0.22 |
| mattcl-ts | input-mattcl | 12.7 ± 0.4 | 11.8 | 14.3 | 13.13 ± 2.23 |
| mattcl-ts | input-mikofo | 12.7 ± 0.3 | 11.7 | 13.6 | 13.14 ± 2.22 |
| mattcl-ts | input-chancalan | 12.9 ± 0.4 | 11.9 | 14.1 | 13.34 ± 2.26 |
| mattcl-ts | input-kcen | 13.1 ± 0.4 | 12.1 | 14.5 | 13.55 ± 2.30 |
| mattcl-ts | input-lanjian | 14.0 ± 0.4 | 13.0 | 15.4 | 14.46 ± 2.45 |
| kcen | input-mattcl | 15.1 ± 0.6 | 13.8 | 17.9 | 15.61 ± 2.69 |
| kcen | input-mikofo | 15.2 ± 0.8 | 14.1 | 18.2 | 15.66 ± 2.73 |
| kcen | input-chancalan | 15.2 ± 0.5 | 14.2 | 17.7 | 15.70 ± 2.67 |
| pting | input-mikofo | 15.3 ± 0.6 | 14.2 | 18.4 | 15.79 ± 2.71 |
| pting | input-mattcl | 15.5 ± 2.2 | 14.1 | 44.2 | 15.95 ± 3.47 |
| chancalan | input-mattcl | 15.5 ± 0.6 | 14.2 | 18.3 | 15.96 ± 2.74 |
| kcen | input-kcen | 15.5 ± 0.6 | 14.5 | 18.3 | 15.97 ± 2.74 |
| chancalan | input-mikofo | 15.5 ± 0.7 | 14.5 | 19.0 | 16.02 ± 2.77 |
| pting | input-chancalan | 15.6 ± 0.6 | 14.3 | 18.6 | 16.04 ± 2.76 |
| mattcl-py | input-mikofo | 15.6 ± 0.6 | 14.7 | 19.1 | 16.07 ± 2.76 |
| mattcl-py | input-mattcl | 15.6 ± 0.7 | 14.2 | 18.8 | 16.08 ± 2.76 |
| chancalan | input-chancalan | 15.8 ± 0.6 | 14.8 | 18.5 | 16.25 ± 2.78 |
| mattcl-py | input-chancalan | 16.1 ± 0.7 | 15.0 | 19.7 | 16.58 ± 2.87 |
| pting | input-kcen | 16.1 ± 0.5 | 15.0 | 18.8 | 16.60 ± 2.82 |
| kcen | input-lanjian | 16.3 ± 0.5 | 15.4 | 19.7 | 16.83 ± 2.86 |
| mattcl-py | input-kcen | 16.4 ± 0.7 | 15.1 | 19.7 | 16.92 ± 2.91 |
| chancalan | input-kcen | 16.4 ± 0.8 | 15.0 | 20.0 | 16.96 ± 2.95 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.4 | 20.7 | 17.98 ± 3.10 |
| chancalan | input-lanjian | 17.5 ± 0.6 | 16.4 | 20.3 | 18.10 ± 3.07 |
| mattcl-py | input-lanjian | 18.0 ± 0.8 | 17.0 | 21.6 | 18.59 ± 3.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|