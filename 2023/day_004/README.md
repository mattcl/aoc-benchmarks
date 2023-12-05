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
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.7 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 ± 0.33 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.34 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 0.9 | 1.02 ± 0.33 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.3 | 1.2 | 1.03 ± 0.32 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.6 | 1.38 ± 0.44 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.6 | 1.7 | 1.41 ± 0.40 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.5 | 1.7 | 1.46 ± 0.42 |
| lanjian | input-kcen | 1.1 ± 0.1 | 0.7 | 1.6 | 1.47 ± 0.39 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.4 | 2.0 | 1.48 ± 0.43 |
| mattcl-ts | input-kcen | 11.2 ± 0.4 | 10.2 | 12.4 | 15.14 ± 3.65 |
| mattcl-ts | input-chancalan | 11.2 ± 0.4 | 10.2 | 12.5 | 15.17 ± 3.66 |
| mattcl-ts | input-pting | 11.2 ± 0.4 | 10.1 | 11.9 | 15.25 ± 3.68 |
| mattcl-ts | input-lanjian | 11.3 ± 0.4 | 10.0 | 12.2 | 15.28 ± 3.69 |
| mattcl-ts | input-mattcl | 11.3 ± 0.4 | 10.3 | 12.9 | 15.32 ± 3.70 |
| mattcl-py | input-chancalan | 14.6 ± 0.6 | 13.6 | 18.0 | 19.76 ± 4.80 |
| pting | input-kcen | 14.6 ± 0.6 | 13.4 | 18.2 | 19.81 ± 4.80 |
| pting | input-chancalan | 14.7 ± 0.5 | 13.7 | 17.5 | 19.90 ± 4.81 |
| mattcl-py | input-kcen | 14.7 ± 0.6 | 13.5 | 17.9 | 19.91 ± 4.84 |
| kcen | input-mattcl | 14.7 ± 0.5 | 13.6 | 17.5 | 19.91 ± 4.81 |
| mattcl-py | input-pting | 14.7 ± 0.5 | 13.7 | 17.0 | 19.97 ± 4.83 |
| pting | input-lanjian | 14.7 ± 0.7 | 13.7 | 18.1 | 20.00 ± 4.86 |
| pting | input-pting | 14.8 ± 0.6 | 13.6 | 17.9 | 20.07 ± 4.88 |
| kcen | input-kcen | 14.8 ± 0.5 | 13.9 | 18.3 | 20.07 ± 4.86 |
| mattcl-py | input-mattcl | 14.8 ± 0.7 | 13.6 | 18.2 | 20.08 ± 4.89 |
| kcen | input-chancalan | 14.8 ± 0.7 | 13.8 | 17.8 | 20.11 ± 4.90 |
| kcen | input-lanjian | 14.8 ± 0.7 | 13.5 | 18.2 | 20.15 ± 4.93 |
| mattcl-py | input-lanjian | 14.8 ± 2.4 | 13.6 | 47.2 | 20.15 ± 5.78 |
| kcen | input-pting | 14.9 ± 0.6 | 13.9 | 18.3 | 20.17 ± 4.89 |
| chancalan | input-mattcl | 15.0 ± 0.5 | 14.0 | 18.0 | 20.31 ± 4.90 |
| chancalan | input-chancalan | 15.0 ± 0.6 | 13.9 | 17.7 | 20.39 ± 4.95 |
| chancalan | input-lanjian | 15.1 ± 0.5 | 14.0 | 17.9 | 20.44 ± 4.94 |
| chancalan | input-kcen | 15.1 ± 0.6 | 13.9 | 18.5 | 20.44 ± 4.96 |
| chancalan | input-pting | 15.1 ± 0.6 | 13.8 | 17.6 | 20.52 ± 4.97 |
| pting | input-mattcl | 15.2 ± 4.6 | 14.0 | 63.9 | 20.64 ± 8.00 |
| mikofo | input-pting | 277.8 ± 1.8 | 275.3 | 280.8 | 376.99 ± 90.21 |
| mikofo | input-mattcl | 279.6 ± 1.4 | 277.8 | 282.2 | 379.51 ± 90.80 |
| mikofo | input-kcen | 280.1 ± 2.2 | 277.5 | 282.7 | 380.21 ± 91.00 |
| mikofo | input-chancalan | 280.3 ± 2.1 | 276.4 | 283.7 | 380.48 ± 91.06 |
| mikofo | input-lanjian | 280.5 ± 1.8 | 278.0 | 283.3 | 380.74 ± 91.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|