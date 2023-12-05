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
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.11 ± 0.44 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.12 ± 0.43 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.12 ± 0.43 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.13 ± 0.44 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.6 | 1.48 ± 0.54 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.5 | 1.7 | 1.55 ± 0.55 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.56 ± 0.56 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.7 | 1.57 ± 0.54 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.6 | 1.5 | 1.62 ± 0.55 |
| mattcl-py | input-pting | 14.5 ± 0.4 | 13.5 | 16.7 | 20.54 ± 6.47 |
| mattcl-py | input-kcen | 14.5 ± 0.5 | 13.5 | 17.3 | 20.62 ± 6.51 |
| pting | input-kcen | 14.5 ± 0.6 | 13.6 | 18.1 | 20.63 ± 6.54 |
| pting | input-mattcl | 14.5 ± 0.5 | 13.5 | 17.6 | 20.64 ± 6.52 |
| pting | input-lanjian | 14.5 ± 0.5 | 13.6 | 17.0 | 20.66 ± 6.52 |
| mattcl-py | input-lanjian | 14.6 ± 0.6 | 13.7 | 17.5 | 20.68 ± 6.56 |
| mattcl-py | input-chancalan | 14.6 ± 0.6 | 13.6 | 17.9 | 20.69 ± 6.56 |
| pting | input-chancalan | 14.6 ± 0.7 | 13.5 | 18.2 | 20.69 ± 6.58 |
| pting | input-pting | 14.6 ± 0.6 | 13.7 | 17.9 | 20.71 ± 6.56 |
| mattcl-py | input-mattcl | 14.6 ± 2.0 | 13.6 | 41.1 | 20.81 ± 7.11 |
| kcen | input-chancalan | 14.7 ± 0.6 | 13.7 | 18.3 | 20.84 ± 6.60 |
| kcen | input-kcen | 14.7 ± 0.6 | 13.7 | 17.4 | 20.87 ± 6.60 |
| kcen | input-pting | 14.7 ± 0.6 | 13.9 | 17.5 | 20.95 ± 6.63 |
| kcen | input-mattcl | 14.8 ± 0.7 | 13.8 | 18.1 | 20.96 ± 6.66 |
| kcen | input-lanjian | 14.8 ± 0.7 | 13.7 | 17.9 | 20.96 ± 6.65 |
| chancalan | input-lanjian | 14.9 ± 0.5 | 13.8 | 17.6 | 21.19 ± 6.69 |
| chancalan | input-chancalan | 15.0 ± 0.6 | 13.7 | 18.1 | 21.26 ± 6.73 |
| chancalan | input-kcen | 15.0 ± 0.6 | 14.1 | 17.8 | 21.32 ± 6.75 |
| chancalan | input-mattcl | 15.0 ± 0.6 | 13.9 | 17.9 | 21.35 ± 6.76 |
| chancalan | input-pting | 15.1 ± 0.7 | 13.9 | 18.2 | 21.38 ± 6.79 |
| mikofo | input-lanjian | 277.6 ± 1.6 | 275.4 | 281.2 | 394.29 ± 123.79 |
| mikofo | input-pting | 278.3 ± 1.4 | 277.1 | 281.5 | 395.30 ± 124.10 |
| mikofo | input-chancalan | 278.7 ± 1.4 | 276.6 | 280.7 | 395.86 ± 124.28 |
| mikofo | input-mattcl | 278.7 ± 1.9 | 275.6 | 281.4 | 395.90 ± 124.31 |
| mikofo | input-kcen | 278.7 ± 1.6 | 276.4 | 280.8 | 395.98 ± 124.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|