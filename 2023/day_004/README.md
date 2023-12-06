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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.3 | 1.01 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.32 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.3 | 1.04 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.4 | 1.1 | 1.04 ± 0.28 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.4 | 1.7 | 1.32 ± 0.37 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.8 | 1.35 ± 0.37 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.8 | 1.35 ± 0.37 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.38 ± 0.36 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.40 ± 0.35 |
| mattcl-ts | input-chancalan | 11.2 ± 0.4 | 10.3 | 12.2 | 12.93 ± 2.80 |
| mattcl-ts | input-mattcl | 11.3 ± 0.4 | 10.2 | 12.3 | 13.02 ± 2.82 |
| mattcl-ts | input-pting | 11.3 ± 0.4 | 10.3 | 12.5 | 13.08 ± 2.83 |
| mattcl-ts | input-kcen | 11.4 ± 2.4 | 10.3 | 45.0 | 13.25 ± 3.98 |
| mattcl-ts | input-lanjian | 13.5 ± 11.7 | 10.3 | 94.2 | 15.57 ± 13.92 |
| mattcl-py | input-chancalan | 14.4 ± 0.5 | 13.6 | 16.8 | 16.63 ± 3.59 |
| mattcl-py | input-kcen | 14.5 ± 0.6 | 13.6 | 18.1 | 16.79 ± 3.66 |
| pting | input-chancalan | 14.5 ± 0.6 | 13.5 | 17.8 | 16.83 ± 3.67 |
| pting | input-lanjian | 14.5 ± 0.5 | 13.9 | 18.1 | 16.84 ± 3.65 |
| pting | input-kcen | 14.6 ± 0.6 | 13.8 | 17.6 | 16.87 ± 3.66 |
| mattcl-py | input-mattcl | 14.6 ± 0.6 | 13.6 | 17.8 | 16.90 ± 3.69 |
| kcen | input-kcen | 14.6 ± 0.5 | 13.5 | 17.3 | 16.93 ± 3.67 |
| mattcl-py | input-lanjian | 14.7 ± 1.7 | 13.7 | 37.1 | 16.96 ± 4.12 |
| kcen | input-lanjian | 14.7 ± 0.7 | 13.6 | 17.8 | 16.96 ± 3.70 |
| pting | input-pting | 14.7 ± 0.6 | 13.6 | 17.7 | 16.96 ± 3.69 |
| pting | input-mattcl | 14.7 ± 0.6 | 13.7 | 18.2 | 16.96 ± 3.70 |
| kcen | input-mattcl | 14.7 ± 0.5 | 13.7 | 18.0 | 16.96 ± 3.68 |
| kcen | input-chancalan | 14.7 ± 0.7 | 13.6 | 17.8 | 16.97 ± 3.72 |
| mattcl-py | input-pting | 14.7 ± 0.7 | 13.7 | 17.6 | 17.00 ± 3.71 |
| kcen | input-pting | 14.9 ± 0.7 | 13.8 | 18.3 | 17.20 ± 3.78 |
| chancalan | input-chancalan | 14.9 ± 0.7 | 13.7 | 18.2 | 17.23 ± 3.76 |
| chancalan | input-kcen | 15.0 ± 0.6 | 13.8 | 17.8 | 17.32 ± 3.77 |
| chancalan | input-lanjian | 15.0 ± 0.6 | 14.0 | 17.9 | 17.32 ± 3.78 |
| chancalan | input-pting | 15.0 ± 0.5 | 13.8 | 18.0 | 17.36 ± 3.75 |
| chancalan | input-mattcl | 15.1 ± 0.6 | 13.8 | 18.1 | 17.47 ± 3.81 |
| mikofo | input-chancalan | 32.2 ± 0.4 | 31.2 | 33.4 | 37.29 ± 7.98 |
| mikofo | input-lanjian | 32.4 ± 0.5 | 31.3 | 33.5 | 37.46 ± 8.02 |
| mikofo | input-mattcl | 32.4 ± 0.5 | 31.4 | 34.4 | 37.54 ± 8.04 |
| mikofo | input-pting | 32.6 ± 0.5 | 31.5 | 34.5 | 37.70 ± 8.08 |
| mikofo | input-kcen | 36.0 ± 14.1 | 31.4 | 108.0 | 41.64 ± 18.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|