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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.30 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.4 | 1.3 | 1.04 ± 0.30 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.4 | 1.07 ± 0.28 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.27 ± 0.37 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.3 | 1.6 | 1.29 ± 0.33 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.4 | 1.8 | 1.31 ± 0.37 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.31 ± 0.35 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.8 | 1.34 ± 0.36 |
| mattcl-ts | input-chancalan | 11.6 ± 0.3 | 10.6 | 12.8 | 12.88 ± 2.88 |
| mattcl-ts | input-lanjian | 11.6 ± 0.4 | 10.7 | 12.5 | 12.90 ± 2.89 |
| mattcl-ts | input-mattcl | 11.6 ± 0.4 | 10.7 | 13.0 | 12.91 ± 2.90 |
| mattcl-ts | input-kcen | 11.6 ± 0.3 | 10.9 | 12.6 | 12.92 ± 2.89 |
| mattcl-ts | input-mikofo | 11.8 ± 0.4 | 10.8 | 12.6 | 13.10 ± 2.93 |
| mikofo | input-kcen | 13.9 ± 0.4 | 13.0 | 15.0 | 15.39 ± 3.44 |
| mikofo | input-chancalan | 13.9 ± 0.3 | 13.1 | 14.8 | 15.40 ± 3.44 |
| mikofo | input-mattcl | 13.9 ± 0.3 | 13.1 | 14.7 | 15.40 ± 3.44 |
| mikofo | input-lanjian | 13.9 ± 0.3 | 13.2 | 15.3 | 15.47 ± 3.45 |
| mikofo | input-mikofo | 14.1 ± 0.4 | 13.1 | 15.2 | 15.67 ± 3.50 |
| mattcl-py | input-chancalan | 14.4 ± 0.5 | 13.4 | 17.0 | 15.98 ± 3.59 |
| mattcl-py | input-mattcl | 14.4 ± 0.5 | 13.4 | 17.5 | 16.00 ± 3.60 |
| kcen | input-mattcl | 14.4 ± 0.6 | 13.4 | 17.5 | 16.02 ± 3.62 |
| pting | input-chancalan | 14.4 ± 0.6 | 13.4 | 17.3 | 16.02 ± 3.62 |
| kcen | input-kcen | 14.4 ± 0.6 | 13.3 | 17.5 | 16.02 ± 3.62 |
| kcen | input-chancalan | 14.5 ± 0.7 | 13.4 | 18.3 | 16.06 ± 3.64 |
| mattcl-py | input-kcen | 14.5 ± 0.6 | 13.5 | 17.3 | 16.07 ± 3.62 |
| mattcl-py | input-lanjian | 14.5 ± 0.7 | 13.4 | 17.8 | 16.12 ± 3.65 |
| kcen | input-lanjian | 14.5 ± 0.8 | 13.4 | 18.1 | 16.13 ± 3.68 |
| pting | input-kcen | 14.5 ± 0.6 | 13.5 | 17.9 | 16.15 ± 3.65 |
| kcen | input-mikofo | 14.6 ± 0.6 | 13.7 | 17.5 | 16.17 ± 3.65 |
| pting | input-lanjian | 14.6 ± 0.7 | 13.5 | 17.5 | 16.20 ± 3.68 |
| pting | input-mikofo | 14.6 ± 0.7 | 13.6 | 17.9 | 16.23 ± 3.69 |
| mattcl-py | input-mikofo | 14.6 ± 0.8 | 13.4 | 17.8 | 16.25 ± 3.71 |
| chancalan | input-chancalan | 14.8 ± 0.5 | 14.0 | 18.2 | 16.43 ± 3.70 |
| chancalan | input-lanjian | 14.9 ± 0.5 | 14.1 | 17.3 | 16.53 ± 3.70 |
| chancalan | input-kcen | 14.9 ± 0.6 | 13.7 | 17.2 | 16.56 ± 3.73 |
| chancalan | input-mattcl | 15.0 ± 0.7 | 14.1 | 18.1 | 16.64 ± 3.78 |
| pting | input-mattcl | 15.1 ± 4.7 | 13.4 | 58.6 | 16.76 ± 6.44 |
| chancalan | input-mikofo | 15.1 ± 0.7 | 13.9 | 18.5 | 16.78 ± 3.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|