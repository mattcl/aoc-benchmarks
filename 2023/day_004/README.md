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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 ± 0.30 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.2 | 1.00 ± 0.28 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.4 | 1.1 | 1.05 ± 0.26 |
| mattcl | input-mikofo | 1.0 ± 0.1 | 0.6 | 1.1 | 1.05 ± 0.26 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.24 ± 0.33 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.28 ± 0.32 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.7 | 1.7 | 1.29 ± 0.30 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.5 | 1.7 | 1.30 ± 0.33 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.9 | 1.32 ± 0.34 |
| mattcl-ts | input-chancalan | 11.6 ± 0.4 | 10.8 | 12.7 | 12.39 ± 2.67 |
| mattcl-ts | input-kcen | 11.7 ± 0.3 | 10.8 | 12.9 | 12.40 ± 2.67 |
| mattcl-ts | input-lanjian | 11.7 ± 0.4 | 10.6 | 12.7 | 12.44 ± 2.69 |
| mattcl-ts | input-mikofo | 11.7 ± 0.4 | 10.7 | 12.9 | 12.49 ± 2.70 |
| mattcl-ts | input-mattcl | 11.7 ± 0.3 | 10.9 | 12.8 | 12.49 ± 2.69 |
| mikofo | input-lanjian | 13.9 ± 0.3 | 12.8 | 15.2 | 14.74 ± 3.17 |
| mikofo | input-mattcl | 13.9 ± 0.3 | 13.0 | 14.7 | 14.74 ± 3.16 |
| mikofo | input-chancalan | 13.9 ± 0.3 | 12.7 | 14.8 | 14.74 ± 3.17 |
| mikofo | input-kcen | 13.9 ± 0.3 | 12.9 | 14.8 | 14.75 ± 3.17 |
| mikofo | input-mikofo | 14.0 ± 0.4 | 12.9 | 15.0 | 14.93 ± 3.21 |
| kcen | input-kcen | 14.4 ± 0.5 | 13.4 | 18.2 | 15.37 ± 3.33 |
| mattcl-py | input-chancalan | 14.5 ± 0.5 | 13.5 | 17.4 | 15.39 ± 3.34 |
| kcen | input-chancalan | 14.5 ± 0.6 | 13.4 | 18.2 | 15.40 ± 3.35 |
| kcen | input-lanjian | 14.5 ± 0.5 | 13.4 | 17.6 | 15.42 ± 3.34 |
| pting | input-kcen | 14.5 ± 0.6 | 13.4 | 17.6 | 15.45 ± 3.35 |
| mattcl-py | input-lanjian | 14.5 ± 0.6 | 13.6 | 17.4 | 15.45 ± 3.36 |
| pting | input-chancalan | 14.5 ± 0.5 | 13.4 | 17.3 | 15.47 ± 3.35 |
| mattcl-py | input-kcen | 14.5 ± 0.6 | 13.4 | 17.8 | 15.48 ± 3.37 |
| pting | input-mattcl | 14.6 ± 0.6 | 13.4 | 17.2 | 15.50 ± 3.38 |
| mattcl-py | input-mattcl | 14.6 ± 0.6 | 13.4 | 17.9 | 15.53 ± 3.38 |
| kcen | input-mikofo | 14.6 ± 0.6 | 13.6 | 17.7 | 15.55 ± 3.38 |
| pting | input-lanjian | 14.6 ± 0.7 | 13.4 | 18.1 | 15.58 ± 3.41 |
| mattcl-py | input-mikofo | 14.7 ± 0.6 | 13.5 | 17.5 | 15.59 ± 3.39 |
| pting | input-mikofo | 14.7 ± 0.5 | 13.7 | 16.9 | 15.60 ± 3.37 |
| kcen | input-mattcl | 14.8 ± 2.7 | 13.4 | 52.1 | 15.79 ± 4.45 |
| chancalan | input-chancalan | 14.9 ± 0.6 | 13.8 | 17.4 | 15.86 ± 3.44 |
| chancalan | input-mattcl | 14.9 ± 0.6 | 13.8 | 17.8 | 15.87 ± 3.44 |
| chancalan | input-kcen | 15.0 ± 0.6 | 14.2 | 18.2 | 15.96 ± 3.46 |
| chancalan | input-lanjian | 15.1 ± 0.7 | 13.8 | 18.3 | 16.03 ± 3.51 |
| chancalan | input-mikofo | 15.1 ± 0.6 | 14.0 | 18.4 | 16.08 ± 3.50 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|