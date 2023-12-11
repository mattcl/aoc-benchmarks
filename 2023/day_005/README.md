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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.4 | 1.01 ± 0.29 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.03 ± 0.32 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.1 | 1.04 ± 0.28 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.3 | 1.6 | 1.05 ± 0.30 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.5 | 1.2 | 1.06 ± 0.29 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.6 | 1.3 | 1.10 ± 0.28 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.3 | 1.2 | 1.11 ± 0.28 |
| mattcl-ts | input-mattcl | 12.7 ± 0.4 | 11.7 | 13.8 | 14.02 ± 3.11 |
| mattcl-ts | input-pting | 13.2 ± 0.4 | 12.3 | 14.8 | 14.55 ± 3.24 |
| mattcl-ts | input-kcen | 13.3 ± 2.9 | 12.2 | 53.7 | 14.76 ± 4.57 |
| mattcl-ts | input-lanjian | 14.2 ± 4.1 | 13.1 | 72.0 | 15.76 ± 5.73 |
| kcen | input-mattcl | 15.0 ± 0.5 | 14.0 | 17.7 | 16.63 ± 3.71 |
| pting | input-mattcl | 15.4 ± 2.2 | 14.0 | 44.0 | 17.04 ± 4.45 |
| kcen | input-pting | 15.4 ± 0.7 | 14.3 | 18.5 | 17.07 ± 3.84 |
| kcen | input-kcen | 15.5 ± 0.7 | 14.3 | 18.5 | 17.15 ± 3.85 |
| mattcl-py | input-mattcl | 15.5 ± 0.6 | 14.5 | 18.0 | 17.18 ± 3.84 |
| pting | input-pting | 16.0 ± 0.7 | 14.8 | 19.6 | 17.65 ± 3.96 |
| mattcl-py | input-pting | 16.2 ± 0.6 | 14.8 | 18.8 | 17.94 ± 4.01 |
| pting | input-kcen | 16.3 ± 0.7 | 15.0 | 18.9 | 18.02 ± 4.05 |
| kcen | input-lanjian | 16.3 ± 0.4 | 15.3 | 19.0 | 18.07 ± 4.01 |
| mattcl-py | input-kcen | 16.4 ± 0.6 | 15.2 | 19.5 | 18.18 ± 4.07 |
| pting | input-lanjian | 17.6 ± 2.0 | 16.2 | 41.9 | 19.48 ± 4.84 |
| mattcl-py | input-lanjian | 17.9 ± 0.7 | 16.5 | 20.7 | 19.86 ± 4.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|