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
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.03 ± 0.38 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.2 | 1.05 ± 0.36 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.1 | 1.07 ± 0.35 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.08 ± 0.36 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.6 | 1.09 ± 0.39 |
| lanjian | input-pting | 0.9 ± 0.1 | 0.4 | 1.2 | 1.09 ± 0.35 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.1 | 1.13 ± 0.36 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.7 | 13.4 | 15.63 ± 4.31 |
| mattcl-ts | input-kcen | 12.9 ± 0.3 | 12.3 | 13.8 | 16.11 ± 4.44 |
| mattcl-ts | input-pting | 13.0 ± 0.3 | 12.2 | 13.9 | 16.15 ± 4.46 |
| mattcl-ts | input-lanjian | 14.1 ± 3.3 | 12.9 | 60.0 | 17.54 ± 6.32 |
| kcen | input-mattcl | 14.9 ± 0.6 | 14.1 | 17.9 | 18.57 ± 5.15 |
| pting | input-mattcl | 15.2 ± 0.6 | 14.1 | 18.4 | 18.88 ± 5.24 |
| kcen | input-pting | 15.2 ± 0.6 | 14.1 | 18.4 | 18.96 ± 5.26 |
| kcen | input-kcen | 15.3 ± 0.5 | 14.4 | 18.4 | 19.03 ± 5.26 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.4 | 18.4 | 19.19 ± 5.33 |
| pting | input-pting | 15.7 ± 0.7 | 14.7 | 19.5 | 19.57 ± 5.44 |
| pting | input-kcen | 16.0 ± 0.5 | 15.1 | 18.6 | 19.91 ± 5.51 |
| kcen | input-lanjian | 16.1 ± 0.6 | 14.9 | 19.0 | 20.06 ± 5.56 |
| mattcl-py | input-pting | 16.1 ± 0.8 | 14.7 | 19.5 | 20.07 ± 5.59 |
| mattcl-py | input-kcen | 16.5 ± 2.4 | 15.2 | 47.7 | 20.55 ± 6.40 |
| pting | input-lanjian | 17.3 ± 0.5 | 16.1 | 19.6 | 21.47 ± 5.93 |
| mattcl-py | input-lanjian | 18.1 ± 3.6 | 16.8 | 63.0 | 22.57 ± 7.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|