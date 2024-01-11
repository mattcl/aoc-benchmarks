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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.7 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.28 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.2 | 1.03 ± 0.27 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.4 | 1.05 ± 0.27 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.4 | 1.06 ± 0.28 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.6 | 1.26 ± 0.31 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.26 ± 0.34 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.27 ± 0.31 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.7 | 1.7 | 1.28 ± 0.31 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.4 | 2.1 | 1.31 ± 0.34 |
| mattcl-ts | input-lanjian | 11.8 ± 0.4 | 10.8 | 12.8 | 12.06 ± 2.58 |
| mattcl-ts | input-kcen | 11.9 ± 0.4 | 10.7 | 13.0 | 12.11 ± 2.60 |
| mattcl-ts | input-mattcl | 11.9 ± 0.4 | 10.8 | 12.8 | 12.12 ± 2.60 |
| mattcl-ts | input-chancalan | 11.9 ± 0.3 | 10.8 | 12.9 | 12.14 ± 2.60 |
| mattcl-ts | input-mikofo | 12.0 ± 0.4 | 11.0 | 13.2 | 12.27 ± 2.63 |
| mikofo | input-mattcl | 14.1 ± 0.4 | 12.8 | 15.3 | 14.36 ± 3.07 |
| mikofo | input-chancalan | 14.1 ± 0.4 | 13.1 | 15.0 | 14.37 ± 3.07 |
| mikofo | input-kcen | 14.1 ± 0.4 | 13.0 | 15.6 | 14.40 ± 3.08 |
| mikofo | input-lanjian | 14.1 ± 0.4 | 13.1 | 15.1 | 14.44 ± 3.09 |
| mikofo | input-mikofo | 14.3 ± 0.4 | 13.3 | 16.2 | 14.64 ± 3.13 |
| kcen | input-mattcl | 14.7 ± 0.6 | 13.5 | 17.8 | 15.01 ± 3.24 |
| mattcl-py | input-chancalan | 14.7 ± 0.7 | 13.7 | 18.4 | 15.01 ± 3.26 |
| pting | input-kcen | 14.7 ± 0.6 | 13.5 | 17.4 | 15.01 ± 3.24 |
| mattcl-py | input-lanjian | 14.7 ± 0.6 | 13.4 | 18.0 | 15.02 ± 3.24 |
| kcen | input-lanjian | 14.7 ± 0.6 | 13.6 | 17.7 | 15.03 ± 3.26 |
| kcen | input-kcen | 14.7 ± 0.6 | 13.8 | 17.9 | 15.03 ± 3.25 |
| pting | input-chancalan | 14.7 ± 0.7 | 13.5 | 18.2 | 15.06 ± 3.27 |
| mattcl-py | input-mattcl | 14.7 ± 0.7 | 13.7 | 18.1 | 15.07 ± 3.27 |
| mattcl-py | input-kcen | 14.8 ± 0.6 | 13.8 | 17.9 | 15.07 ± 3.26 |
| kcen | input-mikofo | 14.8 ± 0.7 | 13.7 | 18.2 | 15.07 ± 3.27 |
| kcen | input-chancalan | 14.8 ± 0.7 | 13.7 | 18.0 | 15.07 ± 3.28 |
| pting | input-mattcl | 14.8 ± 0.7 | 13.5 | 18.3 | 15.12 ± 3.28 |
| pting | input-lanjian | 14.8 ± 0.7 | 13.7 | 18.6 | 15.13 ± 3.30 |
| pting | input-mikofo | 14.9 ± 0.6 | 13.8 | 18.1 | 15.18 ± 3.28 |
| mattcl-py | input-mikofo | 14.9 ± 0.7 | 13.6 | 18.3 | 15.19 ± 3.31 |
| chancalan | input-kcen | 15.0 ± 0.4 | 13.8 | 17.0 | 15.35 ± 3.29 |
| chancalan | input-chancalan | 15.1 ± 0.7 | 14.0 | 17.6 | 15.46 ± 3.35 |
| chancalan | input-mattcl | 15.2 ± 0.6 | 14.1 | 18.6 | 15.49 ± 3.35 |
| chancalan | input-mikofo | 15.2 ± 0.7 | 14.1 | 18.3 | 15.55 ± 3.37 |
| chancalan | input-lanjian | 15.3 ± 2.8 | 14.1 | 52.7 | 15.67 ± 4.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|