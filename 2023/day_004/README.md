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
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.4 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.4 | 1.00 ± 0.23 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.4 | 1.2 | 1.01 ± 0.22 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.23 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.4 | 1.5 | 1.02 ± 0.23 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.16 ± 0.31 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.8 | 1.24 ± 0.27 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.24 ± 0.26 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.6 | 1.8 | 1.26 ± 0.28 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.7 | 2.0 | 1.27 ± 0.27 |
| mattcl-ts | input-chancalan | 11.5 ± 0.3 | 10.5 | 12.4 | 11.35 ± 1.92 |
| mattcl-ts | input-lanjian | 11.5 ± 0.3 | 10.4 | 12.2 | 11.37 ± 1.93 |
| mattcl-ts | input-mattcl | 11.5 ± 0.3 | 10.6 | 12.6 | 11.41 ± 1.93 |
| mattcl-ts | input-kcen | 11.6 ± 0.4 | 10.5 | 12.7 | 11.43 ± 1.94 |
| mattcl-ts | input-mikofo | 11.7 ± 0.3 | 11.0 | 12.6 | 11.54 ± 1.95 |
| mikofo | input-mattcl | 13.7 ± 0.3 | 12.7 | 14.5 | 13.50 ± 2.28 |
| mikofo | input-chancalan | 13.7 ± 0.4 | 12.7 | 15.2 | 13.53 ± 2.29 |
| mikofo | input-kcen | 13.7 ± 0.4 | 12.7 | 14.9 | 13.56 ± 2.29 |
| mikofo | input-mikofo | 13.9 ± 0.3 | 12.9 | 14.7 | 13.74 ± 2.32 |
| mikofo | input-lanjian | 14.2 ± 4.8 | 12.9 | 74.6 | 13.99 ± 5.31 |
| mattcl-py | input-chancalan | 14.5 ± 0.6 | 13.3 | 17.6 | 14.36 ± 2.47 |
| pting | input-kcen | 14.5 ± 0.5 | 13.8 | 17.7 | 14.38 ± 2.44 |
| mattcl-py | input-mattcl | 14.5 ± 0.5 | 13.4 | 17.7 | 14.38 ± 2.45 |
| kcen | input-kcen | 14.6 ± 0.5 | 13.6 | 17.7 | 14.40 ± 2.46 |
| kcen | input-chancalan | 14.6 ± 0.7 | 13.6 | 17.4 | 14.43 ± 2.50 |
| mattcl-py | input-kcen | 14.6 ± 0.7 | 13.6 | 17.8 | 14.45 ± 2.51 |
| pting | input-chancalan | 14.6 ± 0.6 | 13.7 | 18.1 | 14.46 ± 2.49 |
| mattcl-py | input-mikofo | 14.6 ± 0.4 | 13.7 | 17.0 | 14.48 ± 2.45 |
| kcen | input-mattcl | 14.7 ± 0.7 | 13.6 | 18.2 | 14.49 ± 2.53 |
| kcen | input-mikofo | 14.7 ± 0.6 | 13.5 | 17.6 | 14.50 ± 2.49 |
| pting | input-mattcl | 14.7 ± 0.7 | 13.7 | 18.1 | 14.51 ± 2.51 |
| pting | input-lanjian | 14.7 ± 0.7 | 13.6 | 18.4 | 14.52 ± 2.52 |
| pting | input-mikofo | 14.7 ± 0.6 | 13.6 | 18.2 | 14.56 ± 2.50 |
| mattcl-py | input-lanjian | 14.8 ± 2.4 | 13.7 | 46.7 | 14.63 ± 3.38 |
| chancalan | input-chancalan | 14.9 ± 0.7 | 13.8 | 18.2 | 14.77 ± 2.55 |
| chancalan | input-mattcl | 15.0 ± 0.5 | 13.9 | 17.3 | 14.84 ± 2.52 |
| chancalan | input-kcen | 15.0 ± 0.6 | 14.0 | 18.4 | 14.85 ± 2.54 |
| chancalan | input-mikofo | 15.1 ± 0.5 | 14.1 | 18.2 | 14.95 ± 2.55 |
| kcen | input-lanjian | 15.2 ± 4.6 | 13.6 | 55.1 | 15.01 ± 5.18 |
| chancalan | input-lanjian | 15.4 ± 3.5 | 14.0 | 63.3 | 15.21 ± 4.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|