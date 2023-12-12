# Day 12 benchmarks

[link to problem](https://adventofcode.com/2023/day/12)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 12)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [s] | Min [s] | Max [s] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.13 |
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.13 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.004 | 1.30 ± 0.18 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.004 | 1.32 ± 0.18 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.005 | 1.34 ± 0.20 |
| mattcl | input-lanjian | 0.003 ± 0.000 | 0.002 | 0.005 | 1.36 ± 0.26 |
| mattcl-py | input-kcen | 0.088 ± 0.001 | 0.085 | 0.091 | 47.28 ± 4.52 |
| mattcl-py | input-lanjian | 0.089 ± 0.001 | 0.087 | 0.092 | 48.13 ± 4.59 |
| mattcl-py | input-mattcl | 0.090 ± 0.001 | 0.087 | 0.092 | 48.48 ± 4.63 |
| mattcl-py | input-pting | 0.092 ± 0.001 | 0.089 | 0.094 | 49.72 ± 4.74 |
| pting | input-kcen | 0.295 ± 0.003 | 0.291 | 0.302 | 159.25 ± 15.14 |
| pting | input-lanjian | 0.299 ± 0.003 | 0.294 | 0.304 | 161.10 ± 15.31 |
| pting | input-mattcl | 0.302 ± 0.003 | 0.298 | 0.306 | 162.63 ± 15.43 |
| pting | input-pting | 0.312 ± 0.003 | 0.309 | 0.316 | 168.40 ± 15.97 |
| kcen | input-kcen | 1.251 ± 0.008 | 1.246 | 1.260 | 674.47 ± 63.84 |
| kcen | input-pting | 1.277 ± 0.009 | 1.271 | 1.287 | 688.60 ± 65.20 |
| kcen | input-mattcl | 1.405 ± 0.004 | 1.402 | 1.410 | 757.93 ± 71.59 |
| kcen | input-lanjian | 1.429 ± 0.030 | 1.408 | 1.464 | 770.76 ± 74.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|