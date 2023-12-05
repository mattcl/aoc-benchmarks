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
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.33 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.2 | 1.05 ± 0.36 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.3 | 1.10 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.4 | 1.2 | 1.12 ± 0.32 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.8 | 1.46 ± 0.41 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.5 | 1.47 ± 0.40 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.6 | 1.5 | 1.50 ± 0.39 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.0 | 1.52 ± 0.41 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.1 | 1.53 ± 0.42 |
| pting | input-mattcl | 16.9 ± 0.6 | 15.5 | 19.3 | 20.15 ± 4.62 |
| pting | input-pting | 17.0 ± 0.6 | 15.7 | 20.2 | 20.23 ± 4.63 |
| mattcl-py | input-mattcl | 17.0 ± 0.8 | 15.9 | 20.3 | 20.30 ± 4.68 |
| mattcl-py | input-pting | 17.1 ± 0.6 | 16.1 | 19.8 | 20.35 ± 4.66 |
| pting | input-lanjian | 17.1 ± 0.8 | 16.0 | 23.5 | 20.37 ± 4.71 |
| kcen | input-mattcl | 17.2 ± 0.6 | 15.8 | 20.0 | 20.52 ± 4.70 |
| mattcl-py | input-chancalan | 17.3 ± 0.5 | 16.3 | 19.9 | 20.64 ± 4.70 |
| chancalan | input-mattcl | 17.3 ± 0.5 | 16.4 | 20.0 | 20.65 ± 4.72 |
| chancalan | input-pting | 17.3 ± 0.6 | 16.3 | 20.4 | 20.67 ± 4.72 |
| pting | input-chancalan | 17.4 ± 0.5 | 16.5 | 19.7 | 20.70 ± 4.72 |
| mattcl-py | input-kcen | 17.4 ± 0.5 | 16.4 | 19.9 | 20.70 ± 4.72 |
| kcen | input-pting | 17.4 ± 3.2 | 16.0 | 54.8 | 20.78 ± 6.04 |
| kcen | input-chancalan | 17.5 ± 0.5 | 16.4 | 19.8 | 20.80 ± 4.75 |
| mattcl-py | input-lanjian | 17.7 ± 0.5 | 16.5 | 19.7 | 21.06 ± 4.80 |
| chancalan | input-kcen | 17.7 ± 0.6 | 16.8 | 20.5 | 21.10 ± 4.82 |
| kcen | input-lanjian | 18.0 ± 0.5 | 17.1 | 20.2 | 21.42 ± 4.88 |
| kcen | input-kcen | 18.2 ± 2.3 | 16.5 | 31.7 | 21.63 ± 5.60 |
| pting | input-kcen | 18.2 ± 2.1 | 16.2 | 23.9 | 21.70 ± 5.49 |
| chancalan | input-chancalan | 18.5 ± 5.5 | 16.5 | 85.9 | 22.01 ± 8.28 |
| chancalan | input-lanjian | 18.7 ± 1.4 | 17.5 | 27.0 | 22.27 ± 5.30 |
| mikofo | input-mattcl | 319.6 ± 2.5 | 315.9 | 322.4 | 380.74 ± 86.19 |
| mikofo | input-pting | 319.7 ± 2.4 | 314.3 | 321.4 | 380.87 ± 86.21 |
| mikofo | input-lanjian | 326.5 ± 2.7 | 321.2 | 330.0 | 388.95 ± 88.06 |
| mikofo | input-kcen | 328.0 ± 2.0 | 326.4 | 332.9 | 390.84 ± 88.45 |
| mikofo | input-chancalan | 349.3 ± 44.2 | 326.6 | 450.9 | 416.16 ± 107.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|