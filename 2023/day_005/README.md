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
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-lanjian | 0.7 ± 0.3 | 0.1 | 1.1 | 1.02 ± 0.45 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.37 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.37 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.0 | 1.5 | 1.06 ± 0.38 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.1 | 1.0 | 1.06 ± 0.36 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.37 |
| lanjian | input-lanjian | 0.8 ± 3.2 | 0.0 | 45.4 | 1.12 ± 4.34 |
| mattcl-ts | input-mattcl | 12.4 ± 0.4 | 11.4 | 13.3 | 16.95 ± 4.73 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.9 | 14.4 | 17.31 ± 4.83 |
| mattcl-ts | input-pting | 13.0 ± 2.2 | 12.0 | 44.1 | 17.72 ± 5.78 |
| mattcl-ts | input-lanjian | 13.6 ± 0.3 | 12.8 | 14.5 | 18.60 ± 5.18 |
| kcen | input-mattcl | 14.7 ± 0.6 | 13.6 | 17.9 | 20.03 ± 5.61 |
| pting | input-mattcl | 14.9 ± 0.5 | 13.9 | 18.3 | 20.35 ± 5.69 |
| kcen | input-pting | 15.0 ± 0.6 | 13.8 | 18.2 | 20.49 ± 5.74 |
| mattcl-py | input-mattcl | 15.1 ± 0.5 | 14.0 | 17.6 | 20.61 ± 5.76 |
| kcen | input-kcen | 15.2 ± 0.7 | 14.2 | 18.2 | 20.65 ± 5.80 |
| pting | input-pting | 15.6 ± 0.9 | 14.5 | 19.3 | 21.31 ± 6.03 |
| pting | input-kcen | 15.7 ± 0.6 | 14.6 | 18.5 | 21.36 ± 5.98 |
| mattcl-py | input-pting | 15.9 ± 0.7 | 15.0 | 18.7 | 21.64 ± 6.08 |
| mattcl-py | input-kcen | 16.0 ± 0.6 | 14.7 | 19.3 | 21.74 ± 6.10 |
| kcen | input-lanjian | 16.0 ± 0.5 | 15.2 | 18.7 | 21.77 ± 6.08 |
| pting | input-lanjian | 17.1 ± 2.9 | 16.0 | 54.6 | 23.36 ± 7.58 |
| mattcl-py | input-lanjian | 17.6 ± 0.7 | 16.8 | 20.5 | 24.01 ± 6.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|