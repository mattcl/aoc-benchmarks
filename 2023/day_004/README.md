# Day 4 benchmarks

[link to problem](https://adventofcode.com/2023/day/4)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 4)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.26 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.3 | 1.2 | 1.04 ± 0.23 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.6 | 1.2 | 1.06 ± 0.23 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.6 | 1.07 ± 0.26 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.4 | 1.6 | 1.32 ± 0.31 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.4 | 1.8 | 1.34 ± 0.29 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.5 | 2.1 | 1.34 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.8 | 1.6 | 1.35 ± 0.29 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.9 | 1.38 ± 0.30 |
| mattcl-py | input-chancalan | 16.7 ± 0.5 | 15.9 | 19.7 | 17.38 ± 3.07 |
| pting | input-lanjian | 16.7 ± 0.6 | 15.9 | 19.7 | 17.38 ± 3.09 |
| mattcl-py | input-lanjian | 16.7 ± 0.6 | 16.1 | 20.5 | 17.39 ± 3.10 |
| pting | input-kcen | 16.7 ± 0.7 | 15.6 | 20.4 | 17.39 ± 3.12 |
| pting | input-mattcl | 16.8 ± 0.7 | 15.9 | 20.4 | 17.44 ± 3.11 |
| mattcl-py | input-kcen | 16.8 ± 0.6 | 15.7 | 19.5 | 17.47 ± 3.11 |
| pting | input-pting | 16.9 ± 0.7 | 16.1 | 20.4 | 17.50 ± 3.12 |
| mattcl-py | input-pting | 16.9 ± 0.6 | 15.7 | 19.7 | 17.51 ± 3.11 |
| kcen | input-kcen | 16.9 ± 0.6 | 16.2 | 20.1 | 17.52 ± 3.10 |
| pting | input-chancalan | 16.9 ± 2.3 | 15.7 | 46.0 | 17.53 ± 3.88 |
| kcen | input-chancalan | 17.0 ± 0.6 | 16.2 | 19.9 | 17.61 ± 3.13 |
| kcen | input-pting | 17.0 ± 0.6 | 15.8 | 20.1 | 17.62 ± 3.13 |
| kcen | input-lanjian | 17.1 ± 0.7 | 16.1 | 19.8 | 17.71 ± 3.17 |
| kcen | input-mattcl | 17.1 ± 0.7 | 16.2 | 20.4 | 17.71 ± 3.17 |
| mattcl-py | input-mattcl | 17.1 ± 3.7 | 15.7 | 65.7 | 17.74 ± 4.95 |
| chancalan | input-chancalan | 17.2 ± 0.7 | 16.0 | 19.9 | 17.87 ± 3.19 |
| chancalan | input-mattcl | 17.3 ± 0.7 | 16.3 | 20.9 | 17.93 ± 3.19 |
| chancalan | input-kcen | 17.3 ± 0.7 | 16.4 | 20.5 | 17.96 ± 3.21 |
| chancalan | input-lanjian | 17.3 ± 0.6 | 16.3 | 20.0 | 17.97 ± 3.19 |
| chancalan | input-pting | 17.3 ± 0.6 | 16.3 | 20.7 | 18.01 ± 3.20 |
| mikofo | input-mattcl | 317.8 ± 2.6 | 313.0 | 320.9 | 329.92 ± 57.44 |
| mikofo | input-pting | 318.4 ± 2.3 | 315.7 | 321.6 | 330.57 ± 57.54 |
| mikofo | input-kcen | 318.7 ± 3.0 | 314.2 | 322.1 | 330.89 ± 57.63 |
| mikofo | input-chancalan | 318.9 ± 1.9 | 316.4 | 321.5 | 331.10 ± 57.61 |
| mikofo | input-lanjian | 319.0 ± 1.4 | 317.1 | 321.4 | 331.18 ± 57.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|