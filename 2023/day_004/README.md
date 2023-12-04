# Day 4 benchmarks

[link to problem](https://adventofcode.com/2023/day/4)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 4)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.1 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.1 | 1.1 | 1.02 ± 0.24 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.3 | 1.04 ± 0.25 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.4 | 1.32 ± 0.30 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.4 | 1.35 ± 0.29 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.3 | 2.0 | 1.48 ± 0.36 |
| mattcl-py | input-lanjian | 17.5 ± 0.4 | 16.6 | 19.7 | 19.67 ± 3.48 |
| mattcl-py | input-mattcl | 17.6 ± 0.7 | 16.8 | 20.6 | 19.78 ± 3.56 |
| mattcl-py | input-pting | 17.6 ± 0.8 | 16.8 | 20.9 | 19.86 ± 3.60 |
| pting | input-lanjian | 18.3 ± 0.7 | 17.2 | 21.1 | 20.62 ± 3.69 |
| pting | input-mattcl | 18.4 ± 0.8 | 17.2 | 21.2 | 20.78 ± 3.75 |
| pting | input-pting | 18.5 ± 0.6 | 17.5 | 21.7 | 20.79 ± 3.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|