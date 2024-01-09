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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.26 |
| mattcl | input-chancalan | 1.1 ± 0.1 | 0.3 | 1.3 | 1.03 ± 0.24 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.6 | 1.04 ± 0.24 |
| mattcl | input-lanjian | 1.1 ± 0.1 | 0.5 | 1.5 | 1.05 ± 0.24 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.3 | 1.9 | 1.23 ± 0.31 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.6 | 1.9 | 1.26 ± 0.29 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.7 | 1.8 | 1.26 ± 0.28 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.4 | 1.8 | 1.26 ± 0.28 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.8 | 1.26 ± 0.29 |
| mattcl-ts | input-kcen | 11.8 ± 0.3 | 11.0 | 12.6 | 11.52 ± 2.13 |
| mattcl-ts | input-mattcl | 11.8 ± 0.4 | 10.8 | 13.0 | 11.55 ± 2.15 |
| mattcl-ts | input-chancalan | 11.8 ± 0.4 | 10.8 | 12.8 | 11.55 ± 2.14 |
| mattcl-ts | input-mikofo | 11.9 ± 0.3 | 10.9 | 13.0 | 11.67 ± 2.16 |
| mattcl-ts | input-lanjian | 12.2 ± 4.3 | 10.8 | 56.2 | 11.95 ± 4.74 |
| mikofo | input-chancalan | 14.0 ± 0.3 | 13.0 | 14.9 | 13.68 ± 2.53 |
| mikofo | input-kcen | 14.0 ± 0.4 | 13.0 | 15.0 | 13.71 ± 2.53 |
| mikofo | input-mattcl | 14.0 ± 0.3 | 13.2 | 15.1 | 13.72 ± 2.53 |
| mikofo | input-lanjian | 14.1 ± 0.3 | 13.0 | 15.1 | 13.76 ± 2.54 |
| mikofo | input-mikofo | 14.3 ± 0.3 | 13.5 | 15.1 | 13.97 ± 2.58 |
| kcen | input-chancalan | 14.5 ± 0.5 | 13.6 | 17.3 | 14.21 ± 2.65 |
| mattcl-py | input-chancalan | 14.6 ± 0.6 | 13.5 | 17.1 | 14.25 ± 2.66 |
| pting | input-kcen | 14.7 ± 0.5 | 13.7 | 18.5 | 14.33 ± 2.67 |
| mattcl-py | input-kcen | 14.7 ± 0.7 | 13.6 | 17.7 | 14.33 ± 2.70 |
| mattcl-py | input-mattcl | 14.7 ± 0.6 | 13.7 | 17.6 | 14.34 ± 2.68 |
| pting | input-chancalan | 14.7 ± 0.7 | 13.8 | 18.0 | 14.34 ± 2.70 |
| kcen | input-mikofo | 14.7 ± 0.5 | 13.8 | 18.1 | 14.35 ± 2.68 |
| kcen | input-kcen | 14.7 ± 0.7 | 13.7 | 18.7 | 14.36 ± 2.71 |
| kcen | input-lanjian | 14.7 ± 0.7 | 13.6 | 17.9 | 14.36 ± 2.71 |
| kcen | input-mattcl | 14.7 ± 0.7 | 13.9 | 17.9 | 14.37 ± 2.71 |
| pting | input-lanjian | 14.7 ± 0.6 | 13.8 | 17.7 | 14.38 ± 2.69 |
| pting | input-mattcl | 14.7 ± 0.7 | 13.6 | 17.8 | 14.41 ± 2.73 |
| mattcl-py | input-mikofo | 14.8 ± 0.7 | 13.8 | 18.2 | 14.47 ± 2.73 |
| pting | input-mikofo | 14.8 ± 0.7 | 13.6 | 18.3 | 14.51 ± 2.74 |
| chancalan | input-chancalan | 15.0 ± 0.6 | 13.9 | 18.6 | 14.65 ± 2.75 |
| chancalan | input-kcen | 15.0 ± 0.6 | 13.8 | 18.3 | 14.68 ± 2.74 |
| mattcl-py | input-lanjian | 15.0 ± 3.2 | 13.5 | 51.5 | 14.68 ± 4.15 |
| chancalan | input-mattcl | 15.1 ± 0.5 | 13.8 | 18.4 | 14.73 ± 2.75 |
| chancalan | input-lanjian | 15.1 ± 0.7 | 13.9 | 18.7 | 14.74 ± 2.77 |
| chancalan | input-mikofo | 15.3 ± 0.8 | 14.0 | 18.7 | 14.92 ± 2.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|