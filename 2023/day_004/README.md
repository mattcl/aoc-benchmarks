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
| mattcl | input-pting | 0.7 ± 0.2 | 0.0 | 1.4 | 1.00 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 0.9 | 1.00 ± 0.39 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.2 | 1.01 ± 0.38 |
| mattcl | input-chancalan | 0.7 ± 0.2 | 0.0 | 1.3 | 1.03 ± 0.38 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.38 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.4 | 1.6 | 1.44 ± 0.48 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.5 | 1.44 ± 0.49 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.6 | 1.44 ± 0.50 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.2 | 1.48 ± 0.48 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.2 | 1.8 | 1.55 ± 0.52 |
| mattcl-ts | input-lanjian | 11.1 ± 0.3 | 10.3 | 11.8 | 16.35 ± 4.68 |
| mattcl-ts | input-mattcl | 11.1 ± 0.4 | 10.0 | 12.3 | 16.35 ± 4.69 |
| mattcl-ts | input-chancalan | 11.1 ± 0.4 | 10.0 | 11.9 | 16.36 ± 4.70 |
| mattcl-ts | input-pting | 11.1 ± 0.4 | 10.0 | 11.9 | 16.44 ± 4.71 |
| mattcl-ts | input-kcen | 11.2 ± 0.4 | 9.9 | 12.2 | 16.52 ± 4.74 |
| mattcl-py | input-kcen | 14.3 ± 0.6 | 13.4 | 17.8 | 21.19 ± 6.09 |
| mattcl-py | input-chancalan | 14.4 ± 0.5 | 13.5 | 17.2 | 21.23 ± 6.09 |
| mattcl-py | input-mattcl | 14.4 ± 0.6 | 13.3 | 17.4 | 21.27 ± 6.12 |
| pting | input-chancalan | 14.4 ± 0.6 | 13.3 | 18.0 | 21.28 ± 6.13 |
| pting | input-pting | 14.4 ± 0.5 | 13.8 | 17.5 | 21.35 ± 6.13 |
| kcen | input-chancalan | 14.5 ± 0.6 | 13.4 | 17.4 | 21.36 ± 6.14 |
| mattcl-py | input-pting | 14.5 ± 0.6 | 13.4 | 17.8 | 21.39 ± 6.15 |
| pting | input-lanjian | 14.5 ± 0.6 | 13.5 | 17.9 | 21.39 ± 6.15 |
| mattcl-py | input-lanjian | 14.5 ± 0.7 | 13.6 | 17.8 | 21.41 ± 6.17 |
| kcen | input-mattcl | 14.5 ± 0.5 | 13.6 | 17.7 | 21.44 ± 6.15 |
| pting | input-kcen | 14.5 ± 0.7 | 13.5 | 17.5 | 21.44 ± 6.18 |
| kcen | input-lanjian | 14.5 ± 0.6 | 13.7 | 17.2 | 21.49 ± 6.17 |
| pting | input-mattcl | 14.6 ± 0.8 | 13.5 | 17.9 | 21.51 ± 6.23 |
| kcen | input-kcen | 14.6 ± 0.7 | 13.6 | 17.9 | 21.56 ± 6.23 |
| kcen | input-pting | 14.6 ± 0.7 | 13.7 | 17.6 | 21.64 ± 6.24 |
| chancalan | input-kcen | 14.8 ± 0.6 | 13.7 | 17.7 | 21.91 ± 6.30 |
| chancalan | input-mattcl | 14.8 ± 0.6 | 13.8 | 18.3 | 21.94 ± 6.30 |
| chancalan | input-chancalan | 14.8 ± 0.6 | 13.9 | 17.6 | 21.94 ± 6.30 |
| chancalan | input-lanjian | 14.9 ± 0.6 | 14.0 | 18.1 | 22.01 ± 6.32 |
| chancalan | input-pting | 15.0 ± 0.7 | 13.9 | 18.4 | 22.19 ± 6.39 |
| mikofo | input-lanjian | 32.3 ± 0.5 | 31.2 | 34.3 | 47.66 ± 13.58 |
| mikofo | input-mattcl | 32.3 ± 0.4 | 31.2 | 33.3 | 47.73 ± 13.60 |
| mikofo | input-chancalan | 32.3 ± 0.5 | 31.4 | 34.8 | 47.74 ± 13.61 |
| mikofo | input-pting | 32.4 ± 0.5 | 31.5 | 34.6 | 47.86 ± 13.64 |
| mikofo | input-kcen | 32.8 ± 4.0 | 31.1 | 70.1 | 48.50 ± 15.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|