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
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.28 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.4 | 1.01 ± 0.29 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.31 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.6 | 1.06 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.28 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.4 | 1.5 | 1.08 ± 0.28 |
| lanjian | input-pting | 0.9 ± 0.1 | 0.3 | 1.3 | 1.08 ± 0.28 |
| mattcl-ts | input-mattcl | 11.7 ± 0.4 | 10.8 | 13.0 | 13.79 ± 2.95 |
| mattcl-ts | input-kcen | 12.3 ± 0.4 | 11.2 | 13.1 | 14.47 ± 3.08 |
| mattcl-ts | input-pting | 12.6 ± 3.0 | 11.1 | 42.8 | 14.85 ± 4.74 |
| mattcl-ts | input-lanjian | 12.9 ± 0.3 | 11.9 | 13.9 | 15.18 ± 3.23 |
| kcen | input-mattcl | 15.0 ± 0.5 | 13.8 | 18.5 | 17.58 ± 3.76 |
| pting | input-mattcl | 15.2 ± 0.6 | 14.0 | 18.3 | 17.88 ± 3.85 |
| kcen | input-kcen | 15.2 ± 0.6 | 14.1 | 18.5 | 17.90 ± 3.84 |
| kcen | input-pting | 15.2 ± 0.5 | 14.3 | 18.5 | 17.90 ± 3.83 |
| mattcl-py | input-mattcl | 15.4 ± 0.7 | 14.2 | 19.0 | 18.16 ± 3.91 |
| pting | input-pting | 15.8 ± 0.6 | 14.5 | 18.7 | 18.56 ± 3.98 |
| pting | input-kcen | 16.0 ± 0.7 | 15.0 | 19.2 | 18.81 ± 4.06 |
| kcen | input-lanjian | 16.1 ± 0.7 | 14.9 | 18.9 | 18.93 ± 4.07 |
| mattcl-py | input-kcen | 16.2 ± 0.5 | 15.1 | 18.4 | 18.99 ± 4.05 |
| mattcl-py | input-pting | 16.2 ± 0.5 | 15.0 | 18.5 | 19.04 ± 4.07 |
| pting | input-lanjian | 17.2 ± 0.6 | 15.9 | 20.3 | 20.19 ± 4.32 |
| mattcl-py | input-lanjian | 17.9 ± 0.7 | 16.9 | 21.2 | 21.01 ± 4.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|