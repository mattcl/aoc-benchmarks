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
| lanjian | input-kcen | 0.7 ± 0.2 | 0.0 | 1.1 | 1.00 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.0 | 1.2 | 1.00 ± 0.37 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.1 | 1.01 ± 0.33 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.0 | 1.01 ± 0.37 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.0 | 1.07 ± 0.36 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.3 | 1.07 ± 0.37 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.1 | 1.2 | 1.09 ± 0.36 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.3 | 1.4 | 1.11 ± 0.33 |
| mattcl-ts | input-mattcl | 11.9 ± 0.4 | 10.9 | 12.8 | 17.44 ± 4.33 |
| mattcl-ts | input-kcen | 12.4 ± 0.4 | 11.3 | 13.3 | 18.11 ± 4.50 |
| mattcl-ts | input-pting | 12.5 ± 0.4 | 11.2 | 13.5 | 18.20 ± 4.52 |
| mattcl-ts | input-lanjian | 13.2 ± 0.4 | 12.3 | 14.3 | 19.28 ± 4.78 |
| kcen | input-mattcl | 14.9 ± 0.6 | 13.8 | 17.8 | 21.77 ± 5.44 |
| pting | input-mattcl | 15.3 ± 3.0 | 14.1 | 56.1 | 22.44 ± 7.02 |
| kcen | input-pting | 15.4 ± 2.8 | 14.1 | 53.6 | 22.47 ± 6.89 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.5 | 18.1 | 22.49 ± 5.60 |
| kcen | input-kcen | 15.6 ± 3.7 | 14.1 | 65.6 | 22.75 ± 7.80 |
| pting | input-pting | 15.7 ± 0.6 | 14.5 | 18.6 | 22.95 ± 5.71 |
| pting | input-kcen | 15.9 ± 0.6 | 14.7 | 18.7 | 23.26 ± 5.80 |
| kcen | input-lanjian | 16.0 ± 0.6 | 14.8 | 18.9 | 23.46 ± 5.84 |
| mattcl-py | input-pting | 16.1 ± 0.7 | 15.2 | 19.6 | 23.53 ± 5.87 |
| mattcl-py | input-kcen | 16.2 ± 0.7 | 14.8 | 19.4 | 23.70 ± 5.91 |
| pting | input-lanjian | 17.2 ± 0.9 | 15.8 | 20.6 | 25.11 ± 6.31 |
| mattcl-py | input-lanjian | 17.8 ± 0.7 | 16.7 | 21.0 | 25.99 ± 6.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>806029445</pre>|<pre>59370572</pre>|
|input-lanjian|<pre>3374647</pre>|<pre>6082852</pre>|
|input-mattcl|<pre>825516882</pre>|<pre>136096660</pre>|
|input-pting|<pre>993500720</pre>|<pre>4917124</pre>|