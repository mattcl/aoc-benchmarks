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

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.33 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.03 ± 0.33 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.4 | 1.03 ± 0.33 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.34 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.6 | 1.04 ± 0.34 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.33 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.06 ± 0.34 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.1 | 1.07 ± 0.35 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.1 | 1.1 | 1.11 ± 0.32 |
| mattcl-ts | input-mattcl | 12.2 ± 0.4 | 11.2 | 13.1 | 15.42 ± 3.72 |
| mattcl-ts | input-chancalan | 12.5 ± 0.3 | 11.6 | 13.4 | 15.80 ± 3.80 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.7 | 13.7 | 15.91 ± 3.82 |
| mattcl-ts | input-pting | 12.6 ± 0.3 | 11.7 | 13.8 | 15.93 ± 3.83 |
| mattcl-ts | input-lanjian | 13.5 ± 0.4 | 12.3 | 14.9 | 17.09 ± 4.12 |
| kcen | input-mattcl | 15.0 ± 0.6 | 14.3 | 17.7 | 18.95 ± 4.58 |
| pting | input-mattcl | 15.1 ± 0.6 | 13.9 | 18.1 | 19.13 ± 4.64 |
| kcen | input-pting | 15.3 ± 0.7 | 14.3 | 18.5 | 19.33 ± 4.70 |
| kcen | input-kcen | 15.4 ± 0.6 | 14.3 | 18.3 | 19.41 ± 4.70 |
| mattcl-py | input-mattcl | 15.4 ± 0.7 | 14.4 | 18.6 | 19.47 ± 4.74 |
| kcen | input-chancalan | 15.4 ± 3.3 | 14.2 | 53.3 | 19.51 ± 6.25 |
| pting | input-chancalan | 15.5 ± 0.6 | 14.6 | 18.0 | 19.60 ± 4.74 |
| pting | input-pting | 15.9 ± 0.7 | 14.7 | 19.0 | 20.04 ± 4.88 |
| mattcl-py | input-chancalan | 16.0 ± 0.7 | 14.6 | 18.9 | 20.20 ± 4.90 |
| mattcl-py | input-pting | 16.1 ± 0.6 | 14.7 | 19.1 | 20.39 ± 4.94 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.0 | 19.7 | 20.60 ± 5.00 |
| pting | input-kcen | 16.3 ± 2.4 | 15.2 | 48.1 | 20.66 ± 5.81 |
| mattcl-py | input-kcen | 16.4 ± 0.7 | 15.2 | 19.6 | 20.67 ± 5.02 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.3 | 20.3 | 21.87 ± 5.30 |
| mattcl-py | input-lanjian | 17.9 ± 0.8 | 17.0 | 21.3 | 22.63 ± 5.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|