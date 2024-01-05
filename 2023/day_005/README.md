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
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.5 | 1.00 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.7 | 1.01 ± 0.31 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.4 | 1.01 ± 0.28 |
| lanjian | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.7 | 1.02 ± 0.26 |
| mattcl | input-mikofo | 1.0 ± 0.1 | 0.5 | 1.2 | 1.04 ± 0.26 |
| lanjian | input-kcen | 1.0 ± 0.1 | 0.6 | 1.3 | 1.04 ± 0.25 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.6 | 1.2 | 1.05 ± 0.26 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 1.06 ± 0.29 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.5 | 1.07 ± 0.27 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.5 | 1.08 ± 0.27 |
| mattcl-ts | input-mattcl | 12.6 ± 0.4 | 11.8 | 13.5 | 13.01 ± 2.65 |
| mattcl-ts | input-chancalan | 12.9 ± 0.3 | 12.2 | 14.4 | 13.28 ± 2.70 |
| mattcl-ts | input-kcen | 13.1 ± 0.3 | 12.3 | 14.0 | 13.50 ± 2.75 |
| mattcl-ts | input-mikofo | 13.5 ± 6.2 | 11.8 | 85.4 | 13.86 ± 6.95 |
| mattcl-ts | input-lanjian | 14.0 ± 0.4 | 13.1 | 14.9 | 14.42 ± 2.93 |
| kcen | input-mattcl | 15.1 ± 0.5 | 14.0 | 17.5 | 15.53 ± 3.18 |
| kcen | input-mikofo | 15.1 ± 0.6 | 14.1 | 18.3 | 15.53 ± 3.20 |
| kcen | input-chancalan | 15.2 ± 0.5 | 13.9 | 17.9 | 15.60 ± 3.19 |
| pting | input-mikofo | 15.2 ± 0.6 | 14.2 | 18.3 | 15.67 ± 3.21 |
| pting | input-mattcl | 15.2 ± 0.6 | 14.2 | 18.6 | 15.68 ± 3.22 |
| kcen | input-kcen | 15.4 ± 0.6 | 14.2 | 17.9 | 15.80 ± 3.24 |
| chancalan | input-mikofo | 15.4 ± 0.7 | 14.2 | 19.1 | 15.88 ± 3.28 |
| chancalan | input-mattcl | 15.6 ± 0.7 | 14.5 | 18.4 | 16.01 ± 3.31 |
| mattcl-py | input-mattcl | 15.6 ± 0.6 | 14.3 | 18.5 | 16.03 ± 3.30 |
| chancalan | input-chancalan | 15.7 ± 0.6 | 14.7 | 18.9 | 16.18 ± 3.33 |
| pting | input-chancalan | 15.7 ± 0.6 | 14.6 | 19.3 | 16.20 ± 3.33 |
| mattcl-py | input-mikofo | 16.1 ± 3.8 | 14.5 | 60.0 | 16.57 ± 5.12 |
| pting | input-kcen | 16.2 ± 0.7 | 14.7 | 18.9 | 16.65 ± 3.43 |
| mattcl-py | input-chancalan | 16.2 ± 0.8 | 15.0 | 19.8 | 16.71 ± 3.48 |
| chancalan | input-kcen | 16.3 ± 0.6 | 14.9 | 19.4 | 16.78 ± 3.45 |
| kcen | input-lanjian | 16.4 ± 0.8 | 15.2 | 19.8 | 16.89 ± 3.50 |
| mattcl-py | input-kcen | 16.4 ± 0.7 | 15.0 | 19.0 | 16.89 ± 3.49 |
| pting | input-lanjian | 17.3 ± 0.6 | 16.2 | 20.6 | 17.84 ± 3.65 |
| chancalan | input-lanjian | 17.5 ± 0.6 | 16.4 | 20.2 | 18.04 ± 3.69 |
| mattcl-py | input-lanjian | 18.1 ± 0.9 | 16.9 | 21.7 | 18.64 ± 3.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|