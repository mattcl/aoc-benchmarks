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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.7 | 1.03 ± 0.30 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.30 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.2 | 1.05 ± 0.30 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.1 | 1.5 | 1.06 ± 0.31 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.2 | 1.6 | 1.26 ± 0.35 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.7 | 1.28 ± 0.34 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.29 ± 0.35 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.3 | 1.6 | 1.29 ± 0.34 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.32 ± 0.34 |
| mattcl-ts | input-lanjian | 11.8 ± 0.3 | 10.8 | 12.9 | 13.15 ± 2.94 |
| mattcl-ts | input-chancalan | 11.8 ± 0.4 | 10.8 | 12.9 | 13.17 ± 2.95 |
| mattcl-ts | input-mattcl | 11.8 ± 0.4 | 10.9 | 12.9 | 13.19 ± 2.95 |
| mattcl-ts | input-kcen | 11.9 ± 0.4 | 10.8 | 13.2 | 13.30 ± 2.98 |
| mattcl-ts | input-mikofo | 12.0 ± 0.3 | 11.0 | 13.1 | 13.41 ± 3.00 |
| mikofo | input-chancalan | 14.0 ± 0.4 | 13.1 | 16.3 | 15.62 ± 3.50 |
| mikofo | input-kcen | 14.1 ± 0.4 | 13.4 | 15.0 | 15.72 ± 3.51 |
| mikofo | input-mattcl | 14.1 ± 0.4 | 13.2 | 15.9 | 15.74 ± 3.52 |
| mikofo | input-lanjian | 14.1 ± 0.4 | 13.0 | 15.0 | 15.76 ± 3.52 |
| mikofo | input-mikofo | 14.3 ± 0.3 | 13.5 | 15.0 | 15.95 ± 3.56 |
| mattcl-py | input-chancalan | 14.7 ± 0.5 | 13.8 | 18.0 | 16.36 ± 3.67 |
| pting | input-mattcl | 14.7 ± 0.5 | 13.7 | 17.6 | 16.37 ± 3.68 |
| kcen | input-mattcl | 14.7 ± 0.5 | 13.7 | 17.4 | 16.45 ± 3.70 |
| mattcl-py | input-lanjian | 14.8 ± 0.7 | 13.5 | 18.3 | 16.48 ± 3.74 |
| pting | input-chancalan | 14.8 ± 0.6 | 13.7 | 18.0 | 16.48 ± 3.71 |
| mattcl-py | input-mattcl | 14.8 ± 0.7 | 13.6 | 17.9 | 16.48 ± 3.75 |
| kcen | input-chancalan | 14.8 ± 0.6 | 13.5 | 17.5 | 16.48 ± 3.71 |
| kcen | input-mikofo | 14.8 ± 0.5 | 13.8 | 17.1 | 16.49 ± 3.70 |
| kcen | input-kcen | 14.8 ± 0.6 | 13.7 | 18.0 | 16.51 ± 3.73 |
| pting | input-lanjian | 14.8 ± 0.5 | 13.5 | 18.2 | 16.52 ± 3.72 |
| mattcl-py | input-kcen | 14.8 ± 0.8 | 13.7 | 18.3 | 16.53 ± 3.76 |
| kcen | input-lanjian | 14.8 ± 0.6 | 13.7 | 17.5 | 16.55 ± 3.73 |
| pting | input-kcen | 14.8 ± 0.6 | 13.8 | 18.0 | 16.56 ± 3.73 |
| mattcl-py | input-mikofo | 14.9 ± 0.7 | 13.8 | 18.0 | 16.62 ± 3.76 |
| pting | input-mikofo | 14.9 ± 0.6 | 13.9 | 17.6 | 16.65 ± 3.76 |
| chancalan | input-chancalan | 15.0 ± 0.6 | 13.7 | 18.1 | 16.80 ± 3.79 |
| chancalan | input-mattcl | 15.1 ± 0.5 | 14.1 | 17.8 | 16.85 ± 3.79 |
| chancalan | input-lanjian | 15.1 ± 0.6 | 13.7 | 18.1 | 16.89 ± 3.81 |
| chancalan | input-kcen | 15.1 ± 0.7 | 14.1 | 18.0 | 16.90 ± 3.82 |
| chancalan | input-mikofo | 15.2 ± 0.6 | 13.9 | 18.8 | 16.97 ± 3.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|