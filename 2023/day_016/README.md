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
| mattcl | input-pting | 4.2 ± 0.3 | 3.5 | 6.0 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.4 | 4.6 | 7.2 | 1.21 ± 0.12 |
| mattcl | input-mattcl | 5.5 ± 2.8 | 4.8 | 44.1 | 1.31 ± 0.67 |
| mattcl | input-lanjian | 6.3 ± 0.5 | 5.8 | 8.7 | 1.51 ± 0.16 |
| lanjian | input-pting | 33.6 ± 0.7 | 32.4 | 36.2 | 8.05 ± 0.60 |
| lanjian | input-kcen | 41.8 ± 0.9 | 40.3 | 44.4 | 10.03 ± 0.74 |
| lanjian | input-mattcl | 45.9 ± 5.8 | 43.4 | 89.0 | 11.02 ± 1.60 |
| lanjian | input-lanjian | 53.8 ± 0.9 | 52.3 | 56.2 | 12.91 ± 0.94 |
| pting | input-pting | 203.4 ± 2.8 | 200.6 | 208.3 | 48.78 ± 3.52 |
| mattcl-py | input-pting | 206.8 ± 3.8 | 201.9 | 214.7 | 49.61 ± 3.63 |
| pting | input-kcen | 255.3 ± 6.1 | 247.5 | 268.3 | 61.25 ± 4.58 |
| pting | input-mattcl | 263.5 ± 2.7 | 259.1 | 267.3 | 63.19 ± 4.52 |
| mattcl-py | input-kcen | 266.6 ± 5.8 | 260.6 | 276.6 | 63.94 ± 4.74 |
| mattcl-py | input-mattcl | 272.8 ± 6.6 | 266.7 | 290.9 | 65.43 ± 4.90 |
| pting | input-lanjian | 330.2 ± 5.1 | 324.8 | 341.3 | 79.20 ± 5.74 |
| mattcl-py | input-lanjian | 333.2 ± 4.6 | 325.8 | 341.7 | 79.93 ± 5.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|