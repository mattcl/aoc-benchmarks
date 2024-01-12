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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 1.1 ± 0.1 | 0.5 | 1.3 | 1.04 ± 0.24 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.26 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.8 | 1.06 ± 0.25 |
| lanjian | input-chancalan | 1.3 ± 0.1 | 0.7 | 1.5 | 1.24 ± 0.27 |
| lanjian | input-kcen | 1.3 ± 0.1 | 0.4 | 1.6 | 1.24 ± 0.27 |
| lanjian | input-lanjian | 1.3 ± 0.1 | 0.5 | 1.7 | 1.25 ± 0.27 |
| lanjian | input-mattcl | 1.3 ± 0.1 | 0.6 | 1.7 | 1.26 ± 0.28 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.4 | 1.8 | 1.26 ± 0.28 |
| mattcl-ts | input-chancalan | 12.0 ± 0.4 | 11.0 | 12.8 | 11.53 ± 2.21 |
| mattcl-ts | input-kcen | 12.0 ± 0.4 | 11.1 | 12.8 | 11.57 ± 2.22 |
| mattcl-ts | input-lanjian | 12.0 ± 0.4 | 10.8 | 13.0 | 11.59 ± 2.23 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 11.0 | 12.8 | 11.59 ± 2.22 |
| mattcl-ts | input-mikofo | 12.2 ± 0.4 | 11.1 | 13.0 | 11.73 ± 2.25 |
| mikofo | input-chancalan | 14.1 ± 0.4 | 12.9 | 15.6 | 13.65 ± 2.61 |
| mikofo | input-mattcl | 14.2 ± 0.4 | 13.2 | 15.2 | 13.73 ± 2.62 |
| mikofo | input-lanjian | 14.2 ± 0.3 | 13.4 | 15.1 | 13.74 ± 2.62 |
| mikofo | input-kcen | 14.2 ± 0.4 | 13.2 | 15.6 | 13.75 ± 2.63 |
| mikofo | input-mikofo | 14.4 ± 0.4 | 13.7 | 15.4 | 13.92 ± 2.66 |
| kcen | input-lanjian | 14.8 ± 0.5 | 13.6 | 17.5 | 14.27 ± 2.74 |
| mattcl-py | input-mattcl | 14.8 ± 0.6 | 13.7 | 17.6 | 14.30 ± 2.76 |
| mattcl-py | input-chancalan | 14.8 ± 0.7 | 13.6 | 18.0 | 14.32 ± 2.79 |
| mattcl-py | input-kcen | 14.8 ± 0.7 | 13.7 | 18.0 | 14.32 ± 2.79 |
| kcen | input-mattcl | 14.8 ± 0.7 | 13.8 | 18.4 | 14.33 ± 2.79 |
| pting | input-mattcl | 14.9 ± 0.6 | 13.7 | 17.8 | 14.33 ± 2.78 |
| kcen | input-chancalan | 14.9 ± 0.6 | 13.8 | 18.4 | 14.34 ± 2.78 |
| kcen | input-kcen | 14.9 ± 0.5 | 13.6 | 17.5 | 14.34 ± 2.76 |
| mattcl-py | input-lanjian | 14.9 ± 0.7 | 13.9 | 18.3 | 14.38 ± 2.79 |
| pting | input-lanjian | 14.9 ± 0.6 | 14.0 | 18.3 | 14.40 ± 2.79 |
| pting | input-chancalan | 14.9 ± 0.6 | 13.7 | 18.2 | 14.40 ± 2.78 |
| mattcl-py | input-mikofo | 14.9 ± 0.5 | 13.8 | 17.9 | 14.40 ± 2.77 |
| pting | input-mikofo | 14.9 ± 0.5 | 14.1 | 17.7 | 14.42 ± 2.78 |
| kcen | input-mikofo | 15.0 ± 0.5 | 13.8 | 17.8 | 14.43 ± 2.78 |
| chancalan | input-chancalan | 15.2 ± 0.6 | 14.1 | 17.9 | 14.62 ± 2.82 |
| pting | input-kcen | 15.2 ± 3.0 | 13.6 | 56.0 | 14.67 ± 4.01 |
| chancalan | input-kcen | 15.2 ± 0.5 | 14.4 | 17.6 | 14.69 ± 2.83 |
| chancalan | input-mikofo | 15.2 ± 0.6 | 14.1 | 18.1 | 14.70 ± 2.84 |
| chancalan | input-lanjian | 15.3 ± 0.5 | 14.3 | 18.2 | 14.72 ± 2.83 |
| chancalan | input-mattcl | 15.4 ± 2.7 | 13.7 | 51.5 | 14.87 ± 3.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|