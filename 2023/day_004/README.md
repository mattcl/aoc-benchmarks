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
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.5 | 1.01 ± 0.28 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.5 | 1.05 ± 0.28 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.7 | 1.05 ± 0.27 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.27 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.24 ± 0.32 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.8 | 1.4 | 1.25 ± 0.28 |
| lanjian | input-chancalan | 1.3 ± 0.1 | 0.8 | 1.7 | 1.25 ± 0.29 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.3 | 1.7 | 1.26 ± 0.32 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.4 | 2.1 | 1.29 ± 0.35 |
| mattcl-ts | input-chancalan | 12.0 ± 0.4 | 11.0 | 13.0 | 11.99 ± 2.52 |
| mattcl-ts | input-kcen | 12.0 ± 0.4 | 11.0 | 13.1 | 12.00 ± 2.52 |
| mattcl-ts | input-lanjian | 12.0 ± 0.3 | 11.2 | 13.1 | 12.00 ± 2.52 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 11.1 | 13.6 | 12.03 ± 2.53 |
| mattcl-ts | input-mikofo | 12.5 ± 4.3 | 11.2 | 73.4 | 12.49 ± 5.07 |
| mikofo | input-chancalan | 14.1 ± 0.4 | 13.4 | 16.3 | 14.15 ± 2.97 |
| mikofo | input-kcen | 14.2 ± 0.4 | 13.1 | 15.5 | 14.21 ± 2.98 |
| mikofo | input-mattcl | 14.2 ± 0.4 | 13.4 | 15.4 | 14.25 ± 2.98 |
| mikofo | input-lanjian | 14.3 ± 0.4 | 13.3 | 15.3 | 14.28 ± 2.99 |
| mattcl-py | input-chancalan | 14.7 ± 0.6 | 13.5 | 17.9 | 14.70 ± 3.12 |
| kcen | input-kcen | 14.7 ± 0.5 | 13.5 | 17.7 | 14.73 ± 3.10 |
| pting | input-kcen | 14.7 ± 0.4 | 13.9 | 16.8 | 14.77 ± 3.10 |
| kcen | input-mattcl | 14.7 ± 0.6 | 13.5 | 18.4 | 14.78 ± 3.13 |
| pting | input-lanjian | 14.8 ± 0.6 | 13.9 | 17.9 | 14.84 ± 3.14 |
| pting | input-chancalan | 14.8 ± 0.6 | 13.8 | 18.4 | 14.85 ± 3.14 |
| kcen | input-lanjian | 14.8 ± 0.6 | 13.8 | 17.5 | 14.86 ± 3.14 |
| mattcl-py | input-mattcl | 14.8 ± 0.6 | 14.1 | 18.4 | 14.88 ± 3.15 |
| mattcl-py | input-kcen | 14.9 ± 0.6 | 13.9 | 17.7 | 14.89 ± 3.15 |
| mattcl-py | input-mikofo | 14.9 ± 0.6 | 13.8 | 17.6 | 14.92 ± 3.16 |
| kcen | input-chancalan | 14.9 ± 0.7 | 13.9 | 18.2 | 14.95 ± 3.18 |
| mattcl-py | input-lanjian | 14.9 ± 0.8 | 13.9 | 19.2 | 14.98 ± 3.20 |
| kcen | input-mikofo | 14.9 ± 0.7 | 13.8 | 17.9 | 14.98 ± 3.19 |
| pting | input-mikofo | 15.0 ± 0.7 | 13.6 | 17.6 | 15.02 ± 3.19 |
| chancalan | input-kcen | 15.1 ± 0.6 | 13.8 | 18.2 | 15.12 ± 3.20 |
| chancalan | input-mattcl | 15.1 ± 0.5 | 13.8 | 18.4 | 15.17 ± 3.19 |
| mikofo | input-mikofo | 15.2 ± 5.8 | 13.5 | 68.7 | 15.18 ± 6.64 |
| chancalan | input-chancalan | 15.2 ± 0.6 | 14.3 | 17.7 | 15.22 ± 3.22 |
| chancalan | input-lanjian | 15.2 ± 0.7 | 13.9 | 18.1 | 15.24 ± 3.24 |
| chancalan | input-mikofo | 15.3 ± 0.6 | 14.2 | 18.4 | 15.32 ± 3.24 |
| pting | input-mattcl | 15.4 ± 3.9 | 13.5 | 53.4 | 15.39 ± 5.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|