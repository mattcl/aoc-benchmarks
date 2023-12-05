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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.24 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.24 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.4 | 1.1 | 1.04 ± 0.23 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.2 | 1.6 | 1.06 ± 0.24 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.8 | 1.7 | 1.35 ± 0.28 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.7 | 1.7 | 1.35 ± 0.30 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.7 | 2.0 | 1.36 ± 0.33 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.0 | 1.37 ± 0.29 |
| lanjian | input-pting | 1.3 ± 0.1 | 0.8 | 1.7 | 1.43 ± 0.29 |
| mattcl-py | input-kcen | 16.9 ± 0.5 | 15.9 | 20.0 | 18.34 ± 3.15 |
| pting | input-chancalan | 17.0 ± 0.7 | 15.6 | 19.9 | 18.36 ± 3.19 |
| mattcl-py | input-lanjian | 17.0 ± 0.6 | 15.8 | 20.2 | 18.40 ± 3.18 |
| pting | input-mattcl | 17.0 ± 0.7 | 16.1 | 21.0 | 18.41 ± 3.20 |
| pting | input-lanjian | 17.0 ± 0.6 | 16.2 | 19.9 | 18.41 ± 3.19 |
| pting | input-pting | 17.0 ± 0.6 | 15.8 | 20.0 | 18.44 ± 3.19 |
| pting | input-kcen | 17.0 ± 0.7 | 16.1 | 20.4 | 18.44 ± 3.20 |
| mattcl-py | input-pting | 17.0 ± 0.7 | 16.0 | 19.9 | 18.46 ± 3.21 |
| mattcl-py | input-mattcl | 17.1 ± 0.7 | 16.1 | 20.4 | 18.48 ± 3.22 |
| kcen | input-pting | 17.2 ± 0.6 | 16.4 | 20.1 | 18.63 ± 3.21 |
| kcen | input-chancalan | 17.2 ± 0.7 | 16.3 | 20.6 | 18.65 ± 3.24 |
| mattcl-py | input-chancalan | 17.2 ± 2.8 | 15.9 | 52.6 | 18.67 ± 4.38 |
| kcen | input-kcen | 17.3 ± 0.7 | 16.2 | 20.7 | 18.69 ± 3.26 |
| kcen | input-mattcl | 17.3 ± 0.8 | 16.1 | 20.8 | 18.74 ± 3.29 |
| kcen | input-lanjian | 17.4 ± 0.7 | 16.3 | 20.8 | 18.79 ± 3.28 |
| chancalan | input-kcen | 17.5 ± 0.7 | 16.5 | 20.7 | 18.90 ± 3.29 |
| chancalan | input-pting | 17.5 ± 0.7 | 16.1 | 20.8 | 18.94 ± 3.30 |
| chancalan | input-mattcl | 17.5 ± 0.8 | 16.4 | 20.7 | 18.94 ± 3.31 |
| chancalan | input-chancalan | 17.5 ± 0.7 | 16.3 | 20.6 | 18.98 ± 3.31 |
| chancalan | input-lanjian | 17.6 ± 0.8 | 16.4 | 20.6 | 19.04 ± 3.34 |
| mikofo | input-kcen | 320.6 ± 2.9 | 316.8 | 324.6 | 347.06 ± 58.89 |
| mikofo | input-chancalan | 321.6 ± 2.5 | 318.3 | 325.3 | 348.15 ± 59.05 |
| mikofo | input-lanjian | 322.3 ± 2.9 | 317.8 | 327.3 | 348.86 ± 59.19 |
| mikofo | input-mattcl | 322.6 ± 3.0 | 319.5 | 327.4 | 349.24 ± 59.26 |
| mikofo | input-pting | 326.9 ± 15.4 | 319.1 | 367.6 | 353.93 ± 62.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|