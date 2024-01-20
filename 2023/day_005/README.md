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
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 ± 0.25 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.29 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.26 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.4 | 1.2 | 1.04 ± 0.26 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.26 |
| lanjian | input-kcen | 1.0 ± 0.1 | 0.4 | 1.1 | 1.05 ± 0.25 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.2 | 1.05 ± 0.26 |
| lanjian | input-mikofo | 1.0 ± 0.1 | 0.6 | 1.1 | 1.05 ± 0.23 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.5 | 1.06 ± 0.26 |
| mattcl-ts | input-mattcl | 12.1 ± 0.4 | 11.2 | 13.7 | 13.14 ± 2.58 |
| mattcl-ts | input-mikofo | 12.2 ± 0.4 | 11.2 | 13.1 | 13.24 ± 2.58 |
| mattcl-ts | input-chancalan | 12.5 ± 0.4 | 11.6 | 13.3 | 13.50 ± 2.63 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.5 | 13.4 | 13.65 ± 2.66 |
| mattcl-ts | input-lanjian | 13.4 ± 0.4 | 12.5 | 14.5 | 14.52 ± 2.84 |
| kcen | input-mikofo | 14.7 ± 0.5 | 13.8 | 17.7 | 15.92 ± 3.12 |
| kcen | input-mattcl | 14.8 ± 0.6 | 13.9 | 18.0 | 16.04 ± 3.16 |
| kcen | input-chancalan | 15.0 ± 0.6 | 14.2 | 18.1 | 16.30 ± 3.21 |
| pting | input-mattcl | 15.1 ± 0.7 | 14.1 | 18.1 | 16.36 ± 3.24 |
| mattcl-py | input-mikofo | 15.2 ± 0.6 | 14.2 | 18.2 | 16.45 ± 3.23 |
| pting | input-mikofo | 15.2 ± 0.6 | 14.0 | 18.0 | 16.46 ± 3.24 |
| chancalan | input-mattcl | 15.2 ± 0.5 | 14.5 | 18.8 | 16.47 ± 3.23 |
| kcen | input-kcen | 15.2 ± 0.5 | 14.0 | 17.7 | 16.48 ± 3.23 |
| chancalan | input-mikofo | 15.2 ± 0.6 | 14.2 | 17.9 | 16.49 ± 3.24 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.1 | 18.1 | 16.51 ± 3.25 |
| pting | input-chancalan | 15.4 ± 0.6 | 14.1 | 18.9 | 16.68 ± 3.29 |
| chancalan | input-chancalan | 15.4 ± 0.6 | 14.4 | 18.3 | 16.74 ± 3.30 |
| pting | input-kcen | 15.8 ± 0.5 | 14.9 | 18.7 | 17.11 ± 3.35 |
| mattcl-py | input-chancalan | 15.8 ± 0.7 | 14.7 | 19.2 | 17.12 ± 3.40 |
| mattcl-py | input-kcen | 16.1 ± 0.6 | 14.9 | 18.5 | 17.41 ± 3.42 |
| kcen | input-lanjian | 16.1 ± 0.6 | 14.9 | 19.3 | 17.43 ± 3.44 |
| chancalan | input-kcen | 16.2 ± 0.7 | 15.1 | 19.3 | 17.53 ± 3.48 |
| pting | input-lanjian | 17.1 ± 0.7 | 16.2 | 20.7 | 18.55 ± 3.67 |
| chancalan | input-lanjian | 17.4 ± 0.8 | 16.2 | 20.8 | 18.87 ± 3.74 |
| mattcl-py | input-lanjian | 17.6 ± 0.6 | 16.9 | 20.8 | 19.13 ± 3.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|