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
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.36 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.0 | 1.1 | 1.02 ± 0.34 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.33 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.2 | 1.0 | 1.07 ± 0.33 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.39 ± 0.43 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.2 | 1.7 | 1.42 ± 0.43 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.43 ± 0.42 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.2 | 1.7 | 1.46 ± 0.43 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.5 | 1.8 | 1.47 ± 0.43 |
| mattcl-ts | input-kcen | 11.2 ± 0.4 | 10.3 | 12.4 | 15.06 ± 3.77 |
| mattcl-ts | input-chancalan | 11.2 ± 0.4 | 10.1 | 12.3 | 15.07 ± 3.78 |
| mattcl-ts | input-mattcl | 11.3 ± 0.3 | 10.0 | 12.5 | 15.11 ± 3.78 |
| mattcl-ts | input-lanjian | 11.3 ± 0.3 | 10.3 | 12.1 | 15.16 ± 3.78 |
| mattcl-ts | input-pting | 11.4 ± 0.4 | 10.4 | 12.8 | 15.23 ± 3.81 |
| mattcl-py | input-kcen | 14.6 ± 0.5 | 13.7 | 17.0 | 19.52 ± 4.88 |
| pting | input-lanjian | 14.6 ± 0.5 | 13.7 | 17.4 | 19.57 ± 4.91 |
| pting | input-mattcl | 14.6 ± 0.5 | 13.3 | 17.7 | 19.58 ± 4.91 |
| mattcl-py | input-lanjian | 14.6 ± 0.7 | 13.6 | 18.6 | 19.59 ± 4.94 |
| mattcl-py | input-pting | 14.6 ± 0.5 | 13.4 | 17.2 | 19.59 ± 4.90 |
| pting | input-chancalan | 14.7 ± 0.6 | 13.7 | 17.6 | 19.66 ± 4.93 |
| pting | input-kcen | 14.7 ± 0.7 | 13.4 | 17.7 | 19.71 ± 4.98 |
| mattcl-py | input-mattcl | 14.7 ± 0.8 | 13.8 | 18.0 | 19.73 ± 5.00 |
| mattcl-py | input-chancalan | 14.7 ± 0.7 | 13.6 | 18.1 | 19.76 ± 5.00 |
| pting | input-pting | 14.7 ± 0.6 | 14.0 | 17.7 | 19.77 ± 4.97 |
| kcen | input-chancalan | 14.8 ± 0.6 | 13.7 | 17.9 | 19.78 ± 4.97 |
| kcen | input-kcen | 14.8 ± 0.6 | 13.7 | 18.2 | 19.84 ± 4.98 |
| kcen | input-mattcl | 14.8 ± 0.6 | 13.7 | 17.8 | 19.85 ± 5.00 |
| kcen | input-pting | 14.8 ± 0.6 | 13.5 | 17.6 | 19.85 ± 4.98 |
| kcen | input-lanjian | 14.8 ± 0.7 | 13.5 | 17.5 | 19.86 ± 5.01 |
| chancalan | input-chancalan | 15.0 ± 0.5 | 13.9 | 17.4 | 20.05 ± 5.01 |
| chancalan | input-lanjian | 15.1 ± 0.7 | 13.7 | 18.1 | 20.19 ± 5.10 |
| chancalan | input-pting | 15.1 ± 0.6 | 14.2 | 17.9 | 20.19 ± 5.07 |
| chancalan | input-kcen | 15.1 ± 0.8 | 13.7 | 18.7 | 20.27 ± 5.13 |
| chancalan | input-mattcl | 15.2 ± 1.3 | 14.1 | 30.6 | 20.35 ± 5.34 |
| mikofo | input-kcen | 278.9 ± 2.3 | 274.9 | 282.1 | 373.90 ± 92.82 |
| mikofo | input-pting | 279.4 ± 2.2 | 276.7 | 282.7 | 374.55 ± 92.97 |
| mikofo | input-mattcl | 279.5 ± 2.0 | 276.6 | 282.7 | 374.70 ± 93.00 |
| mikofo | input-chancalan | 280.2 ± 2.0 | 277.0 | 283.1 | 375.75 ± 93.26 |
| mikofo | input-lanjian | 280.5 ± 1.9 | 277.0 | 283.6 | 376.04 ± 93.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|