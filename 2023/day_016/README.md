# Day 16 benchmarks

[link to problem](https://adventofcode.com/2023/day/16)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 16)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 4.4 ± 0.4 | 3.9 | 6.1 | 1.00 |
| mattcl | input-mattcl | 6.0 ± 3.7 | 5.2 | 57.0 | 1.37 ± 0.85 |
| mattcl | input-lanjian | 6.8 ± 0.6 | 6.2 | 10.3 | 1.55 ± 0.19 |
| mattcl | input-kcen | 10.5 ± 5.5 | 5.9 | 42.4 | 2.38 ± 1.25 |
| lanjian | input-pting | 35.9 ± 6.7 | 32.3 | 55.9 | 8.13 ± 1.65 |
| lanjian | input-mattcl | 48.2 ± 9.0 | 44.1 | 77.1 | 10.91 ± 2.22 |
| lanjian | input-lanjian | 63.4 ± 16.5 | 53.6 | 97.6 | 14.35 ± 3.91 |
| lanjian | input-kcen | 73.2 ± 0.5 | 72.3 | 75.0 | 16.58 ± 1.34 |
| pting | input-pting | 218.0 ± 2.0 | 214.9 | 220.9 | 49.38 ± 4.00 |
| mattcl-py | input-pting | 220.3 ± 4.6 | 214.6 | 229.6 | 49.89 ± 4.15 |
| pting | input-mattcl | 282.7 ± 4.5 | 277.3 | 288.1 | 64.02 ± 5.25 |
| mattcl-py | input-mattcl | 288.0 ± 5.2 | 279.5 | 296.2 | 65.23 ± 5.38 |
| mattcl-py | input-kcen | 324.2 ± 9.4 | 312.4 | 338.3 | 73.43 ± 6.28 |
| pting | input-kcen | 332.8 ± 17.5 | 315.5 | 365.8 | 75.36 ± 7.24 |
| pting | input-lanjian | 347.8 ± 3.9 | 343.7 | 356.5 | 78.76 ± 6.40 |
| mattcl-py | input-lanjian | 362.2 ± 2.7 | 357.4 | 365.0 | 82.04 ± 6.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|