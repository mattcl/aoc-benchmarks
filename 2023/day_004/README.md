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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.30 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.30 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.3 | 1.1 | 1.06 ± 0.29 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.33 ± 0.35 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.37 ± 0.36 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.7 | 1.8 | 1.38 ± 0.35 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.41 ± 0.36 |
| lanjian | input-pting | 1.3 ± 0.1 | 0.4 | 1.8 | 1.41 ± 0.35 |
| mattcl-ts | input-chancalan | 11.3 ± 0.3 | 10.1 | 12.1 | 12.65 ± 2.78 |
| mattcl-ts | input-mattcl | 11.3 ± 0.4 | 10.4 | 12.3 | 12.71 ± 2.79 |
| mattcl-ts | input-kcen | 11.4 ± 0.3 | 10.3 | 12.3 | 12.74 ± 2.80 |
| mattcl-ts | input-lanjian | 11.4 ± 0.3 | 10.5 | 12.3 | 12.75 ± 2.80 |
| mattcl-ts | input-pting | 11.4 ± 0.3 | 10.4 | 12.4 | 12.77 ± 2.80 |
| kcen | input-kcen | 14.7 ± 0.6 | 13.9 | 17.9 | 16.49 ± 3.65 |
| kcen | input-mattcl | 14.7 ± 0.5 | 13.5 | 17.7 | 16.50 ± 3.64 |
| kcen | input-chancalan | 14.7 ± 0.6 | 13.7 | 17.9 | 16.51 ± 3.65 |
| kcen | input-lanjian | 14.7 ± 0.6 | 14.0 | 18.3 | 16.51 ± 3.66 |
| mattcl-py | input-chancalan | 14.7 ± 0.7 | 13.5 | 18.4 | 16.51 ± 3.67 |
| mattcl-py | input-kcen | 14.8 ± 0.5 | 13.9 | 17.4 | 16.53 ± 3.64 |
| pting | input-lanjian | 14.8 ± 0.6 | 14.1 | 17.9 | 16.58 ± 3.66 |
| mattcl-py | input-pting | 14.8 ± 0.6 | 13.6 | 18.0 | 16.58 ± 3.67 |
| pting | input-pting | 14.8 ± 0.6 | 14.0 | 17.5 | 16.58 ± 3.66 |
| mattcl-py | input-mattcl | 14.8 ± 0.7 | 13.8 | 18.3 | 16.59 ± 3.70 |
| mattcl-py | input-lanjian | 14.8 ± 0.7 | 13.8 | 17.9 | 16.59 ± 3.69 |
| kcen | input-pting | 14.8 ± 0.5 | 13.7 | 17.7 | 16.62 ± 3.67 |
| pting | input-kcen | 14.9 ± 0.7 | 13.9 | 18.4 | 16.68 ± 3.71 |
| pting | input-mattcl | 14.9 ± 0.6 | 13.6 | 17.5 | 16.69 ± 3.69 |
| chancalan | input-chancalan | 15.1 ± 0.4 | 14.2 | 17.0 | 16.87 ± 3.70 |
| chancalan | input-kcen | 15.1 ± 0.6 | 13.8 | 18.5 | 16.89 ± 3.74 |
| pting | input-chancalan | 15.1 ± 4.3 | 13.5 | 75.4 | 16.95 ± 6.10 |
| chancalan | input-mattcl | 15.2 ± 0.5 | 14.0 | 17.7 | 16.98 ± 3.75 |
| chancalan | input-lanjian | 15.2 ± 0.5 | 14.1 | 17.1 | 17.00 ± 3.74 |
| chancalan | input-pting | 15.3 ± 0.7 | 13.9 | 18.3 | 17.14 ± 3.81 |
| mikofo | input-mattcl | 32.7 ± 0.6 | 31.5 | 35.2 | 36.60 ± 7.99 |
| mikofo | input-kcen | 32.8 ± 0.4 | 32.0 | 33.9 | 36.76 ± 8.01 |
| mikofo | input-pting | 32.9 ± 0.4 | 31.7 | 33.9 | 36.82 ± 8.03 |
| mikofo | input-chancalan | 32.9 ± 0.5 | 31.9 | 34.8 | 36.83 ± 8.04 |
| mikofo | input-lanjian | 32.9 ± 0.4 | 32.1 | 34.2 | 36.84 ± 8.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|