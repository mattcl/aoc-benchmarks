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
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.37 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.3 | 1.04 ± 0.35 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.34 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.09 ± 0.35 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.2 | 1.5 | 1.09 ± 0.33 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.11 ± 0.35 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.2 | 1.1 | 1.14 ± 0.31 |
| mattcl-ts | input-pting | 12.6 ± 0.3 | 11.8 | 13.5 | 16.14 ± 4.04 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.6 | 13.5 | 16.14 ± 4.04 |
| mattcl-ts | input-mattcl | 12.7 ± 4.4 | 11.4 | 74.2 | 16.16 ± 6.89 |
| mattcl-ts | input-lanjian | 13.6 ± 0.4 | 12.7 | 14.7 | 17.33 ± 4.34 |
| kcen | input-mattcl | 14.8 ± 0.5 | 14.1 | 17.6 | 18.86 ± 4.74 |
| pting | input-mattcl | 15.1 ± 0.5 | 14.2 | 18.4 | 19.20 ± 4.83 |
| kcen | input-pting | 15.1 ± 0.5 | 14.1 | 18.3 | 19.30 ± 4.85 |
| mattcl-py | input-mattcl | 15.1 ± 0.5 | 14.2 | 18.4 | 19.31 ± 4.85 |
| kcen | input-kcen | 15.2 ± 0.6 | 14.1 | 18.4 | 19.33 ± 4.87 |
| pting | input-pting | 15.6 ± 0.6 | 14.4 | 18.6 | 19.87 ± 5.00 |
| pting | input-kcen | 15.9 ± 0.6 | 14.8 | 18.4 | 20.30 ± 5.12 |
| mattcl-py | input-pting | 16.0 ± 0.7 | 14.9 | 18.7 | 20.39 ± 5.16 |
| kcen | input-lanjian | 16.1 ± 0.8 | 14.9 | 18.8 | 20.57 ± 5.22 |
| mattcl-py | input-kcen | 16.3 ± 3.0 | 14.9 | 56.2 | 20.82 ± 6.45 |
| pting | input-lanjian | 17.0 ± 0.7 | 16.1 | 19.9 | 21.75 ± 5.48 |
| mattcl-py | input-lanjian | 17.6 ± 0.6 | 16.7 | 20.7 | 22.49 ± 5.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|