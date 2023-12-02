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

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.4 | 1.02 ± 0.33 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.05 ± 0.33 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.1 | 1.2 | 1.06 ± 0.32 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.3 | 1.1 | 1.09 ± 0.32 |
| lanjian | input-pting | 0.8 ± 0.1 | 0.3 | 1.2 | 1.11 ± 0.31 |
| pting | input-mattcl | 16.3 ± 0.5 | 15.4 | 18.8 | 21.70 ± 5.08 |
| pting | input-pting | 16.4 ± 0.6 | 15.3 | 19.4 | 21.80 ± 5.14 |
| pting | input-lanjian | 16.4 ± 0.6 | 15.4 | 19.4 | 21.81 ± 5.13 |
| mattcl-py | input-lanjian | 17.0 ± 0.6 | 16.1 | 19.9 | 22.59 ± 5.30 |
| mattcl-py | input-mattcl | 17.1 ± 0.7 | 16.3 | 20.6 | 22.73 ± 5.37 |
| mattcl-py | input-pting | 17.3 ± 2.8 | 15.8 | 53.3 | 23.03 ± 6.53 |
| kcen | input-lanjian | 17.5 ± 0.6 | 16.5 | 20.8 | 23.29 ± 5.47 |
| kcen | input-pting | 17.7 ± 0.6 | 16.6 | 20.6 | 23.51 ± 5.52 |
| kcen | input-mattcl | 18.2 ± 5.4 | 16.7 | 71.9 | 24.23 ± 9.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|