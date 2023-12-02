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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.4 | 1.01 ± 0.34 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.4 | 1.4 | 1.08 ± 0.31 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.2 | 1.1 | 1.08 ± 0.31 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.0 | 1.10 ± 0.31 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.5 | 1.5 | 1.11 ± 0.32 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.1 | 1.2 | 1.11 ± 0.32 |
| pting | input-lanjian | 16.4 ± 0.5 | 15.6 | 19.0 | 20.43 ± 4.83 |
| pting | input-pting | 16.4 ± 0.6 | 15.4 | 19.5 | 20.51 ± 4.87 |
| pting | input-kcen | 16.5 ± 0.7 | 15.4 | 19.5 | 20.52 ± 4.87 |
| pting | input-mattcl | 16.5 ± 0.7 | 15.4 | 19.1 | 20.55 ± 4.88 |
| mattcl-py | input-kcen | 16.5 ± 0.6 | 15.5 | 20.0 | 20.62 ± 4.88 |
| mattcl-py | input-pting | 16.6 ± 0.7 | 15.8 | 19.6 | 20.76 ± 4.93 |
| mattcl-py | input-mattcl | 16.7 ± 0.7 | 15.7 | 19.5 | 20.79 ± 4.94 |
| mattcl-py | input-lanjian | 16.9 ± 2.9 | 15.6 | 50.1 | 21.06 ± 6.14 |
| kcen | input-lanjian | 17.6 ± 0.5 | 17.0 | 20.7 | 21.98 ± 5.19 |
| kcen | input-mattcl | 17.7 ± 0.6 | 16.8 | 21.3 | 22.09 ± 5.22 |
| kcen | input-kcen | 17.7 ± 0.8 | 17.1 | 21.1 | 22.14 ± 5.27 |
| kcen | input-pting | 17.9 ± 0.8 | 16.7 | 21.0 | 22.34 ± 5.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|