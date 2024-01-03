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
| mattcl | input-pting | 4.3 ± 0.5 | 3.7 | 7.9 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.5 | 4.4 | 7.7 | 1.21 ± 0.18 |
| mattcl | input-mattcl | 5.4 ± 0.6 | 4.7 | 8.7 | 1.25 ± 0.19 |
| mattcl | input-lanjian | 6.3 ± 0.6 | 5.7 | 11.9 | 1.48 ± 0.22 |
| lanjian | input-pting | 33.5 ± 0.8 | 32.4 | 36.2 | 7.81 ± 0.88 |
| lanjian | input-kcen | 41.9 ± 1.0 | 40.5 | 44.7 | 9.78 ± 1.11 |
| lanjian | input-mattcl | 44.7 ± 0.9 | 43.5 | 47.2 | 10.43 ± 1.18 |
| lanjian | input-lanjian | 54.1 ± 1.3 | 51.9 | 56.5 | 12.62 ± 1.43 |
| pting | input-pting | 201.3 ± 1.6 | 199.4 | 205.2 | 46.95 ± 5.22 |
| mattcl-py | input-pting | 205.3 ± 2.3 | 201.7 | 210.4 | 47.88 ± 5.34 |
| pting | input-kcen | 257.2 ± 5.6 | 249.4 | 267.5 | 59.98 ± 6.79 |
| pting | input-mattcl | 261.1 ± 6.5 | 249.2 | 271.3 | 60.89 ± 6.93 |
| mattcl-py | input-mattcl | 271.6 ± 4.4 | 264.8 | 279.8 | 63.33 ± 7.10 |
| mattcl-py | input-kcen | 272.9 ± 18.2 | 260.7 | 321.7 | 63.65 ± 8.24 |
| pting | input-lanjian | 326.9 ± 4.0 | 321.0 | 331.5 | 76.25 ± 8.51 |
| mattcl-py | input-lanjian | 334.1 ± 2.2 | 331.0 | 337.2 | 77.92 ± 8.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|