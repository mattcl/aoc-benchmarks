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
| mattcl | input-pting | 4.2 ± 0.6 | 3.4 | 10.3 | 1.00 |
| mattcl | input-mattcl | 5.3 ± 0.6 | 4.8 | 10.0 | 1.25 ± 0.22 |
| mattcl | input-lanjian | 6.2 ± 0.5 | 5.7 | 10.6 | 1.47 ± 0.23 |
| lanjian | input-pting | 31.8 ± 0.8 | 30.7 | 34.7 | 7.52 ± 1.02 |
| lanjian | input-mattcl | 42.6 ± 1.1 | 40.2 | 45.6 | 10.06 ± 1.37 |
| lanjian | input-lanjian | 51.1 ± 1.0 | 49.2 | 53.1 | 12.07 ± 1.63 |
| pting | input-pting | 203.2 ± 3.5 | 198.7 | 209.9 | 48.02 ± 6.47 |
| mattcl-py | input-pting | 206.9 ± 3.1 | 203.0 | 211.9 | 48.91 ± 6.57 |
| pting | input-mattcl | 266.3 ± 5.0 | 257.1 | 275.6 | 62.94 ± 8.49 |
| mattcl-py | input-mattcl | 268.9 ± 2.5 | 266.0 | 273.0 | 63.57 ± 8.51 |
| pting | input-lanjian | 320.7 ± 4.8 | 315.2 | 331.0 | 75.80 ± 10.19 |
| mattcl-py | input-lanjian | 337.4 ± 6.2 | 327.7 | 345.4 | 79.76 ± 10.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>8901</pre>|<pre>9064</pre>|
|input-mattcl|<pre>8249</pre>|<pre>8444</pre>|
|input-pting|<pre>7034</pre>|<pre>7759</pre>|