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
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.2 | 1.01 ± 0.38 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 0.9 | 1.02 ± 0.37 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.03 ± 0.38 |
| mattcl | input-chancalan | 0.8 ± 0.1 | 0.2 | 1.0 | 1.08 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.2 | 1.8 | 1.46 ± 0.50 |
| lanjian | input-kcen | 1.1 ± 0.1 | 0.5 | 1.6 | 1.46 ± 0.45 |
| lanjian | input-chancalan | 1.1 ± 0.1 | 0.5 | 1.6 | 1.47 ± 0.45 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.49 ± 0.48 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.8 | 1.54 ± 0.47 |
| mattcl-ts | input-lanjian | 10.8 ± 0.4 | 9.7 | 11.7 | 14.89 ± 4.13 |
| mattcl-ts | input-chancalan | 10.9 ± 0.4 | 9.9 | 12.0 | 14.94 ± 4.14 |
| mattcl-ts | input-kcen | 10.9 ± 0.4 | 9.9 | 11.7 | 14.95 ± 4.14 |
| mattcl-ts | input-mattcl | 10.9 ± 0.4 | 9.9 | 11.8 | 14.98 ± 4.15 |
| mattcl-ts | input-pting | 10.9 ± 0.4 | 9.8 | 11.8 | 15.05 ± 4.17 |
| mattcl-py | input-mattcl | 14.4 ± 0.5 | 13.6 | 18.0 | 19.81 ± 5.48 |
| pting | input-chancalan | 14.5 ± 0.5 | 13.5 | 17.7 | 19.90 ± 5.52 |
| mattcl-py | input-kcen | 14.5 ± 0.7 | 13.5 | 17.9 | 19.90 ± 5.54 |
| mattcl-py | input-chancalan | 14.5 ± 0.6 | 13.7 | 17.4 | 19.91 ± 5.53 |
| pting | input-kcen | 14.5 ± 0.6 | 13.7 | 17.5 | 19.91 ± 5.53 |
| pting | input-lanjian | 14.5 ± 0.4 | 13.5 | 18.0 | 19.92 ± 5.50 |
| mattcl-py | input-lanjian | 14.5 ± 0.7 | 13.6 | 17.9 | 19.98 ± 5.56 |
| kcen | input-kcen | 14.6 ± 0.5 | 13.8 | 17.4 | 20.06 ± 5.55 |
| mattcl-py | input-pting | 14.6 ± 0.7 | 13.6 | 17.9 | 20.06 ± 5.60 |
| pting | input-mattcl | 14.6 ± 1.8 | 13.4 | 38.9 | 20.07 ± 6.06 |
| pting | input-pting | 14.6 ± 0.7 | 13.6 | 18.4 | 20.11 ± 5.60 |
| kcen | input-chancalan | 14.6 ± 0.6 | 13.7 | 17.6 | 20.15 ± 5.60 |
| kcen | input-lanjian | 14.7 ± 0.6 | 13.7 | 17.7 | 20.16 ± 5.61 |
| kcen | input-mattcl | 14.7 ± 0.7 | 13.6 | 18.0 | 20.17 ± 5.62 |
| kcen | input-pting | 14.7 ± 0.6 | 13.6 | 17.5 | 20.17 ± 5.61 |
| chancalan | input-mattcl | 14.9 ± 0.6 | 13.8 | 17.7 | 20.44 ± 5.67 |
| chancalan | input-chancalan | 14.9 ± 0.6 | 13.7 | 18.0 | 20.46 ± 5.69 |
| chancalan | input-kcen | 14.9 ± 0.5 | 14.0 | 18.1 | 20.48 ± 5.66 |
| chancalan | input-pting | 15.0 ± 0.5 | 14.1 | 17.9 | 20.58 ± 5.70 |
| chancalan | input-lanjian | 15.0 ± 2.1 | 13.7 | 42.1 | 20.63 ± 6.35 |
| mikofo | input-kcen | 276.8 ± 1.2 | 275.3 | 278.6 | 380.95 ± 104.64 |
| mikofo | input-chancalan | 277.6 ± 2.4 | 275.5 | 282.1 | 382.05 ± 104.98 |
| mikofo | input-mattcl | 277.9 ± 2.1 | 275.1 | 280.6 | 382.47 ± 105.08 |
| mikofo | input-pting | 278.5 ± 1.2 | 276.6 | 280.3 | 383.20 ± 105.26 |
| mikofo | input-lanjian | 279.1 ± 4.0 | 275.7 | 289.4 | 384.11 ± 105.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|