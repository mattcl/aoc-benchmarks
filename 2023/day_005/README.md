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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.29 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.28 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.4 | 1.03 ± 0.29 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.3 | 2.3 | 1.05 ± 0.30 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.0 | 1.07 ± 0.28 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.3 | 1.07 ± 0.29 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.0 | 1.11 ± 0.26 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 11.0 | 13.0 | 15.17 ± 2.98 |
| mattcl-ts | input-pting | 12.4 ± 0.4 | 11.5 | 13.4 | 15.74 ± 3.09 |
| mattcl-ts | input-kcen | 12.5 ± 0.4 | 11.2 | 13.9 | 15.79 ± 3.09 |
| mattcl-ts | input-lanjian | 13.2 ± 0.4 | 12.4 | 14.5 | 16.76 ± 3.27 |
| kcen | input-mattcl | 14.7 ± 0.6 | 13.6 | 17.4 | 18.59 ± 3.68 |
| pting | input-mattcl | 15.0 ± 0.5 | 14.1 | 18.0 | 18.98 ± 3.72 |
| kcen | input-pting | 15.1 ± 0.6 | 14.0 | 18.1 | 19.15 ± 3.78 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.3 | 18.1 | 19.20 ± 3.78 |
| kcen | input-kcen | 15.2 ± 0.7 | 14.1 | 18.6 | 19.22 ± 3.82 |
| pting | input-pting | 15.5 ± 0.6 | 14.7 | 18.7 | 19.64 ± 3.87 |
| pting | input-kcen | 15.8 ± 0.7 | 15.1 | 18.8 | 20.00 ± 3.96 |
| kcen | input-lanjian | 16.0 ± 0.6 | 14.9 | 18.5 | 20.20 ± 3.98 |
| mattcl-py | input-pting | 16.0 ± 0.8 | 14.6 | 18.9 | 20.22 ± 4.03 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 14.7 | 19.0 | 20.27 ± 4.01 |
| pting | input-lanjian | 17.1 ± 0.8 | 16.1 | 20.1 | 21.65 ± 4.31 |
| mattcl-py | input-lanjian | 17.7 ± 0.8 | 16.6 | 22.5 | 22.40 ± 4.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|