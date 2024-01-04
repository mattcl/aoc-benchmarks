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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.3 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 ± 0.28 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.27 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.8 | 1.03 ± 0.27 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.5 | 1.7 | 1.07 ± 0.28 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.6 | 1.7 | 1.27 ± 0.31 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.8 | 1.28 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.6 | 1.28 ± 0.31 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.5 | 1.7 | 1.29 ± 0.30 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.5 | 2.0 | 1.29 ± 0.32 |
| mattcl-ts | input-chancalan | 11.8 ± 0.4 | 10.9 | 13.1 | 12.93 ± 2.59 |
| mattcl-ts | input-kcen | 11.9 ± 0.4 | 10.8 | 13.0 | 12.94 ± 2.60 |
| mattcl-ts | input-lanjian | 11.9 ± 0.4 | 10.9 | 13.2 | 12.97 ± 2.60 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 11.1 | 12.9 | 13.05 ± 2.62 |
| mattcl-ts | input-mikofo | 12.1 ± 0.4 | 11.2 | 13.0 | 13.16 ± 2.64 |
| mikofo | input-lanjian | 14.0 ± 0.4 | 12.9 | 16.0 | 15.32 ± 3.07 |
| mikofo | input-mattcl | 14.1 ± 0.3 | 13.0 | 14.9 | 15.36 ± 3.07 |
| mikofo | input-kcen | 14.1 ± 0.4 | 13.4 | 16.0 | 15.40 ± 3.08 |
| mikofo | input-mikofo | 14.4 ± 0.4 | 13.4 | 16.2 | 15.67 ± 3.14 |
| mikofo | input-chancalan | 14.4 ± 4.6 | 13.3 | 79.3 | 15.72 ± 5.93 |
| kcen | input-kcen | 14.6 ± 0.5 | 13.7 | 17.5 | 15.93 ± 3.21 |
| kcen | input-chancalan | 14.6 ± 0.7 | 13.5 | 17.8 | 15.95 ± 3.25 |
| mattcl-py | input-chancalan | 14.7 ± 0.5 | 13.9 | 17.2 | 16.01 ± 3.23 |
| pting | input-kcen | 14.7 ± 0.5 | 13.7 | 17.4 | 16.01 ± 3.22 |
| mattcl-py | input-kcen | 14.7 ± 0.6 | 13.4 | 17.9 | 16.01 ± 3.25 |
| kcen | input-lanjian | 14.7 ± 0.8 | 13.5 | 18.3 | 16.03 ± 3.29 |
| pting | input-mattcl | 14.7 ± 0.6 | 13.7 | 18.4 | 16.07 ± 3.25 |
| kcen | input-mikofo | 14.7 ± 0.6 | 13.5 | 18.0 | 16.09 ± 3.26 |
| mattcl-py | input-lanjian | 14.8 ± 0.7 | 13.5 | 18.1 | 16.10 ± 3.27 |
| pting | input-chancalan | 14.8 ± 0.6 | 13.3 | 17.8 | 16.12 ± 3.27 |
| pting | input-lanjian | 14.8 ± 0.7 | 13.7 | 17.8 | 16.14 ± 3.28 |
| mattcl-py | input-mikofo | 14.8 ± 0.7 | 13.5 | 18.1 | 16.16 ± 3.29 |
| mattcl-py | input-mattcl | 14.9 ± 2.0 | 13.5 | 40.7 | 16.24 ± 3.87 |
| pting | input-mikofo | 14.9 ± 0.8 | 13.7 | 18.1 | 16.30 ± 3.34 |
| chancalan | input-chancalan | 15.0 ± 0.6 | 13.7 | 17.5 | 16.38 ± 3.31 |
| chancalan | input-kcen | 15.0 ± 0.6 | 14.0 | 18.4 | 16.42 ± 3.33 |
| chancalan | input-lanjian | 15.1 ± 0.6 | 13.8 | 18.3 | 16.48 ± 3.33 |
| chancalan | input-mikofo | 15.2 ± 0.7 | 13.9 | 18.2 | 16.61 ± 3.37 |
| kcen | input-mattcl | 15.3 ± 4.2 | 13.2 | 52.8 | 16.66 ± 5.66 |
| chancalan | input-mattcl | 15.4 ± 3.3 | 14.0 | 59.7 | 16.75 ± 4.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|