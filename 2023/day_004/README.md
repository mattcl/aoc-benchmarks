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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.1 | 1.06 ± 0.36 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.3 | 1.2 | 1.07 ± 0.34 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.2 | 1.09 ± 0.35 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 1.2 | 1.12 ± 0.35 |
| mattcl | input-mikofo | 1.0 ± 0.1 | 0.4 | 1.2 | 1.13 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.4 | 0.3 | 4.5 | 1.22 ± 0.55 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.35 ± 0.43 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.40 ± 0.43 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.8 | 1.41 ± 0.45 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.7 | 1.7 | 1.42 ± 0.43 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.6 | 1.8 | 1.45 ± 0.44 |
| mattcl-ts | input-chancalan | 11.3 ± 0.4 | 10.3 | 12.3 | 12.94 ± 3.56 |
| mattcl-ts | input-kcen | 11.3 ± 0.3 | 10.2 | 12.2 | 12.98 ± 3.57 |
| mattcl-ts | input-lanjian | 11.3 ± 0.4 | 10.2 | 12.2 | 12.99 ± 3.57 |
| mattcl-ts | input-mattcl | 11.4 ± 0.4 | 10.2 | 12.8 | 13.02 ± 3.58 |
| mattcl-ts | input-mikofo | 11.4 ± 0.3 | 10.3 | 12.3 | 13.10 ± 3.60 |
| mattcl-ts | input-pting | 11.4 ± 0.4 | 10.4 | 12.5 | 13.10 ± 3.60 |
| mikofo | input-chancalan | 13.9 ± 0.3 | 12.7 | 14.9 | 15.86 ± 4.35 |
| mikofo | input-kcen | 13.9 ± 0.4 | 13.0 | 14.9 | 15.95 ± 4.37 |
| mikofo | input-mattcl | 13.9 ± 0.3 | 12.9 | 14.8 | 15.96 ± 4.37 |
| mikofo | input-lanjian | 14.0 ± 0.3 | 13.2 | 14.7 | 15.98 ± 4.38 |
| mikofo | input-pting | 14.0 ± 0.4 | 13.0 | 15.2 | 16.06 ± 4.41 |
| mikofo | input-mikofo | 14.2 ± 0.3 | 13.4 | 15.3 | 16.20 ± 4.44 |
| mattcl-py | input-chancalan | 14.4 ± 0.6 | 13.5 | 17.4 | 16.50 ± 4.55 |
| kcen | input-chancalan | 14.4 ± 0.6 | 13.4 | 17.3 | 16.51 ± 4.56 |
| mattcl-py | input-lanjian | 14.5 ± 0.5 | 13.6 | 18.0 | 16.55 ± 4.56 |
| mattcl-py | input-kcen | 14.5 ± 0.6 | 13.5 | 17.1 | 16.57 ± 4.57 |
| kcen | input-kcen | 14.5 ± 0.6 | 13.5 | 17.7 | 16.57 ± 4.58 |
| kcen | input-lanjian | 14.5 ± 0.7 | 13.5 | 17.7 | 16.61 ± 4.60 |
| kcen | input-mattcl | 14.5 ± 0.6 | 13.5 | 18.4 | 16.61 ± 4.58 |
| pting | input-chancalan | 14.5 ± 0.5 | 13.6 | 17.8 | 16.61 ± 4.58 |
| pting | input-lanjian | 14.6 ± 0.6 | 13.7 | 17.6 | 16.71 ± 4.61 |
| mattcl-py | input-pting | 14.6 ± 0.5 | 13.7 | 17.7 | 16.71 ± 4.60 |
| mattcl-py | input-mattcl | 14.6 ± 0.6 | 13.6 | 17.6 | 16.72 ± 4.62 |
| pting | input-mattcl | 14.6 ± 0.7 | 13.5 | 18.0 | 16.76 ± 4.64 |
| kcen | input-pting | 14.6 ± 0.7 | 13.8 | 17.9 | 16.76 ± 4.64 |
| mattcl-py | input-mikofo | 14.7 ± 0.7 | 13.8 | 18.2 | 16.77 ± 4.64 |
| pting | input-mikofo | 14.7 ± 0.5 | 13.7 | 17.8 | 16.79 ± 4.62 |
| kcen | input-mikofo | 14.7 ± 0.6 | 13.8 | 18.2 | 16.80 ± 4.64 |
| pting | input-pting | 14.7 ± 0.6 | 13.7 | 17.6 | 16.86 ± 4.66 |
| chancalan | input-chancalan | 14.8 ± 0.7 | 13.6 | 17.7 | 16.92 ± 4.68 |
| pting | input-kcen | 14.9 ± 2.7 | 13.6 | 51.4 | 17.03 ± 5.60 |
| chancalan | input-lanjian | 15.0 ± 0.6 | 13.9 | 18.2 | 17.13 ± 4.72 |
| chancalan | input-mattcl | 15.0 ± 0.6 | 13.9 | 17.8 | 17.17 ± 4.74 |
| chancalan | input-pting | 15.1 ± 0.7 | 13.9 | 17.9 | 17.27 ± 4.78 |
| chancalan | input-mikofo | 15.2 ± 0.7 | 14.2 | 18.5 | 17.34 ± 4.80 |
| chancalan | input-kcen | 15.3 ± 4.5 | 13.9 | 78.3 | 17.47 ± 7.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|