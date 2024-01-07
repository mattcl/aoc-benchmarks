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
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.6 | 1.00 ± 0.28 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.6 | 1.01 ± 0.28 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.3 | 1.02 ± 0.29 |
| lanjian | input-mikofo | 0.9 ± 0.1 | 0.5 | 1.1 | 1.04 ± 0.25 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.29 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.2 | 1.04 ± 0.29 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.4 | 1.0 | 1.06 ± 0.26 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.07 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.1 | 1.11 ± 0.27 |
| mattcl-ts | input-mikofo | 12.5 ± 0.4 | 11.4 | 13.7 | 14.74 ± 3.05 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.6 | 13.4 | 14.80 ± 3.05 |
| mattcl-ts | input-chancalan | 12.8 ± 0.3 | 11.8 | 13.7 | 15.02 ± 3.09 |
| mattcl-ts | input-kcen | 12.9 ± 0.4 | 12.3 | 14.3 | 15.22 ± 3.14 |
| mattcl-ts | input-lanjian | 13.8 ± 0.4 | 13.0 | 15.1 | 16.28 ± 3.36 |
| kcen | input-mikofo | 15.0 ± 0.5 | 13.8 | 17.7 | 17.58 ± 3.64 |
| kcen | input-mattcl | 15.0 ± 0.7 | 13.9 | 18.2 | 17.61 ± 3.68 |
| kcen | input-chancalan | 15.1 ± 0.6 | 13.8 | 17.5 | 17.74 ± 3.68 |
| pting | input-mattcl | 15.1 ± 0.4 | 13.8 | 17.3 | 17.74 ± 3.66 |
| pting | input-mikofo | 15.1 ± 0.6 | 14.0 | 18.9 | 17.76 ± 3.69 |
| chancalan | input-mattcl | 15.2 ± 0.6 | 14.0 | 18.8 | 17.92 ± 3.72 |
| chancalan | input-mikofo | 15.4 ± 0.6 | 14.0 | 18.7 | 18.05 ± 3.75 |
| kcen | input-kcen | 15.4 ± 0.6 | 14.3 | 18.5 | 18.05 ± 3.77 |
| mattcl-py | input-mikofo | 15.4 ± 0.6 | 14.4 | 17.9 | 18.11 ± 3.76 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.2 | 18.9 | 18.15 ± 3.77 |
| pting | input-chancalan | 15.4 ± 0.7 | 14.3 | 18.6 | 18.16 ± 3.80 |
| chancalan | input-chancalan | 15.7 ± 1.0 | 14.4 | 25.2 | 18.43 ± 3.93 |
| mattcl-py | input-chancalan | 15.9 ± 0.7 | 14.5 | 18.5 | 18.69 ± 3.90 |
| pting | input-kcen | 16.0 ± 0.6 | 14.9 | 18.9 | 18.83 ± 3.92 |
| mattcl-py | input-kcen | 16.2 ± 0.8 | 14.8 | 19.5 | 19.04 ± 3.99 |
| kcen | input-lanjian | 16.2 ± 0.8 | 14.8 | 19.8 | 19.07 ± 4.01 |
| chancalan | input-kcen | 16.3 ± 0.7 | 15.0 | 18.9 | 19.18 ± 4.02 |
| pting | input-lanjian | 17.2 ± 0.7 | 16.1 | 20.2 | 20.23 ± 4.21 |
| chancalan | input-lanjian | 17.4 ± 0.7 | 16.2 | 20.8 | 20.46 ± 4.27 |
| mattcl-py | input-lanjian | 17.9 ± 0.9 | 16.9 | 21.2 | 21.09 ± 4.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|