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
| mattcl | input-mattcl | 0.024 ± 0.001 | 0.023 | 0.027 | 1.01 ± 0.03 |
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.023 | 0.027 | 1.01 ± 0.04 |
| mattcl-py | input-pting | 0.384 ± 0.003 | 0.379 | 0.388 | 16.12 ± 0.42 |
| mattcl-py | input-mattcl | 0.385 ± 0.004 | 0.379 | 0.390 | 16.17 ± 0.44 |
| mattcl-py | input-lanjian | 0.389 ± 0.004 | 0.380 | 0.393 | 16.34 ± 0.45 |
| pting | input-mattcl | 1.884 ± 0.011 | 1.871 | 1.891 | 79.17 ± 2.03 |
| pting | input-lanjian | 1.923 ± 0.056 | 1.882 | 1.987 | 80.82 ± 3.10 |
| pting | input-pting | 1.959 ± 0.111 | 1.869 | 2.083 | 82.35 ± 5.09 |
| lanjian | input-mattcl | 2.384 ± 0.013 | 2.375 | 2.399 | 100.20 ± 2.56 |
| lanjian | input-pting | 2.394 ± 0.006 | 2.388 | 2.400 | 100.64 ± 2.53 |
| lanjian | input-lanjian | 2.394 ± 0.024 | 2.369 | 2.416 | 100.64 ± 2.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|