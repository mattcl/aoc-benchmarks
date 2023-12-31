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
| mattcl | input-pting | 4.3 ± 0.5 | 3.8 | 6.7 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.5 | 4.1 | 9.7 | 1.20 ± 0.19 |
| mattcl | input-mattcl | 5.4 ± 0.5 | 4.9 | 7.8 | 1.24 ± 0.19 |
| mattcl | input-lanjian | 6.3 ± 0.7 | 5.8 | 11.0 | 1.46 ± 0.23 |
| lanjian | input-pting | 32.8 ± 0.9 | 31.4 | 35.6 | 7.56 ± 0.93 |
| lanjian | input-kcen | 40.8 ± 1.8 | 38.9 | 52.6 | 9.42 ± 1.21 |
| lanjian | input-mattcl | 43.8 ± 0.9 | 42.7 | 47.9 | 10.12 ± 1.24 |
| lanjian | input-lanjian | 52.7 ± 1.1 | 51.0 | 55.4 | 12.15 ± 1.48 |
| pting | input-pting | 203.3 ± 2.6 | 199.7 | 209.7 | 46.92 ± 5.68 |
| mattcl-py | input-pting | 206.9 ± 2.2 | 204.1 | 211.1 | 47.76 ± 5.77 |
| pting | input-kcen | 254.6 ± 4.8 | 247.5 | 266.2 | 58.77 ± 7.16 |
| pting | input-mattcl | 264.4 ± 3.2 | 258.4 | 269.1 | 61.01 ± 7.37 |
| mattcl-py | input-kcen | 264.8 ± 5.6 | 258.7 | 277.6 | 61.11 ± 7.46 |
| mattcl-py | input-mattcl | 269.2 ± 3.6 | 263.9 | 276.5 | 62.12 ± 7.52 |
| pting | input-lanjian | 328.0 ± 5.6 | 316.2 | 337.3 | 75.69 ± 9.19 |
| mattcl-py | input-lanjian | 336.1 ± 2.4 | 333.6 | 340.0 | 77.58 ± 9.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|