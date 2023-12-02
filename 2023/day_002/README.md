# Day 2 benchmarks

[link to problem](https://adventofcode.com/2023/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 772.5 ± 211.8 | 40.7 | 1294.4 | 1.00 |
| mattcl | input-mattcl | 784.1 ± 200.7 | 87.6 | 1073.1 | 1.01 ± 0.38 |
| mattcl | input-lanjian | 871.4 ± 112.7 | 468.5 | 1465.2 | 1.13 ± 0.34 |
| pting | input-mattcl | 17445.8 ± 545.1 | 16867.0 | 20365.5 | 22.58 ± 6.23 |
| pting | input-lanjian | 17518.8 ± 670.1 | 16667.1 | 20409.0 | 22.68 ± 6.28 |
| pting | input-pting | 17555.0 ± 674.7 | 16358.6 | 20635.0 | 22.73 ± 6.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>2256</pre>|<pre>8693</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|