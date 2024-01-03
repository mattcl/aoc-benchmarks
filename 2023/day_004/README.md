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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.4 | 1.04 ± 0.26 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.7 | 1.06 ± 0.27 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.4 | 1.7 | 1.06 ± 0.25 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.6 | 1.7 | 1.07 ± 0.24 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.25 ± 0.30 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 2.1 | 1.27 ± 0.32 |
| lanjian | input-mikofo | 1.2 ± 0.1 | 0.6 | 1.5 | 1.27 ± 0.28 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.7 | 1.7 | 1.28 ± 0.27 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.7 | 1.7 | 1.28 ± 0.27 |
| mattcl-ts | input-chancalan | 11.9 ± 0.3 | 10.8 | 12.8 | 12.20 ± 2.36 |
| mattcl-ts | input-lanjian | 11.9 ± 0.3 | 11.0 | 12.6 | 12.21 ± 2.36 |
| mattcl-ts | input-mattcl | 11.9 ± 0.4 | 10.8 | 12.9 | 12.22 ± 2.37 |
| mattcl-ts | input-kcen | 12.0 ± 0.4 | 11.0 | 13.0 | 12.25 ± 2.37 |
| mattcl-ts | input-mikofo | 12.0 ± 0.3 | 11.1 | 13.0 | 12.33 ± 2.38 |
| mikofo | input-chancalan | 14.1 ± 0.4 | 13.3 | 15.2 | 14.45 ± 2.79 |
| mikofo | input-kcen | 14.1 ± 0.4 | 13.3 | 15.1 | 14.47 ± 2.79 |
| mikofo | input-lanjian | 14.1 ± 0.4 | 13.0 | 15.1 | 14.48 ± 2.79 |
| mikofo | input-mattcl | 14.3 ± 1.9 | 13.1 | 40.1 | 14.69 ± 3.40 |
| mikofo | input-mikofo | 14.4 ± 0.4 | 13.4 | 16.1 | 14.78 ± 2.85 |
| kcen | input-mattcl | 14.7 ± 0.6 | 13.8 | 17.8 | 15.07 ± 2.94 |
| kcen | input-chancalan | 14.7 ± 0.6 | 13.8 | 17.5 | 15.09 ± 2.95 |
| pting | input-lanjian | 14.8 ± 0.5 | 13.6 | 17.9 | 15.13 ± 2.94 |
| mattcl-py | input-lanjian | 14.8 ± 0.5 | 14.0 | 17.1 | 15.14 ± 2.93 |
| mattcl-py | input-chancalan | 14.8 ± 0.7 | 13.8 | 18.1 | 15.14 ± 2.97 |
| pting | input-kcen | 14.8 ± 0.6 | 13.8 | 17.6 | 15.18 ± 2.97 |
| pting | input-chancalan | 14.8 ± 0.5 | 13.7 | 17.0 | 15.19 ± 2.94 |
| mattcl-py | input-kcen | 14.8 ± 0.8 | 13.6 | 18.0 | 15.20 ± 3.00 |
| kcen | input-kcen | 14.8 ± 0.6 | 14.0 | 18.1 | 15.20 ± 2.98 |
| mattcl-py | input-mattcl | 14.8 ± 0.6 | 13.8 | 18.1 | 15.22 ± 2.98 |
| pting | input-mattcl | 14.9 ± 0.6 | 13.9 | 18.0 | 15.25 ± 2.98 |
| mattcl-py | input-mikofo | 14.9 ± 0.6 | 13.8 | 17.6 | 15.26 ± 2.97 |
| kcen | input-mikofo | 14.9 ± 0.7 | 13.8 | 18.2 | 15.31 ± 3.02 |
| pting | input-mikofo | 15.0 ± 0.7 | 13.9 | 18.3 | 15.35 ± 3.02 |
| kcen | input-lanjian | 15.0 ± 2.2 | 13.7 | 44.1 | 15.42 ± 3.70 |
| chancalan | input-kcen | 15.1 ± 0.6 | 13.8 | 18.5 | 15.46 ± 3.01 |
| chancalan | input-chancalan | 15.1 ± 0.6 | 14.0 | 18.3 | 15.48 ± 3.03 |
| chancalan | input-lanjian | 15.2 ± 0.7 | 13.8 | 18.4 | 15.56 ± 3.05 |
| chancalan | input-mikofo | 15.2 ± 0.6 | 13.9 | 18.5 | 15.60 ± 3.04 |
| chancalan | input-mattcl | 15.6 ± 4.0 | 13.8 | 53.7 | 15.94 ± 5.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|