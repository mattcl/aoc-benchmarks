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
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.0 | 1.1 | 1.00 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.03 ± 0.34 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.5 | 1.05 ± 0.36 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.2 | 1.05 ± 0.37 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.1 | 1.6 | 1.07 ± 0.37 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.3 | 1.08 ± 0.36 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.08 ± 0.37 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.5 | 1.10 ± 0.39 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.2 | 1.5 | 1.12 ± 0.35 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.7 | 1.14 ± 0.36 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.4 | 13.6 | 15.40 ± 4.18 |
| mattcl-ts | input-mikofo | 12.6 ± 0.3 | 11.6 | 13.4 | 15.52 ± 4.20 |
| mattcl-ts | input-chancalan | 12.8 ± 0.3 | 12.0 | 14.3 | 15.72 ± 4.26 |
| mattcl-ts | input-kcen | 12.9 ± 0.4 | 12.1 | 14.5 | 15.93 ± 4.32 |
| mattcl-ts | input-lanjian | 13.8 ± 0.4 | 13.0 | 15.9 | 17.01 ± 4.61 |
| kcen | input-mikofo | 14.9 ± 0.6 | 13.7 | 18.1 | 18.38 ± 5.00 |
| kcen | input-mattcl | 14.9 ± 0.6 | 13.9 | 18.2 | 18.38 ± 5.00 |
| kcen | input-chancalan | 15.1 ± 0.7 | 14.0 | 18.3 | 18.57 ± 5.09 |
| pting | input-mattcl | 15.1 ± 0.5 | 14.0 | 18.6 | 18.63 ± 5.06 |
| pting | input-mikofo | 15.2 ± 0.7 | 14.1 | 18.2 | 18.73 ± 5.13 |
| chancalan | input-mikofo | 15.3 ± 0.6 | 14.1 | 18.6 | 18.80 ± 5.12 |
| kcen | input-kcen | 15.3 ± 0.7 | 14.1 | 18.8 | 18.90 ± 5.16 |
| chancalan | input-mattcl | 15.3 ± 0.6 | 14.3 | 17.8 | 18.91 ± 5.15 |
| mattcl-py | input-mattcl | 15.4 ± 0.7 | 14.1 | 18.7 | 18.95 ± 5.17 |
| mattcl-py | input-mikofo | 15.5 ± 0.7 | 14.7 | 18.7 | 19.09 ± 5.22 |
| chancalan | input-chancalan | 15.6 ± 0.6 | 14.7 | 18.3 | 19.17 ± 5.22 |
| pting | input-chancalan | 15.8 ± 3.7 | 14.7 | 65.5 | 19.43 ± 6.94 |
| mattcl-py | input-chancalan | 15.9 ± 0.7 | 14.6 | 19.3 | 19.58 ± 5.35 |
| pting | input-kcen | 16.1 ± 0.7 | 15.1 | 19.4 | 19.80 ± 5.41 |
| kcen | input-lanjian | 16.2 ± 0.6 | 15.0 | 19.5 | 20.00 ± 5.45 |
| chancalan | input-kcen | 16.2 ± 0.6 | 15.2 | 19.1 | 20.00 ± 5.44 |
| mattcl-py | input-kcen | 16.3 ± 0.8 | 15.0 | 19.7 | 20.04 ± 5.48 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.3 | 20.2 | 21.36 ± 5.82 |
| chancalan | input-lanjian | 17.6 ± 2.2 | 16.2 | 44.3 | 21.68 ± 6.44 |
| mattcl-py | input-lanjian | 17.8 ± 0.7 | 16.4 | 21.2 | 21.90 ± 5.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|