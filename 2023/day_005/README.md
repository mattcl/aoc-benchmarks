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
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.33 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.6 | 1.04 ± 0.34 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.6 | 1.05 ± 0.33 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.06 ± 0.33 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.5 | 1.07 ± 0.35 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.08 ± 0.35 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.4 | 1.2 | 1.09 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.5 | 1.2 | 1.11 ± 0.31 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.1 | 1.11 ± 0.31 |
| mattcl-ts | input-mattcl | 12.7 ± 0.4 | 11.6 | 14.1 | 14.44 ± 3.61 |
| mattcl-ts | input-chancalan | 12.9 ± 0.3 | 11.9 | 13.7 | 14.67 ± 3.65 |
| mattcl-ts | input-pting | 13.0 ± 0.4 | 12.3 | 14.0 | 14.82 ± 3.70 |
| mattcl-ts | input-kcen | 13.0 ± 0.3 | 12.3 | 14.2 | 14.83 ± 3.70 |
| mattcl-ts | input-lanjian | 13.9 ± 0.3 | 12.9 | 14.8 | 15.87 ± 3.95 |
| kcen | input-mattcl | 15.0 ± 0.6 | 14.0 | 18.5 | 17.11 ± 4.30 |
| kcen | input-chancalan | 15.2 ± 0.6 | 14.1 | 17.7 | 17.30 ± 4.34 |
| kcen | input-pting | 15.4 ± 0.6 | 14.4 | 18.4 | 17.54 ± 4.40 |
| chancalan | input-mattcl | 15.4 ± 0.7 | 14.2 | 19.0 | 17.59 ± 4.42 |
| pting | input-chancalan | 15.5 ± 0.4 | 14.7 | 18.1 | 17.68 ± 4.41 |
| kcen | input-kcen | 15.5 ± 0.7 | 14.2 | 18.6 | 17.70 ± 4.47 |
| mattcl-py | input-mattcl | 15.5 ± 0.7 | 14.4 | 18.5 | 17.70 ± 4.45 |
| pting | input-mattcl | 15.6 ± 3.1 | 14.5 | 57.4 | 17.78 ± 5.65 |
| chancalan | input-chancalan | 15.9 ± 2.4 | 14.7 | 47.5 | 18.15 ± 5.27 |
| pting | input-pting | 15.9 ± 0.6 | 14.8 | 19.0 | 18.19 ± 4.57 |
| mattcl-py | input-chancalan | 16.0 ± 0.6 | 15.0 | 18.7 | 18.25 ± 4.58 |
| pting | input-kcen | 16.1 ± 0.4 | 15.1 | 18.4 | 18.33 ± 4.57 |
| chancalan | input-pting | 16.1 ± 0.5 | 14.9 | 19.4 | 18.35 ± 4.59 |
| mattcl-py | input-pting | 16.2 ± 0.6 | 15.0 | 19.1 | 18.49 ± 4.63 |
| kcen | input-lanjian | 16.3 ± 0.7 | 14.9 | 19.5 | 18.59 ± 4.68 |
| mattcl-py | input-kcen | 16.3 ± 0.7 | 15.3 | 19.6 | 18.60 ± 4.67 |
| chancalan | input-kcen | 16.4 ± 0.7 | 15.3 | 19.3 | 18.70 ± 4.70 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.3 | 20.8 | 19.72 ± 4.95 |
| chancalan | input-lanjian | 17.5 ± 0.7 | 16.7 | 21.0 | 20.00 ± 5.03 |
| mattcl-py | input-lanjian | 18.0 ± 0.8 | 16.9 | 21.5 | 20.52 ± 5.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|