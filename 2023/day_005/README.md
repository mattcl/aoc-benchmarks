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
| lanjian | input-kcen | 0.9 ± 0.2 | 0.3 | 1.2 | 1.02 ± 0.29 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.4 | 1.02 ± 0.28 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.3 | 1.04 ± 0.28 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.2 | 1.04 ± 0.29 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.4 | 1.06 ± 0.30 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.5 | 1.06 ± 0.27 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.5 | 1.08 ± 0.29 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.5 | 1.09 ± 0.30 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.2 | 1.11 ± 0.28 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.3 | 13.5 | 13.49 ± 2.72 |
| mattcl-ts | input-mikofo | 12.6 ± 0.4 | 11.6 | 13.7 | 13.55 ± 2.74 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.7 | 13.7 | 13.73 ± 2.77 |
| mattcl-ts | input-kcen | 12.9 ± 0.4 | 12.0 | 14.6 | 13.88 ± 2.80 |
| mattcl-ts | input-lanjian | 13.8 ± 0.3 | 12.8 | 14.7 | 14.87 ± 2.99 |
| kcen | input-mattcl | 14.8 ± 0.6 | 14.0 | 18.6 | 16.00 ± 3.25 |
| kcen | input-mikofo | 15.0 ± 0.7 | 13.8 | 17.8 | 16.14 ± 3.32 |
| pting | input-mattcl | 15.1 ± 0.6 | 13.9 | 18.3 | 16.34 ± 3.33 |
| kcen | input-chancalan | 15.2 ± 0.7 | 14.0 | 18.7 | 16.36 ± 3.35 |
| pting | input-mikofo | 15.2 ± 0.6 | 14.1 | 18.1 | 16.36 ± 3.33 |
| kcen | input-kcen | 15.3 ± 0.6 | 14.1 | 18.0 | 16.46 ± 3.35 |
| chancalan | input-mikofo | 15.3 ± 0.6 | 14.2 | 18.0 | 16.47 ± 3.35 |
| chancalan | input-mattcl | 15.3 ± 0.6 | 14.2 | 18.5 | 16.48 ± 3.35 |
| pting | input-chancalan | 15.3 ± 0.5 | 14.4 | 18.5 | 16.55 ± 3.36 |
| mattcl-py | input-mattcl | 15.4 ± 0.5 | 14.4 | 18.6 | 16.58 ± 3.37 |
| mattcl-py | input-mikofo | 15.4 ± 0.7 | 14.5 | 18.5 | 16.59 ± 3.41 |
| chancalan | input-chancalan | 15.5 ± 0.6 | 14.3 | 18.5 | 16.70 ± 3.39 |
| mattcl-py | input-chancalan | 15.8 ± 0.6 | 14.8 | 18.8 | 17.10 ± 3.48 |
| kcen | input-lanjian | 16.0 ± 0.6 | 15.0 | 19.0 | 17.32 ± 3.51 |
| mattcl-py | input-kcen | 16.2 ± 0.8 | 15.1 | 19.6 | 17.52 ± 3.61 |
| pting | input-kcen | 16.5 ± 4.6 | 14.7 | 59.3 | 17.86 ± 6.13 |
| chancalan | input-kcen | 16.6 ± 4.5 | 15.1 | 72.9 | 17.97 ± 6.08 |
| pting | input-lanjian | 17.1 ± 0.7 | 16.1 | 20.0 | 18.46 ± 3.76 |
| chancalan | input-lanjian | 17.5 ± 0.7 | 16.4 | 20.3 | 18.84 ± 3.84 |
| mattcl-py | input-lanjian | 17.8 ± 0.6 | 17.1 | 20.9 | 19.19 ± 3.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|