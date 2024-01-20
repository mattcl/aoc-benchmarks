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
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.01 ± 0.25 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.3 | 1.6 | 1.03 ± 0.25 |
| mattcl | input-mikofo | 1.0 ± 0.1 | 0.3 | 1.1 | 1.03 ± 0.24 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.1 | 1.7 | 1.04 ± 0.27 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.25 ± 0.31 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.25 ± 0.29 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.9 | 1.25 ± 0.29 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.28 ± 0.29 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.5 | 1.7 | 1.28 ± 0.29 |
| mattcl-ts | input-chancalan | 11.3 ± 0.3 | 10.1 | 12.1 | 12.03 ± 2.23 |
| mattcl-ts | input-kcen | 11.3 ± 0.3 | 10.1 | 12.2 | 12.06 ± 2.23 |
| mattcl-ts | input-lanjian | 11.3 ± 0.4 | 10.2 | 12.6 | 12.08 ± 2.25 |
| mattcl-ts | input-mattcl | 11.3 ± 0.4 | 10.2 | 12.2 | 12.09 ± 2.24 |
| mattcl-ts | input-mikofo | 11.4 ± 0.4 | 10.4 | 12.8 | 12.19 ± 2.27 |
| mikofo | input-kcen | 13.4 ± 0.4 | 12.3 | 14.5 | 14.33 ± 2.66 |
| mikofo | input-lanjian | 13.4 ± 0.5 | 12.1 | 14.7 | 14.34 ± 2.67 |
| mikofo | input-mattcl | 13.4 ± 0.4 | 12.2 | 14.4 | 14.34 ± 2.66 |
| mikofo | input-chancalan | 13.5 ± 0.4 | 12.5 | 14.7 | 14.44 ± 2.67 |
| mikofo | input-mikofo | 13.6 ± 0.4 | 12.5 | 15.0 | 14.57 ± 2.70 |
| kcen | input-mattcl | 14.7 ± 0.5 | 13.6 | 17.4 | 15.65 ± 2.92 |
| mattcl-py | input-lanjian | 14.7 ± 0.6 | 13.5 | 17.3 | 15.69 ± 2.93 |
| mattcl-py | input-mattcl | 14.7 ± 0.5 | 13.8 | 17.3 | 15.69 ± 2.92 |
| mattcl-py | input-kcen | 14.7 ± 0.5 | 13.5 | 17.2 | 15.72 ± 2.92 |
| pting | input-lanjian | 14.7 ± 0.5 | 13.5 | 17.7 | 15.75 ± 2.94 |
| kcen | input-lanjian | 14.7 ± 0.6 | 13.5 | 17.4 | 15.76 ± 2.94 |
| pting | input-chancalan | 14.8 ± 0.5 | 13.7 | 17.4 | 15.77 ± 2.93 |
| pting | input-mattcl | 14.8 ± 0.6 | 13.5 | 18.5 | 15.78 ± 2.95 |
| mattcl-py | input-chancalan | 14.8 ± 0.6 | 13.8 | 17.8 | 15.79 ± 2.97 |
| kcen | input-chancalan | 14.8 ± 0.7 | 13.8 | 18.5 | 15.81 ± 2.98 |
| kcen | input-kcen | 14.8 ± 0.6 | 13.8 | 17.5 | 15.86 ± 2.96 |
| kcen | input-mikofo | 14.8 ± 0.7 | 13.7 | 18.1 | 15.86 ± 2.99 |
| pting | input-kcen | 14.8 ± 0.7 | 13.5 | 18.0 | 15.86 ± 3.00 |
| mattcl-py | input-mikofo | 14.9 ± 0.6 | 13.8 | 18.1 | 15.90 ± 2.97 |
| pting | input-mikofo | 14.9 ± 0.6 | 13.6 | 17.7 | 15.96 ± 2.98 |
| chancalan | input-lanjian | 15.1 ± 0.5 | 14.0 | 18.5 | 16.09 ± 2.99 |
| chancalan | input-chancalan | 15.1 ± 0.5 | 14.1 | 17.7 | 16.11 ± 3.00 |
| chancalan | input-mattcl | 15.1 ± 0.7 | 13.8 | 18.4 | 16.13 ± 3.04 |
| chancalan | input-kcen | 15.1 ± 0.6 | 14.1 | 17.8 | 16.15 ± 3.02 |
| chancalan | input-mikofo | 15.3 ± 0.7 | 13.9 | 18.2 | 16.29 ± 3.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|