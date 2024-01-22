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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.3 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 ± 0.24 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 1.6 | 1.02 ± 0.23 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.22 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.5 | 1.21 ± 0.26 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.4 | 1.6 | 1.23 ± 0.25 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.7 | 1.23 ± 0.26 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.7 | 1.8 | 1.23 ± 0.25 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.8 | 2.0 | 1.24 ± 0.25 |
| mattcl-ts | input-chancalan | 11.3 ± 0.4 | 10.2 | 12.0 | 10.65 ± 1.80 |
| mattcl-ts | input-lanjian | 11.3 ± 0.4 | 10.3 | 12.3 | 10.67 ± 1.81 |
| mattcl-ts | input-kcen | 11.3 ± 0.4 | 10.4 | 12.3 | 10.69 ± 1.81 |
| mattcl-ts | input-mattcl | 11.3 ± 0.4 | 10.3 | 12.7 | 10.70 ± 1.81 |
| mattcl-ts | input-mikofo | 11.4 ± 0.4 | 10.3 | 12.6 | 10.79 ± 1.83 |
| mikofo | input-chancalan | 13.4 ± 0.4 | 12.0 | 14.8 | 12.65 ± 2.14 |
| mikofo | input-lanjian | 13.5 ± 0.4 | 12.4 | 14.5 | 12.70 ± 2.15 |
| mikofo | input-kcen | 13.5 ± 0.4 | 12.4 | 14.5 | 12.71 ± 2.15 |
| mikofo | input-mattcl | 13.5 ± 0.4 | 12.4 | 14.3 | 12.73 ± 2.15 |
| mikofo | input-mikofo | 13.6 ± 0.4 | 12.5 | 15.0 | 12.84 ± 2.17 |
| kcen | input-lanjian | 14.7 ± 0.6 | 13.7 | 18.3 | 13.93 ± 2.38 |
| kcen | input-mikofo | 14.8 ± 0.5 | 13.7 | 18.4 | 13.96 ± 2.38 |
| mattcl-py | input-lanjian | 14.8 ± 0.7 | 13.9 | 18.0 | 13.99 ± 2.41 |
| mattcl-py | input-chancalan | 14.8 ± 0.5 | 14.0 | 17.5 | 13.99 ± 2.38 |
| pting | input-chancalan | 14.8 ± 0.5 | 14.1 | 17.8 | 13.99 ± 2.38 |
| pting | input-mattcl | 14.8 ± 0.6 | 13.8 | 18.3 | 14.00 ± 2.41 |
| kcen | input-kcen | 14.9 ± 0.8 | 13.7 | 18.6 | 14.05 ± 2.46 |
| kcen | input-mattcl | 14.9 ± 0.7 | 13.7 | 18.3 | 14.05 ± 2.42 |
| mattcl-py | input-mattcl | 14.9 ± 0.7 | 13.8 | 18.1 | 14.05 ± 2.43 |
| kcen | input-chancalan | 14.9 ± 0.8 | 13.5 | 18.3 | 14.07 ± 2.45 |
| pting | input-kcen | 14.9 ± 0.7 | 13.7 | 17.7 | 14.08 ± 2.43 |
| mattcl-py | input-kcen | 14.9 ± 0.7 | 13.8 | 17.8 | 14.08 ± 2.42 |
| pting | input-lanjian | 14.9 ± 0.7 | 13.8 | 17.9 | 14.09 ± 2.45 |
| mattcl-py | input-mikofo | 14.9 ± 0.6 | 14.0 | 17.9 | 14.10 ± 2.42 |
| pting | input-mikofo | 15.0 ± 0.7 | 13.9 | 18.1 | 14.18 ± 2.44 |
| chancalan | input-lanjian | 15.1 ± 0.5 | 14.0 | 18.1 | 14.29 ± 2.43 |
| chancalan | input-mattcl | 15.2 ± 0.6 | 14.0 | 18.1 | 14.35 ± 2.46 |
| chancalan | input-kcen | 15.2 ± 0.7 | 14.2 | 18.1 | 14.39 ± 2.47 |
| chancalan | input-chancalan | 15.3 ± 0.7 | 13.8 | 18.5 | 14.40 ± 2.49 |
| chancalan | input-mikofo | 15.3 ± 0.6 | 14.0 | 18.6 | 14.43 ± 2.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|