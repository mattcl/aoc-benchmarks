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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.6 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.29 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.4 | 1.04 ± 0.29 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.6 | 1.04 ± 0.29 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.1 | 1.5 | 1.04 ± 0.28 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.9 | 1.40 ± 0.40 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.7 | 1.7 | 1.42 ± 0.37 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.6 | 1.8 | 1.42 ± 0.38 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.5 | 2.0 | 1.43 ± 0.37 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.8 | 1.43 ± 0.36 |
| mattcl-py | input-kcen | 16.9 ± 0.7 | 15.7 | 20.0 | 19.78 ± 4.32 |
| pting | input-chancalan | 16.9 ± 0.7 | 16.0 | 20.0 | 19.79 ± 4.34 |
| pting | input-mattcl | 17.0 ± 0.7 | 15.7 | 20.4 | 19.79 ± 4.33 |
| mattcl-py | input-chancalan | 17.0 ± 0.7 | 15.7 | 21.2 | 19.81 ± 4.35 |
| pting | input-lanjian | 17.0 ± 0.7 | 15.9 | 20.1 | 19.86 ± 4.34 |
| mattcl-py | input-mattcl | 17.0 ± 0.7 | 16.0 | 20.2 | 19.88 ± 4.36 |
| pting | input-pting | 17.0 ± 0.7 | 15.6 | 20.6 | 19.89 ± 4.37 |
| mattcl-py | input-pting | 17.1 ± 0.7 | 15.9 | 20.5 | 19.93 ± 4.36 |
| kcen | input-kcen | 17.1 ± 0.7 | 16.1 | 20.6 | 19.94 ± 4.36 |
| pting | input-kcen | 17.1 ± 0.8 | 15.9 | 20.3 | 19.96 ± 4.40 |
| kcen | input-chancalan | 17.2 ± 0.6 | 16.2 | 20.0 | 20.09 ± 4.38 |
| kcen | input-lanjian | 17.2 ± 0.7 | 16.2 | 20.4 | 20.11 ± 4.40 |
| kcen | input-mattcl | 17.2 ± 0.7 | 16.1 | 20.1 | 20.11 ± 4.41 |
| kcen | input-pting | 17.2 ± 0.7 | 16.0 | 20.3 | 20.12 ± 4.40 |
| mattcl-py | input-lanjian | 17.2 ± 3.5 | 15.9 | 61.9 | 20.13 ± 5.92 |
| chancalan | input-pting | 17.4 ± 0.5 | 16.6 | 19.9 | 20.26 ± 4.40 |
| chancalan | input-lanjian | 17.4 ± 0.6 | 16.3 | 20.5 | 20.31 ± 4.43 |
| chancalan | input-mattcl | 17.4 ± 0.6 | 16.0 | 20.7 | 20.32 ± 4.43 |
| chancalan | input-chancalan | 17.4 ± 0.6 | 16.6 | 20.1 | 20.32 ± 4.44 |
| chancalan | input-kcen | 17.5 ± 0.8 | 16.1 | 20.7 | 20.43 ± 4.50 |
| mikofo | input-pting | 321.4 ± 2.4 | 318.4 | 326.0 | 375.28 ± 80.85 |
| mikofo | input-lanjian | 321.5 ± 2.6 | 317.3 | 324.5 | 375.37 ± 80.87 |
| mikofo | input-kcen | 322.2 ± 1.1 | 321.1 | 324.7 | 376.22 ± 81.01 |
| mikofo | input-chancalan | 322.4 ± 2.5 | 318.4 | 325.8 | 376.40 ± 81.09 |
| mikofo | input-mattcl | 322.4 ± 3.1 | 318.9 | 326.8 | 376.44 ± 81.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|