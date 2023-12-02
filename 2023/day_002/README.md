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

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 770.2 ± 251.8 | 31.7 | 1387.8 | 1.00 |
| mattcl | input-mattcl | 799.5 ± 196.0 | 44.2 | 1020.4 | 1.04 ± 0.42 |
| mattcl | input-lanjian | 811.8 ± 210.0 | 39.0 | 1271.8 | 1.05 ± 0.44 |
| lanjian | input-mattcl | 851.2 ± 182.0 | 153.3 | 1387.5 | 1.11 ± 0.43 |
| lanjian | input-lanjian | 858.4 ± 165.7 | 161.8 | 1237.4 | 1.11 ± 0.42 |
| lanjian | input-pting | 870.7 ± 162.4 | 176.7 | 1540.0 | 1.13 ± 0.43 |
| pting | input-mattcl | 17559.3 ± 664.6 | 17025.2 | 20336.7 | 22.80 ± 7.50 |
| pting | input-lanjian | 17565.5 ± 708.1 | 16615.1 | 20948.5 | 22.81 ± 7.51 |
| pting | input-pting | 17679.9 ± 741.8 | 16578.8 | 20543.6 | 22.96 ± 7.57 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|