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
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.5 | 1.00 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.1 | 1.1 | 1.00 ± 0.46 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.4 | 1.01 ± 0.43 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.43 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.9 | 1.05 ± 0.47 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.0 | 1.05 ± 0.42 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.0 | 1.3 | 1.06 ± 0.43 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.3 | 1.5 | 1.14 ± 0.41 |
| mattcl-ts | input-mattcl | 12.7 ± 0.5 | 11.7 | 16.5 | 17.67 ± 5.65 |
| mattcl-ts | input-kcen | 13.4 ± 2.5 | 12.1 | 48.4 | 18.52 ± 6.84 |
| mattcl-ts | input-pting | 13.4 ± 0.4 | 12.4 | 15.2 | 18.55 ± 5.91 |
| mattcl-ts | input-lanjian | 14.3 ± 4.1 | 12.9 | 55.2 | 19.88 ± 8.47 |
| kcen | input-mattcl | 15.2 ± 0.6 | 14.2 | 17.9 | 21.07 ± 6.74 |
| kcen | input-kcen | 15.2 ± 0.6 | 14.1 | 18.2 | 21.14 ± 6.75 |
| mattcl-py | input-mattcl | 15.8 ± 3.3 | 14.4 | 59.9 | 21.87 ± 8.29 |
| pting | input-kcen | 15.9 ± 0.7 | 14.7 | 18.7 | 22.04 ± 7.06 |
| pting | input-mattcl | 15.9 ± 3.4 | 14.4 | 61.7 | 22.05 ± 8.41 |
| kcen | input-pting | 15.9 ± 0.6 | 14.8 | 18.5 | 22.12 ± 7.07 |
| pting | input-pting | 16.2 ± 0.5 | 14.9 | 17.8 | 22.42 ± 7.14 |
| kcen | input-lanjian | 16.2 ± 1.8 | 14.8 | 37.8 | 22.47 ± 7.53 |
| mattcl-py | input-kcen | 16.5 ± 2.8 | 15.0 | 52.5 | 22.86 ± 8.21 |
| mattcl-py | input-pting | 16.7 ± 0.7 | 15.0 | 19.4 | 23.16 ± 7.41 |
| pting | input-lanjian | 17.3 ± 0.6 | 16.0 | 20.4 | 23.98 ± 7.66 |
| mattcl-py | input-lanjian | 17.8 ± 0.7 | 16.4 | 21.0 | 24.62 ± 7.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|