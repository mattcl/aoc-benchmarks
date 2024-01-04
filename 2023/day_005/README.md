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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.30 |
| lanjian | input-mikofo | 0.9 ± 0.1 | 0.3 | 1.1 | 1.02 ± 0.27 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.2 | 1.03 ± 0.27 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.3 | 1.05 ± 0.28 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.3 | 1.06 ± 0.29 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.28 |
| mattcl | input-mikofo | 0.9 ± 0.1 | 0.4 | 1.1 | 1.06 ± 0.27 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.1 | 1.11 ± 0.26 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.4 | 1.12 ± 0.28 |
| mattcl-ts | input-mattcl | 12.2 ± 0.4 | 11.2 | 13.1 | 13.95 ± 2.96 |
| mattcl-ts | input-mikofo | 12.3 ± 0.4 | 11.2 | 13.5 | 14.03 ± 2.98 |
| mattcl-ts | input-chancalan | 12.5 ± 0.4 | 11.5 | 13.5 | 14.27 ± 3.02 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.9 | 14.0 | 14.43 ± 3.05 |
| mattcl-ts | input-lanjian | 13.4 ± 0.4 | 12.4 | 14.7 | 15.31 ± 3.24 |
| kcen | input-mattcl | 14.7 ± 0.6 | 13.7 | 17.8 | 16.82 ± 3.59 |
| kcen | input-mikofo | 14.8 ± 0.8 | 13.7 | 18.3 | 16.92 ± 3.66 |
| kcen | input-chancalan | 14.9 ± 0.6 | 13.8 | 17.8 | 16.98 ± 3.63 |
| pting | input-mattcl | 15.0 ± 0.6 | 14.0 | 18.0 | 17.11 ± 3.65 |
| pting | input-mikofo | 15.0 ± 0.6 | 13.9 | 17.6 | 17.14 ± 3.66 |
| chancalan | input-mikofo | 15.1 ± 0.6 | 14.1 | 18.0 | 17.29 ± 3.69 |
| kcen | input-kcen | 15.1 ± 0.6 | 14.0 | 18.0 | 17.30 ± 3.68 |
| chancalan | input-mattcl | 15.2 ± 0.6 | 14.1 | 17.7 | 17.35 ± 3.70 |
| pting | input-chancalan | 15.2 ± 0.6 | 14.2 | 18.3 | 17.37 ± 3.70 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.1 | 17.8 | 17.42 ± 3.72 |
| mattcl-py | input-mikofo | 15.3 ± 0.7 | 14.2 | 18.1 | 17.47 ± 3.74 |
| chancalan | input-chancalan | 15.3 ± 0.6 | 14.2 | 18.6 | 17.54 ± 3.75 |
| mattcl-py | input-chancalan | 15.6 ± 0.6 | 14.8 | 18.5 | 17.84 ± 3.80 |
| kcen | input-lanjian | 15.9 ± 0.6 | 15.0 | 18.7 | 18.22 ± 3.89 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 14.8 | 18.8 | 18.28 ± 3.91 |
| chancalan | input-kcen | 16.0 ± 0.7 | 14.9 | 19.4 | 18.29 ± 3.91 |
| pting | input-kcen | 16.1 ± 2.9 | 14.6 | 52.8 | 18.37 ± 5.06 |
| pting | input-lanjian | 16.9 ± 0.7 | 15.8 | 20.4 | 19.33 ± 4.12 |
| chancalan | input-lanjian | 17.5 ± 3.3 | 16.1 | 57.1 | 19.95 ± 5.62 |
| mattcl-py | input-lanjian | 17.6 ± 0.6 | 17.0 | 20.7 | 20.13 ± 4.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|