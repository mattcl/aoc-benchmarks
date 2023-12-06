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
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.25 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.5 | 1.03 ± 0.24 |
| lanjian | input-pting | 0.9 ± 0.1 | 0.2 | 1.1 | 1.03 ± 0.23 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.4 | 1.1 | 1.03 ± 0.22 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.4 | 1.0 | 1.04 ± 0.22 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.5 | 1.1 | 1.07 ± 0.21 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.3 | 1.10 ± 0.22 |
| mattcl-ts | input-mattcl | 12.1 ± 0.4 | 11.1 | 13.1 | 13.96 ± 2.34 |
| mattcl-ts | input-pting | 12.6 ± 0.3 | 11.9 | 13.5 | 14.48 ± 2.42 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.7 | 13.8 | 14.54 ± 2.43 |
| mattcl-ts | input-lanjian | 13.4 ± 0.3 | 12.6 | 14.3 | 15.50 ± 2.58 |
| kcen | input-mattcl | 15.0 ± 0.6 | 13.8 | 18.5 | 17.26 ± 2.94 |
| pting | input-mattcl | 15.2 ± 0.7 | 13.9 | 18.5 | 17.54 ± 3.00 |
| kcen | input-pting | 15.2 ± 0.6 | 14.4 | 18.0 | 17.58 ± 2.97 |
| kcen | input-kcen | 15.3 ± 0.6 | 14.2 | 18.6 | 17.67 ± 2.99 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.3 | 18.3 | 17.80 ± 3.03 |
| pting | input-pting | 15.9 ± 0.7 | 14.7 | 18.5 | 18.37 ± 3.15 |
| pting | input-kcen | 16.2 ± 0.8 | 14.7 | 19.4 | 18.63 ± 3.20 |
| mattcl-py | input-pting | 16.2 ± 0.7 | 14.9 | 18.8 | 18.73 ± 3.18 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.1 | 20.0 | 18.80 ± 3.21 |
| mattcl-py | input-kcen | 16.6 ± 3.6 | 14.9 | 49.7 | 19.18 ± 5.20 |
| pting | input-lanjian | 17.3 ± 0.6 | 16.1 | 20.8 | 19.89 ± 3.36 |
| mattcl-py | input-lanjian | 17.8 ± 0.6 | 17.0 | 20.8 | 20.57 ± 3.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|