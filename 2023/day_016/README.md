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
| mattcl | input-pting | 4.2 ± 0.4 | 3.7 | 6.8 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.5 | 4.7 | 7.8 | 1.22 ± 0.16 |
| mattcl | input-mattcl | 5.3 ± 0.5 | 4.8 | 8.6 | 1.25 ± 0.16 |
| mattcl | input-lanjian | 6.3 ± 0.6 | 5.8 | 10.7 | 1.50 ± 0.19 |
| lanjian | input-pting | 32.9 ± 1.0 | 31.5 | 35.4 | 7.78 ± 0.72 |
| lanjian | input-kcen | 40.9 ± 1.3 | 39.0 | 44.0 | 9.66 ± 0.89 |
| lanjian | input-mattcl | 44.2 ± 4.3 | 42.3 | 78.2 | 10.43 ± 1.35 |
| lanjian | input-lanjian | 52.6 ± 1.0 | 51.0 | 54.9 | 12.42 ± 1.10 |
| pting | input-pting | 202.4 ± 2.0 | 199.4 | 205.6 | 47.82 ± 4.18 |
| mattcl-py | input-pting | 205.9 ± 2.5 | 201.6 | 210.5 | 48.63 ± 4.26 |
| pting | input-kcen | 254.8 ± 7.0 | 245.2 | 266.1 | 60.19 ± 5.48 |
| pting | input-mattcl | 264.8 ± 4.6 | 259.7 | 271.3 | 62.56 ± 5.53 |
| mattcl-py | input-kcen | 266.3 ± 6.8 | 258.2 | 277.2 | 62.92 ± 5.69 |
| mattcl-py | input-mattcl | 268.2 ± 3.0 | 263.4 | 272.0 | 63.36 ± 5.54 |
| pting | input-lanjian | 329.7 ± 7.0 | 320.2 | 345.5 | 77.90 ± 6.96 |
| mattcl-py | input-lanjian | 334.7 ± 5.3 | 328.3 | 344.6 | 79.06 ± 6.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|