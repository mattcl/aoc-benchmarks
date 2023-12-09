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
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.3 | 1.0 | 1.00 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.0 | 1.00 ± 0.29 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.30 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.01 ± 0.29 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.5 | 1.02 ± 0.29 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.29 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.30 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.9 | 1.05 ± 0.29 |
| mattcl-ts | input-mattcl | 11.8 ± 0.4 | 10.7 | 13.0 | 15.27 ± 2.97 |
| mattcl-ts | input-pting | 12.4 ± 0.4 | 11.5 | 13.2 | 15.95 ± 3.08 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.5 | 13.2 | 16.06 ± 3.10 |
| mattcl-ts | input-lanjian | 13.1 ± 0.4 | 11.9 | 14.3 | 16.85 ± 3.26 |
| kcen | input-mattcl | 14.9 ± 0.7 | 13.5 | 18.1 | 19.24 ± 3.79 |
| pting | input-mattcl | 15.1 ± 0.7 | 14.0 | 18.4 | 19.52 ± 3.83 |
| kcen | input-pting | 15.1 ± 0.7 | 14.1 | 18.7 | 19.52 ± 3.83 |
| kcen | input-kcen | 15.2 ± 0.6 | 14.4 | 18.9 | 19.58 ± 3.82 |
| mattcl-py | input-mattcl | 15.3 ± 0.6 | 14.2 | 18.6 | 19.74 ± 3.85 |
| pting | input-pting | 15.7 ± 0.6 | 14.6 | 18.5 | 20.22 ± 3.94 |
| pting | input-kcen | 15.9 ± 0.5 | 15.0 | 18.5 | 20.52 ± 3.98 |
| mattcl-py | input-pting | 15.9 ± 0.5 | 14.8 | 18.8 | 20.55 ± 3.99 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 15.0 | 19.7 | 20.66 ± 4.04 |
| kcen | input-lanjian | 16.5 ± 3.8 | 15.1 | 62.8 | 21.25 ± 6.39 |
| pting | input-lanjian | 17.2 ± 0.7 | 16.0 | 20.3 | 22.14 ± 4.33 |
| mattcl-py | input-lanjian | 17.7 ± 0.7 | 16.6 | 20.9 | 22.82 ± 4.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|