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
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.2 | 1.00 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.27 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.27 |
| lanjian | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.8 | 1.03 ± 0.27 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.27 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.3 | 1.6 | 1.05 ± 0.25 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.6 | 1.8 | 1.07 ± 0.27 |
| lanjian | input-chancalan | 1.0 ± 0.1 | 0.5 | 1.2 | 1.08 ± 0.24 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.7 | 1.09 ± 0.27 |
| mattcl | input-lanjian | 1.1 ± 0.1 | 0.5 | 1.7 | 1.09 ± 0.26 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 10.9 | 13.0 | 12.43 ± 2.44 |
| mattcl-ts | input-mikofo | 12.0 ± 0.5 | 10.8 | 13.1 | 12.46 ± 2.46 |
| mattcl-ts | input-chancalan | 12.4 ± 0.4 | 11.2 | 13.7 | 12.85 ± 2.52 |
| mattcl-ts | input-kcen | 12.5 ± 0.4 | 11.4 | 13.4 | 13.00 ± 2.54 |
| mattcl-ts | input-lanjian | 13.3 ± 0.4 | 12.4 | 14.3 | 13.79 ± 2.69 |
| kcen | input-mikofo | 15.0 ± 0.5 | 14.0 | 17.6 | 15.57 ± 3.05 |
| kcen | input-mattcl | 15.1 ± 0.6 | 14.0 | 17.9 | 15.63 ± 3.07 |
| kcen | input-chancalan | 15.2 ± 0.6 | 14.2 | 18.5 | 15.83 ± 3.12 |
| pting | input-mikofo | 15.3 ± 0.7 | 14.0 | 18.5 | 15.87 ± 3.14 |
| pting | input-mattcl | 15.3 ± 0.6 | 14.2 | 18.2 | 15.88 ± 3.12 |
| chancalan | input-mikofo | 15.4 ± 0.5 | 14.2 | 17.8 | 15.95 ± 3.13 |
| chancalan | input-mattcl | 15.4 ± 0.6 | 14.4 | 19.0 | 15.96 ± 3.15 |
| kcen | input-kcen | 15.4 ± 0.7 | 14.2 | 18.4 | 16.00 ± 3.17 |
| pting | input-chancalan | 15.5 ± 0.5 | 14.3 | 18.3 | 16.13 ± 3.15 |
| mattcl-py | input-mattcl | 15.6 ± 0.7 | 14.2 | 18.5 | 16.18 ± 3.20 |
| mattcl-py | input-mikofo | 15.6 ± 0.5 | 14.6 | 18.3 | 16.20 ± 3.17 |
| chancalan | input-chancalan | 15.9 ± 0.8 | 14.6 | 19.0 | 16.47 ± 3.30 |
| mattcl-py | input-chancalan | 16.1 ± 0.7 | 14.7 | 18.8 | 16.68 ± 3.31 |
| pting | input-kcen | 16.2 ± 0.7 | 14.9 | 18.9 | 16.81 ± 3.34 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.0 | 19.5 | 16.95 ± 3.35 |
| chancalan | input-kcen | 16.4 ± 0.7 | 15.0 | 19.1 | 16.98 ± 3.36 |
| mattcl-py | input-kcen | 16.4 ± 0.6 | 15.6 | 19.3 | 17.00 ± 3.34 |
| pting | input-lanjian | 17.3 ± 0.5 | 16.3 | 19.4 | 17.95 ± 3.50 |
| chancalan | input-lanjian | 17.6 ± 0.6 | 16.3 | 20.3 | 18.24 ± 3.58 |
| mattcl-py | input-lanjian | 17.9 ± 0.4 | 17.2 | 19.6 | 18.55 ± 3.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|