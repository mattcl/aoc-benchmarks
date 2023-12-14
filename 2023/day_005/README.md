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
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.39 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.36 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.37 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.2 | 1.06 ± 0.37 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.38 |
| lanjian | input-pting | 0.8 ± 0.1 | 0.1 | 1.0 | 1.07 ± 0.35 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.08 ± 0.37 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.4 | 1.4 | 1.09 ± 0.36 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.10 ± 0.39 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.8 | 13.5 | 16.51 ± 4.67 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 12.1 | 13.6 | 16.55 ± 4.68 |
| mattcl-ts | input-mattcl | 12.7 ± 2.8 | 11.5 | 52.2 | 16.60 ± 5.96 |
| mattcl-ts | input-pting | 12.8 ± 0.4 | 11.9 | 13.8 | 16.75 ± 4.74 |
| mattcl-ts | input-lanjian | 13.6 ± 0.3 | 12.7 | 14.8 | 17.81 ± 5.04 |
| kcen | input-mattcl | 14.8 ± 0.7 | 13.7 | 18.1 | 19.30 ± 5.52 |
| kcen | input-chancalan | 14.9 ± 0.6 | 13.9 | 17.8 | 19.52 ± 5.55 |
| pting | input-mattcl | 15.0 ± 0.6 | 13.9 | 17.8 | 19.65 ± 5.58 |
| kcen | input-pting | 15.1 ± 0.6 | 14.2 | 17.8 | 19.70 ± 5.60 |
| kcen | input-kcen | 15.1 ± 0.5 | 14.1 | 17.8 | 19.73 ± 5.60 |
| chancalan | input-mattcl | 15.1 ± 0.6 | 14.1 | 18.6 | 19.76 ± 5.61 |
| mattcl-py | input-mattcl | 15.1 ± 0.5 | 14.2 | 17.6 | 19.79 ± 5.61 |
| pting | input-chancalan | 15.2 ± 0.6 | 14.5 | 18.5 | 19.89 ± 5.66 |
| chancalan | input-chancalan | 15.3 ± 0.5 | 14.4 | 18.2 | 19.99 ± 5.67 |
| pting | input-pting | 15.5 ± 0.6 | 14.4 | 18.0 | 20.27 ± 5.76 |
| chancalan | input-pting | 15.7 ± 0.6 | 14.8 | 18.3 | 20.56 ± 5.84 |
| mattcl-py | input-chancalan | 15.8 ± 0.8 | 14.6 | 18.9 | 20.59 ± 5.89 |
| mattcl-py | input-pting | 15.9 ± 0.6 | 14.8 | 19.0 | 20.75 ± 5.90 |
| pting | input-kcen | 15.9 ± 0.6 | 14.8 | 18.6 | 20.75 ± 5.90 |
| kcen | input-lanjian | 16.0 ± 0.8 | 14.7 | 19.4 | 20.89 ± 5.97 |
| chancalan | input-kcen | 16.0 ± 0.6 | 15.0 | 19.0 | 20.95 ± 5.95 |
| mattcl-py | input-kcen | 16.0 ± 0.6 | 14.9 | 18.8 | 20.97 ± 5.97 |
| pting | input-lanjian | 17.0 ± 0.6 | 15.8 | 19.9 | 22.22 ± 6.31 |
| chancalan | input-lanjian | 17.2 ± 0.7 | 16.2 | 19.8 | 22.49 ± 6.40 |
| mattcl-py | input-lanjian | 17.6 ± 0.7 | 16.5 | 20.9 | 23.01 ± 6.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|