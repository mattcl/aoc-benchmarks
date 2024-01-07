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
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.29 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.29 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.3 | 1.3 | 1.04 ± 0.27 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.2 | 1.07 ± 0.26 |
| lanjian | input-mikofo | 1.2 ± 1.9 | 0.3 | 26.8 | 1.25 ± 1.97 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.25 ± 0.35 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.7 | 1.8 | 1.30 ± 0.33 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.6 | 1.7 | 1.31 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.7 | 1.8 | 1.32 ± 0.32 |
| mattcl-ts | input-chancalan | 11.6 ± 0.3 | 10.8 | 12.7 | 12.25 ± 2.69 |
| mattcl-ts | input-lanjian | 11.7 ± 0.4 | 10.9 | 12.9 | 12.37 ± 2.71 |
| mattcl-ts | input-kcen | 11.8 ± 0.4 | 11.1 | 13.0 | 12.44 ± 2.73 |
| mattcl-ts | input-mattcl | 11.8 ± 0.4 | 11.1 | 12.8 | 12.46 ± 2.73 |
| mattcl-ts | input-mikofo | 11.9 ± 0.3 | 11.0 | 12.6 | 12.56 ± 2.75 |
| mikofo | input-chancalan | 13.9 ± 0.4 | 13.0 | 14.9 | 14.73 ± 3.22 |
| mikofo | input-lanjian | 14.0 ± 0.3 | 13.2 | 15.1 | 14.74 ± 3.22 |
| mikofo | input-mattcl | 14.0 ± 0.4 | 12.9 | 15.1 | 14.74 ± 3.23 |
| mikofo | input-kcen | 14.0 ± 0.3 | 13.1 | 15.0 | 14.82 ± 3.24 |
| mikofo | input-mikofo | 14.2 ± 0.4 | 13.1 | 15.0 | 15.01 ± 3.28 |
| kcen | input-chancalan | 14.5 ± 0.5 | 13.6 | 17.9 | 15.29 ± 3.36 |
| mattcl-py | input-lanjian | 14.5 ± 0.4 | 13.4 | 17.0 | 15.32 ± 3.36 |
| mattcl-py | input-mattcl | 14.5 ± 0.6 | 13.7 | 18.0 | 15.35 ± 3.39 |
| mattcl-py | input-chancalan | 14.5 ± 0.5 | 13.5 | 17.3 | 15.35 ± 3.38 |
| kcen | input-kcen | 14.6 ± 0.6 | 13.7 | 17.5 | 15.37 ± 3.39 |
| mattcl-py | input-kcen | 14.6 ± 0.6 | 13.6 | 17.6 | 15.38 ± 3.41 |
| pting | input-chancalan | 14.6 ± 0.5 | 13.5 | 17.6 | 15.39 ± 3.39 |
| pting | input-lanjian | 14.6 ± 0.6 | 13.5 | 17.2 | 15.40 ± 3.40 |
| kcen | input-mattcl | 14.6 ± 0.7 | 13.6 | 18.3 | 15.40 ± 3.42 |
| kcen | input-lanjian | 14.6 ± 0.7 | 13.6 | 17.7 | 15.41 ± 3.43 |
| pting | input-kcen | 14.7 ± 0.8 | 13.8 | 18.4 | 15.48 ± 3.46 |
| pting | input-mattcl | 14.7 ± 2.2 | 13.6 | 44.3 | 15.50 ± 4.09 |
| mattcl-py | input-mikofo | 14.7 ± 0.8 | 13.5 | 18.5 | 15.51 ± 3.47 |
| kcen | input-mikofo | 14.7 ± 0.8 | 13.6 | 18.1 | 15.57 ± 3.48 |
| pting | input-mikofo | 14.8 ± 0.7 | 13.5 | 18.3 | 15.58 ± 3.47 |
| chancalan | input-lanjian | 15.0 ± 0.5 | 13.8 | 17.6 | 15.82 ± 3.48 |
| chancalan | input-kcen | 15.0 ± 0.6 | 13.9 | 17.9 | 15.85 ± 3.51 |
| chancalan | input-chancalan | 15.2 ± 1.8 | 13.7 | 38.5 | 16.00 ± 3.98 |
| chancalan | input-mattcl | 15.3 ± 3.4 | 13.9 | 61.9 | 16.13 ± 5.01 |
| chancalan | input-mikofo | 15.3 ± 3.5 | 14.1 | 63.6 | 16.20 ± 5.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|