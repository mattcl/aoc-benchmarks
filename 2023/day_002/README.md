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
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 843.5 ± 177.2 | 136.0 | 1485.6 | 1.00 |
| mattcl | input-pting | 857.8 ± 158.8 | 161.2 | 1331.7 | 1.02 ± 0.28 |
| mattcl | input-mattcl | 864.7 ± 152.0 | 143.3 | 1029.6 | 1.03 ± 0.28 |
| lanjian | input-lanjian | 872.8 ± 163.9 | 308.6 | 1101.5 | 1.03 ± 0.29 |
| lanjian | input-pting | 883.2 ± 182.7 | 131.0 | 1346.1 | 1.05 ± 0.31 |
| lanjian | input-mattcl | 900.6 ± 150.3 | 147.1 | 1127.6 | 1.07 ± 0.29 |
| mattcl-py | input-lanjian | 17065.3 ± 630.2 | 15940.2 | 19813.6 | 20.23 ± 4.32 |
| mattcl-py | input-mattcl | 17112.5 ± 633.6 | 15997.2 | 20277.0 | 20.29 ± 4.33 |
| pting | input-mattcl | 17539.7 ± 656.0 | 16417.5 | 20800.1 | 20.79 ± 4.44 |
| pting | input-pting | 17606.9 ± 635.1 | 16729.2 | 20412.5 | 20.87 ± 4.45 |
| pting | input-lanjian | 17656.2 ± 826.0 | 16599.5 | 20740.1 | 20.93 ± 4.50 |
| mattcl-py | input-pting | 17658.4 ± 5043.9 | 16015.5 | 67474.7 | 20.94 ± 7.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|