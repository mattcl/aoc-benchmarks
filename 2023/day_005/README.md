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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.37 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.36 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.03 ± 0.36 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.0 | 1.06 ± 0.35 |
| lanjian | input-pting | 0.8 ± 0.1 | 0.2 | 1.2 | 1.08 ± 0.33 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.1 | 1.09 ± 0.34 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.1 | 1.13 ± 0.33 |
| mattcl-ts | input-mattcl | 12.1 ± 0.4 | 11.1 | 13.1 | 15.36 ± 4.01 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.4 | 13.4 | 15.99 ± 4.17 |
| mattcl-ts | input-pting | 12.6 ± 0.3 | 11.5 | 13.3 | 15.99 ± 4.17 |
| mattcl-ts | input-lanjian | 13.3 ± 0.3 | 12.5 | 14.2 | 16.98 ± 4.43 |
| kcen | input-mattcl | 15.1 ± 0.7 | 14.0 | 18.6 | 19.18 ± 5.07 |
| pting | input-mattcl | 15.2 ± 0.6 | 13.9 | 18.1 | 19.33 ± 5.07 |
| kcen | input-pting | 15.2 ± 0.6 | 14.0 | 18.5 | 19.39 ± 5.10 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.2 | 18.5 | 19.54 ± 5.14 |
| kcen | input-kcen | 15.6 ± 4.3 | 14.1 | 74.4 | 19.88 ± 7.55 |
| pting | input-pting | 15.9 ± 0.7 | 14.5 | 18.9 | 20.19 ± 5.32 |
| mattcl-py | input-pting | 16.2 ± 0.7 | 15.1 | 19.0 | 20.55 ± 5.42 |
| pting | input-kcen | 16.2 ± 0.8 | 15.3 | 19.7 | 20.63 ± 5.45 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.1 | 19.2 | 20.69 ± 5.43 |
| mattcl-py | input-kcen | 16.7 ± 4.8 | 14.9 | 68.8 | 21.29 ± 8.21 |
| pting | input-lanjian | 17.3 ± 0.6 | 16.1 | 20.4 | 21.94 ± 5.75 |
| mattcl-py | input-lanjian | 17.9 ± 0.8 | 17.0 | 21.4 | 22.80 ± 6.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|