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
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.36 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.2 | 1.04 ± 0.37 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 0.9 | 1.05 ± 0.34 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.0 | 1.0 | 1.05 ± 0.37 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.0 | 1.0 | 1.06 ± 0.36 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.1 | 1.1 | 1.08 ± 0.34 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.3 | 1.0 | 1.11 ± 0.32 |
| mattcl-ts | input-mattcl | 11.8 ± 0.4 | 11.0 | 12.8 | 16.45 ± 4.14 |
| mattcl-ts | input-pting | 12.4 ± 0.4 | 11.3 | 13.4 | 17.25 ± 4.33 |
| mattcl-ts | input-kcen | 12.4 ± 0.3 | 11.4 | 13.3 | 17.27 ± 4.33 |
| mattcl-ts | input-lanjian | 13.4 ± 3.5 | 12.3 | 62.1 | 18.62 ± 6.71 |
| kcen | input-mattcl | 14.7 ± 0.6 | 13.7 | 18.3 | 20.49 ± 5.19 |
| kcen | input-pting | 15.0 ± 0.5 | 14.0 | 18.2 | 20.90 ± 5.26 |
| pting | input-mattcl | 15.1 ± 0.5 | 13.9 | 17.6 | 20.93 ± 5.27 |
| kcen | input-kcen | 15.1 ± 0.5 | 14.2 | 17.9 | 20.97 ± 5.28 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.3 | 18.7 | 21.17 ± 5.38 |
| pting | input-pting | 15.5 ± 0.7 | 14.7 | 18.5 | 21.56 ± 5.46 |
| pting | input-kcen | 15.8 ± 0.7 | 14.6 | 18.5 | 21.94 ± 5.56 |
| mattcl-py | input-pting | 15.8 ± 0.6 | 14.8 | 18.4 | 21.95 ± 5.54 |
| kcen | input-lanjian | 15.9 ± 0.6 | 14.7 | 19.3 | 22.13 ± 5.59 |
| mattcl-py | input-kcen | 16.0 ± 0.8 | 14.9 | 19.1 | 22.30 ± 5.66 |
| pting | input-lanjian | 17.0 ± 0.6 | 16.1 | 19.9 | 23.58 ± 5.95 |
| mattcl-py | input-lanjian | 17.6 ± 0.7 | 16.6 | 20.8 | 24.52 ± 6.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|