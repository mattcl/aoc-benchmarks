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
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.6 | 1.00 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.1 | 1.02 ± 0.28 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.32 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.3 | 1.3 | 1.03 ± 0.29 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.29 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.30 |
| mattcl | input-mikofo | 0.9 ± 0.1 | 0.2 | 1.1 | 1.05 ± 0.29 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.30 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.3 | 1.06 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.7 | 1.07 ± 0.32 |
| mattcl-ts | input-mikofo | 12.5 ± 0.3 | 11.4 | 13.7 | 14.70 ± 3.30 |
| mattcl-ts | input-mattcl | 12.5 ± 0.3 | 11.4 | 13.4 | 14.72 ± 3.31 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.9 | 14.6 | 14.88 ± 3.34 |
| mattcl-ts | input-kcen | 12.8 ± 0.3 | 12.0 | 14.2 | 15.06 ± 3.38 |
| mattcl-ts | input-lanjian | 14.4 ± 4.7 | 12.8 | 53.0 | 16.95 ± 6.68 |
| kcen | input-mattcl | 14.7 ± 0.5 | 13.6 | 17.3 | 17.33 ± 3.90 |
| kcen | input-mikofo | 14.8 ± 0.7 | 13.7 | 18.2 | 17.40 ± 3.98 |
| kcen | input-chancalan | 14.9 ± 0.6 | 13.9 | 18.1 | 17.54 ± 3.98 |
| pting | input-mikofo | 15.0 ± 0.5 | 14.0 | 18.0 | 17.63 ± 3.98 |
| kcen | input-kcen | 15.1 ± 0.5 | 14.0 | 17.8 | 17.75 ± 4.00 |
| chancalan | input-mattcl | 15.1 ± 0.6 | 14.2 | 18.3 | 17.80 ± 4.02 |
| mattcl-py | input-mikofo | 15.2 ± 0.5 | 14.3 | 18.1 | 17.82 ± 4.01 |
| pting | input-mattcl | 15.2 ± 2.5 | 13.8 | 48.3 | 17.84 ± 4.91 |
| mattcl-py | input-mattcl | 15.3 ± 0.7 | 14.3 | 18.4 | 17.98 ± 4.08 |
| pting | input-chancalan | 15.3 ± 0.8 | 14.2 | 19.0 | 18.03 ± 4.12 |
| chancalan | input-mikofo | 15.4 ± 3.2 | 14.0 | 58.8 | 18.07 ± 5.48 |
| chancalan | input-chancalan | 15.4 ± 0.7 | 14.4 | 18.4 | 18.10 ± 4.11 |
| pting | input-kcen | 15.8 ± 0.7 | 14.8 | 19.1 | 18.60 ± 4.22 |
| mattcl-py | input-chancalan | 15.8 ± 2.5 | 14.6 | 49.3 | 18.63 ± 5.12 |
| chancalan | input-kcen | 16.1 ± 0.7 | 14.9 | 19.4 | 18.88 ± 4.29 |
| kcen | input-lanjian | 16.1 ± 0.7 | 14.8 | 19.1 | 18.94 ± 4.31 |
| mattcl-py | input-kcen | 16.1 ± 0.6 | 15.0 | 18.8 | 18.95 ± 4.29 |
| pting | input-lanjian | 17.1 ± 0.7 | 16.2 | 20.2 | 20.07 ± 4.55 |
| chancalan | input-lanjian | 17.3 ± 0.6 | 16.3 | 20.8 | 20.29 ± 4.58 |
| mattcl-py | input-lanjian | 17.7 ± 0.8 | 16.5 | 20.8 | 20.87 ± 4.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|