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
| mattcl | input-mattcl | 0.024 ± 0.001 | 0.023 | 0.027 | 1.00 |
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.023 | 0.027 | 1.03 ± 0.03 |
| mattcl | input-pting | 0.025 ± 0.001 | 0.024 | 0.028 | 1.06 ± 0.03 |
| mattcl-py | input-mattcl | 0.387 ± 0.003 | 0.384 | 0.392 | 16.45 ± 0.40 |
| mattcl-py | input-lanjian | 0.392 ± 0.006 | 0.386 | 0.403 | 16.68 ± 0.47 |
| mattcl-py | input-pting | 0.401 ± 0.008 | 0.393 | 0.413 | 17.07 ± 0.52 |
| pting | input-lanjian | 1.958 ± 0.076 | 1.887 | 2.038 | 83.29 ± 3.77 |
| pting | input-pting | 1.977 ± 0.046 | 1.937 | 2.028 | 84.10 ± 2.78 |
| lanjian | input-mattcl | 2.472 ± 0.103 | 2.411 | 2.591 | 105.14 ± 5.02 |
| lanjian | input-lanjian | 2.502 ± 0.143 | 2.413 | 2.667 | 106.44 ± 6.57 |
| pting | input-mattcl | 2.674 ± 0.014 | 2.660 | 2.688 | 113.73 ± 2.72 |
| lanjian | input-pting | 2.987 ± 0.047 | 2.937 | 3.030 | 127.05 ± 3.57 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|