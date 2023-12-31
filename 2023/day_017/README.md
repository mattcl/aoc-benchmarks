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
| mattcl | input-lanjian | 0.024 ± 0.001 | 0.023 | 0.026 | 1.00 ± 0.04 |
| mattcl | input-mattcl | 0.024 ± 0.001 | 0.023 | 0.026 | 1.01 ± 0.04 |
| mattcl | input-kcen | 0.024 ± 0.000 | 0.023 | 0.026 | 1.01 ± 0.04 |
| mattcl-py | input-pting | 0.382 ± 0.002 | 0.378 | 0.385 | 16.01 ± 0.52 |
| mattcl-py | input-lanjian | 0.386 ± 0.005 | 0.379 | 0.391 | 16.17 ± 0.55 |
| mattcl-py | input-mattcl | 0.386 ± 0.002 | 0.383 | 0.389 | 16.19 ± 0.52 |
| mattcl-py | input-kcen | 0.392 ± 0.006 | 0.383 | 0.399 | 16.44 ± 0.58 |
| pting | input-kcen | 1.863 ± 0.019 | 1.848 | 1.885 | 78.11 ± 2.61 |
| pting | input-mattcl | 1.882 ± 0.038 | 1.838 | 1.907 | 78.90 ± 2.98 |
| pting | input-lanjian | 1.910 ± 0.023 | 1.894 | 1.936 | 80.09 ± 2.72 |
| pting | input-pting | 1.911 ± 0.024 | 1.891 | 1.937 | 80.10 ± 2.74 |
| lanjian | input-mattcl | 2.385 ± 0.030 | 2.350 | 2.407 | 99.99 ± 3.43 |
| lanjian | input-pting | 2.396 ± 0.030 | 2.368 | 2.428 | 100.45 ± 3.43 |
| lanjian | input-lanjian | 2.414 ± 0.001 | 2.413 | 2.415 | 101.22 ± 3.22 |
| lanjian | input-kcen | 2.429 ± 0.006 | 2.422 | 2.434 | 101.82 ± 3.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|