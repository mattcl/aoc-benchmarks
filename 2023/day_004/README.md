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
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.4 | 1.02 ± 0.27 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.3 | 1.02 ± 0.29 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.2 | 1.03 ± 0.27 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.29 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.8 | 1.26 ± 0.33 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.4 | 1.8 | 1.28 ± 0.34 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.7 | 1.28 ± 0.32 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.4 | 1.7 | 1.29 ± 0.33 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.6 | 2.2 | 1.31 ± 0.35 |
| mattcl-ts | input-kcen | 11.7 ± 0.3 | 10.9 | 12.7 | 11.98 ± 2.60 |
| mattcl-ts | input-lanjian | 11.8 ± 0.3 | 11.0 | 12.8 | 12.05 ± 2.62 |
| mattcl-ts | input-mattcl | 11.8 ± 0.4 | 10.8 | 13.1 | 12.07 ± 2.63 |
| mattcl-ts | input-mikofo | 12.1 ± 2.1 | 10.9 | 41.7 | 12.29 ± 3.43 |
| mattcl-ts | input-chancalan | 12.2 ± 4.6 | 10.8 | 69.1 | 12.40 ± 5.36 |
| mikofo | input-kcen | 14.0 ± 0.3 | 13.2 | 15.1 | 14.23 ± 3.08 |
| mikofo | input-mattcl | 14.0 ± 0.4 | 13.0 | 15.2 | 14.27 ± 3.09 |
| mikofo | input-lanjian | 14.0 ± 0.4 | 13.0 | 15.1 | 14.31 ± 3.11 |
| mikofo | input-mikofo | 14.2 ± 0.4 | 13.3 | 15.2 | 14.51 ± 3.15 |
| mikofo | input-chancalan | 14.3 ± 4.5 | 13.0 | 77.0 | 14.55 ± 5.53 |
| mattcl-py | input-chancalan | 14.5 ± 0.5 | 13.5 | 17.4 | 14.74 ± 3.22 |
| kcen | input-chancalan | 14.5 ± 0.6 | 13.8 | 17.5 | 14.83 ± 3.25 |
| mattcl-py | input-mattcl | 14.5 ± 0.5 | 13.6 | 17.1 | 14.83 ± 3.24 |
| mattcl-py | input-kcen | 14.6 ± 0.7 | 13.6 | 18.2 | 14.84 ± 3.27 |
| pting | input-mattcl | 14.6 ± 0.5 | 13.5 | 17.7 | 14.85 ± 3.24 |
| kcen | input-kcen | 14.6 ± 0.7 | 13.7 | 17.8 | 14.85 ± 3.27 |
| kcen | input-lanjian | 14.6 ± 0.6 | 13.6 | 18.0 | 14.86 ± 3.26 |
| mattcl-py | input-lanjian | 14.6 ± 0.6 | 13.6 | 18.3 | 14.87 ± 3.27 |
| pting | input-kcen | 14.6 ± 0.5 | 13.5 | 17.0 | 14.87 ± 3.24 |
| pting | input-lanjian | 14.6 ± 0.5 | 13.5 | 17.4 | 14.88 ± 3.24 |
| kcen | input-mattcl | 14.6 ± 0.7 | 13.6 | 18.1 | 14.91 ± 3.28 |
| pting | input-chancalan | 14.6 ± 0.6 | 13.8 | 17.6 | 14.92 ± 3.28 |
| pting | input-mikofo | 14.7 ± 0.6 | 13.6 | 18.0 | 14.97 ± 3.29 |
| kcen | input-mikofo | 14.7 ± 0.7 | 13.6 | 18.3 | 15.00 ± 3.32 |
| chancalan | input-kcen | 15.0 ± 0.6 | 13.9 | 18.3 | 15.25 ± 3.34 |
| mattcl-py | input-mikofo | 15.0 ± 3.4 | 13.4 | 51.6 | 15.27 ± 4.76 |
| chancalan | input-lanjian | 15.0 ± 0.5 | 13.9 | 17.7 | 15.28 ± 3.33 |
| chancalan | input-mikofo | 15.0 ± 0.6 | 13.8 | 17.7 | 15.30 ± 3.35 |
| chancalan | input-chancalan | 15.0 ± 0.7 | 13.9 | 18.1 | 15.31 ± 3.38 |
| chancalan | input-mattcl | 15.0 ± 0.6 | 13.9 | 17.9 | 15.33 ± 3.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|