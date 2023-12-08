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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 ± 0.35 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.0 | 1.03 ± 0.34 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.32 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.34 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.05 ± 0.36 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.0 | 1.05 ± 0.33 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.3 | 1.08 ± 0.35 |
| mattcl-ts | input-mattcl | 11.6 ± 0.4 | 10.6 | 12.9 | 14.82 ± 3.70 |
| mattcl-ts | input-pting | 12.1 ± 0.4 | 11.0 | 13.2 | 15.53 ± 3.88 |
| mattcl-ts | input-kcen | 12.2 ± 0.4 | 11.1 | 13.2 | 15.66 ± 3.92 |
| mattcl-ts | input-lanjian | 13.0 ± 3.2 | 11.8 | 58.2 | 16.68 ± 5.84 |
| kcen | input-mattcl | 14.7 ± 0.5 | 14.0 | 17.5 | 18.84 ± 4.72 |
| pting | input-mattcl | 15.0 ± 0.5 | 13.9 | 17.7 | 19.14 ± 4.79 |
| kcen | input-pting | 15.0 ± 0.6 | 13.9 | 17.7 | 19.26 ± 4.83 |
| kcen | input-kcen | 15.1 ± 0.5 | 14.0 | 17.8 | 19.36 ± 4.84 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.2 | 18.3 | 19.51 ± 4.91 |
| pting | input-pting | 15.5 ± 0.5 | 14.7 | 18.7 | 19.82 ± 4.96 |
| pting | input-kcen | 15.7 ± 0.6 | 14.6 | 18.5 | 20.08 ± 5.02 |
| mattcl-py | input-pting | 15.8 ± 0.6 | 14.8 | 18.8 | 20.26 ± 5.08 |
| kcen | input-lanjian | 16.0 ± 0.6 | 14.7 | 18.6 | 20.42 ± 5.12 |
| mattcl-py | input-kcen | 16.4 ± 4.8 | 14.8 | 79.9 | 20.95 ± 8.01 |
| pting | input-lanjian | 16.8 ± 0.5 | 16.1 | 20.0 | 21.55 ± 5.38 |
| mattcl-py | input-lanjian | 17.9 ± 4.2 | 16.8 | 71.4 | 22.95 ± 7.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|