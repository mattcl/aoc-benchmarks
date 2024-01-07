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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.27 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.28 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.4 | 1.5 | 1.03 ± 0.25 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.27 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.23 ± 0.31 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.25 ± 0.32 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.3 | 1.9 | 1.27 ± 0.35 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.6 | 2.0 | 1.27 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.8 | 1.28 ± 0.32 |
| mattcl-ts | input-chancalan | 11.6 ± 0.4 | 10.4 | 12.7 | 12.13 ± 2.47 |
| mattcl-ts | input-lanjian | 11.6 ± 0.3 | 10.6 | 12.7 | 12.15 ± 2.47 |
| mattcl-ts | input-mattcl | 11.6 ± 0.4 | 10.8 | 12.6 | 12.16 ± 2.48 |
| mattcl-ts | input-mikofo | 11.7 ± 0.4 | 10.6 | 12.7 | 12.22 ± 2.49 |
| mattcl-ts | input-kcen | 12.1 ± 3.9 | 10.7 | 58.5 | 12.59 ± 4.76 |
| mikofo | input-chancalan | 13.6 ± 0.4 | 12.5 | 14.6 | 14.23 ± 2.89 |
| mikofo | input-mattcl | 13.7 ± 0.4 | 12.6 | 15.1 | 14.29 ± 2.90 |
| mikofo | input-lanjian | 13.7 ± 0.4 | 12.7 | 14.4 | 14.29 ± 2.90 |
| mikofo | input-mikofo | 13.8 ± 0.4 | 12.7 | 14.6 | 14.42 ± 2.93 |
| mikofo | input-kcen | 13.9 ± 2.7 | 12.9 | 51.2 | 14.51 ± 4.04 |
| mattcl-py | input-kcen | 14.4 ± 0.4 | 13.5 | 16.0 | 15.03 ± 3.06 |
| mattcl-py | input-lanjian | 14.4 ± 0.5 | 13.6 | 17.3 | 15.04 ± 3.08 |
| kcen | input-chancalan | 14.4 ± 0.6 | 13.4 | 17.6 | 15.06 ± 3.10 |
| kcen | input-kcen | 14.4 ± 0.5 | 13.6 | 16.8 | 15.09 ± 3.08 |
| pting | input-kcen | 14.5 ± 0.5 | 13.4 | 18.4 | 15.12 ± 3.09 |
| pting | input-mattcl | 14.5 ± 0.7 | 13.5 | 17.6 | 15.13 ± 3.12 |
| mattcl-py | input-mikofo | 14.5 ± 0.5 | 13.5 | 17.3 | 15.13 ± 3.09 |
| mattcl-py | input-chancalan | 14.5 ± 0.8 | 13.4 | 17.4 | 15.15 ± 3.15 |
| kcen | input-mattcl | 14.5 ± 0.7 | 13.5 | 18.2 | 15.15 ± 3.14 |
| mattcl-py | input-mattcl | 14.5 ± 0.6 | 13.6 | 17.6 | 15.16 ± 3.12 |
| pting | input-chancalan | 14.5 ± 0.8 | 13.7 | 17.8 | 15.16 ± 3.15 |
| kcen | input-mikofo | 14.6 ± 0.6 | 13.6 | 17.2 | 15.21 ± 3.13 |
| pting | input-lanjian | 14.6 ± 0.7 | 13.6 | 18.4 | 15.24 ± 3.15 |
| pting | input-mikofo | 14.7 ± 0.7 | 13.7 | 18.4 | 15.32 ± 3.16 |
| kcen | input-lanjian | 14.8 ± 3.7 | 13.6 | 66.3 | 15.41 ± 4.97 |
| chancalan | input-chancalan | 14.8 ± 0.6 | 13.8 | 18.1 | 15.50 ± 3.19 |
| chancalan | input-lanjian | 14.9 ± 0.6 | 13.7 | 18.3 | 15.56 ± 3.19 |
| chancalan | input-kcen | 14.9 ± 0.6 | 13.8 | 18.0 | 15.58 ± 3.20 |
| chancalan | input-mattcl | 14.9 ± 0.6 | 13.9 | 17.9 | 15.62 ± 3.20 |
| chancalan | input-mikofo | 15.1 ± 0.5 | 14.0 | 17.7 | 15.73 ± 3.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|