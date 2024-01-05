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
| mattcl | input-pting | 4.4 ± 0.5 | 3.8 | 7.2 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.6 | 4.7 | 8.5 | 1.20 ± 0.18 |
| mattcl | input-mattcl | 5.4 ± 0.5 | 4.9 | 7.7 | 1.23 ± 0.18 |
| mattcl | input-lanjian | 6.3 ± 0.6 | 5.8 | 10.4 | 1.46 ± 0.20 |
| lanjian | input-pting | 33.7 ± 1.0 | 32.4 | 36.3 | 7.73 ± 0.87 |
| lanjian | input-kcen | 41.7 ± 1.1 | 39.9 | 45.4 | 9.57 ± 1.07 |
| lanjian | input-mattcl | 45.1 ± 3.3 | 43.1 | 64.9 | 10.36 ± 1.35 |
| lanjian | input-lanjian | 53.5 ± 0.9 | 52.0 | 55.6 | 12.30 ± 1.35 |
| pting | input-pting | 199.9 ± 2.1 | 196.4 | 203.1 | 45.92 ± 5.01 |
| mattcl-py | input-pting | 203.6 ± 2.4 | 200.8 | 209.5 | 46.77 ± 5.11 |
| pting | input-kcen | 251.3 ± 6.5 | 244.1 | 266.1 | 57.73 ± 6.45 |
| pting | input-mattcl | 259.0 ± 4.5 | 252.5 | 266.4 | 59.50 ± 6.54 |
| mattcl-py | input-kcen | 262.1 ± 5.7 | 255.3 | 271.7 | 60.23 ± 6.67 |
| mattcl-py | input-mattcl | 266.5 ± 4.0 | 257.6 | 270.1 | 61.22 ± 6.71 |
| pting | input-lanjian | 322.9 ± 6.9 | 315.0 | 334.9 | 74.20 ± 8.21 |
| mattcl-py | input-lanjian | 331.6 ± 4.4 | 327.0 | 342.0 | 76.19 ± 8.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|