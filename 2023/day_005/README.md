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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.31 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 2.1 | 0.1 | 29.7 | 1.03 ± 2.48 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.04 ± 0.31 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.30 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.2 | 1.05 ± 0.28 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.32 |
| mattcl-ts | input-mattcl | 12.2 ± 0.4 | 11.1 | 13.3 | 14.57 ± 3.21 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.6 | 13.7 | 15.14 ± 3.31 |
| mattcl-ts | input-pting | 12.7 ± 0.3 | 11.7 | 13.6 | 15.16 ± 3.32 |
| mattcl-ts | input-lanjian | 13.5 ± 0.4 | 12.4 | 14.4 | 16.17 ± 3.54 |
| kcen | input-mattcl | 15.0 ± 0.6 | 13.8 | 18.3 | 17.92 ± 3.95 |
| pting | input-mattcl | 15.2 ± 0.7 | 14.0 | 18.5 | 18.19 ± 4.03 |
| kcen | input-pting | 15.2 ± 0.5 | 14.1 | 17.7 | 18.19 ± 4.00 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.4 | 18.2 | 18.39 ± 4.05 |
| pting | input-pting | 15.8 ± 0.7 | 14.9 | 19.3 | 18.92 ± 4.20 |
| kcen | input-kcen | 15.9 ± 4.8 | 14.3 | 63.9 | 18.96 ± 7.08 |
| pting | input-kcen | 16.0 ± 0.6 | 15.1 | 18.7 | 19.13 ± 4.21 |
| mattcl-py | input-pting | 16.1 ± 0.6 | 14.8 | 18.6 | 19.26 ± 4.26 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.0 | 18.7 | 19.44 ± 4.30 |
| mattcl-py | input-kcen | 16.5 ± 2.0 | 15.2 | 41.4 | 19.66 ± 4.91 |
| pting | input-lanjian | 17.2 ± 0.7 | 15.9 | 19.9 | 20.60 ± 4.56 |
| mattcl-py | input-lanjian | 18.0 ± 0.7 | 16.8 | 20.9 | 21.47 ± 4.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|