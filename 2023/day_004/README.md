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
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mikofo | 0.8 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.07 ± 0.38 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.2 | 1.08 ± 0.38 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.6 | 1.10 ± 0.37 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.4 | 1.1 | 1.12 ± 0.37 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.4 | 1.12 ± 0.37 |
| lanjian | input-mikofo | 1.1 ± 0.2 | 0.4 | 2.2 | 1.29 ± 0.47 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.5 | 1.40 ± 0.46 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.43 ± 0.48 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.43 ± 0.49 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.43 ± 0.47 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.8 | 1.47 ± 0.49 |
| mattcl-ts | input-chancalan | 11.2 ± 0.4 | 10.1 | 12.1 | 13.56 ± 3.99 |
| mattcl-ts | input-mattcl | 11.4 ± 0.3 | 10.4 | 12.8 | 13.73 ± 4.03 |
| mattcl-ts | input-lanjian | 11.4 ± 0.3 | 10.3 | 12.5 | 13.79 ± 4.05 |
| mattcl-ts | input-mikofo | 11.4 ± 0.3 | 10.4 | 12.8 | 13.82 ± 4.06 |
| mattcl-ts | input-pting | 11.4 ± 0.3 | 10.4 | 12.3 | 13.82 ± 4.05 |
| mattcl-ts | input-kcen | 11.7 ± 4.3 | 10.4 | 61.3 | 14.17 ± 6.60 |
| mattcl-py | input-chancalan | 14.4 ± 0.6 | 13.3 | 17.3 | 17.34 ± 5.11 |
| kcen | input-chancalan | 14.4 ± 0.6 | 13.7 | 17.4 | 17.34 ± 5.11 |
| pting | input-chancalan | 14.4 ± 0.5 | 13.4 | 17.2 | 17.38 ± 5.12 |
| mattcl-py | input-lanjian | 14.5 ± 0.7 | 13.4 | 18.3 | 17.48 ± 5.17 |
| mattcl-py | input-kcen | 14.5 ± 0.6 | 13.6 | 18.1 | 17.50 ± 5.16 |
| kcen | input-pting | 14.5 ± 0.5 | 13.6 | 17.7 | 17.51 ± 5.15 |
| kcen | input-lanjian | 14.5 ± 0.6 | 13.4 | 17.8 | 17.54 ± 5.18 |
| pting | input-kcen | 14.5 ± 0.6 | 13.5 | 17.6 | 17.54 ± 5.18 |
| kcen | input-mattcl | 14.5 ± 0.6 | 13.7 | 17.6 | 17.55 ± 5.18 |
| mattcl-py | input-mattcl | 14.5 ± 0.7 | 13.6 | 18.0 | 17.57 ± 5.19 |
| mattcl-py | input-mikofo | 14.6 ± 0.5 | 13.5 | 17.7 | 17.59 ± 5.18 |
| mattcl-py | input-pting | 14.6 ± 0.6 | 13.6 | 17.6 | 17.59 ± 5.18 |
| kcen | input-mikofo | 14.7 ± 0.7 | 13.6 | 17.7 | 17.72 ± 5.24 |
| pting | input-mattcl | 14.7 ± 2.4 | 13.4 | 47.7 | 17.74 ± 5.96 |
| pting | input-lanjian | 14.8 ± 0.8 | 13.7 | 19.0 | 17.83 ± 5.31 |
| pting | input-pting | 14.8 ± 2.0 | 13.5 | 40.8 | 17.87 ± 5.73 |
| chancalan | input-chancalan | 14.9 ± 0.7 | 13.9 | 18.1 | 17.94 ± 5.30 |
| chancalan | input-kcen | 14.9 ± 0.5 | 13.9 | 18.2 | 17.98 ± 5.29 |
| chancalan | input-lanjian | 14.9 ± 0.6 | 13.7 | 17.9 | 18.00 ± 5.30 |
| pting | input-mikofo | 15.0 ± 3.3 | 13.6 | 60.6 | 18.07 ± 6.63 |
| chancalan | input-mattcl | 15.0 ± 0.6 | 13.9 | 17.6 | 18.10 ± 5.34 |
| kcen | input-kcen | 15.1 ± 5.7 | 13.4 | 80.9 | 18.21 ± 8.75 |
| chancalan | input-mikofo | 15.2 ± 0.8 | 14.0 | 20.6 | 18.31 ± 5.43 |
| chancalan | input-pting | 15.4 ± 3.5 | 14.0 | 52.0 | 18.63 ± 6.91 |
| mikofo | input-chancalan | 32.2 ± 0.5 | 31.0 | 33.4 | 38.89 ± 11.38 |
| mikofo | input-mattcl | 32.4 ± 0.5 | 31.2 | 34.1 | 39.08 ± 11.43 |
| mikofo | input-pting | 32.5 ± 0.4 | 31.5 | 34.3 | 39.24 ± 11.48 |
| mikofo | input-kcen | 32.9 ± 4.7 | 31.3 | 76.8 | 39.70 ± 12.93 |
| mikofo | input-lanjian | 33.1 ± 3.4 | 31.2 | 60.8 | 39.98 ± 12.39 |
| mikofo | input-mikofo | 34.6 ± 7.5 | 31.5 | 77.3 | 41.82 ± 15.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|