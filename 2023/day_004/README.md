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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.4 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.25 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.2 | 1.02 ± 0.25 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.5 | 1.5 | 1.05 ± 0.24 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.25 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.24 ± 0.31 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.6 | 1.8 | 1.28 ± 0.29 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.7 | 1.28 ± 0.29 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.6 | 1.7 | 1.28 ± 0.28 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.6 | 2.1 | 1.31 ± 0.29 |
| mattcl-ts | input-lanjian | 11.4 ± 0.4 | 10.4 | 12.6 | 11.61 ± 2.18 |
| mattcl-ts | input-kcen | 11.5 ± 0.3 | 10.4 | 12.5 | 11.63 ± 2.18 |
| mattcl-ts | input-chancalan | 11.5 ± 0.3 | 10.4 | 12.4 | 11.65 ± 2.18 |
| mattcl-ts | input-mattcl | 11.5 ± 0.3 | 10.4 | 12.5 | 11.67 ± 2.19 |
| mattcl-ts | input-mikofo | 11.5 ± 0.4 | 10.6 | 12.6 | 11.73 ± 2.20 |
| mikofo | input-chancalan | 13.6 ± 0.4 | 12.9 | 15.2 | 13.86 ± 2.60 |
| mikofo | input-kcen | 13.7 ± 0.4 | 12.6 | 14.5 | 13.92 ± 2.60 |
| mikofo | input-mattcl | 13.7 ± 0.4 | 12.4 | 14.6 | 13.94 ± 2.61 |
| mikofo | input-lanjian | 13.7 ± 0.3 | 12.9 | 14.4 | 13.94 ± 2.60 |
| mikofo | input-mikofo | 13.8 ± 0.4 | 12.8 | 15.4 | 14.04 ± 2.63 |
| kcen | input-chancalan | 14.5 ± 0.4 | 13.5 | 16.2 | 14.69 ± 2.76 |
| mattcl-py | input-lanjian | 14.5 ± 0.6 | 13.5 | 17.9 | 14.77 ± 2.80 |
| kcen | input-lanjian | 14.6 ± 0.6 | 13.6 | 18.2 | 14.79 ± 2.81 |
| mattcl-py | input-kcen | 14.6 ± 0.6 | 13.7 | 17.7 | 14.81 ± 2.80 |
| pting | input-lanjian | 14.6 ± 0.4 | 13.8 | 17.3 | 14.81 ± 2.78 |
| pting | input-chancalan | 14.6 ± 0.5 | 13.6 | 18.1 | 14.82 ± 2.80 |
| kcen | input-kcen | 14.6 ± 0.7 | 13.5 | 18.2 | 14.83 ± 2.83 |
| pting | input-kcen | 14.6 ± 0.5 | 13.7 | 17.3 | 14.83 ± 2.80 |
| mattcl-py | input-mattcl | 14.6 ± 0.7 | 13.5 | 18.1 | 14.84 ± 2.83 |
| mattcl-py | input-chancalan | 14.6 ± 0.7 | 13.5 | 17.5 | 14.84 ± 2.83 |
| pting | input-mattcl | 14.6 ± 0.6 | 13.7 | 17.8 | 14.84 ± 2.82 |
| mattcl-py | input-mikofo | 14.6 ± 0.6 | 13.5 | 17.8 | 14.86 ± 2.81 |
| kcen | input-mattcl | 14.6 ± 0.7 | 13.5 | 17.5 | 14.87 ± 2.85 |
| kcen | input-mikofo | 14.6 ± 0.6 | 13.8 | 17.6 | 14.87 ± 2.82 |
| pting | input-mikofo | 14.7 ± 0.6 | 13.5 | 17.7 | 14.91 ± 2.83 |
| chancalan | input-chancalan | 15.0 ± 0.6 | 13.7 | 18.3 | 15.21 ± 2.87 |
| chancalan | input-mattcl | 15.0 ± 0.7 | 13.9 | 18.2 | 15.23 ± 2.90 |
| chancalan | input-kcen | 15.0 ± 0.7 | 14.0 | 18.2 | 15.25 ± 2.92 |
| chancalan | input-lanjian | 15.0 ± 0.5 | 14.0 | 17.7 | 15.27 ± 2.88 |
| chancalan | input-mikofo | 15.0 ± 0.5 | 14.0 | 18.0 | 15.28 ± 2.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|