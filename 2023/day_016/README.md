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
| mattcl | input-pting | 4.3 ± 0.4 | 3.6 | 7.0 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.4 | 4.7 | 8.4 | 1.21 ± 0.15 |
| mattcl | input-mattcl | 5.5 ± 0.6 | 4.9 | 9.8 | 1.26 ± 0.18 |
| mattcl | input-lanjian | 6.4 ± 0.7 | 5.9 | 10.6 | 1.49 ± 0.20 |
| lanjian | input-pting | 33.2 ± 1.1 | 31.8 | 36.7 | 7.67 ± 0.71 |
| lanjian | input-kcen | 40.7 ± 0.9 | 39.3 | 43.9 | 9.41 ± 0.84 |
| lanjian | input-mattcl | 44.3 ± 1.3 | 42.8 | 48.2 | 10.25 ± 0.94 |
| lanjian | input-lanjian | 53.0 ± 1.0 | 51.6 | 55.3 | 12.25 ± 1.09 |
| pting | input-pting | 203.9 ± 2.0 | 200.8 | 207.9 | 47.16 ± 4.13 |
| mattcl-py | input-pting | 206.2 ± 2.4 | 202.6 | 210.6 | 47.70 ± 4.19 |
| pting | input-kcen | 252.5 ± 5.5 | 249.2 | 268.6 | 58.41 ± 5.24 |
| pting | input-mattcl | 264.4 ± 4.2 | 259.9 | 274.7 | 61.15 ± 5.40 |
| mattcl-py | input-kcen | 266.7 ± 6.6 | 258.0 | 276.7 | 61.69 ± 5.58 |
| mattcl-py | input-mattcl | 270.6 ± 3.6 | 265.9 | 276.7 | 62.59 ± 5.51 |
| pting | input-lanjian | 329.5 ± 4.8 | 321.2 | 336.2 | 76.21 ± 6.72 |
| mattcl-py | input-lanjian | 334.3 ± 3.3 | 327.0 | 337.8 | 77.32 ± 6.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|