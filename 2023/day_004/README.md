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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.27 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.4 | 1.6 | 1.03 ± 0.28 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.4 | 1.4 | 1.06 ± 0.27 |
| mattcl | input-mikofo | 1.0 ± 0.1 | 0.6 | 1.4 | 1.08 ± 0.27 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.6 | 1.24 ± 0.32 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.26 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.9 | 1.29 ± 0.33 |
| lanjian | input-mikofo | 1.3 ± 0.1 | 0.4 | 1.7 | 1.32 ± 0.32 |
| lanjian | input-lanjian | 1.3 ± 0.1 | 0.4 | 1.7 | 1.32 ± 0.32 |
| mattcl-ts | input-mattcl | 11.4 ± 0.3 | 10.4 | 12.4 | 12.03 ± 2.56 |
| mattcl-ts | input-lanjian | 11.4 ± 0.3 | 10.5 | 12.3 | 12.04 ± 2.56 |
| mattcl-ts | input-chancalan | 11.5 ± 0.3 | 10.5 | 12.4 | 12.04 ± 2.56 |
| mattcl-ts | input-kcen | 11.5 ± 0.3 | 10.4 | 12.6 | 12.04 ± 2.57 |
| mattcl-ts | input-mikofo | 11.6 ± 0.4 | 10.6 | 12.8 | 12.15 ± 2.59 |
| mikofo | input-chancalan | 13.6 ± 0.4 | 12.5 | 14.5 | 14.26 ± 3.03 |
| mikofo | input-mattcl | 13.6 ± 0.4 | 12.7 | 15.2 | 14.33 ± 3.05 |
| mikofo | input-mikofo | 13.8 ± 0.4 | 13.0 | 14.8 | 14.55 ± 3.09 |
| mikofo | input-kcen | 14.0 ± 4.3 | 12.7 | 60.1 | 14.76 ± 5.53 |
| mikofo | input-lanjian | 14.2 ± 4.7 | 12.8 | 65.6 | 14.91 ± 5.86 |
| kcen | input-kcen | 14.4 ± 0.5 | 13.5 | 17.6 | 15.16 ± 3.24 |
| mattcl-py | input-mattcl | 14.5 ± 0.5 | 13.6 | 17.4 | 15.21 ± 3.25 |
| mattcl-py | input-lanjian | 14.5 ± 0.6 | 13.5 | 17.5 | 15.24 ± 3.26 |
| pting | input-chancalan | 14.5 ± 0.6 | 13.5 | 17.9 | 15.26 ± 3.27 |
| mattcl-py | input-chancalan | 14.5 ± 0.6 | 13.5 | 17.7 | 15.27 ± 3.29 |
| pting | input-lanjian | 14.5 ± 0.6 | 13.5 | 18.0 | 15.29 ± 3.29 |
| kcen | input-lanjian | 14.6 ± 0.7 | 13.5 | 17.9 | 15.31 ± 3.31 |
| kcen | input-chancalan | 14.6 ± 0.8 | 13.4 | 18.3 | 15.32 ± 3.33 |
| pting | input-kcen | 14.6 ± 0.6 | 13.6 | 17.9 | 15.33 ± 3.30 |
| mattcl-py | input-kcen | 14.6 ± 0.7 | 13.6 | 17.8 | 15.34 ± 3.32 |
| pting | input-mattcl | 14.6 ± 0.7 | 13.6 | 17.8 | 15.38 ± 3.32 |
| kcen | input-mikofo | 14.6 ± 0.7 | 13.6 | 17.7 | 15.39 ± 3.32 |
| kcen | input-mattcl | 14.7 ± 2.8 | 13.5 | 52.4 | 15.44 ± 4.36 |
| mattcl-py | input-mikofo | 14.7 ± 0.7 | 13.5 | 18.2 | 15.44 ± 3.33 |
| pting | input-mikofo | 14.8 ± 0.8 | 13.5 | 18.0 | 15.53 ± 3.37 |
| chancalan | input-chancalan | 14.9 ± 0.6 | 13.7 | 17.9 | 15.66 ± 3.36 |
| chancalan | input-mattcl | 14.9 ± 0.5 | 13.8 | 17.8 | 15.68 ± 3.36 |
| chancalan | input-lanjian | 14.9 ± 0.6 | 13.9 | 17.5 | 15.71 ± 3.36 |
| chancalan | input-kcen | 15.0 ± 0.6 | 13.9 | 17.8 | 15.75 ± 3.38 |
| chancalan | input-mikofo | 15.0 ± 0.5 | 14.1 | 17.6 | 15.81 ± 3.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|