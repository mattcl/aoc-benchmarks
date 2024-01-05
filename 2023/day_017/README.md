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
| mattcl | input-lanjian | 0.011 ± 0.000 | 0.010 | 0.013 | 1.00 |
| mattcl | input-pting | 0.011 ± 0.000 | 0.009 | 0.012 | 1.00 ± 0.05 |
| mattcl | input-mattcl | 0.011 ± 0.000 | 0.009 | 0.012 | 1.00 ± 0.05 |
| mattcl | input-kcen | 0.011 ± 0.000 | 0.010 | 0.013 | 1.01 ± 0.06 |
| mattcl-py | input-pting | 0.295 ± 0.003 | 0.289 | 0.301 | 27.90 ± 1.09 |
| mattcl-py | input-mattcl | 0.298 ± 0.003 | 0.292 | 0.302 | 28.18 ± 1.08 |
| mattcl-py | input-lanjian | 0.300 ± 0.002 | 0.296 | 0.304 | 28.38 ± 1.08 |
| mattcl-py | input-kcen | 0.303 ± 0.004 | 0.297 | 0.311 | 28.67 ± 1.14 |
| pting | input-mattcl | 1.881 ± 0.026 | 1.850 | 1.898 | 178.01 ± 7.10 |
| pting | input-pting | 1.883 ± 0.025 | 1.860 | 1.909 | 178.17 ± 7.06 |
| pting | input-kcen | 1.893 ± 0.026 | 1.870 | 1.922 | 179.21 ± 7.14 |
| pting | input-lanjian | 1.920 ± 0.014 | 1.909 | 1.936 | 181.74 ± 6.91 |
| lanjian | input-pting | 2.366 ± 0.028 | 2.348 | 2.399 | 223.97 ± 8.78 |
| lanjian | input-mattcl | 2.390 ± 0.004 | 2.387 | 2.394 | 226.25 ± 8.45 |
| lanjian | input-lanjian | 2.396 ± 0.028 | 2.364 | 2.417 | 226.81 ± 8.88 |
| lanjian | input-kcen | 2.423 ± 0.011 | 2.412 | 2.434 | 229.33 ± 8.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1260</pre>|<pre>1416</pre>|
|input-lanjian|<pre>1099</pre>|<pre>1266</pre>|
|input-mattcl|<pre>1004</pre>|<pre>1171</pre>|
|input-pting|<pre>843</pre>|<pre>1017</pre>|