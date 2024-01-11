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
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.3 | 1.6 | 1.00 ± 0.27 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.01 ± 0.28 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.1 | 1.02 ± 0.27 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.1 | 1.03 ± 0.25 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.4 | 1.1 | 1.03 ± 0.26 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.27 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.4 | 1.3 | 1.04 ± 0.26 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.06 ± 0.28 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.3 | 1.6 | 1.09 ± 0.27 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.7 | 13.5 | 14.30 ± 2.90 |
| mattcl-ts | input-mikofo | 12.5 ± 0.4 | 11.5 | 13.4 | 14.32 ± 2.90 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.8 | 13.7 | 14.53 ± 2.94 |
| mattcl-ts | input-kcen | 12.9 ± 0.3 | 12.2 | 13.8 | 14.72 ± 2.98 |
| mattcl-ts | input-lanjian | 13.7 ± 0.4 | 12.9 | 14.8 | 15.69 ± 3.17 |
| kcen | input-mikofo | 14.9 ± 0.7 | 13.6 | 18.0 | 17.00 ± 3.49 |
| kcen | input-mattcl | 14.9 ± 0.6 | 13.7 | 17.9 | 17.04 ± 3.49 |
| kcen | input-chancalan | 14.9 ± 0.5 | 13.8 | 17.6 | 17.05 ± 3.46 |
| pting | input-mikofo | 15.1 ± 0.6 | 14.0 | 18.4 | 17.23 ± 3.53 |
| pting | input-mattcl | 15.1 ± 0.6 | 13.9 | 17.8 | 17.25 ± 3.53 |
| kcen | input-kcen | 15.2 ± 0.5 | 14.0 | 17.7 | 17.32 ± 3.52 |
| chancalan | input-mattcl | 15.2 ± 0.7 | 14.0 | 18.5 | 17.40 ± 3.59 |
| chancalan | input-mikofo | 15.2 ± 0.7 | 14.1 | 18.3 | 17.41 ± 3.57 |
| mattcl-py | input-mattcl | 15.4 ± 0.7 | 14.0 | 18.7 | 17.54 ± 3.61 |
| mattcl-py | input-mikofo | 15.4 ± 0.8 | 14.3 | 19.5 | 17.61 ± 3.65 |
| pting | input-chancalan | 15.5 ± 0.8 | 14.1 | 19.1 | 17.65 ± 3.64 |
| chancalan | input-chancalan | 15.5 ± 0.7 | 14.6 | 18.5 | 17.73 ± 3.63 |
| mattcl-py | input-chancalan | 15.9 ± 0.7 | 14.8 | 19.6 | 18.16 ± 3.73 |
| pting | input-kcen | 15.9 ± 0.7 | 14.5 | 18.8 | 18.17 ± 3.73 |
| chancalan | input-kcen | 16.2 ± 0.5 | 15.1 | 19.4 | 18.46 ± 3.74 |
| kcen | input-lanjian | 16.3 ± 2.0 | 14.7 | 42.4 | 18.57 ± 4.38 |
| mattcl-py | input-kcen | 16.3 ± 0.6 | 15.3 | 20.0 | 18.58 ± 3.80 |
| pting | input-lanjian | 17.1 ± 0.7 | 16.1 | 20.0 | 19.48 ± 3.98 |
| chancalan | input-lanjian | 17.3 ± 0.6 | 16.3 | 20.2 | 19.74 ± 4.02 |
| mattcl-py | input-lanjian | 17.7 ± 0.7 | 16.7 | 20.6 | 20.24 ± 4.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|