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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.7 | 1.01 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.3 | 1.2 | 1.03 ± 0.24 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.26 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.3 | 1.2 | 1.04 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.26 ± 0.31 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.26 ± 0.29 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 2.1 | 1.27 ± 0.31 |
| lanjian | input-mikofo | 1.2 ± 0.1 | 0.7 | 1.7 | 1.28 ± 0.28 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.9 | 1.29 ± 0.31 |
| mattcl-ts | input-chancalan | 11.7 ± 0.4 | 10.7 | 12.7 | 12.29 ± 2.28 |
| mattcl-ts | input-lanjian | 11.7 ± 0.3 | 11.0 | 13.0 | 12.32 ± 2.28 |
| mattcl-ts | input-kcen | 11.7 ± 0.3 | 10.8 | 12.5 | 12.37 ± 2.29 |
| mattcl-ts | input-mattcl | 11.8 ± 0.4 | 10.8 | 13.7 | 12.43 ± 2.31 |
| mattcl-ts | input-mikofo | 11.9 ± 0.3 | 10.9 | 12.7 | 12.51 ± 2.32 |
| mikofo | input-kcen | 13.9 ± 0.3 | 12.8 | 14.8 | 14.65 ± 2.70 |
| mikofo | input-chancalan | 13.9 ± 0.4 | 13.0 | 15.2 | 14.68 ± 2.71 |
| mikofo | input-lanjian | 13.9 ± 0.3 | 13.0 | 14.9 | 14.68 ± 2.71 |
| mikofo | input-mattcl | 13.9 ± 0.4 | 13.1 | 15.2 | 14.70 ± 2.71 |
| mikofo | input-mikofo | 14.2 ± 0.3 | 13.4 | 15.0 | 14.92 ± 2.75 |
| kcen | input-chancalan | 14.4 ± 0.6 | 13.6 | 17.5 | 15.21 ± 2.84 |
| mattcl-py | input-kcen | 14.4 ± 0.5 | 13.4 | 17.4 | 15.22 ± 2.83 |
| mattcl-py | input-chancalan | 14.4 ± 0.5 | 13.5 | 17.2 | 15.22 ± 2.83 |
| mattcl-py | input-mikofo | 14.5 ± 0.4 | 13.6 | 17.0 | 15.29 ± 2.83 |
| pting | input-chancalan | 14.5 ± 0.6 | 13.5 | 17.1 | 15.29 ± 2.86 |
| kcen | input-mattcl | 14.5 ± 0.6 | 13.5 | 17.3 | 15.29 ± 2.87 |
| kcen | input-mikofo | 14.5 ± 0.4 | 13.7 | 17.7 | 15.30 ± 2.83 |
| pting | input-mattcl | 14.5 ± 0.6 | 13.5 | 17.5 | 15.32 ± 2.87 |
| kcen | input-lanjian | 14.5 ± 0.7 | 13.7 | 18.1 | 15.32 ± 2.89 |
| kcen | input-kcen | 14.6 ± 0.7 | 13.5 | 18.1 | 15.34 ± 2.90 |
| pting | input-lanjian | 14.6 ± 0.6 | 13.7 | 17.5 | 15.35 ± 2.88 |
| mattcl-py | input-mattcl | 14.6 ± 0.6 | 13.4 | 17.3 | 15.36 ± 2.89 |
| mattcl-py | input-lanjian | 14.6 ± 0.7 | 13.5 | 18.1 | 15.37 ± 2.91 |
| pting | input-mikofo | 14.7 ± 0.7 | 14.0 | 18.1 | 15.47 ± 2.91 |
| chancalan | input-kcen | 14.9 ± 0.6 | 13.7 | 18.2 | 15.66 ± 2.93 |
| chancalan | input-mattcl | 14.9 ± 0.6 | 13.8 | 17.8 | 15.74 ± 2.94 |
| chancalan | input-lanjian | 15.0 ± 0.6 | 13.7 | 17.6 | 15.77 ± 2.94 |
| chancalan | input-chancalan | 15.0 ± 0.7 | 13.8 | 18.1 | 15.79 ± 2.97 |
| chancalan | input-mikofo | 15.1 ± 0.6 | 14.0 | 17.8 | 15.89 ± 2.98 |
| pting | input-kcen | 15.2 ± 5.0 | 13.4 | 61.1 | 16.03 ± 6.05 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|