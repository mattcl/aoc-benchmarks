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
| mattcl | input-pting | 0.015 ± 0.000 | 0.014 | 0.015 | 1.00 |
| mattcl | input-lanjian | 0.015 ± 0.000 | 0.014 | 0.017 | 1.02 ± 0.04 |
| mattcl | input-mattcl | 0.015 ± 0.003 | 0.014 | 0.051 | 1.03 ± 0.18 |
| mattcl | input-kcen | 0.015 ± 0.000 | 0.014 | 0.017 | 1.03 ± 0.04 |
| mattcl-py | input-pting | 0.385 ± 0.006 | 0.375 | 0.393 | 26.46 ± 0.78 |
| mattcl-py | input-mattcl | 0.388 ± 0.003 | 0.383 | 0.392 | 26.64 ± 0.71 |
| mattcl-py | input-kcen | 0.391 ± 0.003 | 0.387 | 0.395 | 26.87 ± 0.71 |
| mattcl-py | input-lanjian | 0.395 ± 0.006 | 0.386 | 0.402 | 27.11 ± 0.79 |
| pting | input-mattcl | 1.876 ± 0.026 | 1.846 | 1.891 | 128.82 ± 3.72 |
| pting | input-lanjian | 1.884 ± 0.021 | 1.863 | 1.905 | 129.37 ± 3.58 |
| pting | input-kcen | 1.899 ± 0.027 | 1.883 | 1.930 | 130.39 ± 3.78 |
| pting | input-pting | 1.919 ± 0.012 | 1.908 | 1.932 | 131.78 ± 3.44 |
| lanjian | input-pting | 2.399 ± 0.027 | 2.368 | 2.415 | 164.71 ± 4.56 |
| lanjian | input-lanjian | 2.410 ± 0.025 | 2.381 | 2.428 | 165.52 ± 4.54 |
| lanjian | input-mattcl | 2.413 ± 0.010 | 2.404 | 2.424 | 165.73 ± 4.26 |
| lanjian | input-kcen | 2.423 ± 0.023 | 2.397 | 2.436 | 166.36 ± 4.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|