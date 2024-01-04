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
| mattcl | input-pting | 0.014 ± 0.000 | 0.013 | 0.017 | 1.00 |
| mattcl | input-mattcl | 0.014 ± 0.000 | 0.013 | 0.016 | 1.01 ± 0.04 |
| mattcl | input-lanjian | 0.014 ± 0.000 | 0.013 | 0.017 | 1.01 ± 0.05 |
| mattcl | input-kcen | 0.015 ± 0.000 | 0.014 | 0.017 | 1.03 ± 0.05 |
| mattcl-py | input-pting | 0.378 ± 0.004 | 0.373 | 0.385 | 26.68 ± 0.92 |
| mattcl-py | input-mattcl | 0.383 ± 0.003 | 0.379 | 0.387 | 27.04 ± 0.92 |
| mattcl-py | input-lanjian | 0.387 ± 0.005 | 0.381 | 0.392 | 27.28 ± 0.96 |
| mattcl-py | input-kcen | 0.399 ± 0.024 | 0.384 | 0.446 | 28.11 ± 1.91 |
| pting | input-mattcl | 1.845 ± 0.021 | 1.821 | 1.859 | 130.14 ± 4.56 |
| pting | input-pting | 1.855 ± 0.026 | 1.835 | 1.885 | 130.84 ± 4.71 |
| pting | input-lanjian | 1.889 ± 0.043 | 1.857 | 1.938 | 133.22 ± 5.34 |
| pting | input-kcen | 1.920 ± 0.020 | 1.897 | 1.935 | 135.42 ± 4.71 |
| lanjian | input-mattcl | 2.372 ± 0.012 | 2.364 | 2.386 | 167.26 ± 5.61 |
| lanjian | input-pting | 2.373 ± 0.011 | 2.364 | 2.385 | 167.35 ± 5.60 |
| lanjian | input-lanjian | 2.397 ± 0.005 | 2.391 | 2.400 | 169.04 ± 5.61 |
| lanjian | input-kcen | 2.398 ± 0.008 | 2.389 | 2.405 | 169.09 ± 5.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|