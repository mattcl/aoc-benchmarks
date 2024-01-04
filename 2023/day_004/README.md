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
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.32 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.4 | 1.6 | 1.05 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.07 ± 0.31 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.28 ± 0.38 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.4 | 1.6 | 1.29 ± 0.36 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.8 | 1.32 ± 0.37 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.6 | 1.6 | 1.35 ± 0.35 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.6 | 1.7 | 1.36 ± 0.38 |
| mattcl-ts | input-chancalan | 11.4 ± 0.3 | 10.5 | 12.1 | 13.04 ± 3.10 |
| mattcl-ts | input-mattcl | 11.4 ± 0.3 | 10.3 | 12.0 | 13.06 ± 3.11 |
| mattcl-ts | input-kcen | 11.4 ± 0.3 | 10.4 | 12.3 | 13.08 ± 3.11 |
| mattcl-ts | input-lanjian | 11.4 ± 0.3 | 10.5 | 12.9 | 13.09 ± 3.12 |
| mattcl-ts | input-mikofo | 11.5 ± 0.3 | 10.5 | 12.8 | 13.23 ± 3.15 |
| mikofo | input-chancalan | 13.7 ± 0.4 | 12.6 | 14.6 | 15.74 ± 3.74 |
| mikofo | input-mattcl | 13.7 ± 0.3 | 12.7 | 14.9 | 15.76 ± 3.74 |
| mikofo | input-lanjian | 13.8 ± 0.4 | 12.9 | 14.8 | 15.81 ± 3.76 |
| mikofo | input-mikofo | 13.9 ± 0.3 | 13.0 | 14.8 | 15.95 ± 3.79 |
| mikofo | input-kcen | 14.1 ± 4.4 | 12.7 | 66.6 | 16.24 ± 6.37 |
| mattcl-py | input-kcen | 14.3 ± 0.5 | 13.6 | 18.0 | 16.48 ± 3.93 |
| kcen | input-chancalan | 14.4 ± 0.6 | 13.6 | 17.4 | 16.52 ± 3.95 |
| kcen | input-mattcl | 14.4 ± 0.6 | 13.3 | 17.6 | 16.53 ± 3.97 |
| mattcl-py | input-lanjian | 14.4 ± 0.6 | 13.4 | 17.6 | 16.53 ± 3.97 |
| pting | input-mattcl | 14.4 ± 0.5 | 13.4 | 17.5 | 16.55 ± 3.96 |
| kcen | input-kcen | 14.4 ± 0.5 | 13.4 | 17.4 | 16.55 ± 3.96 |
| kcen | input-mikofo | 14.4 ± 0.5 | 13.5 | 17.2 | 16.59 ± 3.97 |
| pting | input-kcen | 14.4 ± 0.6 | 13.4 | 17.5 | 16.60 ± 3.98 |
| mattcl-py | input-mikofo | 14.5 ± 0.6 | 13.4 | 18.2 | 16.61 ± 3.98 |
| mattcl-py | input-mattcl | 14.5 ± 0.6 | 13.4 | 17.5 | 16.62 ± 3.99 |
| mattcl-py | input-chancalan | 14.5 ± 0.7 | 13.4 | 18.1 | 16.62 ± 4.02 |
| pting | input-chancalan | 14.5 ± 0.7 | 13.5 | 17.6 | 16.63 ± 4.00 |
| kcen | input-lanjian | 14.5 ± 0.8 | 13.4 | 18.0 | 16.66 ± 4.04 |
| pting | input-lanjian | 14.5 ± 0.7 | 13.5 | 17.6 | 16.66 ± 4.01 |
| pting | input-mikofo | 14.6 ± 0.8 | 13.5 | 18.3 | 16.75 ± 4.05 |
| chancalan | input-chancalan | 14.8 ± 0.6 | 13.8 | 17.8 | 17.01 ± 4.08 |
| chancalan | input-kcen | 14.8 ± 0.5 | 13.7 | 17.4 | 17.04 ± 4.06 |
| chancalan | input-mattcl | 14.9 ± 0.7 | 13.7 | 18.1 | 17.11 ± 4.12 |
| chancalan | input-lanjian | 14.9 ± 0.6 | 13.6 | 18.1 | 17.11 ± 4.11 |
| chancalan | input-mikofo | 15.0 ± 0.7 | 13.7 | 18.2 | 17.25 ± 4.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|