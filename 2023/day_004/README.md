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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.0 | 1.5 | 1.01 ± 0.38 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.36 |
| mattcl | input-chancalan | 0.8 ± 0.1 | 0.1 | 1.0 | 1.02 ± 0.32 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.07 ± 0.34 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 1.6 | 1.35 ± 0.46 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.38 ± 0.42 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.38 ± 0.43 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.6 | 1.39 ± 0.44 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.52 ± 0.46 |
| mattcl-ts | input-chancalan | 11.0 ± 0.4 | 9.7 | 13.1 | 14.54 ± 3.80 |
| mattcl-ts | input-mattcl | 11.1 ± 0.4 | 10.0 | 12.3 | 14.63 ± 3.83 |
| mattcl-ts | input-lanjian | 11.1 ± 0.4 | 10.1 | 12.1 | 14.63 ± 3.81 |
| mattcl-ts | input-pting | 11.1 ± 0.4 | 10.1 | 12.1 | 14.65 ± 3.82 |
| mattcl-ts | input-kcen | 11.1 ± 0.4 | 10.2 | 12.0 | 14.68 ± 3.83 |
| mattcl-py | input-chancalan | 14.2 ± 0.5 | 13.4 | 17.6 | 18.75 ± 4.89 |
| kcen | input-chancalan | 14.3 ± 0.6 | 13.1 | 17.3 | 18.85 ± 4.94 |
| kcen | input-kcen | 14.4 ± 0.5 | 13.4 | 17.6 | 18.92 ± 4.94 |
| kcen | input-lanjian | 14.4 ± 0.7 | 13.4 | 18.1 | 18.96 ± 4.99 |
| pting | input-chancalan | 14.4 ± 0.6 | 13.5 | 17.5 | 19.00 ± 4.98 |
| pting | input-lanjian | 14.4 ± 0.5 | 13.5 | 17.4 | 19.00 ± 4.95 |
| mattcl-py | input-lanjian | 14.4 ± 0.6 | 13.5 | 18.0 | 19.01 ± 4.99 |
| pting | input-pting | 14.4 ± 0.4 | 13.4 | 16.6 | 19.01 ± 4.94 |
| mattcl-py | input-mattcl | 14.4 ± 0.6 | 13.5 | 17.7 | 19.02 ± 4.98 |
| kcen | input-mattcl | 14.5 ± 0.6 | 13.3 | 17.1 | 19.04 ± 4.98 |
| mattcl-py | input-pting | 14.5 ± 0.6 | 13.4 | 17.5 | 19.05 ± 4.99 |
| pting | input-kcen | 14.5 ± 0.7 | 13.4 | 17.6 | 19.06 ± 5.01 |
| kcen | input-pting | 14.5 ± 0.6 | 13.5 | 17.5 | 19.07 ± 5.00 |
| mattcl-py | input-kcen | 14.5 ± 0.7 | 13.4 | 17.7 | 19.08 ± 5.02 |
| pting | input-mattcl | 14.5 ± 0.5 | 13.5 | 17.3 | 19.14 ± 5.00 |
| chancalan | input-chancalan | 14.8 ± 0.7 | 13.8 | 18.1 | 19.46 ± 5.10 |
| chancalan | input-mattcl | 14.8 ± 0.5 | 13.8 | 17.8 | 19.50 ± 5.09 |
| chancalan | input-kcen | 14.9 ± 0.7 | 13.6 | 18.2 | 19.57 ± 5.13 |
| chancalan | input-lanjian | 14.9 ± 0.7 | 13.9 | 17.9 | 19.61 ± 5.14 |
| chancalan | input-pting | 15.0 ± 0.8 | 13.9 | 18.5 | 19.78 ± 5.21 |
| mikofo | input-chancalan | 32.0 ± 0.5 | 31.0 | 33.1 | 42.18 ± 10.92 |
| mikofo | input-lanjian | 32.2 ± 0.5 | 31.0 | 33.5 | 42.40 ± 10.98 |
| mikofo | input-mattcl | 32.3 ± 0.5 | 31.1 | 35.2 | 42.46 ± 11.00 |
| mikofo | input-pting | 32.3 ± 0.5 | 31.3 | 33.4 | 42.56 ± 11.02 |
| mikofo | input-kcen | 33.0 ± 5.7 | 31.3 | 73.6 | 43.47 ± 13.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|