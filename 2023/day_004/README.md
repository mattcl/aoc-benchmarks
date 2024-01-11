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
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.25 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.5 | 1.04 ± 0.24 |
| mattcl | input-mikofo | 1.1 ± 0.1 | 0.5 | 1.6 | 1.08 ± 0.25 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.22 ± 0.30 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.8 | 1.23 ± 0.29 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.6 | 1.5 | 1.25 ± 0.28 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.7 | 1.7 | 1.25 ± 0.28 |
| lanjian | input-mikofo | 1.3 ± 0.2 | 0.5 | 1.7 | 1.27 ± 0.29 |
| mattcl-ts | input-kcen | 12.0 ± 0.4 | 10.8 | 13.2 | 12.03 ± 2.29 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 11.0 | 13.1 | 12.03 ± 2.29 |
| mattcl-ts | input-lanjian | 12.0 ± 0.3 | 11.2 | 13.0 | 12.04 ± 2.28 |
| mattcl-ts | input-chancalan | 12.0 ± 0.4 | 11.0 | 13.2 | 12.05 ± 2.29 |
| mattcl-ts | input-mikofo | 12.5 ± 3.9 | 11.3 | 67.7 | 12.52 ± 4.60 |
| mikofo | input-chancalan | 14.1 ± 0.4 | 13.1 | 16.1 | 14.19 ± 2.69 |
| mikofo | input-kcen | 14.2 ± 0.4 | 13.0 | 15.5 | 14.24 ± 2.70 |
| mikofo | input-lanjian | 14.2 ± 0.4 | 13.2 | 15.2 | 14.26 ± 2.70 |
| mikofo | input-mattcl | 14.2 ± 0.4 | 13.3 | 15.5 | 14.27 ± 2.70 |
| mikofo | input-mikofo | 14.5 ± 0.3 | 13.5 | 15.6 | 14.51 ± 2.74 |
| mattcl-py | input-lanjian | 14.8 ± 0.5 | 13.5 | 17.9 | 14.85 ± 2.83 |
| pting | input-chancalan | 14.8 ± 0.6 | 13.5 | 17.9 | 14.86 ± 2.84 |
| mattcl-py | input-mattcl | 14.8 ± 0.4 | 13.9 | 16.5 | 14.86 ± 2.82 |
| mattcl-py | input-kcen | 14.8 ± 0.7 | 13.6 | 17.7 | 14.86 ± 2.86 |
| kcen | input-chancalan | 14.8 ± 0.6 | 13.6 | 18.1 | 14.88 ± 2.86 |
| kcen | input-mattcl | 14.8 ± 0.6 | 13.8 | 17.6 | 14.88 ± 2.85 |
| kcen | input-kcen | 14.8 ± 0.5 | 13.9 | 17.8 | 14.88 ± 2.84 |
| pting | input-mattcl | 14.9 ± 0.5 | 13.6 | 18.0 | 14.93 ± 2.85 |
| kcen | input-lanjian | 14.9 ± 0.5 | 13.8 | 17.6 | 14.93 ± 2.85 |
| kcen | input-mikofo | 14.9 ± 0.6 | 14.1 | 17.5 | 14.97 ± 2.86 |
| pting | input-mikofo | 14.9 ± 0.5 | 13.7 | 17.5 | 14.97 ± 2.86 |
| pting | input-lanjian | 14.9 ± 0.6 | 13.7 | 18.2 | 14.98 ± 2.87 |
| mattcl-py | input-chancalan | 15.0 ± 2.6 | 13.5 | 50.6 | 15.01 ± 3.86 |
| mattcl-py | input-mikofo | 15.0 ± 0.7 | 14.0 | 18.5 | 15.11 ± 2.91 |
| pting | input-kcen | 15.1 ± 2.5 | 13.6 | 48.8 | 15.16 ± 3.79 |
| chancalan | input-mattcl | 15.2 ± 0.5 | 14.2 | 18.4 | 15.24 ± 2.91 |
| chancalan | input-chancalan | 15.2 ± 0.5 | 14.1 | 17.9 | 15.26 ± 2.92 |
| chancalan | input-kcen | 15.2 ± 0.6 | 13.9 | 18.4 | 15.26 ± 2.93 |
| chancalan | input-lanjian | 15.2 ± 0.5 | 14.3 | 17.6 | 15.26 ± 2.91 |
| chancalan | input-mikofo | 15.3 ± 0.7 | 14.0 | 18.3 | 15.37 ± 2.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|