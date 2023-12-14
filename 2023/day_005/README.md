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
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.3 | 1.3 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.31 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.28 |
| mattcl | input-chancalan | 0.8 ± 0.1 | 0.1 | 1.0 | 1.04 ± 0.27 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.5 | 1.04 ± 0.30 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.29 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 2.2 | 1.04 ± 0.29 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.2 | 1.05 ± 0.26 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.28 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.4 | 1.6 | 1.09 ± 0.29 |
| mattcl-ts | input-mattcl | 12.6 ± 0.4 | 11.4 | 13.5 | 15.45 ± 3.09 |
| mattcl-ts | input-chancalan | 12.8 ± 0.4 | 11.9 | 13.6 | 15.71 ± 3.15 |
| mattcl-ts | input-kcen | 12.9 ± 0.3 | 12.1 | 13.7 | 15.86 ± 3.17 |
| mattcl-ts | input-pting | 13.2 ± 3.0 | 12.0 | 54.5 | 16.25 ± 4.86 |
| mattcl-ts | input-lanjian | 13.9 ± 0.4 | 12.9 | 15.2 | 17.03 ± 3.40 |
| kcen | input-chancalan | 15.1 ± 0.5 | 14.0 | 18.2 | 18.50 ± 3.71 |
| kcen | input-mattcl | 15.1 ± 0.7 | 13.9 | 18.6 | 18.53 ± 3.76 |
| pting | input-mattcl | 15.2 ± 0.6 | 14.0 | 18.4 | 18.68 ± 3.77 |
| kcen | input-pting | 15.2 ± 0.6 | 14.2 | 18.0 | 18.73 ± 3.78 |
| chancalan | input-mattcl | 15.4 ± 0.6 | 14.0 | 18.9 | 18.88 ± 3.82 |
| mattcl-py | input-mattcl | 15.4 ± 0.7 | 14.2 | 18.4 | 18.89 ± 3.84 |
| kcen | input-kcen | 15.4 ± 0.6 | 14.5 | 18.2 | 18.92 ± 3.82 |
| pting | input-chancalan | 15.6 ± 0.8 | 14.9 | 18.8 | 19.22 ± 3.93 |
| chancalan | input-chancalan | 15.8 ± 0.7 | 14.4 | 18.8 | 19.42 ± 3.96 |
| pting | input-pting | 15.9 ± 0.7 | 14.5 | 19.0 | 19.54 ± 3.98 |
| mattcl-py | input-chancalan | 15.9 ± 0.6 | 14.8 | 18.2 | 19.57 ± 3.94 |
| chancalan | input-pting | 16.0 ± 0.6 | 14.9 | 18.8 | 19.67 ± 3.96 |
| pting | input-kcen | 16.1 ± 0.7 | 14.6 | 19.2 | 19.73 ± 4.00 |
| mattcl-py | input-pting | 16.2 ± 0.7 | 15.0 | 19.4 | 19.90 ± 4.05 |
| kcen | input-lanjian | 16.2 ± 0.7 | 14.8 | 19.2 | 19.91 ± 4.04 |
| mattcl-py | input-kcen | 16.2 ± 0.5 | 15.1 | 19.2 | 19.97 ± 4.01 |
| chancalan | input-kcen | 16.3 ± 0.6 | 15.0 | 19.5 | 19.98 ± 4.02 |
| pting | input-lanjian | 17.3 ± 0.8 | 16.0 | 21.1 | 21.31 ± 4.34 |
| chancalan | input-lanjian | 17.6 ± 0.8 | 16.7 | 20.8 | 21.62 ± 4.41 |
| mattcl-py | input-lanjian | 17.9 ± 0.8 | 16.9 | 20.7 | 22.01 ± 4.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>240320250</pre>|<pre>28580589</pre>|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|