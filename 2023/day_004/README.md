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
| mattcl | input-chancalan | 0.4 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.82 ± 0.97 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.83 ± 0.99 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.83 ± 1.01 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.3 | 1.88 ± 1.00 |
| mattcl | input-mikofo | 0.9 ± 0.1 | 0.3 | 1.0 | 1.95 ± 1.00 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.5 | 2.32 ± 1.23 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 2.49 ± 1.29 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 2.51 ± 1.31 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.9 | 2.54 ± 1.32 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.8 | 2.59 ± 1.35 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.6 | 2.6 | 2.62 ± 1.37 |
| mattcl-ts | input-chancalan | 11.2 ± 0.4 | 10.4 | 12.6 | 25.44 ± 12.57 |
| mattcl-ts | input-lanjian | 11.2 ± 0.3 | 10.5 | 12.1 | 25.56 ± 12.62 |
| mattcl-ts | input-mattcl | 11.3 ± 0.3 | 10.1 | 12.3 | 25.62 ± 12.65 |
| mattcl-ts | input-kcen | 11.3 ± 0.3 | 10.4 | 12.8 | 25.71 ± 12.70 |
| mattcl-ts | input-mikofo | 11.4 ± 0.3 | 10.4 | 12.9 | 25.87 ± 12.77 |
| mattcl-ts | input-pting | 11.6 ± 3.5 | 10.5 | 60.2 | 26.25 ± 15.15 |
| mikofo | input-kcen | 13.8 ± 0.3 | 12.9 | 15.0 | 31.45 ± 15.52 |
| mikofo | input-mattcl | 13.9 ± 0.3 | 12.6 | 15.2 | 31.48 ± 15.53 |
| mikofo | input-lanjian | 13.9 ± 0.3 | 13.0 | 14.9 | 31.54 ± 15.57 |
| mikofo | input-chancalan | 14.0 ± 2.7 | 12.6 | 51.8 | 31.71 ± 16.80 |
| mikofo | input-mikofo | 14.1 ± 0.3 | 13.3 | 14.9 | 32.05 ± 15.81 |
| mikofo | input-pting | 14.2 ± 3.7 | 13.1 | 65.8 | 32.37 ± 18.01 |
| kcen | input-chancalan | 14.3 ± 0.5 | 13.2 | 16.6 | 32.40 ± 16.02 |
| pting | input-chancalan | 14.3 ± 0.5 | 13.4 | 17.4 | 32.48 ± 16.05 |
| mattcl-py | input-kcen | 14.3 ± 0.7 | 13.5 | 18.2 | 32.52 ± 16.10 |
| mattcl-py | input-chancalan | 14.4 ± 0.7 | 13.3 | 17.5 | 32.61 ± 16.16 |
| pting | input-lanjian | 14.4 ± 0.4 | 13.3 | 16.2 | 32.67 ± 16.13 |
| mattcl-py | input-mattcl | 14.4 ± 0.6 | 13.3 | 18.3 | 32.69 ± 16.18 |
| kcen | input-lanjian | 14.4 ± 0.6 | 13.4 | 18.3 | 32.73 ± 16.19 |
| mattcl-py | input-mikofo | 14.5 ± 0.5 | 13.5 | 17.7 | 32.84 ± 16.23 |
| kcen | input-mattcl | 14.5 ± 0.6 | 13.5 | 17.6 | 32.84 ± 16.25 |
| mattcl-py | input-lanjian | 14.5 ± 0.6 | 13.7 | 17.5 | 32.84 ± 16.25 |
| pting | input-kcen | 14.5 ± 0.7 | 13.4 | 17.8 | 32.87 ± 16.28 |
| pting | input-mattcl | 14.5 ± 0.6 | 13.4 | 18.0 | 32.93 ± 16.29 |
| kcen | input-mikofo | 14.5 ± 0.5 | 13.5 | 17.8 | 32.94 ± 16.28 |
| mattcl-py | input-pting | 14.5 ± 0.6 | 13.5 | 17.7 | 33.01 ± 16.33 |
| pting | input-pting | 14.6 ± 0.6 | 13.5 | 17.8 | 33.10 ± 16.38 |
| pting | input-mikofo | 14.6 ± 0.6 | 13.7 | 18.4 | 33.21 ± 16.43 |
| chancalan | input-chancalan | 14.7 ± 0.7 | 13.7 | 18.2 | 33.33 ± 16.50 |
| kcen | input-pting | 14.7 ± 2.5 | 13.5 | 49.4 | 33.40 ± 17.42 |
| kcen | input-kcen | 14.8 ± 4.9 | 13.4 | 75.5 | 33.52 ± 19.94 |
| chancalan | input-kcen | 14.8 ± 0.6 | 13.8 | 17.6 | 33.65 ± 16.63 |
| chancalan | input-lanjian | 14.8 ± 0.5 | 13.6 | 17.5 | 33.65 ± 16.63 |
| chancalan | input-mattcl | 14.9 ± 0.7 | 13.8 | 18.1 | 33.92 ± 16.79 |
| chancalan | input-pting | 14.9 ± 0.6 | 14.0 | 17.6 | 33.96 ± 16.79 |
| chancalan | input-mikofo | 15.0 ± 0.7 | 13.8 | 18.2 | 34.10 ± 16.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|