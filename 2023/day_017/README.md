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
| mattcl | input-mattcl | 0.024 ± 0.001 | 0.023 | 0.027 | 1.01 ± 0.04 |
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.023 | 0.027 | 1.01 ± 0.04 |
| mattcl-py | input-pting | 0.384 ± 0.001 | 0.382 | 0.386 | 16.17 ± 0.48 |
| mattcl-py | input-lanjian | 0.385 ± 0.005 | 0.377 | 0.392 | 16.22 ± 0.53 |
| mattcl-py | input-mattcl | 0.389 ± 0.003 | 0.383 | 0.394 | 16.38 ± 0.50 |
| pting | input-lanjian | 1.896 ± 0.032 | 1.859 | 1.920 | 79.85 ± 2.72 |
| pting | input-mattcl | 1.908 ± 0.028 | 1.881 | 1.937 | 80.34 ± 2.65 |
| pting | input-pting | 1.925 ± 0.011 | 1.913 | 1.932 | 81.06 ± 2.43 |
| lanjian | input-mattcl | 2.384 ± 0.013 | 2.372 | 2.397 | 100.37 ± 3.01 |
| lanjian | input-pting | 2.406 ± 0.047 | 2.362 | 2.455 | 101.33 ± 3.59 |
| lanjian | input-lanjian | 2.407 ± 0.009 | 2.398 | 2.416 | 101.36 ± 3.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|