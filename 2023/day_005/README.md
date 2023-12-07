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
| lanjian | input-kcen | 0.9 ± 0.2 | 0.3 | 1.2 | 1.00 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.01 ± 0.28 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.6 | 1.04 ± 0.28 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.0 | 1.06 ± 0.23 |
| lanjian | input-pting | 0.9 ± 0.1 | 0.2 | 1.2 | 1.06 ± 0.26 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.1 | 1.07 ± 0.27 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.08 ± 0.27 |
| mattcl | input-kcen | 0.9 ± 2.6 | 0.1 | 37.6 | 1.09 ± 3.06 |
| mattcl-ts | input-mattcl | 12.1 ± 0.4 | 11.0 | 13.3 | 14.03 ± 2.63 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.5 | 13.3 | 14.53 ± 2.71 |
| mattcl-ts | input-pting | 12.5 ± 0.4 | 11.7 | 13.6 | 14.59 ± 2.72 |
| mattcl-ts | input-lanjian | 13.3 ± 0.4 | 12.0 | 14.4 | 15.45 ± 2.88 |
| kcen | input-mattcl | 15.0 ± 0.7 | 13.9 | 17.7 | 17.39 ± 3.30 |
| kcen | input-pting | 15.2 ± 0.6 | 14.1 | 18.3 | 17.74 ± 3.35 |
| pting | input-mattcl | 15.3 ± 0.7 | 14.2 | 18.4 | 17.78 ± 3.37 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.2 | 18.5 | 17.89 ± 3.38 |
| kcen | input-kcen | 15.5 ± 3.1 | 14.3 | 56.4 | 18.05 ± 4.87 |
| pting | input-pting | 15.7 ± 0.5 | 14.9 | 19.5 | 18.30 ± 3.43 |
| pting | input-kcen | 16.0 ± 0.6 | 14.9 | 19.0 | 18.57 ± 3.50 |
| mattcl-py | input-pting | 16.1 ± 0.7 | 14.8 | 19.4 | 18.73 ± 3.55 |
| kcen | input-lanjian | 16.2 ± 0.6 | 15.2 | 19.0 | 18.81 ± 3.55 |
| mattcl-py | input-kcen | 16.4 ± 3.1 | 14.9 | 57.3 | 19.07 ± 5.03 |
| pting | input-lanjian | 17.1 ± 0.6 | 15.8 | 19.8 | 19.90 ± 3.73 |
| mattcl-py | input-lanjian | 17.9 ± 0.8 | 16.5 | 20.8 | 20.85 ± 3.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|