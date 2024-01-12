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
| mattcl | input-pting | 4.4 ± 0.5 | 3.8 | 6.7 | 1.00 |
| mattcl | input-kcen | 5.3 ± 0.5 | 4.7 | 8.0 | 1.20 ± 0.18 |
| mattcl | input-mattcl | 5.5 ± 0.7 | 4.9 | 9.3 | 1.25 ± 0.20 |
| mattcl | input-lanjian | 6.3 ± 0.5 | 5.8 | 9.1 | 1.44 ± 0.19 |
| lanjian | input-pting | 32.6 ± 0.9 | 31.2 | 35.5 | 7.44 ± 0.85 |
| lanjian | input-kcen | 40.2 ± 1.1 | 39.0 | 43.3 | 9.17 ± 1.05 |
| lanjian | input-mattcl | 43.3 ± 0.8 | 41.9 | 45.9 | 9.88 ± 1.11 |
| lanjian | input-lanjian | 51.8 ± 0.9 | 50.6 | 54.4 | 11.80 ± 1.32 |
| pting | input-pting | 200.7 ± 2.6 | 194.9 | 205.9 | 45.78 ± 5.11 |
| mattcl-py | input-pting | 203.5 ± 2.2 | 200.1 | 207.3 | 46.40 ± 5.17 |
| pting | input-kcen | 254.6 ± 6.2 | 245.1 | 263.5 | 58.06 ± 6.59 |
| pting | input-mattcl | 258.2 ± 4.7 | 250.8 | 263.5 | 58.88 ± 6.62 |
| mattcl-py | input-kcen | 260.9 ± 3.8 | 256.4 | 267.9 | 59.51 ± 6.66 |
| mattcl-py | input-mattcl | 267.8 ± 2.6 | 263.6 | 272.0 | 61.08 ± 6.80 |
| pting | input-lanjian | 324.0 ± 6.4 | 314.2 | 335.1 | 73.89 ± 8.32 |
| mattcl-py | input-lanjian | 332.7 ± 13.0 | 321.3 | 364.3 | 75.89 ± 8.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|