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
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.3 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.3 | 1.1 | 1.01 ± 0.24 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.3 | 1.3 | 1.03 ± 0.23 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.5 | 1.03 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.25 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.27 ± 0.29 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.28 ± 0.30 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.7 | 1.7 | 1.29 ± 0.26 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.9 | 1.32 ± 0.29 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.6 | 1.9 | 1.39 ± 0.33 |
| mattcl-ts | input-kcen | 11.7 ± 0.4 | 10.7 | 13.1 | 12.43 ± 2.20 |
| mattcl-ts | input-mattcl | 11.8 ± 0.4 | 11.0 | 12.5 | 12.54 ± 2.21 |
| mattcl-ts | input-lanjian | 11.8 ± 0.4 | 10.9 | 12.8 | 12.54 ± 2.22 |
| mattcl-ts | input-chancalan | 11.8 ± 0.4 | 11.1 | 13.9 | 12.58 ± 2.22 |
| mattcl-ts | input-mikofo | 11.9 ± 0.4 | 10.8 | 12.8 | 12.71 ± 2.24 |
| mikofo | input-chancalan | 13.9 ± 0.3 | 12.9 | 14.9 | 14.82 ± 2.61 |
| mikofo | input-mattcl | 14.0 ± 0.3 | 13.1 | 15.6 | 14.86 ± 2.61 |
| mikofo | input-kcen | 14.0 ± 0.4 | 12.9 | 14.9 | 14.87 ± 2.62 |
| mikofo | input-lanjian | 14.0 ± 0.4 | 13.1 | 15.6 | 14.93 ± 2.63 |
| mikofo | input-mikofo | 14.2 ± 0.4 | 13.4 | 16.2 | 15.16 ± 2.67 |
| mattcl-py | input-mattcl | 14.5 ± 0.5 | 13.4 | 17.4 | 15.39 ± 2.73 |
| mattcl-py | input-chancalan | 14.5 ± 0.7 | 13.6 | 18.2 | 15.45 ± 2.78 |
| pting | input-lanjian | 14.5 ± 0.5 | 13.5 | 17.7 | 15.48 ± 2.76 |
| kcen | input-lanjian | 14.6 ± 0.6 | 13.6 | 17.4 | 15.49 ± 2.76 |
| pting | input-chancalan | 14.6 ± 0.5 | 13.4 | 17.6 | 15.50 ± 2.76 |
| mattcl-py | input-lanjian | 14.6 ± 0.7 | 13.4 | 17.9 | 15.50 ± 2.79 |
| kcen | input-kcen | 14.6 ± 0.7 | 13.5 | 17.4 | 15.51 ± 2.79 |
| pting | input-kcen | 14.6 ± 0.6 | 13.7 | 17.5 | 15.51 ± 2.76 |
| kcen | input-chancalan | 14.6 ± 0.8 | 13.6 | 17.6 | 15.53 ± 2.83 |
| pting | input-mattcl | 14.6 ± 0.5 | 13.7 | 17.4 | 15.56 ± 2.77 |
| kcen | input-mattcl | 14.7 ± 0.7 | 13.4 | 17.9 | 15.60 ± 2.83 |
| kcen | input-mikofo | 14.7 ± 0.7 | 13.6 | 17.4 | 15.62 ± 2.82 |
| mattcl-py | input-mikofo | 14.7 ± 0.6 | 13.7 | 17.5 | 15.62 ± 2.79 |
| pting | input-mikofo | 14.7 ± 0.6 | 13.8 | 18.3 | 15.65 ± 2.80 |
| mattcl-py | input-kcen | 14.8 ± 2.2 | 13.5 | 44.8 | 15.74 ± 3.63 |
| chancalan | input-chancalan | 15.0 ± 0.5 | 14.0 | 17.5 | 15.96 ± 2.83 |
| chancalan | input-lanjian | 15.0 ± 0.5 | 14.1 | 17.4 | 15.98 ± 2.84 |
| chancalan | input-kcen | 15.0 ± 0.7 | 13.8 | 18.7 | 16.00 ± 2.89 |
| chancalan | input-mattcl | 15.1 ± 0.7 | 13.8 | 18.6 | 16.05 ± 2.90 |
| chancalan | input-mikofo | 15.1 ± 0.6 | 14.1 | 18.2 | 16.07 ± 2.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|