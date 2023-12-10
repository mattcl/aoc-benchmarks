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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 ± 0.32 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.03 ± 0.31 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.30 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.28 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.05 ± 0.30 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.2 | 1.07 ± 0.29 |
| lanjian | input-mattcl | 1.1 ± 3.6 | 0.2 | 52.1 | 1.23 ± 4.06 |
| mattcl-ts | input-mattcl | 11.6 ± 0.4 | 10.6 | 12.6 | 12.92 ± 2.67 |
| mattcl-ts | input-pting | 12.0 ± 0.5 | 11.1 | 13.2 | 13.46 ± 2.79 |
| mattcl-ts | input-kcen | 12.1 ± 0.5 | 11.0 | 13.2 | 13.53 ± 2.80 |
| mattcl-ts | input-lanjian | 12.7 ± 0.4 | 11.6 | 13.9 | 14.13 ± 2.91 |
| kcen | input-mattcl | 15.2 ± 3.2 | 13.7 | 57.0 | 16.95 ± 5.01 |
| kcen | input-pting | 15.2 ± 0.5 | 14.1 | 17.6 | 17.00 ± 3.51 |
| pting | input-mattcl | 15.3 ± 0.7 | 14.2 | 18.8 | 17.05 ± 3.55 |
| kcen | input-kcen | 15.3 ± 0.5 | 14.4 | 17.9 | 17.10 ± 3.54 |
| mattcl-py | input-mattcl | 15.3 ± 0.6 | 14.2 | 18.4 | 17.11 ± 3.54 |
| pting | input-pting | 15.7 ± 0.6 | 14.7 | 18.9 | 17.58 ± 3.64 |
| pting | input-kcen | 16.1 ± 0.7 | 14.8 | 19.0 | 17.93 ± 3.73 |
| mattcl-py | input-pting | 16.1 ± 0.8 | 14.8 | 19.2 | 17.97 ± 3.76 |
| kcen | input-lanjian | 16.2 ± 0.5 | 15.1 | 19.4 | 18.07 ± 3.73 |
| mattcl-py | input-kcen | 16.2 ± 0.8 | 14.9 | 19.1 | 18.07 ± 3.79 |
| pting | input-lanjian | 17.6 ± 2.5 | 16.1 | 43.7 | 19.70 ± 4.91 |
| mattcl-py | input-lanjian | 17.8 ± 0.8 | 16.8 | 21.0 | 19.93 ± 4.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|