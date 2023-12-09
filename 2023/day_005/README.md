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
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 2.9 | 0.0 | 41.8 | 1.01 ± 3.88 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.2 | 1.03 ± 0.32 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.32 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.05 ± 0.32 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.5 | 1.09 ± 0.36 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.10 ± 0.34 |
| mattcl-ts | input-mattcl | 12.1 ± 0.4 | 11.1 | 13.3 | 16.02 ± 3.81 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.5 | 13.8 | 16.60 ± 3.94 |
| mattcl-ts | input-pting | 12.6 ± 0.3 | 11.8 | 13.7 | 16.64 ± 3.95 |
| mattcl-ts | input-lanjian | 13.5 ± 0.4 | 12.5 | 14.5 | 17.78 ± 4.22 |
| kcen | input-mattcl | 14.9 ± 0.6 | 13.9 | 18.8 | 19.71 ± 4.72 |
| kcen | input-pting | 15.1 ± 0.5 | 13.9 | 18.2 | 19.97 ± 4.76 |
| pting | input-mattcl | 15.1 ± 0.6 | 13.9 | 18.3 | 20.00 ± 4.79 |
| kcen | input-kcen | 15.3 ± 0.7 | 14.4 | 18.7 | 20.24 ± 4.85 |
| mattcl-py | input-mattcl | 15.4 ± 0.5 | 14.5 | 16.9 | 20.32 ± 4.83 |
| pting | input-pting | 15.9 ± 0.8 | 14.7 | 19.4 | 20.95 ± 5.04 |
| pting | input-kcen | 16.0 ± 0.7 | 14.7 | 19.7 | 21.19 ± 5.09 |
| kcen | input-lanjian | 16.1 ± 0.7 | 14.8 | 19.3 | 21.29 ± 5.09 |
| mattcl-py | input-pting | 16.2 ± 0.6 | 14.9 | 18.4 | 21.34 ± 5.09 |
| mattcl-py | input-kcen | 16.3 ± 0.7 | 14.8 | 19.1 | 21.47 ± 5.14 |
| pting | input-lanjian | 17.4 ± 3.6 | 16.3 | 63.9 | 23.01 ± 7.23 |
| mattcl-py | input-lanjian | 17.8 ± 0.7 | 16.9 | 21.4 | 23.53 ± 5.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|