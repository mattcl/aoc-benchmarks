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
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.5 | 1.01 ± 0.25 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.26 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.2 | 1.04 ± 0.24 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.2 | 1.6 | 1.04 ± 0.25 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.23 ± 0.32 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.26 ± 0.29 |
| lanjian | input-mikofo | 1.2 ± 0.1 | 0.6 | 1.7 | 1.27 ± 0.29 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.8 | 1.4 | 1.27 ± 0.26 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.9 | 1.28 ± 0.31 |
| mattcl-ts | input-kcen | 11.9 ± 0.4 | 10.6 | 13.3 | 12.67 ± 2.42 |
| mattcl-ts | input-lanjian | 11.9 ± 0.4 | 10.7 | 13.0 | 12.70 ± 2.43 |
| mattcl-ts | input-mattcl | 11.9 ± 0.4 | 10.8 | 12.9 | 12.74 ± 2.43 |
| mattcl-ts | input-mikofo | 12.0 ± 0.4 | 11.1 | 13.1 | 12.86 ± 2.45 |
| mattcl-ts | input-chancalan | 12.6 ± 4.8 | 11.2 | 63.4 | 13.47 ± 5.71 |
| mikofo | input-mattcl | 14.1 ± 0.3 | 13.1 | 15.0 | 15.07 ± 2.86 |
| mikofo | input-kcen | 14.1 ± 0.4 | 13.1 | 15.4 | 15.08 ± 2.86 |
| mikofo | input-lanjian | 14.2 ± 0.4 | 13.3 | 16.0 | 15.14 ± 2.88 |
| mikofo | input-chancalan | 14.3 ± 2.4 | 13.3 | 47.2 | 15.24 ± 3.82 |
| mikofo | input-mikofo | 14.4 ± 0.5 | 13.3 | 18.0 | 15.37 ± 2.94 |
| mattcl-py | input-chancalan | 14.7 ± 0.7 | 13.8 | 18.5 | 15.70 ± 3.03 |
| kcen | input-lanjian | 14.7 ± 0.7 | 13.8 | 17.7 | 15.72 ± 3.04 |
| kcen | input-mattcl | 14.7 ± 0.6 | 13.7 | 17.7 | 15.72 ± 3.03 |
| kcen | input-chancalan | 14.7 ± 0.7 | 13.8 | 18.0 | 15.72 ± 3.06 |
| mattcl-py | input-kcen | 14.7 ± 0.6 | 13.6 | 18.0 | 15.74 ± 3.03 |
| kcen | input-kcen | 14.7 ± 0.6 | 13.9 | 17.7 | 15.75 ± 3.02 |
| mattcl-py | input-mattcl | 14.8 ± 0.6 | 13.7 | 17.6 | 15.76 ± 3.04 |
| pting | input-mattcl | 14.8 ± 0.7 | 13.6 | 17.8 | 15.77 ± 3.05 |
| mattcl-py | input-mikofo | 14.8 ± 0.5 | 13.8 | 17.7 | 15.82 ± 3.03 |
| pting | input-kcen | 14.8 ± 0.7 | 13.8 | 18.2 | 15.84 ± 3.06 |
| kcen | input-mikofo | 14.9 ± 0.6 | 13.7 | 18.4 | 15.88 ± 3.06 |
| mattcl-py | input-lanjian | 14.9 ± 0.7 | 14.0 | 18.5 | 15.93 ± 3.10 |
| pting | input-lanjian | 15.0 ± 2.4 | 13.9 | 46.8 | 16.00 ± 3.94 |
| chancalan | input-mattcl | 15.0 ± 0.5 | 13.8 | 17.5 | 16.04 ± 3.06 |
| pting | input-chancalan | 15.0 ± 2.4 | 13.8 | 46.9 | 16.05 ± 3.95 |
| chancalan | input-lanjian | 15.1 ± 0.6 | 13.8 | 17.8 | 16.10 ± 3.09 |
| chancalan | input-chancalan | 15.1 ± 0.5 | 14.1 | 18.4 | 16.13 ± 3.09 |
| chancalan | input-kcen | 15.1 ± 0.7 | 13.8 | 18.4 | 16.17 ± 3.13 |
| chancalan | input-mikofo | 15.3 ± 0.7 | 14.2 | 18.4 | 16.34 ± 3.16 |
| pting | input-mikofo | 15.3 ± 3.4 | 13.8 | 49.0 | 16.36 ± 4.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|