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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.28 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.25 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.8 | 1.03 ± 0.25 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.8 | 1.05 ± 0.25 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.22 ± 0.29 |
| mattcl | input-lanjian | 1.3 ± 3.8 | 0.3 | 55.2 | 1.24 ± 3.75 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.4 | 1.7 | 1.25 ± 0.29 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.7 | 1.8 | 1.26 ± 0.28 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.1 | 1.27 ± 0.30 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 2.0 | 1.27 ± 0.28 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.6 | 2.1 | 1.34 ± 0.33 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 10.8 | 13.0 | 11.64 ± 2.20 |
| mattcl-ts | input-chancalan | 12.0 ± 0.4 | 11.1 | 12.9 | 11.67 ± 2.20 |
| mattcl-ts | input-kcen | 12.0 ± 0.4 | 11.1 | 12.9 | 11.68 ± 2.20 |
| mattcl-ts | input-lanjian | 12.0 ± 0.4 | 11.0 | 12.8 | 11.72 ± 2.21 |
| mattcl-ts | input-mikofo | 12.1 ± 0.4 | 11.1 | 12.9 | 11.80 ± 2.23 |
| mattcl-ts | input-pting | 12.2 ± 0.4 | 11.2 | 13.4 | 11.83 ± 2.23 |
| mikofo | input-chancalan | 14.2 ± 0.4 | 13.1 | 15.6 | 13.82 ± 2.60 |
| mikofo | input-lanjian | 14.3 ± 0.3 | 13.5 | 15.2 | 13.87 ± 2.60 |
| mikofo | input-kcen | 14.3 ± 0.4 | 13.2 | 15.9 | 13.90 ± 2.62 |
| mikofo | input-mattcl | 14.3 ± 0.4 | 13.4 | 16.0 | 13.91 ± 2.62 |
| mikofo | input-pting | 14.4 ± 0.4 | 13.4 | 16.2 | 14.03 ± 2.64 |
| mikofo | input-mikofo | 14.5 ± 0.4 | 13.5 | 16.0 | 14.10 ± 2.65 |
| mattcl-py | input-lanjian | 14.8 ± 0.4 | 13.6 | 16.7 | 14.41 ± 2.71 |
| pting | input-mattcl | 14.8 ± 0.4 | 13.6 | 16.8 | 14.42 ± 2.71 |
| kcen | input-pting | 14.8 ± 0.4 | 14.0 | 17.7 | 14.44 ± 2.72 |
| kcen | input-chancalan | 14.9 ± 0.6 | 13.7 | 17.6 | 14.46 ± 2.76 |
| mattcl-py | input-chancalan | 14.9 ± 0.7 | 13.8 | 17.7 | 14.47 ± 2.77 |
| pting | input-chancalan | 14.9 ± 0.6 | 13.5 | 17.7 | 14.48 ± 2.76 |
| pting | input-kcen | 14.9 ± 0.7 | 13.6 | 18.3 | 14.51 ± 2.78 |
| kcen | input-mattcl | 14.9 ± 0.7 | 13.8 | 18.8 | 14.51 ± 2.79 |
| mattcl-py | input-kcen | 14.9 ± 0.5 | 13.9 | 17.7 | 14.52 ± 2.75 |
| mattcl-py | input-mattcl | 14.9 ± 0.6 | 13.6 | 18.1 | 14.52 ± 2.77 |
| pting | input-lanjian | 14.9 ± 0.5 | 14.0 | 17.7 | 14.54 ± 2.74 |
| kcen | input-lanjian | 15.0 ± 2.2 | 13.7 | 44.0 | 14.55 ± 3.43 |
| kcen | input-mikofo | 15.0 ± 0.7 | 13.8 | 18.6 | 14.55 ± 2.78 |
| mattcl-py | input-pting | 15.0 ± 0.7 | 13.9 | 18.2 | 14.56 ± 2.79 |
| pting | input-pting | 15.0 ± 0.6 | 13.8 | 18.2 | 14.57 ± 2.78 |
| pting | input-mikofo | 15.0 ± 0.4 | 13.8 | 17.8 | 14.57 ± 2.75 |
| mattcl-py | input-mikofo | 15.0 ± 0.8 | 13.9 | 18.4 | 14.59 ± 2.82 |
| kcen | input-kcen | 15.0 ± 0.7 | 13.9 | 18.4 | 14.60 ± 2.81 |
| chancalan | input-kcen | 15.1 ± 0.4 | 14.2 | 18.3 | 14.69 ± 2.77 |
| chancalan | input-chancalan | 15.2 ± 0.6 | 14.1 | 18.4 | 14.75 ± 2.81 |
| chancalan | input-pting | 15.2 ± 0.6 | 13.9 | 17.9 | 14.80 ± 2.81 |
| chancalan | input-mattcl | 15.2 ± 0.6 | 14.2 | 18.4 | 14.84 ± 2.81 |
| chancalan | input-mikofo | 15.3 ± 0.6 | 14.1 | 18.3 | 14.85 ± 2.83 |
| chancalan | input-lanjian | 15.5 ± 3.5 | 13.8 | 53.6 | 15.13 ± 4.40 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|