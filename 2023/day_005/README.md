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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 0.9 | 1.01 ± 0.34 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.35 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.1 | 1.0 | 1.05 ± 0.32 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.05 ± 0.34 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.2 | 1.06 ± 0.34 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.1 | 1.2 | 1.09 ± 0.34 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.09 ± 0.36 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 10.8 | 13.1 | 16.04 ± 4.02 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.3 | 13.2 | 16.68 ± 4.17 |
| mattcl-ts | input-pting | 12.5 ± 0.3 | 11.5 | 13.4 | 16.69 ± 4.18 |
| mattcl-ts | input-lanjian | 13.3 ± 0.4 | 12.3 | 14.4 | 17.79 ± 4.46 |
| kcen | input-mattcl | 14.8 ± 0.7 | 13.7 | 17.7 | 19.73 ± 4.99 |
| pting | input-mattcl | 15.0 ± 0.7 | 13.9 | 18.1 | 20.07 ± 5.07 |
| kcen | input-kcen | 15.1 ± 0.6 | 14.1 | 18.2 | 20.15 ± 5.07 |
| kcen | input-pting | 15.1 ± 1.5 | 14.0 | 34.7 | 20.20 ± 5.41 |
| mattcl-py | input-mattcl | 15.1 ± 0.5 | 14.1 | 17.9 | 20.22 ± 5.07 |
| pting | input-pting | 15.6 ± 0.7 | 14.5 | 19.0 | 20.85 ± 5.28 |
| pting | input-kcen | 15.9 ± 0.7 | 14.8 | 18.8 | 21.22 ± 5.37 |
| kcen | input-lanjian | 15.9 ± 0.5 | 15.0 | 18.7 | 21.29 ± 5.35 |
| mattcl-py | input-pting | 15.9 ± 0.8 | 14.8 | 19.5 | 21.31 ± 5.41 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 15.0 | 18.7 | 21.41 ± 5.41 |
| pting | input-lanjian | 17.0 ± 0.7 | 15.7 | 19.8 | 22.74 ± 5.74 |
| mattcl-py | input-lanjian | 17.6 ± 0.6 | 16.5 | 20.1 | 23.49 ± 5.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|