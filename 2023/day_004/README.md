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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.2 | 1.02 ± 0.27 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.0 | 1.2 | 1.03 ± 0.28 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.4 | 1.6 | 1.05 ± 0.29 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.6 | 1.33 ± 0.38 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.36 ± 0.34 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.41 ± 0.34 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.9 | 1.42 ± 0.38 |
| chancalan | input-mattcl | 17.4 ± 0.6 | 16.4 | 20.5 | 20.50 ± 4.17 |
| chancalan | input-chancalan | 17.5 ± 0.8 | 16.4 | 21.0 | 20.53 ± 4.22 |
| chancalan | input-pting | 17.5 ± 0.8 | 16.7 | 21.1 | 20.61 ± 4.22 |
| mattcl-py | input-chancalan | 17.6 ± 0.8 | 16.6 | 20.8 | 20.71 ± 4.25 |
| mattcl-py | input-mattcl | 17.7 ± 0.6 | 16.8 | 21.0 | 20.84 ± 4.24 |
| mattcl-py | input-pting | 17.8 ± 0.7 | 16.7 | 21.2 | 20.88 ± 4.25 |
| mattcl-py | input-lanjian | 17.8 ± 0.8 | 16.6 | 21.0 | 20.91 ± 4.30 |
| pting | input-mattcl | 18.0 ± 0.7 | 17.0 | 21.0 | 21.16 ± 4.32 |
| pting | input-chancalan | 18.0 ± 0.8 | 16.7 | 22.3 | 21.18 ± 4.35 |
| pting | input-lanjian | 18.1 ± 0.8 | 16.9 | 21.5 | 21.30 ± 4.38 |
| chancalan | input-lanjian | 18.2 ± 6.6 | 16.1 | 79.8 | 21.40 ± 8.87 |
| pting | input-pting | 18.3 ± 0.8 | 17.2 | 21.6 | 21.49 ± 4.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|