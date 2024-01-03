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
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.6 | 1.04 ± 0.33 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.6 | 1.05 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.34 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.4 | 1.1 | 1.06 ± 0.31 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.6 | 1.07 ± 0.33 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.4 | 1.5 | 1.08 ± 0.33 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.4 | 1.2 | 1.08 ± 0.32 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.1 | 1.09 ± 0.32 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.5 | 1.11 ± 0.34 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.6 | 13.4 | 14.32 ± 3.70 |
| mattcl-ts | input-mikofo | 12.7 ± 0.3 | 11.7 | 13.7 | 14.40 ± 3.72 |
| mattcl-ts | input-chancalan | 12.8 ± 0.4 | 11.7 | 13.8 | 14.60 ± 3.77 |
| mattcl-ts | input-kcen | 13.0 ± 0.4 | 12.2 | 14.9 | 14.79 ± 3.82 |
| mattcl-ts | input-lanjian | 13.9 ± 0.4 | 12.9 | 15.2 | 15.84 ± 4.09 |
| kcen | input-mattcl | 15.0 ± 0.5 | 13.9 | 18.2 | 17.02 ± 4.41 |
| kcen | input-mikofo | 15.1 ± 0.6 | 13.8 | 17.9 | 17.14 ± 4.46 |
| pting | input-mikofo | 15.1 ± 0.6 | 13.9 | 18.3 | 17.22 ± 4.47 |
| kcen | input-chancalan | 15.2 ± 0.8 | 13.9 | 18.4 | 17.29 ± 4.53 |
| pting | input-mattcl | 15.3 ± 0.7 | 14.2 | 18.9 | 17.38 ± 4.53 |
| chancalan | input-mattcl | 15.4 ± 0.6 | 14.0 | 17.9 | 17.48 ± 4.55 |
| mattcl-py | input-mikofo | 15.4 ± 0.7 | 14.2 | 18.5 | 17.57 ± 4.57 |
| mattcl-py | input-mattcl | 15.5 ± 0.7 | 14.2 | 18.5 | 17.65 ± 4.60 |
| chancalan | input-mikofo | 15.5 ± 2.1 | 14.2 | 43.8 | 17.67 ± 5.15 |
| kcen | input-kcen | 15.6 ± 2.4 | 14.0 | 45.2 | 17.78 ± 5.32 |
| pting | input-chancalan | 15.6 ± 0.7 | 14.5 | 18.4 | 17.81 ± 4.65 |
| chancalan | input-chancalan | 15.7 ± 0.6 | 14.7 | 18.5 | 17.87 ± 4.64 |
| pting | input-kcen | 16.0 ± 0.6 | 15.1 | 19.3 | 18.27 ± 4.74 |
| kcen | input-lanjian | 16.3 ± 0.8 | 14.8 | 20.7 | 18.54 ± 4.84 |
| mattcl-py | input-kcen | 16.3 ± 0.7 | 15.2 | 19.8 | 18.59 ± 4.84 |
| chancalan | input-kcen | 16.4 ± 0.8 | 15.1 | 19.5 | 18.68 ± 4.88 |
| mattcl-py | input-chancalan | 16.5 ± 2.8 | 14.8 | 41.2 | 18.78 ± 5.77 |
| pting | input-lanjian | 17.3 ± 0.8 | 15.9 | 20.6 | 19.67 ± 5.12 |
| chancalan | input-lanjian | 17.5 ± 0.6 | 16.7 | 20.7 | 19.89 ± 5.15 |
| mattcl-py | input-lanjian | 18.0 ± 0.8 | 17.1 | 21.2 | 20.47 ± 5.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-mikofo|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|