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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.30 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.7 | 1.06 ± 0.30 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.6 | 1.07 ± 0.31 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.4 | 1.6 | 1.10 ± 0.33 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.4 | 1.27 ± 0.34 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.2 | 1.5 | 1.28 ± 0.34 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.7 | 1.28 ± 0.36 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.5 | 1.4 | 1.32 ± 0.34 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.6 | 1.32 ± 0.34 |
| mattcl-ts | input-chancalan | 11.8 ± 0.4 | 10.9 | 12.7 | 13.32 ± 2.96 |
| mattcl-ts | input-kcen | 11.9 ± 0.4 | 11.0 | 13.4 | 13.37 ± 2.98 |
| mattcl-ts | input-mattcl | 11.9 ± 0.3 | 10.9 | 12.7 | 13.37 ± 2.97 |
| mattcl-ts | input-mikofo | 12.1 ± 0.4 | 11.1 | 13.3 | 13.58 ± 3.02 |
| mattcl-ts | input-lanjian | 12.3 ± 4.1 | 10.9 | 64.4 | 13.83 ± 5.51 |
| mikofo | input-chancalan | 14.0 ± 0.4 | 12.8 | 15.0 | 15.77 ± 3.50 |
| mikofo | input-kcen | 14.1 ± 0.4 | 13.0 | 15.4 | 15.88 ± 3.53 |
| mikofo | input-mattcl | 14.2 ± 0.4 | 13.0 | 15.4 | 15.91 ± 3.53 |
| mikofo | input-lanjian | 14.3 ± 1.7 | 12.9 | 38.1 | 16.02 ± 4.04 |
| mikofo | input-mikofo | 14.3 ± 0.3 | 13.5 | 15.2 | 16.11 ± 3.57 |
| pting | input-chancalan | 14.7 ± 0.4 | 13.7 | 17.3 | 16.48 ± 3.67 |
| kcen | input-kcen | 14.7 ± 0.6 | 13.6 | 17.7 | 16.52 ± 3.70 |
| mattcl-py | input-chancalan | 14.7 ± 0.6 | 13.8 | 17.9 | 16.55 ± 3.71 |
| mattcl-py | input-lanjian | 14.7 ± 0.6 | 13.9 | 17.5 | 16.57 ± 3.72 |
| kcen | input-lanjian | 14.7 ± 0.7 | 13.7 | 18.1 | 16.58 ± 3.73 |
| mattcl-py | input-kcen | 14.8 ± 0.7 | 13.4 | 18.3 | 16.58 ± 3.74 |
| pting | input-kcen | 14.8 ± 0.6 | 13.7 | 17.6 | 16.61 ± 3.73 |
| mattcl-py | input-mattcl | 14.8 ± 0.7 | 13.5 | 18.1 | 16.61 ± 3.75 |
| kcen | input-mattcl | 14.8 ± 0.7 | 13.4 | 18.4 | 16.63 ± 3.75 |
| mattcl-py | input-mikofo | 14.8 ± 0.6 | 13.6 | 18.0 | 16.63 ± 3.73 |
| kcen | input-chancalan | 14.8 ± 0.6 | 13.9 | 18.1 | 16.64 ± 3.73 |
| pting | input-lanjian | 14.8 ± 0.7 | 13.7 | 17.8 | 16.66 ± 3.75 |
| pting | input-mattcl | 14.8 ± 0.6 | 13.8 | 18.0 | 16.67 ± 3.73 |
| kcen | input-mikofo | 14.9 ± 0.6 | 13.9 | 17.7 | 16.71 ± 3.74 |
| pting | input-mikofo | 14.9 ± 0.7 | 14.0 | 18.4 | 16.79 ± 3.77 |
| chancalan | input-mattcl | 15.0 ± 0.4 | 14.0 | 17.7 | 16.91 ± 3.76 |
| chancalan | input-kcen | 15.1 ± 0.6 | 13.8 | 17.9 | 16.95 ± 3.79 |
| chancalan | input-chancalan | 15.1 ± 0.7 | 14.0 | 18.1 | 17.00 ± 3.82 |
| chancalan | input-lanjian | 15.1 ± 0.6 | 14.2 | 17.8 | 17.01 ± 3.81 |
| chancalan | input-mikofo | 15.2 ± 0.6 | 14.3 | 18.3 | 17.12 ± 3.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|