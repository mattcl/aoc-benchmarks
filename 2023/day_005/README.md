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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.01 ± 0.30 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.32 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.32 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.03 ± 0.30 |
| lanjian | input-chancalan | 0.8 ± 0.1 | 0.3 | 1.1 | 1.04 ± 0.29 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.31 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.3 | 1.06 ± 0.32 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.5 | 1.0 | 1.07 ± 0.28 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 10.9 | 13.0 | 15.26 ± 3.46 |
| mattcl-ts | input-chancalan | 12.3 ± 0.4 | 11.1 | 13.2 | 15.66 ± 3.54 |
| mattcl-ts | input-pting | 12.4 ± 0.3 | 11.6 | 13.3 | 15.84 ± 3.57 |
| mattcl-ts | input-kcen | 12.4 ± 0.4 | 11.7 | 13.5 | 15.88 ± 3.58 |
| mattcl-ts | input-lanjian | 13.2 ± 0.3 | 12.2 | 14.3 | 16.84 ± 3.79 |
| kcen | input-mattcl | 14.8 ± 0.7 | 13.6 | 17.6 | 18.82 ± 4.30 |
| kcen | input-chancalan | 14.9 ± 0.7 | 13.8 | 18.0 | 19.03 ± 4.34 |
| chancalan | input-mattcl | 15.1 ± 0.5 | 14.2 | 17.6 | 19.20 ± 4.34 |
| pting | input-mattcl | 15.1 ± 0.7 | 14.2 | 18.3 | 19.22 ± 4.39 |
| kcen | input-kcen | 15.1 ± 0.5 | 14.2 | 18.0 | 19.23 ± 4.36 |
| mattcl-py | input-mattcl | 15.1 ± 0.5 | 14.3 | 17.8 | 19.28 ± 4.36 |
| chancalan | input-chancalan | 15.3 ± 0.6 | 14.4 | 18.5 | 19.52 ± 4.44 |
| pting | input-chancalan | 15.3 ± 0.8 | 14.3 | 18.5 | 19.53 ± 4.49 |
| kcen | input-pting | 15.5 ± 3.4 | 14.0 | 47.6 | 19.73 ± 6.23 |
| pting | input-pting | 15.5 ± 0.6 | 14.4 | 18.5 | 19.80 ± 4.49 |
| mattcl-py | input-chancalan | 15.7 ± 0.7 | 14.9 | 18.4 | 20.00 ± 4.56 |
| pting | input-kcen | 15.8 ± 0.6 | 14.8 | 18.6 | 20.16 ± 4.58 |
| mattcl-py | input-pting | 15.9 ± 0.7 | 14.8 | 18.6 | 20.26 ± 4.62 |
| mattcl-py | input-kcen | 15.9 ± 0.6 | 14.8 | 18.5 | 20.26 ± 4.59 |
| kcen | input-lanjian | 15.9 ± 0.7 | 14.8 | 19.1 | 20.32 ± 4.64 |
| chancalan | input-kcen | 16.0 ± 0.5 | 15.0 | 18.6 | 20.36 ± 4.60 |
| chancalan | input-pting | 16.0 ± 2.6 | 14.7 | 50.2 | 20.45 ± 5.65 |
| pting | input-lanjian | 17.0 ± 0.6 | 16.2 | 20.0 | 21.72 ± 4.93 |
| chancalan | input-lanjian | 17.2 ± 0.7 | 16.3 | 20.7 | 21.97 ± 4.99 |
| mattcl-py | input-lanjian | 17.7 ± 0.8 | 16.6 | 20.9 | 22.55 ± 5.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|