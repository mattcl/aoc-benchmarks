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

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.0 | 1.2 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.6 | 1.01 ± 0.39 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.07 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.5 | 1.37 ± 0.46 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.3 | 1.9 | 1.40 ± 0.48 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.9 | 1.50 ± 0.46 |
| mattcl-py | input-lanjian | 17.5 ± 0.7 | 16.6 | 20.5 | 22.36 ± 5.96 |
| mattcl-py | input-pting | 17.6 ± 0.6 | 16.9 | 20.8 | 22.46 ± 5.97 |
| mattcl-py | input-mattcl | 17.6 ± 2.4 | 16.4 | 46.9 | 22.52 ± 6.66 |
| chancalan | input-lanjian | 17.7 ± 0.6 | 17.0 | 20.7 | 22.60 ± 6.00 |
| chancalan | input-mattcl | 17.7 ± 0.6 | 16.9 | 20.8 | 22.62 ± 6.01 |
| chancalan | input-pting | 18.0 ± 0.8 | 16.9 | 21.5 | 23.03 ± 6.16 |
| pting | input-lanjian | 18.3 ± 0.8 | 17.3 | 21.2 | 23.45 ± 6.26 |
| pting | input-mattcl | 18.4 ± 0.8 | 17.4 | 21.7 | 23.49 ± 6.28 |
| pting | input-pting | 18.5 ± 0.7 | 17.2 | 21.2 | 23.59 ± 6.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|