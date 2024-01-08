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
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.2 | 1.00 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.30 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.3 | 1.2 | 1.04 ± 0.27 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.3 | 1.05 ± 0.27 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.05 ± 0.29 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.28 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.4 | 1.06 ± 0.27 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.3 | 1.2 | 1.08 ± 0.27 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.7 | 1.11 ± 0.30 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.7 | 1.12 ± 0.30 |
| mattcl-ts | input-mattcl | 12.5 ± 0.3 | 11.4 | 13.3 | 13.93 ± 2.85 |
| mattcl-ts | input-mikofo | 12.5 ± 0.4 | 11.6 | 13.3 | 13.95 ± 2.86 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.8 | 13.8 | 14.24 ± 2.91 |
| mattcl-ts | input-kcen | 12.9 ± 0.3 | 12.3 | 13.9 | 14.40 ± 2.94 |
| mattcl-ts | input-lanjian | 13.7 ± 0.4 | 12.6 | 15.3 | 15.37 ± 3.14 |
| kcen | input-mikofo | 14.8 ± 0.5 | 13.8 | 17.8 | 16.53 ± 3.39 |
| kcen | input-mattcl | 14.8 ± 0.5 | 13.8 | 17.8 | 16.57 ± 3.41 |
| kcen | input-chancalan | 15.0 ± 0.6 | 14.0 | 18.1 | 16.77 ± 3.46 |
| pting | input-mattcl | 15.1 ± 0.6 | 14.0 | 17.8 | 16.93 ± 3.49 |
| pting | input-mikofo | 15.2 ± 0.6 | 14.2 | 18.0 | 16.97 ± 3.51 |
| chancalan | input-mattcl | 15.2 ± 0.6 | 14.1 | 17.8 | 17.01 ± 3.51 |
| chancalan | input-mikofo | 15.2 ± 0.7 | 14.1 | 18.0 | 17.02 ± 3.53 |
| mattcl-py | input-mikofo | 15.3 ± 0.6 | 14.5 | 18.5 | 17.10 ± 3.53 |
| kcen | input-kcen | 15.3 ± 1.9 | 14.1 | 38.9 | 17.14 ± 4.08 |
| pting | input-chancalan | 15.3 ± 0.6 | 14.3 | 18.5 | 17.15 ± 3.54 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.5 | 18.6 | 17.17 ± 3.55 |
| chancalan | input-chancalan | 15.4 ± 0.6 | 14.5 | 18.2 | 17.27 ± 3.56 |
| mattcl-py | input-chancalan | 15.8 ± 0.8 | 14.9 | 19.2 | 17.68 ± 3.69 |
| pting | input-kcen | 15.9 ± 0.7 | 14.8 | 18.7 | 17.78 ± 3.68 |
| mattcl-py | input-kcen | 16.2 ± 0.7 | 15.2 | 19.7 | 18.07 ± 3.74 |
| kcen | input-lanjian | 16.2 ± 0.7 | 15.0 | 19.2 | 18.10 ± 3.76 |
| chancalan | input-kcen | 16.5 ± 3.2 | 15.3 | 57.2 | 18.43 ± 5.17 |
| pting | input-lanjian | 17.1 ± 0.8 | 15.8 | 20.3 | 19.16 ± 3.99 |
| chancalan | input-lanjian | 17.3 ± 0.7 | 16.3 | 20.6 | 19.36 ± 4.00 |
| mattcl-py | input-lanjian | 17.8 ± 0.6 | 17.0 | 20.5 | 19.85 ± 4.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|