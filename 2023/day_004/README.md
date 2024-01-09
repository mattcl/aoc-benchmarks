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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.7 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.4 | 1.2 | 1.03 ± 0.28 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.5 | 1.03 ± 0.29 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.3 | 1.3 | 1.05 ± 0.27 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.6 | 1.06 ± 0.29 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.5 | 1.27 ± 0.32 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.5 | 1.7 | 1.27 ± 0.32 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.8 | 1.27 ± 0.33 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.7 | 1.28 ± 0.31 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.7 | 1.9 | 1.30 ± 0.34 |
| mattcl-ts | input-chancalan | 11.8 ± 0.4 | 10.9 | 12.9 | 12.36 ± 2.75 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 11.0 | 13.0 | 12.55 ± 2.79 |
| mattcl-ts | input-lanjian | 12.0 ± 0.4 | 10.7 | 13.0 | 12.60 ± 2.80 |
| mattcl-ts | input-kcen | 12.1 ± 1.0 | 11.0 | 25.5 | 12.63 ± 2.98 |
| mattcl-ts | input-mikofo | 12.1 ± 0.4 | 11.1 | 13.2 | 12.72 ± 2.82 |
| mikofo | input-chancalan | 14.1 ± 0.4 | 13.3 | 15.4 | 14.81 ± 3.28 |
| mikofo | input-mattcl | 14.2 ± 0.4 | 13.3 | 15.9 | 14.85 ± 3.29 |
| mikofo | input-lanjian | 14.2 ± 0.3 | 13.4 | 15.3 | 14.87 ± 3.29 |
| mikofo | input-mikofo | 14.4 ± 0.4 | 13.2 | 15.3 | 15.04 ± 3.33 |
| mikofo | input-kcen | 14.4 ± 3.2 | 13.2 | 59.3 | 15.04 ± 4.72 |
| pting | input-lanjian | 14.7 ± 0.4 | 13.8 | 16.2 | 15.43 ± 3.42 |
| kcen | input-mattcl | 14.7 ± 0.7 | 13.5 | 18.2 | 15.44 ± 3.46 |
| mattcl-py | input-mattcl | 14.8 ± 0.6 | 13.8 | 18.0 | 15.46 ± 3.47 |
| kcen | input-lanjian | 14.8 ± 0.5 | 13.8 | 17.7 | 15.47 ± 3.45 |
| mattcl-py | input-chancalan | 14.8 ± 0.6 | 13.6 | 17.6 | 15.47 ± 3.46 |
| pting | input-kcen | 14.8 ± 0.7 | 13.8 | 18.3 | 15.47 ± 3.47 |
| mattcl-py | input-kcen | 14.8 ± 0.5 | 13.9 | 18.0 | 15.47 ± 3.45 |
| pting | input-mattcl | 14.8 ± 0.6 | 14.0 | 17.6 | 15.51 ± 3.47 |
| kcen | input-mikofo | 14.8 ± 0.5 | 13.8 | 17.1 | 15.54 ± 3.45 |
| mattcl-py | input-lanjian | 14.8 ± 0.7 | 13.6 | 17.5 | 15.54 ± 3.49 |
| kcen | input-chancalan | 14.8 ± 0.7 | 13.7 | 18.1 | 15.55 ± 3.50 |
| mattcl-py | input-mikofo | 14.8 ± 0.6 | 13.9 | 17.9 | 15.55 ± 3.48 |
| kcen | input-kcen | 14.9 ± 0.7 | 13.8 | 18.1 | 15.61 ± 3.52 |
| pting | input-mikofo | 14.9 ± 0.5 | 13.9 | 17.8 | 15.63 ± 3.48 |
| chancalan | input-chancalan | 15.1 ± 0.6 | 13.8 | 17.7 | 15.79 ± 3.53 |
| pting | input-chancalan | 15.1 ± 3.5 | 13.8 | 63.5 | 15.84 ± 5.07 |
| chancalan | input-mattcl | 15.2 ± 0.7 | 13.8 | 18.6 | 15.88 ± 3.57 |
| chancalan | input-kcen | 15.2 ± 0.7 | 13.9 | 18.2 | 15.90 ± 3.57 |
| chancalan | input-lanjian | 15.2 ± 0.7 | 14.1 | 18.6 | 15.90 ± 3.57 |
| chancalan | input-mikofo | 15.3 ± 0.6 | 13.9 | 18.3 | 16.00 ± 3.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|