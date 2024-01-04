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
| mattcl | input-mikofo | 0.6 ± 0.3 | 0.2 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.7 | 1.67 ± 0.91 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.4 | 1.5 | 1.73 ± 0.90 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.6 | 1.4 | 1.73 ± 0.90 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.3 | 1.4 | 1.74 ± 0.91 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.99 ± 1.07 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 2.05 ± 1.08 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.7 | 1.6 | 2.07 ± 1.06 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.7 | 1.7 | 2.12 ± 1.09 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.4 | 2.0 | 2.16 ± 1.14 |
| mattcl-ts | input-mattcl | 11.8 ± 0.4 | 10.9 | 12.9 | 20.28 ± 10.23 |
| mattcl-ts | input-lanjian | 11.9 ± 0.4 | 10.9 | 12.8 | 20.32 ± 10.25 |
| mattcl-ts | input-kcen | 11.9 ± 0.4 | 10.7 | 13.0 | 20.35 ± 10.27 |
| mattcl-ts | input-mikofo | 12.1 ± 0.4 | 11.1 | 13.1 | 20.74 ± 10.45 |
| mattcl-ts | input-chancalan | 13.2 ± 7.5 | 11.0 | 66.5 | 22.54 ± 17.14 |
| mikofo | input-kcen | 14.1 ± 0.4 | 13.2 | 15.0 | 24.14 ± 12.17 |
| mikofo | input-lanjian | 14.1 ± 0.4 | 13.3 | 15.8 | 24.20 ± 12.20 |
| mikofo | input-mattcl | 14.1 ± 0.4 | 13.5 | 15.1 | 24.22 ± 12.20 |
| mikofo | input-chancalan | 14.3 ± 2.6 | 13.2 | 50.3 | 24.48 ± 13.09 |
| kcen | input-chancalan | 14.6 ± 0.6 | 13.5 | 18.2 | 25.04 ± 12.65 |
| kcen | input-kcen | 14.7 ± 0.4 | 13.9 | 17.4 | 25.10 ± 12.66 |
| mattcl-py | input-mattcl | 14.7 ± 0.5 | 13.7 | 17.5 | 25.13 ± 12.68 |
| pting | input-kcen | 14.7 ± 0.5 | 13.4 | 17.0 | 25.13 ± 12.68 |
| mattcl-py | input-chancalan | 14.7 ± 0.8 | 13.5 | 18.3 | 25.15 ± 12.73 |
| pting | input-mattcl | 14.7 ± 0.6 | 13.5 | 17.7 | 25.26 ± 12.75 |
| kcen | input-lanjian | 14.8 ± 0.6 | 13.7 | 17.8 | 25.29 ± 12.77 |
| kcen | input-mattcl | 14.8 ± 0.6 | 13.4 | 17.6 | 25.32 ± 12.79 |
| mattcl-py | input-lanjian | 14.8 ± 0.6 | 13.8 | 18.2 | 25.34 ± 12.80 |
| pting | input-lanjian | 14.8 ± 0.7 | 13.7 | 18.0 | 25.42 ± 12.84 |
| mattcl-py | input-kcen | 14.9 ± 0.8 | 13.4 | 19.6 | 25.47 ± 12.88 |
| kcen | input-mikofo | 14.9 ± 0.6 | 13.9 | 17.5 | 25.47 ± 12.86 |
| pting | input-mikofo | 14.9 ± 0.6 | 14.0 | 18.0 | 25.54 ± 12.89 |
| chancalan | input-mattcl | 15.1 ± 0.5 | 14.1 | 18.3 | 25.82 ± 13.02 |
| chancalan | input-chancalan | 15.1 ± 0.6 | 14.1 | 18.1 | 25.85 ± 13.06 |
| chancalan | input-kcen | 15.1 ± 0.6 | 14.1 | 18.0 | 25.88 ± 13.06 |
| mikofo | input-mikofo | 15.1 ± 5.5 | 13.4 | 61.8 | 25.91 ± 16.10 |
| chancalan | input-lanjian | 15.1 ± 0.7 | 14.0 | 18.1 | 25.91 ± 13.09 |
| chancalan | input-mikofo | 15.2 ± 0.6 | 14.0 | 17.8 | 25.95 ± 13.10 |
| mattcl-py | input-mikofo | 15.4 ± 5.4 | 13.4 | 77.8 | 26.36 ± 16.17 |
| pting | input-chancalan | 15.4 ± 4.6 | 13.8 | 54.4 | 26.42 ± 15.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|