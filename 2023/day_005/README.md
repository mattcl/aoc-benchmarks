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
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.7 | 1.03 ± 0.33 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.32 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.04 ± 0.33 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.4 | 1.6 | 1.06 ± 0.32 |
| lanjian | input-pting | 1.0 ± 0.1 | 0.3 | 1.6 | 1.07 ± 0.32 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.7 | 1.09 ± 0.33 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.2 | 1.09 ± 0.32 |
| mattcl-ts | input-mattcl | 12.7 ± 0.4 | 11.6 | 13.6 | 14.23 ± 3.63 |
| mattcl-ts | input-pting | 13.1 ± 0.4 | 12.1 | 14.0 | 14.69 ± 3.75 |
| mattcl-ts | input-kcen | 13.4 ± 4.2 | 12.3 | 71.9 | 15.01 ± 6.04 |
| mattcl-ts | input-lanjian | 13.9 ± 0.3 | 13.2 | 15.1 | 15.65 ± 3.99 |
| kcen | input-mattcl | 15.1 ± 0.6 | 14.0 | 18.4 | 16.91 ± 4.35 |
| pting | input-mattcl | 15.2 ± 0.6 | 14.2 | 19.4 | 17.09 ± 4.39 |
| kcen | input-pting | 15.3 ± 0.7 | 14.1 | 18.4 | 17.19 ± 4.42 |
| kcen | input-kcen | 15.5 ± 0.6 | 14.4 | 18.6 | 17.40 ± 4.47 |
| mattcl-py | input-mattcl | 15.6 ± 0.6 | 14.7 | 19.1 | 17.47 ± 4.48 |
| pting | input-pting | 15.9 ± 0.7 | 14.8 | 18.5 | 17.87 ± 4.59 |
| mattcl-py | input-pting | 16.2 ± 0.6 | 15.0 | 18.9 | 18.18 ± 4.66 |
| pting | input-kcen | 16.2 ± 0.7 | 15.3 | 19.2 | 18.18 ± 4.68 |
| mattcl-py | input-kcen | 16.3 ± 0.7 | 15.0 | 19.9 | 18.34 ± 4.73 |
| kcen | input-lanjian | 16.4 ± 0.8 | 15.2 | 19.7 | 18.46 ± 4.76 |
| pting | input-lanjian | 17.4 ± 0.7 | 15.9 | 20.3 | 19.49 ± 5.00 |
| mattcl-py | input-lanjian | 18.0 ± 0.7 | 16.8 | 21.0 | 20.18 ± 5.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|