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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.5 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.7 | 1.00 ± 0.25 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.26 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.7 | 1.02 ± 0.24 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.4 | 1.02 ± 0.24 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.21 ± 0.30 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.26 ± 0.26 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.27 ± 0.26 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.0 | 1.31 ± 0.30 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.6 | 2.1 | 1.35 ± 0.33 |
| mattcl-ts | input-chancalan | 11.4 ± 0.4 | 10.6 | 12.8 | 11.68 ± 1.99 |
| mattcl-ts | input-lanjian | 11.5 ± 0.3 | 10.3 | 12.3 | 11.70 ± 1.99 |
| mattcl-ts | input-kcen | 11.5 ± 0.4 | 10.4 | 12.6 | 11.71 ± 1.99 |
| mattcl-ts | input-mattcl | 11.5 ± 0.4 | 10.4 | 12.6 | 11.73 ± 1.99 |
| mattcl-ts | input-mikofo | 11.5 ± 0.3 | 10.5 | 12.5 | 11.76 ± 2.00 |
| mikofo | input-chancalan | 13.7 ± 0.4 | 12.6 | 15.4 | 13.96 ± 2.36 |
| mikofo | input-kcen | 13.7 ± 0.4 | 12.6 | 14.5 | 14.00 ± 2.37 |
| mikofo | input-mattcl | 13.7 ± 0.4 | 12.4 | 14.7 | 14.02 ± 2.37 |
| mikofo | input-lanjian | 13.8 ± 0.4 | 12.7 | 14.8 | 14.03 ± 2.37 |
| mikofo | input-mikofo | 13.9 ± 0.4 | 13.1 | 14.9 | 14.18 ± 2.40 |
| kcen | input-chancalan | 14.6 ± 0.5 | 13.3 | 17.6 | 14.91 ± 2.55 |
| pting | input-kcen | 14.6 ± 0.4 | 13.5 | 17.3 | 14.93 ± 2.53 |
| kcen | input-kcen | 14.7 ± 0.6 | 13.8 | 18.1 | 14.95 ± 2.57 |
| mattcl-py | input-kcen | 14.7 ± 0.5 | 13.5 | 17.4 | 14.95 ± 2.54 |
| kcen | input-mattcl | 14.7 ± 0.6 | 13.5 | 18.3 | 15.00 ± 2.59 |
| pting | input-mikofo | 14.7 ± 0.5 | 13.7 | 17.3 | 15.00 ± 2.56 |
| pting | input-mattcl | 14.7 ± 0.6 | 13.5 | 17.6 | 15.02 ± 2.58 |
| kcen | input-lanjian | 14.7 ± 0.6 | 13.4 | 17.5 | 15.03 ± 2.58 |
| pting | input-lanjian | 14.7 ± 0.6 | 13.4 | 17.8 | 15.04 ± 2.59 |
| mattcl-py | input-lanjian | 14.8 ± 0.6 | 13.9 | 18.5 | 15.05 ± 2.60 |
| mattcl-py | input-mattcl | 14.8 ± 0.6 | 13.5 | 17.6 | 15.06 ± 2.59 |
| mattcl-py | input-chancalan | 14.8 ± 0.8 | 13.7 | 18.2 | 15.06 ± 2.65 |
| pting | input-chancalan | 14.8 ± 0.7 | 13.5 | 18.0 | 15.06 ± 2.61 |
| mattcl-py | input-mikofo | 14.8 ± 0.6 | 13.5 | 17.9 | 15.09 ± 2.61 |
| kcen | input-mikofo | 14.8 ± 0.6 | 13.6 | 18.1 | 15.14 ± 2.60 |
| chancalan | input-chancalan | 15.0 ± 0.5 | 13.8 | 16.9 | 15.32 ± 2.61 |
| chancalan | input-lanjian | 15.0 ± 0.6 | 14.0 | 18.2 | 15.34 ± 2.63 |
| chancalan | input-mattcl | 15.1 ± 0.5 | 14.2 | 18.4 | 15.38 ± 2.62 |
| chancalan | input-mikofo | 15.1 ± 0.6 | 14.1 | 18.2 | 15.43 ± 2.66 |
| chancalan | input-kcen | 15.1 ± 0.7 | 14.0 | 18.4 | 15.43 ± 2.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|