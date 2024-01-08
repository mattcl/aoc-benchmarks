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
| mattcl | input-pting | 4.3 ± 0.7 | 3.5 | 8.5 | 1.00 |
| mattcl | input-kcen | 5.1 ± 0.7 | 4.4 | 10.6 | 1.19 ± 0.25 |
| mattcl | input-mattcl | 5.2 ± 0.4 | 4.8 | 7.1 | 1.21 ± 0.22 |
| mattcl | input-lanjian | 6.2 ± 0.5 | 5.7 | 9.4 | 1.44 ± 0.27 |
| lanjian | input-pting | 32.3 ± 0.9 | 31.3 | 35.2 | 7.46 ± 1.26 |
| lanjian | input-kcen | 39.7 ± 1.0 | 38.4 | 42.5 | 9.18 ± 1.54 |
| lanjian | input-mattcl | 43.3 ± 0.8 | 42.0 | 46.1 | 10.02 ± 1.68 |
| lanjian | input-lanjian | 52.1 ± 1.1 | 50.4 | 55.1 | 12.05 ± 2.02 |
| pting | input-pting | 201.2 ± 2.0 | 198.3 | 204.7 | 46.51 ± 7.74 |
| mattcl-py | input-pting | 204.6 ± 2.8 | 200.4 | 210.2 | 47.31 ± 7.88 |
| pting | input-kcen | 257.8 ± 12.8 | 245.8 | 290.6 | 59.60 ± 10.33 |
| pting | input-mattcl | 258.7 ± 5.4 | 252.4 | 267.7 | 59.80 ± 10.01 |
| mattcl-py | input-kcen | 262.8 ± 5.7 | 256.9 | 273.2 | 60.75 ± 10.18 |
| mattcl-py | input-mattcl | 265.5 ± 3.6 | 259.3 | 271.7 | 61.39 ± 10.23 |
| pting | input-lanjian | 320.5 ± 6.1 | 311.9 | 332.3 | 74.09 ± 12.39 |
| mattcl-py | input-lanjian | 336.1 ± 7.4 | 328.2 | 347.6 | 77.71 ± 13.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7623</pre>|<pre>8244</pre>|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|