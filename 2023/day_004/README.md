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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.1 | 1.01 ± 0.29 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.30 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.2 | 1.04 ± 0.28 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.3 | 1.4 | 1.05 ± 0.30 |
| lanjian | input-mattcl | 1.1 ± 1.9 | 0.3 | 26.7 | 1.20 ± 2.11 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.3 | 1.25 ± 0.35 |
| lanjian | input-chancalan | 1.1 ± 0.1 | 0.7 | 1.3 | 1.26 ± 0.32 |
| lanjian | input-kcen | 1.1 ± 0.1 | 0.5 | 1.3 | 1.26 ± 0.33 |
| lanjian | input-pting | 1.2 ± 0.1 | 0.7 | 1.7 | 1.35 ± 0.34 |
| mattcl-ts | input-kcen | 10.9 ± 0.4 | 9.9 | 12.0 | 12.26 ± 2.79 |
| mattcl-ts | input-chancalan | 10.9 ± 0.4 | 9.9 | 11.9 | 12.28 ± 2.80 |
| mattcl-ts | input-mattcl | 11.0 ± 0.4 | 10.0 | 12.1 | 12.38 ± 2.82 |
| mattcl-ts | input-lanjian | 11.0 ± 0.4 | 9.9 | 12.0 | 12.40 ± 2.83 |
| mattcl-ts | input-pting | 11.3 ± 4.3 | 9.9 | 72.0 | 12.81 ± 5.68 |
| mattcl-py | input-chancalan | 14.2 ± 0.4 | 13.4 | 16.6 | 16.06 ± 3.64 |
| pting | input-chancalan | 14.4 ± 0.6 | 13.3 | 17.5 | 16.25 ± 3.72 |
| kcen | input-chancalan | 14.4 ± 0.6 | 13.3 | 18.2 | 16.30 ± 3.73 |
| mattcl-py | input-mattcl | 14.5 ± 0.6 | 13.4 | 17.9 | 16.33 ± 3.74 |
| pting | input-kcen | 14.5 ± 0.6 | 13.7 | 17.7 | 16.34 ± 3.74 |
| mattcl-py | input-kcen | 14.5 ± 0.8 | 13.3 | 17.7 | 16.34 ± 3.78 |
| mattcl-py | input-lanjian | 14.5 ± 0.5 | 13.5 | 17.5 | 16.34 ± 3.73 |
| mattcl-py | input-pting | 14.6 ± 0.6 | 13.6 | 18.5 | 16.47 ± 3.77 |
| kcen | input-lanjian | 14.6 ± 0.5 | 13.6 | 17.3 | 16.48 ± 3.76 |
| kcen | input-kcen | 14.6 ± 0.7 | 13.7 | 17.7 | 16.50 ± 3.79 |
| pting | input-pting | 14.6 ± 0.6 | 13.7 | 18.3 | 16.53 ± 3.78 |
| pting | input-mattcl | 14.7 ± 0.7 | 13.5 | 17.7 | 16.56 ± 3.81 |
| chancalan | input-chancalan | 14.8 ± 0.6 | 13.8 | 17.7 | 16.66 ± 3.81 |
| chancalan | input-kcen | 14.9 ± 0.6 | 13.6 | 17.7 | 16.79 ± 3.84 |
| kcen | input-pting | 14.9 ± 2.2 | 13.7 | 44.1 | 16.80 ± 4.51 |
| kcen | input-mattcl | 14.9 ± 3.2 | 13.4 | 48.2 | 16.83 ± 5.23 |
| chancalan | input-mattcl | 14.9 ± 0.6 | 13.9 | 18.4 | 16.85 ± 3.85 |
| pting | input-lanjian | 14.9 ± 2.8 | 13.6 | 52.7 | 16.87 ± 4.93 |
| chancalan | input-lanjian | 14.9 ± 0.7 | 13.8 | 17.7 | 16.88 ± 3.88 |
| chancalan | input-pting | 15.1 ± 0.6 | 14.0 | 17.9 | 17.03 ± 3.89 |
| mikofo | input-chancalan | 31.6 ± 0.4 | 30.6 | 32.9 | 35.71 ± 8.05 |
| mikofo | input-kcen | 31.8 ± 0.5 | 30.6 | 33.5 | 35.90 ± 8.10 |
| mikofo | input-lanjian | 32.0 ± 0.5 | 30.9 | 33.1 | 36.08 ± 8.13 |
| mikofo | input-mattcl | 32.0 ± 0.5 | 30.8 | 33.7 | 36.12 ± 8.14 |
| mikofo | input-pting | 32.1 ± 0.4 | 31.2 | 33.6 | 36.25 ± 8.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|