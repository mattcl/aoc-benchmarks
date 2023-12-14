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
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 ± 0.29 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.32 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.3 | 1.1 | 1.02 ± 0.29 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.2 | 1.04 ± 0.26 |
| lanjian | input-chancalan | 1.0 ± 0.1 | 0.4 | 1.5 | 1.04 ± 0.28 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 1.4 | 1.04 ± 0.29 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.3 | 1.05 ± 0.30 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.4 | 1.6 | 1.05 ± 0.30 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.3 | 1.2 | 1.05 ± 0.28 |
| mattcl-ts | input-mattcl | 12.6 ± 0.4 | 11.4 | 13.5 | 13.70 ± 2.99 |
| mattcl-ts | input-chancalan | 12.8 ± 0.4 | 11.8 | 14.6 | 13.91 ± 3.04 |
| mattcl-ts | input-kcen | 12.9 ± 0.3 | 11.9 | 14.2 | 14.03 ± 3.05 |
| mattcl-ts | input-pting | 13.0 ± 0.3 | 12.2 | 13.8 | 14.11 ± 3.07 |
| mattcl-ts | input-lanjian | 13.7 ± 0.4 | 12.9 | 14.8 | 14.94 ± 3.25 |
| kcen | input-mattcl | 14.9 ± 0.6 | 14.2 | 18.5 | 16.27 ± 3.58 |
| pting | input-mattcl | 15.1 ± 0.5 | 14.2 | 17.8 | 16.49 ± 3.61 |
| kcen | input-pting | 15.2 ± 0.5 | 14.1 | 18.0 | 16.54 ± 3.61 |
| kcen | input-chancalan | 15.2 ± 0.8 | 14.0 | 18.4 | 16.59 ± 3.70 |
| chancalan | input-mattcl | 15.3 ± 0.5 | 14.1 | 18.0 | 16.64 ± 3.65 |
| mattcl-py | input-mattcl | 15.3 ± 0.6 | 14.1 | 18.5 | 16.67 ± 3.66 |
| kcen | input-kcen | 15.3 ± 0.6 | 14.3 | 18.9 | 16.71 ± 3.68 |
| pting | input-chancalan | 15.3 ± 0.5 | 14.5 | 18.4 | 16.71 ± 3.65 |
| chancalan | input-chancalan | 15.6 ± 0.7 | 14.4 | 18.8 | 17.02 ± 3.77 |
| pting | input-pting | 15.8 ± 0.8 | 14.9 | 19.0 | 17.18 ± 3.81 |
| chancalan | input-pting | 15.9 ± 0.6 | 14.9 | 19.2 | 17.32 ± 3.80 |
| pting | input-kcen | 16.0 ± 0.6 | 14.8 | 19.3 | 17.40 ± 3.82 |
| mattcl-py | input-pting | 16.0 ± 0.6 | 15.1 | 18.7 | 17.45 ± 3.83 |
| mattcl-py | input-kcen | 16.1 ± 0.5 | 15.0 | 18.5 | 17.52 ± 3.83 |
| kcen | input-lanjian | 16.2 ± 0.6 | 15.2 | 19.4 | 17.63 ± 3.87 |
| chancalan | input-kcen | 16.2 ± 0.5 | 15.2 | 19.0 | 17.69 ± 3.87 |
| mattcl-py | input-chancalan | 16.4 ± 5.3 | 14.5 | 76.8 | 17.86 ± 6.91 |
| pting | input-lanjian | 17.2 ± 0.7 | 16.4 | 20.5 | 18.70 ± 4.11 |
| chancalan | input-lanjian | 17.5 ± 0.7 | 16.4 | 20.8 | 19.06 ± 4.20 |
| mattcl-py | input-lanjian | 17.8 ± 0.7 | 16.8 | 21.3 | 19.37 ± 4.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|