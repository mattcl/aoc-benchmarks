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
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.34 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.03 ± 0.35 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.2 | 1.03 ± 0.34 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.4 | 1.04 ± 0.34 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.36 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.35 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.0 | 1.06 ± 0.33 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.06 ± 0.35 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.3 | 1.2 | 1.11 ± 0.31 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.5 | 13.5 | 16.16 ± 4.10 |
| mattcl-ts | input-chancalan | 12.8 ± 0.3 | 11.9 | 13.7 | 16.44 ± 4.18 |
| mattcl-ts | input-kcen | 12.8 ± 0.4 | 12.1 | 13.8 | 16.53 ± 4.20 |
| mattcl-ts | input-pting | 12.9 ± 0.4 | 11.9 | 14.5 | 16.59 ± 4.22 |
| mattcl-ts | input-lanjian | 13.8 ± 0.4 | 12.8 | 15.1 | 17.75 ± 4.51 |
| kcen | input-chancalan | 15.1 ± 0.6 | 13.9 | 18.3 | 19.44 ± 4.98 |
| pting | input-mattcl | 15.2 ± 0.6 | 14.4 | 18.2 | 19.54 ± 5.00 |
| kcen | input-mattcl | 15.2 ± 3.8 | 13.5 | 62.4 | 19.57 ± 6.95 |
| kcen | input-kcen | 15.3 ± 0.6 | 14.1 | 18.4 | 19.65 ± 5.02 |
| kcen | input-pting | 15.3 ± 0.8 | 14.4 | 18.7 | 19.70 ± 5.07 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.2 | 18.1 | 19.75 ± 5.04 |
| pting | input-chancalan | 15.5 ± 0.7 | 14.2 | 18.3 | 19.89 ± 5.10 |
| chancalan | input-mattcl | 15.6 ± 3.4 | 14.5 | 61.7 | 20.07 ± 6.71 |
| chancalan | input-chancalan | 15.7 ± 0.7 | 14.4 | 18.7 | 20.22 ± 5.20 |
| pting | input-pting | 15.8 ± 0.6 | 14.8 | 18.5 | 20.29 ± 5.18 |
| mattcl-py | input-chancalan | 15.9 ± 0.5 | 14.8 | 18.4 | 20.51 ± 5.22 |
| chancalan | input-pting | 16.0 ± 0.7 | 14.6 | 19.7 | 20.63 ± 5.29 |
| mattcl-py | input-kcen | 16.1 ± 0.6 | 14.9 | 19.5 | 20.76 ± 5.30 |
| pting | input-kcen | 16.1 ± 0.7 | 15.0 | 20.0 | 20.76 ± 5.33 |
| mattcl-py | input-pting | 16.2 ± 0.7 | 14.9 | 18.9 | 20.84 ± 5.34 |
| chancalan | input-kcen | 16.3 ± 0.7 | 15.1 | 19.5 | 20.91 ± 5.36 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.1 | 18.9 | 20.95 ± 5.37 |
| pting | input-lanjian | 17.2 ± 0.5 | 15.7 | 19.8 | 22.08 ± 5.62 |
| chancalan | input-lanjian | 17.4 ± 0.7 | 16.1 | 20.8 | 22.44 ± 5.73 |
| mattcl-py | input-lanjian | 17.9 ± 0.9 | 16.9 | 23.3 | 23.03 ± 5.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|