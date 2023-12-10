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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.0 | 1.02 ± 0.32 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.33 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.32 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.0 | 1.06 ± 0.30 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.3 | 1.6 | 1.08 ± 0.32 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.3 | 1.08 ± 0.34 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.4 | 1.5 | 1.09 ± 0.33 |
| mattcl-ts | input-mattcl | 12.2 ± 0.4 | 11.3 | 13.6 | 15.17 ± 3.73 |
| mattcl-ts | input-pting | 12.6 ± 0.4 | 11.7 | 14.5 | 15.71 ± 3.86 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.7 | 13.7 | 15.72 ± 3.85 |
| mattcl-ts | input-lanjian | 13.5 ± 0.4 | 12.6 | 14.6 | 16.77 ± 4.11 |
| kcen | input-mattcl | 15.1 ± 0.9 | 13.8 | 18.5 | 18.84 ± 4.72 |
| pting | input-mattcl | 15.2 ± 0.6 | 14.2 | 18.4 | 18.95 ± 4.69 |
| kcen | input-pting | 15.2 ± 0.6 | 14.3 | 18.2 | 18.96 ± 4.68 |
| kcen | input-kcen | 15.3 ± 0.6 | 14.1 | 18.0 | 19.08 ± 4.71 |
| mattcl-py | input-mattcl | 15.4 ± 0.5 | 14.3 | 18.1 | 19.12 ± 4.71 |
| pting | input-pting | 15.9 ± 0.9 | 14.8 | 19.6 | 19.79 ± 4.95 |
| mattcl-py | input-pting | 16.1 ± 0.6 | 14.7 | 19.2 | 20.00 ± 4.94 |
| mattcl-py | input-kcen | 16.2 ± 0.6 | 14.8 | 19.1 | 20.13 ± 4.97 |
| kcen | input-lanjian | 16.3 ± 0.6 | 15.1 | 19.6 | 20.26 ± 5.00 |
| pting | input-kcen | 16.5 ± 4.3 | 14.9 | 69.5 | 20.56 ± 7.34 |
| pting | input-lanjian | 17.4 ± 0.8 | 16.5 | 20.4 | 21.61 ± 5.36 |
| mattcl-py | input-lanjian | 17.9 ± 0.7 | 16.7 | 20.7 | 22.22 ± 5.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|