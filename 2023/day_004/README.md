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
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.2 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.4 | 1.4 | 1.02 ± 0.25 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.3 | 1.03 ± 0.25 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.8 | 1.05 ± 0.26 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.5 | 1.1 | 1.06 ± 0.23 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.6 | 1.26 ± 0.28 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.9 | 1.27 ± 0.29 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.3 | 1.3 | 1.27 ± 0.27 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.27 ± 0.29 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.4 | 2.0 | 1.32 ± 0.32 |
| mattcl-ts | input-chancalan | 11.6 ± 0.4 | 10.6 | 13.4 | 12.53 ± 2.28 |
| mattcl-ts | input-kcen | 11.6 ± 0.4 | 10.6 | 12.5 | 12.54 ± 2.28 |
| mattcl-ts | input-mattcl | 11.6 ± 0.4 | 10.6 | 12.7 | 12.57 ± 2.28 |
| mattcl-ts | input-mikofo | 11.7 ± 0.4 | 10.5 | 12.7 | 12.59 ± 2.29 |
| mattcl-ts | input-lanjian | 12.1 ± 4.6 | 10.7 | 59.3 | 13.01 ± 5.52 |
| mikofo | input-chancalan | 13.8 ± 0.4 | 12.8 | 15.0 | 14.91 ± 2.70 |
| mikofo | input-kcen | 13.8 ± 0.3 | 13.0 | 14.7 | 14.95 ± 2.70 |
| mikofo | input-lanjian | 13.9 ± 0.3 | 12.8 | 15.0 | 14.98 ± 2.71 |
| mikofo | input-mattcl | 13.9 ± 0.4 | 13.0 | 14.9 | 14.99 ± 2.72 |
| mikofo | input-mikofo | 14.0 ± 0.3 | 13.4 | 14.9 | 15.17 ± 2.74 |
| mattcl-py | input-chancalan | 14.6 ± 0.6 | 13.5 | 18.0 | 15.81 ± 2.91 |
| mattcl-py | input-lanjian | 14.7 ± 1.2 | 13.5 | 29.1 | 15.82 ± 3.10 |
| mattcl-py | input-mattcl | 14.7 ± 0.7 | 13.8 | 17.8 | 15.88 ± 2.93 |
| kcen | input-chancalan | 14.7 ± 0.8 | 13.4 | 17.8 | 15.88 ± 2.96 |
| pting | input-lanjian | 14.7 ± 0.6 | 13.8 | 18.1 | 15.88 ± 2.91 |
| kcen | input-mattcl | 14.7 ± 0.7 | 13.4 | 17.6 | 15.88 ± 2.93 |
| kcen | input-kcen | 14.7 ± 0.7 | 13.6 | 17.8 | 15.89 ± 2.94 |
| kcen | input-lanjian | 14.7 ± 0.6 | 13.9 | 18.2 | 15.92 ± 2.92 |
| mattcl-py | input-mikofo | 14.8 ± 0.5 | 13.9 | 17.3 | 15.93 ± 2.91 |
| pting | input-kcen | 14.8 ± 0.7 | 13.5 | 18.7 | 15.94 ± 2.94 |
| mattcl-py | input-kcen | 14.8 ± 0.7 | 13.5 | 17.9 | 15.96 ± 2.95 |
| pting | input-chancalan | 14.8 ± 0.7 | 13.8 | 17.9 | 15.96 ± 2.94 |
| kcen | input-mikofo | 14.8 ± 0.6 | 13.7 | 17.9 | 15.99 ± 2.94 |
| pting | input-mattcl | 14.8 ± 0.7 | 13.6 | 17.9 | 16.03 ± 2.96 |
| pting | input-mikofo | 14.9 ± 0.7 | 13.7 | 18.5 | 16.06 ± 2.98 |
| chancalan | input-mattcl | 15.0 ± 0.6 | 13.7 | 18.1 | 16.19 ± 2.97 |
| chancalan | input-chancalan | 15.0 ± 0.5 | 13.9 | 17.5 | 16.22 ± 2.96 |
| chancalan | input-kcen | 15.1 ± 0.7 | 13.8 | 18.0 | 16.33 ± 3.02 |
| chancalan | input-lanjian | 15.1 ± 0.7 | 14.1 | 18.5 | 16.35 ± 3.01 |
| chancalan | input-mikofo | 15.2 ± 0.5 | 14.2 | 18.2 | 16.42 ± 3.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|