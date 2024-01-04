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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.2 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.2 | 1.01 ± 0.23 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.7 | 1.01 ± 0.25 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.5 | 1.5 | 1.05 ± 0.23 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.5 | 1.6 | 1.08 ± 0.25 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 2.0 | 1.23 ± 0.30 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.24 ± 0.29 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.7 | 1.7 | 1.24 ± 0.25 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.7 | 1.7 | 1.26 ± 0.25 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.3 | 1.8 | 1.28 ± 0.29 |
| mattcl-ts | input-chancalan | 11.9 ± 0.4 | 10.9 | 13.4 | 12.36 ± 2.13 |
| mattcl-ts | input-lanjian | 12.0 ± 0.4 | 10.9 | 13.1 | 12.40 ± 2.14 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 11.0 | 13.2 | 12.43 ± 2.14 |
| mattcl-ts | input-mikofo | 12.1 ± 0.3 | 11.1 | 12.7 | 12.54 ± 2.16 |
| mattcl-ts | input-kcen | 12.4 ± 4.2 | 11.0 | 60.7 | 12.86 ± 4.86 |
| mikofo | input-chancalan | 14.1 ± 0.4 | 13.3 | 15.6 | 14.64 ± 2.52 |
| mikofo | input-mattcl | 14.2 ± 0.4 | 13.3 | 15.1 | 14.68 ± 2.52 |
| mikofo | input-lanjian | 14.2 ± 0.4 | 13.1 | 15.0 | 14.68 ± 2.52 |
| mikofo | input-mikofo | 14.4 ± 0.4 | 13.4 | 15.4 | 14.91 ± 2.56 |
| mikofo | input-kcen | 14.5 ± 3.9 | 13.3 | 68.9 | 14.99 ± 4.76 |
| kcen | input-kcen | 14.7 ± 0.6 | 13.5 | 17.7 | 15.29 ± 2.66 |
| mattcl-py | input-lanjian | 14.7 ± 0.5 | 13.9 | 17.8 | 15.29 ± 2.65 |
| kcen | input-chancalan | 14.8 ± 0.6 | 13.6 | 17.8 | 15.30 ± 2.67 |
| mattcl-py | input-chancalan | 14.8 ± 0.6 | 13.5 | 18.0 | 15.32 ± 2.68 |
| pting | input-mattcl | 14.8 ± 0.6 | 13.8 | 18.1 | 15.36 ± 2.67 |
| kcen | input-lanjian | 14.8 ± 0.6 | 13.5 | 17.6 | 15.37 ± 2.69 |
| mattcl-py | input-mattcl | 14.8 ± 0.6 | 14.0 | 18.1 | 15.37 ± 2.68 |
| pting | input-lanjian | 14.8 ± 0.6 | 13.6 | 18.2 | 15.38 ± 2.69 |
| mattcl-py | input-mikofo | 14.8 ± 0.5 | 13.9 | 17.3 | 15.39 ± 2.66 |
| kcen | input-mattcl | 14.8 ± 0.7 | 13.7 | 17.5 | 15.39 ± 2.69 |
| pting | input-kcen | 14.9 ± 0.5 | 13.8 | 17.4 | 15.40 ± 2.67 |
| pting | input-mikofo | 14.9 ± 0.6 | 13.9 | 17.8 | 15.45 ± 2.69 |
| kcen | input-mikofo | 14.9 ± 0.7 | 13.9 | 18.1 | 15.46 ± 2.71 |
| mattcl-py | input-kcen | 15.0 ± 1.7 | 13.7 | 36.7 | 15.51 ± 3.14 |
| chancalan | input-chancalan | 15.1 ± 0.5 | 14.1 | 17.7 | 15.65 ± 2.70 |
| chancalan | input-kcen | 15.1 ± 0.6 | 14.3 | 18.4 | 15.67 ± 2.73 |
| chancalan | input-mattcl | 15.1 ± 0.6 | 14.1 | 17.7 | 15.69 ± 2.72 |
| chancalan | input-lanjian | 15.2 ± 0.5 | 13.9 | 17.6 | 15.75 ± 2.73 |
| chancalan | input-mikofo | 15.3 ± 0.7 | 14.1 | 18.1 | 15.82 ± 2.77 |
| pting | input-chancalan | 15.6 ± 4.1 | 13.8 | 56.8 | 16.13 ± 5.07 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|