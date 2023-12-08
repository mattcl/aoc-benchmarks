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
| lanjian | input-lanjian | 0.8 ± 0.3 | 0.1 | 1.2 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.41 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.4 | 1.07 ± 0.42 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.0 | 1.08 ± 0.41 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.5 | 1.2 | 1.08 ± 0.40 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.4 | 1.08 ± 0.40 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.10 ± 0.41 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.4 | 1.3 | 1.13 ± 0.40 |
| mattcl-ts | input-mattcl | 11.7 ± 0.4 | 10.5 | 12.9 | 14.81 ± 4.83 |
| mattcl-ts | input-kcen | 12.2 ± 0.4 | 11.1 | 13.1 | 15.47 ± 5.04 |
| mattcl-ts | input-pting | 12.2 ± 0.4 | 11.3 | 13.1 | 15.50 ± 5.05 |
| mattcl-ts | input-lanjian | 12.7 ± 0.4 | 11.7 | 14.4 | 16.17 ± 5.26 |
| kcen | input-mattcl | 14.7 ± 0.5 | 14.0 | 17.4 | 18.63 ± 6.08 |
| pting | input-mattcl | 15.0 ± 0.4 | 14.2 | 16.7 | 19.05 ± 6.20 |
| kcen | input-pting | 15.2 ± 0.6 | 14.1 | 18.4 | 19.23 ± 6.28 |
| kcen | input-kcen | 15.2 ± 0.7 | 14.2 | 18.0 | 19.26 ± 6.30 |
| mattcl-py | input-mattcl | 15.4 ± 2.6 | 14.2 | 49.9 | 19.50 ± 7.11 |
| pting | input-pting | 15.6 ± 0.7 | 14.6 | 18.7 | 19.79 ± 6.49 |
| mattcl-py | input-kcen | 15.9 ± 0.6 | 14.9 | 18.3 | 20.23 ± 6.61 |
| mattcl-py | input-pting | 16.1 ± 2.6 | 14.8 | 49.4 | 20.44 ± 7.40 |
| kcen | input-lanjian | 16.1 ± 1.5 | 15.0 | 34.1 | 20.46 ± 6.90 |
| pting | input-kcen | 16.2 ± 4.3 | 14.6 | 73.6 | 20.49 ± 8.60 |
| pting | input-lanjian | 16.9 ± 0.7 | 15.8 | 20.1 | 21.49 ± 7.02 |
| mattcl-py | input-lanjian | 17.6 ± 0.7 | 16.4 | 21.0 | 22.34 ± 7.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|