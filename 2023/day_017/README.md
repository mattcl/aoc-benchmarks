# Day 17 benchmarks

[link to problem](https://adventofcode.com/2023/day/17)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 17)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [s] | Min [s] | Max [s] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.024 ± 0.001 | 0.023 | 0.027 | 1.00 |
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.023 | 0.027 | 1.01 ± 0.04 |
| mattcl | input-kcen | 0.024 ± 0.001 | 0.023 | 0.027 | 1.02 ± 0.04 |
| mattcl | input-mattcl | 0.024 ± 0.003 | 0.023 | 0.054 | 1.02 ± 0.13 |
| mattcl-py | input-pting | 0.384 ± 0.003 | 0.381 | 0.388 | 16.07 ± 0.52 |
| mattcl-py | input-lanjian | 0.387 ± 0.006 | 0.377 | 0.397 | 16.18 ± 0.56 |
| mattcl-py | input-mattcl | 0.387 ± 0.005 | 0.379 | 0.394 | 16.19 ± 0.54 |
| mattcl-py | input-kcen | 0.388 ± 0.003 | 0.382 | 0.393 | 16.23 ± 0.53 |
| pting | input-pting | 1.878 ± 0.023 | 1.853 | 1.895 | 78.55 ± 2.64 |
| pting | input-mattcl | 1.889 ± 0.013 | 1.874 | 1.897 | 78.98 ± 2.53 |
| pting | input-lanjian | 1.899 ± 0.027 | 1.869 | 1.923 | 79.42 ± 2.74 |
| pting | input-kcen | 1.915 ± 0.005 | 1.910 | 1.920 | 80.07 ± 2.52 |
| lanjian | input-lanjian | 2.421 ± 0.006 | 2.417 | 2.428 | 101.26 ± 3.18 |
| lanjian | input-pting | 2.425 ± 0.024 | 2.406 | 2.452 | 101.40 ± 3.34 |
| lanjian | input-kcen | 2.426 ± 0.028 | 2.394 | 2.448 | 101.46 ± 3.39 |
| lanjian | input-mattcl | 2.443 ± 0.065 | 2.392 | 2.517 | 102.16 ± 4.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|