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
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.4 | 1.02 ± 0.35 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.2 | 1.04 ± 0.33 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.32 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.31 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.3 | 1.0 | 1.07 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.08 ± 0.32 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.2 | 1.09 ± 0.34 |
| mattcl-ts | input-pting | 12.4 ± 0.4 | 11.5 | 13.4 | 15.65 ± 3.47 |
| mattcl-ts | input-kcen | 12.4 ± 0.3 | 11.4 | 13.2 | 15.66 ± 3.47 |
| mattcl-ts | input-mattcl | 12.6 ± 6.2 | 10.9 | 78.5 | 15.87 ± 8.51 |
| mattcl-ts | input-lanjian | 13.2 ± 0.4 | 12.4 | 14.1 | 16.59 ± 3.68 |
| kcen | input-mattcl | 15.0 ± 0.7 | 13.7 | 18.3 | 18.96 ± 4.25 |
| kcen | input-pting | 15.2 ± 0.6 | 14.2 | 18.0 | 19.21 ± 4.29 |
| kcen | input-kcen | 15.4 ± 0.7 | 14.2 | 19.1 | 19.37 ± 4.34 |
| pting | input-mattcl | 15.5 ± 3.0 | 14.2 | 54.4 | 19.49 ± 5.69 |
| mattcl-py | input-mattcl | 15.5 ± 0.6 | 14.2 | 18.4 | 19.49 ± 4.35 |
| pting | input-pting | 15.8 ± 0.7 | 14.5 | 19.3 | 19.97 ± 4.48 |
| pting | input-kcen | 16.0 ± 0.6 | 14.7 | 19.4 | 20.16 ± 4.49 |
| mattcl-py | input-kcen | 16.2 ± 0.7 | 14.9 | 19.6 | 20.48 ± 4.59 |
| kcen | input-lanjian | 16.3 ± 0.8 | 15.0 | 19.6 | 20.50 ± 4.61 |
| mattcl-py | input-pting | 16.4 ± 3.3 | 15.0 | 61.2 | 20.69 ± 6.21 |
| pting | input-lanjian | 17.3 ± 0.8 | 16.0 | 20.8 | 21.79 ± 4.88 |
| mattcl-py | input-lanjian | 17.8 ± 0.5 | 16.9 | 20.5 | 22.49 ± 4.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|