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
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.3 | 1.1 | 1.03 ± 0.31 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.2 | 1.1 | 1.07 ± 0.29 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 1.7 | 1.07 ± 0.31 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.2 | 1.07 ± 0.30 |
| mattcl | input-mikofo | 1.0 ± 0.1 | 0.4 | 1.2 | 1.07 ± 0.28 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.4 | 1.08 ± 0.31 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 2.5 | 1.08 ± 0.32 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.7 | 1.09 ± 0.32 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.4 | 1.2 | 1.10 ± 0.28 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 11.7 | 13.8 | 13.91 ± 3.16 |
| mattcl-ts | input-mikofo | 12.7 ± 0.4 | 11.6 | 14.7 | 13.92 ± 3.17 |
| mattcl-ts | input-chancalan | 12.9 ± 0.4 | 12.0 | 14.2 | 14.08 ± 3.21 |
| mattcl-ts | input-kcen | 13.0 ± 0.4 | 11.9 | 14.7 | 14.23 ± 3.24 |
| mattcl-ts | input-lanjian | 13.9 ± 0.4 | 13.0 | 14.9 | 15.28 ± 3.47 |
| kcen | input-chancalan | 15.1 ± 0.6 | 13.9 | 18.1 | 16.57 ± 3.80 |
| kcen | input-mattcl | 15.1 ± 0.6 | 14.2 | 18.3 | 16.57 ± 3.81 |
| pting | input-mikofo | 15.2 ± 0.6 | 14.2 | 18.3 | 16.64 ± 3.81 |
| pting | input-mattcl | 15.2 ± 0.6 | 13.9 | 18.1 | 16.67 ± 3.82 |
| chancalan | input-mattcl | 15.4 ± 0.6 | 14.4 | 18.4 | 16.86 ± 3.87 |
| kcen | input-mikofo | 15.4 ± 5.0 | 13.8 | 64.0 | 16.89 ± 6.65 |
| mattcl-py | input-mikofo | 15.4 ± 0.7 | 14.2 | 18.6 | 16.91 ± 3.90 |
| kcen | input-kcen | 15.5 ± 0.7 | 14.5 | 18.5 | 16.94 ± 3.90 |
| mattcl-py | input-mattcl | 15.5 ± 0.6 | 14.3 | 18.5 | 16.94 ± 3.88 |
| pting | input-chancalan | 15.5 ± 0.5 | 14.5 | 18.0 | 16.94 ± 3.87 |
| chancalan | input-mikofo | 15.5 ± 2.3 | 14.3 | 46.2 | 17.03 ± 4.61 |
| chancalan | input-chancalan | 15.7 ± 0.7 | 14.5 | 19.0 | 17.19 ± 3.97 |
| mattcl-py | input-chancalan | 15.9 ± 0.7 | 14.8 | 19.1 | 17.45 ± 4.01 |
| pting | input-kcen | 16.2 ± 0.7 | 14.9 | 19.3 | 17.80 ± 4.10 |
| mattcl-py | input-kcen | 16.3 ± 0.7 | 15.1 | 19.7 | 17.82 ± 4.09 |
| chancalan | input-kcen | 16.3 ± 0.6 | 15.0 | 19.7 | 17.86 ± 4.09 |
| kcen | input-lanjian | 16.3 ± 0.6 | 15.3 | 19.2 | 17.87 ± 4.10 |
| pting | input-lanjian | 17.4 ± 0.8 | 16.4 | 20.7 | 19.07 ± 4.40 |
| chancalan | input-lanjian | 17.6 ± 0.8 | 16.5 | 20.8 | 19.29 ± 4.44 |
| mattcl-py | input-lanjian | 18.0 ± 0.8 | 17.1 | 21.9 | 19.70 ± 4.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|