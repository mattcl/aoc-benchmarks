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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 ± 0.34 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.34 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.34 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.34 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.5 | 1.5 | 1.05 ± 0.32 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.3 | 1.3 | 1.05 ± 0.33 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.7 | 1.08 ± 0.34 |
| mattcl-ts | input-mattcl | 12.1 ± 0.4 | 10.9 | 13.2 | 13.65 ± 3.69 |
| mattcl-ts | input-pting | 12.6 ± 0.4 | 11.5 | 13.5 | 14.22 ± 3.83 |
| mattcl-ts | input-kcen | 12.6 ± 0.4 | 11.6 | 13.9 | 14.26 ± 3.84 |
| mattcl-ts | input-lanjian | 13.3 ± 0.4 | 12.2 | 14.6 | 15.05 ± 4.06 |
| kcen | input-mattcl | 14.9 ± 0.5 | 14.1 | 18.4 | 16.81 ± 4.55 |
| pting | input-mattcl | 15.2 ± 0.5 | 14.1 | 17.9 | 17.14 ± 4.63 |
| kcen | input-kcen | 15.2 ± 0.4 | 14.3 | 17.6 | 17.16 ± 4.63 |
| mattcl-py | input-mattcl | 15.3 ± 0.6 | 14.3 | 18.3 | 17.35 ± 4.71 |
| kcen | input-pting | 15.4 ± 3.6 | 14.3 | 65.0 | 17.47 ± 6.21 |
| pting | input-pting | 15.8 ± 0.7 | 14.7 | 18.8 | 17.86 ± 4.86 |
| pting | input-kcen | 16.0 ± 0.7 | 14.9 | 19.1 | 18.07 ± 4.91 |
| mattcl-py | input-pting | 16.0 ± 0.6 | 15.0 | 18.9 | 18.13 ± 4.91 |
| mattcl-py | input-kcen | 16.1 ± 0.7 | 15.1 | 19.2 | 18.20 ± 4.93 |
| kcen | input-lanjian | 16.1 ± 0.5 | 15.2 | 18.9 | 18.26 ± 4.93 |
| pting | input-lanjian | 17.1 ± 0.6 | 16.1 | 19.8 | 19.34 ± 5.23 |
| mattcl-py | input-lanjian | 17.7 ± 0.6 | 16.9 | 20.7 | 20.04 ± 5.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|