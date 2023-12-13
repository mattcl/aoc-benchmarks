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
| lanjian | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 |
| lanjian | input-pting | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.11 |
| lanjian | input-kcen | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.13 |
| lanjian | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.002 | 1.00 ± 0.12 |
| mattcl | input-lanjian | 0.002 ± 0.000 | 0.002 | 0.005 | 1.33 ± 0.19 |
| mattcl | input-mattcl | 0.002 ± 0.000 | 0.002 | 0.004 | 1.34 ± 0.17 |
| mattcl | input-kcen | 0.002 ± 0.000 | 0.002 | 0.005 | 1.34 ± 0.19 |
| mattcl | input-pting | 0.002 ± 0.000 | 0.002 | 0.006 | 1.38 ± 0.25 |
| pting | input-kcen | 0.067 ± 0.001 | 0.065 | 0.069 | 37.14 ± 3.30 |
| pting | input-lanjian | 0.068 ± 0.001 | 0.066 | 0.073 | 37.76 ± 3.38 |
| pting | input-mattcl | 0.069 ± 0.001 | 0.067 | 0.072 | 38.08 ± 3.41 |
| pting | input-pting | 0.070 ± 0.001 | 0.068 | 0.072 | 38.74 ± 3.44 |
| mattcl-py | input-kcen | 0.091 ± 0.007 | 0.086 | 0.131 | 50.41 ± 5.99 |
| mattcl-py | input-lanjian | 0.091 ± 0.001 | 0.089 | 0.093 | 50.56 ± 4.47 |
| mattcl-py | input-mattcl | 0.092 ± 0.001 | 0.089 | 0.095 | 51.08 ± 4.55 |
| mattcl-py | input-pting | 0.094 ± 0.001 | 0.092 | 0.097 | 52.42 ± 4.65 |
| kcen | input-kcen | 1.259 ± 0.013 | 1.245 | 1.268 | 699.86 ± 61.78 |
| kcen | input-pting | 1.291 ± 0.007 | 1.286 | 1.300 | 717.84 ± 63.09 |
| kcen | input-mattcl | 1.389 ± 0.022 | 1.369 | 1.412 | 771.90 ± 68.75 |
| kcen | input-lanjian | 1.456 ± 0.007 | 1.448 | 1.461 | 809.45 ± 71.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>7307</pre>|<pre>3415570893842</pre>|
|input-lanjian|<pre>7541</pre>|<pre>17485169859432</pre>|
|input-mattcl|<pre>7350</pre>|<pre>200097286528151</pre>|
|input-pting|<pre>7286</pre>|<pre>25470469710341</pre>|