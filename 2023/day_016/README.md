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
| mattcl | input-pting | 4.3 ± 0.5 | 3.3 | 7.8 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.5 | 4.7 | 8.3 | 1.20 ± 0.18 |
| mattcl | input-mattcl | 5.4 ± 0.7 | 4.8 | 8.9 | 1.26 ± 0.21 |
| mattcl | input-lanjian | 6.3 ± 0.6 | 5.7 | 10.2 | 1.47 ± 0.22 |
| lanjian | input-pting | 33.2 ± 1.0 | 31.8 | 36.5 | 7.81 ± 0.94 |
| lanjian | input-kcen | 41.1 ± 1.2 | 39.1 | 44.5 | 9.67 ± 1.15 |
| lanjian | input-mattcl | 44.0 ± 1.1 | 42.1 | 46.8 | 10.34 ± 1.22 |
| lanjian | input-lanjian | 52.7 ± 0.8 | 51.1 | 54.8 | 12.41 ± 1.45 |
| pting | input-pting | 203.9 ± 3.3 | 200.1 | 210.2 | 47.98 ± 5.61 |
| mattcl-py | input-pting | 207.1 ± 3.2 | 202.7 | 211.9 | 48.74 ± 5.70 |
| pting | input-kcen | 254.2 ± 3.6 | 250.4 | 261.9 | 59.82 ± 6.98 |
| pting | input-mattcl | 262.5 ± 5.1 | 252.3 | 270.2 | 61.76 ± 7.26 |
| mattcl-py | input-kcen | 264.5 ± 2.8 | 260.0 | 270.5 | 62.24 ± 7.24 |
| mattcl-py | input-mattcl | 271.5 ± 5.3 | 266.2 | 280.5 | 63.87 ± 7.51 |
| pting | input-lanjian | 329.6 ± 4.5 | 326.0 | 339.2 | 77.56 ± 9.05 |
| mattcl-py | input-lanjian | 332.5 ± 4.0 | 327.5 | 338.6 | 78.23 ± 9.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|