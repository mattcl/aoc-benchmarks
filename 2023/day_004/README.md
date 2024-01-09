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
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.3 | 1.1 | 1.00 ± 0.26 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.28 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.01 ± 0.28 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.4 | 1.6 | 1.02 ± 0.26 |
| lanjian | input-chancalan | 1.0 ± 0.3 | 0.3 | 1.6 | 1.06 ± 0.39 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.5 | 1.21 ± 0.33 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.5 | 1.5 | 1.23 ± 0.30 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.4 | 1.6 | 1.26 ± 0.30 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.3 | 1.8 | 1.30 ± 0.32 |
| mattcl-ts | input-mattcl | 11.9 ± 0.4 | 10.7 | 12.9 | 12.82 ± 2.70 |
| mattcl-ts | input-lanjian | 11.9 ± 0.3 | 11.1 | 12.9 | 12.85 ± 2.70 |
| mattcl-ts | input-chancalan | 11.9 ± 0.4 | 10.9 | 13.7 | 12.85 ± 2.71 |
| mattcl-ts | input-kcen | 12.0 ± 0.4 | 11.1 | 13.3 | 12.93 ± 2.71 |
| mattcl-ts | input-mikofo | 12.1 ± 0.4 | 10.9 | 13.1 | 13.02 ± 2.74 |
| mikofo | input-chancalan | 14.1 ± 0.4 | 13.2 | 15.5 | 15.17 ± 3.18 |
| mikofo | input-kcen | 14.2 ± 0.4 | 13.2 | 15.3 | 15.25 ± 3.20 |
| mikofo | input-lanjian | 14.2 ± 0.4 | 13.2 | 15.4 | 15.27 ± 3.20 |
| mikofo | input-mattcl | 14.2 ± 0.4 | 13.4 | 15.2 | 15.29 ± 3.21 |
| mikofo | input-mikofo | 14.4 ± 0.4 | 13.2 | 15.3 | 15.46 ± 3.24 |
| mattcl-py | input-chancalan | 14.7 ± 0.6 | 13.8 | 17.2 | 15.81 ± 3.34 |
| pting | input-chancalan | 14.7 ± 0.6 | 13.5 | 18.4 | 15.83 ± 3.36 |
| kcen | input-kcen | 14.7 ± 0.6 | 13.6 | 17.5 | 15.84 ± 3.35 |
| pting | input-kcen | 14.7 ± 0.4 | 13.7 | 16.9 | 15.85 ± 3.33 |
| mattcl-py | input-mattcl | 14.7 ± 0.6 | 13.7 | 17.9 | 15.86 ± 3.36 |
| mattcl-py | input-kcen | 14.8 ± 0.5 | 13.8 | 17.4 | 15.88 ± 3.35 |
| mattcl-py | input-lanjian | 14.8 ± 0.7 | 13.6 | 17.6 | 15.95 ± 3.40 |
| kcen | input-chancalan | 14.8 ± 2.6 | 13.5 | 50.2 | 15.97 ± 4.35 |
| pting | input-mattcl | 14.8 ± 0.6 | 13.6 | 17.7 | 15.98 ± 3.39 |
| pting | input-mikofo | 14.8 ± 0.5 | 13.8 | 17.8 | 15.98 ± 3.36 |
| kcen | input-mattcl | 14.9 ± 1.2 | 13.4 | 28.3 | 15.99 ± 3.57 |
| mattcl-py | input-mikofo | 14.9 ± 0.7 | 13.5 | 18.2 | 16.00 ± 3.41 |
| pting | input-lanjian | 14.9 ± 0.6 | 13.8 | 17.4 | 16.00 ± 3.39 |
| chancalan | input-chancalan | 15.0 ± 0.6 | 14.0 | 18.5 | 16.14 ± 3.41 |
| chancalan | input-lanjian | 15.1 ± 0.6 | 13.7 | 18.7 | 16.21 ± 3.43 |
| chancalan | input-kcen | 15.1 ± 0.6 | 14.0 | 18.2 | 16.23 ± 3.43 |
| kcen | input-mikofo | 15.1 ± 2.1 | 13.8 | 43.1 | 16.23 ± 4.07 |
| chancalan | input-mikofo | 15.1 ± 0.6 | 13.9 | 18.4 | 16.29 ± 3.45 |
| kcen | input-lanjian | 15.3 ± 4.1 | 13.9 | 61.0 | 16.49 ± 5.58 |
| chancalan | input-mattcl | 15.5 ± 4.4 | 13.6 | 60.9 | 16.71 ± 5.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|