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
| mattcl | input-chancalan | 0.7 ± 0.3 | 0.1 | 1.2 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.15 ± 0.50 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.19 ± 0.48 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.2 | 1.20 ± 0.49 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.4 | 1.3 | 1.23 ± 0.48 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.38 ± 0.59 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.4 | 1.6 | 1.48 ± 0.59 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.49 ± 0.60 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.8 | 1.50 ± 0.60 |
| lanjian | input-pting | 1.1 ± 0.1 | 0.5 | 1.7 | 1.60 ± 0.60 |
| mattcl-ts | input-chancalan | 11.2 ± 0.4 | 10.1 | 12.1 | 15.61 ± 5.55 |
| mattcl-ts | input-kcen | 11.3 ± 0.3 | 10.2 | 12.2 | 15.64 ± 5.56 |
| mattcl-ts | input-mattcl | 11.3 ± 0.3 | 10.2 | 11.9 | 15.65 ± 5.56 |
| mattcl-ts | input-lanjian | 11.3 ± 0.4 | 10.1 | 13.1 | 15.67 ± 5.58 |
| mattcl-ts | input-pting | 11.4 ± 0.3 | 10.2 | 12.4 | 15.82 ± 5.62 |
| mattcl-py | input-chancalan | 14.5 ± 0.6 | 13.3 | 18.1 | 20.19 ± 7.20 |
| pting | input-chancalan | 14.6 ± 0.6 | 13.4 | 17.9 | 20.31 ± 7.24 |
| mattcl-py | input-mattcl | 14.6 ± 0.5 | 13.5 | 17.5 | 20.35 ± 7.24 |
| mattcl-py | input-lanjian | 14.6 ± 0.6 | 13.6 | 17.7 | 20.35 ± 7.26 |
| mattcl-py | input-kcen | 14.7 ± 0.6 | 13.6 | 17.3 | 20.40 ± 7.27 |
| pting | input-kcen | 14.7 ± 0.6 | 13.9 | 17.4 | 20.47 ± 7.30 |
| mattcl-py | input-pting | 14.7 ± 0.7 | 13.8 | 17.7 | 20.48 ± 7.31 |
| pting | input-mattcl | 14.7 ± 0.5 | 13.7 | 17.8 | 20.49 ± 7.30 |
| kcen | input-chancalan | 14.8 ± 0.6 | 13.4 | 17.4 | 20.50 ± 7.31 |
| pting | input-lanjian | 14.8 ± 0.6 | 13.9 | 18.5 | 20.51 ± 7.31 |
| kcen | input-pting | 14.8 ± 0.5 | 13.8 | 17.6 | 20.57 ± 7.32 |
| kcen | input-lanjian | 14.8 ± 0.7 | 13.5 | 17.9 | 20.64 ± 7.37 |
| kcen | input-kcen | 14.9 ± 0.7 | 13.9 | 18.1 | 20.69 ± 7.40 |
| pting | input-pting | 14.9 ± 0.6 | 13.9 | 18.1 | 20.73 ± 7.39 |
| kcen | input-mattcl | 14.9 ± 0.7 | 13.8 | 18.2 | 20.73 ± 7.40 |
| chancalan | input-chancalan | 15.0 ± 0.6 | 13.9 | 18.0 | 20.85 ± 7.44 |
| chancalan | input-kcen | 15.1 ± 0.6 | 14.0 | 18.2 | 20.94 ± 7.47 |
| chancalan | input-mattcl | 15.1 ± 0.5 | 13.8 | 17.7 | 20.95 ± 7.46 |
| chancalan | input-lanjian | 15.1 ± 0.6 | 14.1 | 18.7 | 20.96 ± 7.47 |
| chancalan | input-pting | 15.1 ± 0.6 | 13.9 | 18.1 | 20.98 ± 7.47 |
| mikofo | input-chancalan | 32.5 ± 0.5 | 31.3 | 33.7 | 45.19 ± 16.02 |
| mikofo | input-lanjian | 32.6 ± 0.5 | 31.5 | 34.5 | 45.28 ± 16.05 |
| mikofo | input-kcen | 32.6 ± 0.6 | 31.6 | 35.2 | 45.31 ± 16.07 |
| mikofo | input-pting | 32.8 ± 0.4 | 31.7 | 34.3 | 45.55 ± 16.15 |
| mikofo | input-mattcl | 32.8 ± 0.6 | 31.7 | 34.8 | 45.57 ± 16.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|