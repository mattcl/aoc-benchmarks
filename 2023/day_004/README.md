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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.4 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 ± 0.40 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.03 ± 0.38 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.40 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.1 | 1.05 ± 0.39 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.7 | 1.45 ± 0.50 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.47 ± 0.50 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.5 | 1.7 | 1.47 ± 0.49 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.7 | 1.49 ± 0.49 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.3 | 1.3 | 1.49 ± 0.48 |
| mattcl-ts | input-chancalan | 11.3 ± 0.4 | 10.3 | 12.5 | 14.94 ± 4.44 |
| mattcl-ts | input-lanjian | 11.3 ± 0.4 | 10.2 | 12.4 | 14.98 ± 4.46 |
| mattcl-ts | input-mattcl | 11.3 ± 0.4 | 10.3 | 12.3 | 15.02 ± 4.46 |
| mattcl-ts | input-pting | 11.3 ± 0.3 | 10.5 | 12.1 | 15.04 ± 4.47 |
| mattcl-ts | input-kcen | 11.7 ± 4.0 | 10.4 | 52.3 | 15.48 ± 7.01 |
| pting | input-kcen | 14.6 ± 0.5 | 13.5 | 17.5 | 19.42 ± 5.79 |
| mattcl-py | input-lanjian | 14.8 ± 0.6 | 13.8 | 18.3 | 19.59 ± 5.85 |
| mattcl-py | input-chancalan | 14.8 ± 0.7 | 13.7 | 18.1 | 19.62 ± 5.87 |
| mattcl-py | input-kcen | 14.8 ± 0.7 | 13.8 | 17.9 | 19.63 ± 5.87 |
| mattcl-py | input-pting | 14.8 ± 0.5 | 13.8 | 17.5 | 19.65 ± 5.85 |
| mattcl-py | input-mattcl | 14.8 ± 0.6 | 13.5 | 17.5 | 19.66 ± 5.87 |
| kcen | input-chancalan | 14.8 ± 0.7 | 13.6 | 18.2 | 19.67 ± 5.89 |
| pting | input-chancalan | 14.8 ± 0.7 | 13.7 | 17.7 | 19.67 ± 5.88 |
| pting | input-pting | 14.9 ± 0.7 | 13.8 | 18.1 | 19.71 ± 5.89 |
| kcen | input-lanjian | 14.9 ± 0.6 | 13.6 | 18.0 | 19.71 ± 5.89 |
| pting | input-lanjian | 14.9 ± 0.6 | 13.8 | 18.2 | 19.71 ± 5.87 |
| pting | input-mattcl | 14.9 ± 0.7 | 13.5 | 17.7 | 19.76 ± 5.91 |
| kcen | input-mattcl | 15.0 ± 0.7 | 13.8 | 18.4 | 19.85 ± 5.94 |
| kcen | input-kcen | 15.0 ± 0.7 | 13.7 | 18.2 | 19.88 ± 5.95 |
| chancalan | input-chancalan | 15.0 ± 0.4 | 14.0 | 18.7 | 19.92 ± 5.91 |
| kcen | input-pting | 15.1 ± 0.7 | 13.6 | 18.0 | 20.00 ± 5.99 |
| chancalan | input-mattcl | 15.1 ± 0.6 | 13.8 | 17.7 | 20.09 ± 5.98 |
| chancalan | input-kcen | 15.1 ± 0.6 | 14.0 | 18.2 | 20.09 ± 6.00 |
| chancalan | input-lanjian | 15.2 ± 0.6 | 14.3 | 18.2 | 20.15 ± 6.01 |
| chancalan | input-pting | 15.2 ± 0.7 | 14.0 | 18.8 | 20.16 ± 6.03 |
| mikofo | input-pting | 280.4 ± 3.0 | 275.5 | 284.8 | 371.93 ± 110.02 |
| mikofo | input-lanjian | 281.3 ± 1.4 | 279.0 | 283.5 | 373.13 ± 110.32 |
| mikofo | input-chancalan | 281.5 ± 3.1 | 275.0 | 284.5 | 373.42 ± 110.46 |
| mikofo | input-kcen | 282.5 ± 2.7 | 278.7 | 287.8 | 374.73 ± 110.84 |
| mikofo | input-mattcl | 282.7 ± 1.9 | 278.5 | 284.5 | 374.99 ± 110.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|