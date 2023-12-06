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
| mattcl | input-chancalan | 0.8 ± 0.3 | 0.2 | 1.2 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.11 ± 0.41 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.4 | 1.14 ± 0.42 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.4 | 1.14 ± 0.41 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.5 | 1.1 | 1.18 ± 0.39 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.4 | 1.39 ± 0.47 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.8 | 1.39 ± 0.49 |
| lanjian | input-chancalan | 1.2 ± 2.1 | 0.3 | 30.4 | 1.40 ± 2.54 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.6 | 1.5 | 1.44 ± 0.48 |
| lanjian | input-pting | 1.2 ± 0.1 | 0.4 | 1.4 | 1.44 ± 0.48 |
| mattcl-ts | input-chancalan | 11.2 ± 0.4 | 10.2 | 12.3 | 13.36 ± 4.17 |
| mattcl-ts | input-mattcl | 11.2 ± 0.4 | 10.4 | 12.5 | 13.43 ± 4.18 |
| mattcl-ts | input-pting | 11.3 ± 0.4 | 10.2 | 12.8 | 13.52 ± 4.22 |
| mattcl-ts | input-kcen | 11.5 ± 3.0 | 10.4 | 53.8 | 13.73 ± 5.59 |
| mattcl-ts | input-lanjian | 11.7 ± 4.0 | 10.2 | 59.6 | 13.99 ± 6.41 |
| mattcl-py | input-mattcl | 14.5 ± 0.6 | 13.5 | 17.8 | 17.33 ± 5.41 |
| mattcl-py | input-chancalan | 14.5 ± 0.7 | 13.5 | 18.3 | 17.34 ± 5.44 |
| mattcl-py | input-lanjian | 14.5 ± 0.6 | 13.5 | 17.6 | 17.35 ± 5.43 |
| mattcl-py | input-kcen | 14.6 ± 0.5 | 13.6 | 17.5 | 17.38 ± 5.43 |
| pting | input-kcen | 14.6 ± 0.6 | 13.6 | 17.7 | 17.41 ± 5.44 |
| pting | input-chancalan | 14.6 ± 0.7 | 13.5 | 18.0 | 17.42 ± 5.46 |
| pting | input-mattcl | 14.6 ± 0.5 | 13.6 | 17.5 | 17.43 ± 5.44 |
| kcen | input-kcen | 14.6 ± 0.5 | 13.7 | 18.3 | 17.47 ± 5.46 |
| kcen | input-chancalan | 14.7 ± 0.6 | 13.8 | 17.8 | 17.50 ± 5.48 |
| pting | input-lanjian | 14.7 ± 0.5 | 13.6 | 17.5 | 17.54 ± 5.47 |
| kcen | input-lanjian | 14.7 ± 0.6 | 13.8 | 18.2 | 17.57 ± 5.49 |
| mattcl-py | input-pting | 14.7 ± 0.7 | 13.8 | 18.0 | 17.57 ± 5.51 |
| kcen | input-mattcl | 14.7 ± 0.6 | 13.6 | 18.4 | 17.57 ± 5.49 |
| kcen | input-pting | 14.8 ± 0.5 | 13.9 | 17.8 | 17.65 ± 5.51 |
| chancalan | input-kcen | 14.9 ± 0.4 | 14.1 | 16.9 | 17.77 ± 5.53 |
| chancalan | input-chancalan | 14.9 ± 0.6 | 13.8 | 17.5 | 17.79 ± 5.56 |
| chancalan | input-lanjian | 15.0 ± 0.5 | 14.1 | 17.6 | 17.90 ± 5.58 |
| chancalan | input-mattcl | 15.0 ± 0.6 | 13.9 | 18.3 | 17.92 ± 5.61 |
| pting | input-pting | 15.1 ± 4.1 | 13.6 | 72.2 | 18.04 ± 7.44 |
| chancalan | input-pting | 15.1 ± 0.6 | 14.2 | 18.2 | 18.04 ± 5.64 |
| mikofo | input-chancalan | 32.4 ± 0.5 | 31.5 | 35.2 | 38.68 ± 12.01 |
| mikofo | input-lanjian | 32.4 ± 0.4 | 31.7 | 33.4 | 38.74 ± 12.02 |
| mikofo | input-kcen | 32.5 ± 0.5 | 31.6 | 34.8 | 38.81 ± 12.05 |
| mikofo | input-mattcl | 32.5 ± 0.5 | 31.4 | 35.1 | 38.82 ± 12.05 |
| mikofo | input-pting | 32.5 ± 0.4 | 31.7 | 33.6 | 38.86 ± 12.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|