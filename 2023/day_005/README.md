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
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.35 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.3 | 1.1 | 1.03 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.1 | 1.08 ± 0.31 |
| lanjian | input-pting | 1.0 ± 0.1 | 0.5 | 1.1 | 1.09 ± 0.32 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.4 | 1.10 ± 0.32 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.6 | 1.3 | 1.11 ± 0.30 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.4 | 1.13 ± 0.33 |
| mattcl-ts | input-mattcl | 12.1 ± 0.4 | 11.2 | 13.4 | 13.79 ± 3.41 |
| mattcl-ts | input-kcen | 12.5 ± 0.4 | 11.6 | 13.5 | 14.27 ± 3.52 |
| mattcl-ts | input-pting | 12.9 ± 3.7 | 11.6 | 64.6 | 14.70 ± 5.55 |
| mattcl-ts | input-lanjian | 13.2 ± 0.4 | 12.2 | 14.2 | 15.09 ± 3.72 |
| kcen | input-mattcl | 14.8 ± 0.7 | 13.9 | 17.6 | 16.86 ± 4.20 |
| pting | input-mattcl | 15.1 ± 0.7 | 14.1 | 18.5 | 17.25 ± 4.31 |
| kcen | input-kcen | 15.1 ± 0.6 | 14.1 | 18.3 | 17.25 ± 4.28 |
| kcen | input-pting | 15.2 ± 0.6 | 14.2 | 17.9 | 17.32 ± 4.30 |
| mattcl-py | input-mattcl | 15.2 ± 0.5 | 14.1 | 17.9 | 17.39 ± 4.30 |
| pting | input-pting | 15.6 ± 0.7 | 14.6 | 18.7 | 17.79 ± 4.43 |
| pting | input-kcen | 15.7 ± 0.6 | 14.7 | 18.4 | 17.94 ± 4.45 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 15.1 | 19.2 | 18.23 ± 4.54 |
| kcen | input-lanjian | 16.0 ± 0.7 | 15.0 | 18.8 | 18.31 ± 4.56 |
| mattcl-py | input-pting | 16.1 ± 3.1 | 14.7 | 55.8 | 18.43 ± 5.72 |
| pting | input-lanjian | 17.0 ± 0.8 | 15.9 | 20.7 | 19.39 ± 4.84 |
| mattcl-py | input-lanjian | 17.7 ± 0.7 | 16.4 | 20.5 | 20.21 ± 5.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|