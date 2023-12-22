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
| mattcl | input-pting | 4.4 ± 0.6 | 3.4 | 8.7 | 1.00 |
| mattcl | input-mattcl | 5.4 ± 0.6 | 4.8 | 8.7 | 1.24 ± 0.21 |
| mattcl | input-lanjian | 6.4 ± 0.6 | 5.8 | 10.0 | 1.46 ± 0.23 |
| lanjian | input-pting | 33.5 ± 1.0 | 32.1 | 36.6 | 7.65 ± 1.02 |
| lanjian | input-mattcl | 44.1 ± 1.2 | 42.5 | 47.5 | 10.06 ± 1.34 |
| lanjian | input-lanjian | 52.8 ± 1.0 | 51.3 | 55.3 | 12.05 ± 1.59 |
| pting | input-pting | 201.6 ± 3.2 | 197.7 | 207.2 | 46.02 ± 6.04 |
| mattcl-py | input-pting | 203.9 ± 2.5 | 199.9 | 209.5 | 46.55 ± 6.09 |
| pting | input-mattcl | 258.5 ± 4.8 | 252.8 | 267.0 | 59.03 ± 7.77 |
| mattcl-py | input-mattcl | 266.0 ± 5.4 | 258.4 | 277.4 | 60.75 ± 8.01 |
| pting | input-lanjian | 318.1 ± 4.2 | 312.4 | 326.7 | 72.63 ± 9.51 |
| mattcl-py | input-lanjian | 335.0 ± 7.7 | 327.8 | 352.1 | 76.49 ± 10.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|