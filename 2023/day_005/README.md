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
| lanjian | input-pting | 0.6 ± 0.3 | 0.2 | 1.1 | 1.00 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.54 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.30 ± 0.60 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.31 ± 0.57 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.34 ± 0.62 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.41 ± 0.64 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.2 | 1.50 ± 0.63 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.2 | 1.53 ± 0.64 |
| mattcl-ts | input-mattcl | 12.1 ± 0.5 | 10.9 | 14.4 | 18.81 ± 7.35 |
| mattcl-ts | input-pting | 12.2 ± 0.4 | 11.0 | 13.5 | 19.00 ± 7.41 |
| mattcl-ts | input-kcen | 12.4 ± 0.4 | 11.4 | 13.4 | 19.29 ± 7.51 |
| mattcl-ts | input-lanjian | 13.4 ± 0.4 | 12.4 | 15.1 | 20.77 ± 8.09 |
| pting | input-mattcl | 15.2 ± 0.5 | 14.1 | 17.9 | 23.53 ± 9.18 |
| kcen | input-pting | 15.2 ± 0.4 | 14.2 | 17.2 | 23.67 ± 9.22 |
| kcen | input-mattcl | 15.4 ± 0.5 | 14.0 | 18.0 | 23.93 ± 9.33 |
| kcen | input-kcen | 15.8 ± 0.6 | 14.7 | 19.1 | 24.52 ± 9.57 |
| mattcl-py | input-mattcl | 16.0 ± 0.5 | 14.6 | 18.1 | 24.85 ± 9.68 |
| mattcl-py | input-kcen | 16.2 ± 0.5 | 15.2 | 18.6 | 25.16 ± 9.80 |
| pting | input-pting | 16.2 ± 0.5 | 15.1 | 18.7 | 25.22 ± 9.83 |
| mattcl-py | input-pting | 16.3 ± 0.5 | 15.3 | 19.3 | 25.27 ± 9.85 |
| pting | input-kcen | 16.3 ± 2.1 | 15.0 | 39.3 | 25.28 ± 10.33 |
| kcen | input-lanjian | 17.2 ± 1.6 | 15.0 | 23.1 | 26.65 ± 10.63 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.4 | 20.0 | 27.03 ± 10.55 |
| mattcl-py | input-lanjian | 18.4 ± 0.7 | 17.2 | 23.0 | 28.51 ± 11.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|