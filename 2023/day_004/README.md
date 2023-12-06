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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-chancalan | 0.8 ± 0.1 | 0.3 | 1.0 | 1.02 ± 0.28 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.0 | 1.04 ± 0.29 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.3 | 1.1 | 1.04 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.4 | 1.1 | 1.04 ± 0.29 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.5 | 2.0 | 1.33 ± 0.41 |
| lanjian | input-chancalan | 1.1 ± 0.1 | 0.5 | 1.9 | 1.38 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.38 ± 0.39 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.5 | 1.6 | 1.39 ± 0.36 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.6 | 1.6 | 1.40 ± 0.37 |
| mattcl-ts | input-chancalan | 11.2 ± 0.3 | 10.2 | 12.0 | 13.47 ± 3.10 |
| mattcl-ts | input-kcen | 11.2 ± 0.3 | 10.3 | 12.0 | 13.49 ± 3.11 |
| mattcl-ts | input-mattcl | 11.3 ± 0.4 | 10.1 | 12.1 | 13.61 ± 3.14 |
| mattcl-ts | input-lanjian | 11.3 ± 0.3 | 10.5 | 12.4 | 13.63 ± 3.14 |
| mattcl-ts | input-pting | 11.3 ± 0.3 | 10.5 | 12.2 | 13.63 ± 3.14 |
| mattcl-py | input-chancalan | 14.5 ± 0.6 | 13.7 | 18.1 | 17.47 ± 4.05 |
| kcen | input-chancalan | 14.5 ± 0.5 | 13.7 | 17.9 | 17.48 ± 4.05 |
| pting | input-chancalan | 14.6 ± 0.6 | 13.4 | 17.7 | 17.56 ± 4.08 |
| kcen | input-kcen | 14.7 ± 0.6 | 13.6 | 17.9 | 17.64 ± 4.09 |
| mattcl-py | input-lanjian | 14.7 ± 0.6 | 13.6 | 18.1 | 17.65 ± 4.10 |
| mattcl-py | input-kcen | 14.7 ± 0.6 | 13.7 | 17.9 | 17.65 ± 4.10 |
| mattcl-py | input-mattcl | 14.7 ± 0.7 | 13.4 | 18.3 | 17.69 ± 4.12 |
| pting | input-kcen | 14.7 ± 0.7 | 13.7 | 18.6 | 17.71 ± 4.12 |
| kcen | input-lanjian | 14.7 ± 0.7 | 13.5 | 17.7 | 17.75 ± 4.13 |
| pting | input-lanjian | 14.8 ± 0.6 | 13.6 | 17.7 | 17.77 ± 4.13 |
| kcen | input-pting | 14.8 ± 0.7 | 13.5 | 18.1 | 17.78 ± 4.14 |
| kcen | input-mattcl | 14.8 ± 0.7 | 13.7 | 18.1 | 17.80 ± 4.15 |
| pting | input-mattcl | 14.8 ± 0.6 | 13.7 | 18.2 | 17.83 ± 4.14 |
| mattcl-py | input-pting | 14.8 ± 0.8 | 13.6 | 18.1 | 17.85 ± 4.18 |
| pting | input-pting | 14.8 ± 0.7 | 13.5 | 17.8 | 17.88 ± 4.18 |
| chancalan | input-chancalan | 14.9 ± 0.5 | 13.9 | 17.5 | 17.96 ± 4.15 |
| chancalan | input-mattcl | 15.0 ± 0.5 | 13.7 | 18.0 | 18.09 ± 4.18 |
| chancalan | input-kcen | 15.0 ± 0.7 | 13.9 | 18.4 | 18.11 ± 4.22 |
| chancalan | input-lanjian | 15.1 ± 0.6 | 13.9 | 17.6 | 18.15 ± 4.21 |
| chancalan | input-pting | 15.2 ± 0.7 | 14.2 | 18.4 | 18.29 ± 4.26 |
| mikofo | input-kcen | 32.6 ± 0.6 | 31.4 | 35.5 | 39.27 ± 8.99 |
| mikofo | input-mattcl | 32.6 ± 0.5 | 31.5 | 34.0 | 39.30 ± 8.99 |
| mikofo | input-lanjian | 32.7 ± 0.5 | 31.7 | 34.4 | 39.36 ± 9.01 |
| mikofo | input-pting | 32.8 ± 0.5 | 31.5 | 34.8 | 39.45 ± 9.03 |
| mikofo | input-chancalan | 33.3 ± 6.4 | 31.5 | 93.8 | 40.05 ± 11.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|