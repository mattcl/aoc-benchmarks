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
| mattcl | input-pting | 4.3 ± 0.5 | 3.6 | 7.4 | 1.00 |
| mattcl | input-kcen | 5.2 ± 0.6 | 4.7 | 8.9 | 1.22 ± 0.19 |
| mattcl | input-mattcl | 5.4 ± 0.6 | 4.7 | 8.4 | 1.26 ± 0.20 |
| mattcl | input-lanjian | 6.4 ± 0.6 | 5.8 | 9.3 | 1.48 ± 0.21 |
| lanjian | input-pting | 32.7 ± 0.8 | 31.4 | 34.7 | 7.60 ± 0.82 |
| lanjian | input-kcen | 40.7 ± 0.9 | 39.4 | 43.1 | 9.46 ± 1.01 |
| lanjian | input-mattcl | 43.6 ± 1.0 | 42.4 | 46.2 | 10.13 ± 1.08 |
| lanjian | input-lanjian | 52.6 ± 1.0 | 51.0 | 54.8 | 12.22 ± 1.30 |
| pting | input-pting | 197.9 ± 2.2 | 193.9 | 201.2 | 45.97 ± 4.84 |
| mattcl-py | input-pting | 203.4 ± 3.1 | 199.5 | 209.5 | 47.26 ± 5.00 |
| pting | input-kcen | 250.0 ± 4.7 | 245.6 | 259.4 | 58.08 ± 6.17 |
| pting | input-mattcl | 256.9 ± 4.5 | 249.2 | 263.8 | 59.67 ± 6.33 |
| mattcl-py | input-kcen | 264.0 ± 6.9 | 257.2 | 277.8 | 61.31 ± 6.61 |
| mattcl-py | input-mattcl | 264.8 ± 3.0 | 257.3 | 269.6 | 61.52 ± 6.47 |
| pting | input-lanjian | 324.3 ± 4.6 | 316.9 | 331.4 | 75.32 ± 7.95 |
| mattcl-py | input-lanjian | 330.4 ± 6.0 | 321.5 | 337.1 | 76.76 ± 8.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|