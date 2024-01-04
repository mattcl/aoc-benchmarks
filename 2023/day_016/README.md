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
| mattcl | input-pting | 4.3 ± 0.3 | 3.8 | 6.8 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.4 | 4.8 | 8.7 | 1.22 ± 0.14 |
| mattcl | input-mattcl | 5.3 ± 0.3 | 4.9 | 7.6 | 1.24 ± 0.12 |
| mattcl | input-lanjian | 6.4 ± 0.5 | 5.9 | 9.4 | 1.48 ± 0.16 |
| lanjian | input-pting | 34.0 ± 0.9 | 32.7 | 37.2 | 7.92 ± 0.62 |
| lanjian | input-kcen | 41.9 ± 1.0 | 40.0 | 44.6 | 9.76 ± 0.75 |
| lanjian | input-mattcl | 44.8 ± 1.0 | 42.7 | 47.6 | 10.44 ± 0.80 |
| lanjian | input-lanjian | 54.7 ± 1.6 | 52.5 | 63.6 | 12.75 ± 1.00 |
| pting | input-pting | 203.3 ± 2.8 | 198.6 | 208.3 | 47.41 ± 3.53 |
| mattcl-py | input-pting | 205.8 ± 2.7 | 202.5 | 212.3 | 47.99 ± 3.57 |
| pting | input-kcen | 256.3 ± 5.4 | 250.8 | 268.3 | 59.75 ± 4.56 |
| pting | input-mattcl | 262.9 ± 7.7 | 251.1 | 279.2 | 61.29 ± 4.84 |
| mattcl-py | input-kcen | 264.6 ± 6.7 | 259.5 | 279.1 | 61.69 ± 4.78 |
| mattcl-py | input-mattcl | 277.1 ± 9.9 | 264.8 | 300.9 | 64.62 ± 5.27 |
| pting | input-lanjian | 327.1 ± 3.8 | 320.5 | 330.7 | 76.26 ± 5.66 |
| mattcl-py | input-lanjian | 337.1 ± 3.6 | 333.1 | 342.9 | 78.59 ± 5.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|