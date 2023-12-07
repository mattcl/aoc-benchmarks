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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.36 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.34 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.07 ± 0.35 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.3 | 1.1 | 1.08 ± 0.34 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.5 | 1.1 | 1.10 ± 0.32 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.11 ± 0.35 |
| lanjian | input-pting | 0.9 ± 0.1 | 0.5 | 1.1 | 1.12 ± 0.34 |
| mattcl-ts | input-mattcl | 11.7 ± 0.4 | 10.8 | 13.0 | 14.05 ± 3.71 |
| mattcl-ts | input-pting | 12.0 ± 0.4 | 11.0 | 13.1 | 14.42 ± 3.81 |
| mattcl-ts | input-kcen | 12.1 ± 0.4 | 11.3 | 13.3 | 14.57 ± 3.85 |
| mattcl-ts | input-lanjian | 12.9 ± 0.4 | 11.8 | 13.8 | 15.42 ± 4.06 |
| kcen | input-mattcl | 15.2 ± 0.5 | 14.2 | 17.5 | 18.28 ± 4.82 |
| mattcl-py | input-mattcl | 15.8 ± 0.6 | 14.7 | 18.5 | 18.97 ± 5.01 |
| kcen | input-pting | 15.9 ± 3.5 | 14.5 | 55.3 | 19.08 ± 6.50 |
| kcen | input-kcen | 16.0 ± 0.5 | 14.7 | 18.3 | 19.14 ± 5.06 |
| pting | input-pting | 16.1 ± 0.3 | 15.1 | 17.6 | 19.35 ± 5.09 |
| pting | input-kcen | 16.3 ± 0.6 | 15.3 | 18.9 | 19.61 ± 5.18 |
| mattcl-py | input-kcen | 16.7 ± 0.6 | 15.7 | 20.2 | 20.10 ± 5.31 |
| pting | input-mattcl | 16.9 ± 5.4 | 14.6 | 67.0 | 20.23 ± 8.40 |
| mattcl-py | input-pting | 17.0 ± 2.2 | 15.4 | 24.9 | 20.46 ± 5.99 |
| kcen | input-lanjian | 17.2 ± 2.5 | 15.4 | 29.7 | 20.68 ± 6.22 |
| mattcl-py | input-lanjian | 18.3 ± 0.6 | 17.2 | 21.1 | 21.96 ± 5.80 |
| pting | input-lanjian | 18.3 ± 2.9 | 16.4 | 32.5 | 22.00 ± 6.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|