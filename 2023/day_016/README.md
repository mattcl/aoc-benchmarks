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
| mattcl | input-pting | 4.3 ± 0.5 | 3.5 | 7.3 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.7 | 4.3 | 10.5 | 1.20 ± 0.20 |
| mattcl | input-mattcl | 5.4 ± 0.5 | 4.9 | 8.4 | 1.24 ± 0.17 |
| mattcl | input-lanjian | 6.4 ± 0.7 | 5.9 | 12.0 | 1.48 ± 0.22 |
| lanjian | input-pting | 33.9 ± 1.0 | 32.5 | 37.5 | 7.85 ± 0.87 |
| lanjian | input-kcen | 41.5 ± 1.1 | 39.9 | 44.3 | 9.62 ± 1.06 |
| lanjian | input-mattcl | 46.4 ± 6.8 | 43.5 | 85.0 | 10.74 ± 1.96 |
| lanjian | input-lanjian | 53.7 ± 1.1 | 52.0 | 56.4 | 12.44 ± 1.35 |
| pting | input-pting | 203.6 ± 2.5 | 200.8 | 209.6 | 47.16 ± 5.07 |
| mattcl-py | input-pting | 207.1 ± 3.4 | 203.0 | 215.2 | 47.97 ± 5.18 |
| pting | input-kcen | 254.5 ± 3.9 | 247.6 | 262.9 | 58.94 ± 6.36 |
| pting | input-mattcl | 266.0 ± 2.3 | 261.7 | 269.5 | 61.61 ± 6.60 |
| mattcl-py | input-kcen | 266.0 ± 5.4 | 259.7 | 274.1 | 61.63 ± 6.70 |
| mattcl-py | input-mattcl | 270.9 ± 3.7 | 264.0 | 276.6 | 62.76 ± 6.76 |
| pting | input-lanjian | 332.5 ± 20.7 | 317.5 | 386.4 | 77.02 ± 9.52 |
| mattcl-py | input-lanjian | 335.9 ± 3.7 | 331.9 | 343.0 | 77.81 ± 8.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|