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
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.0 | 1.00 |
| mattcl | input-pting | 0.8 ± 2.7 | 0.1 | 38.3 | 1.05 ± 3.38 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.35 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.1 | 1.08 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.09 ± 0.33 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.39 ± 0.42 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.39 ± 0.41 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.8 | 1.41 ± 0.42 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.4 | 2.1 | 1.43 ± 0.44 |
| lanjian | input-lanjian | 1.1 ± 0.1 | 0.6 | 1.6 | 1.44 ± 0.39 |
| mattcl-ts | input-lanjian | 11.2 ± 0.4 | 10.0 | 12.1 | 14.12 ± 3.42 |
| mattcl-ts | input-mattcl | 11.3 ± 0.4 | 10.2 | 12.1 | 14.17 ± 3.43 |
| mattcl-ts | input-pting | 11.3 ± 0.4 | 10.3 | 12.2 | 14.22 ± 3.44 |
| mattcl-ts | input-chancalan | 11.4 ± 2.3 | 10.1 | 43.4 | 14.28 ± 4.49 |
| mattcl-ts | input-kcen | 11.4 ± 1.9 | 10.1 | 38.3 | 14.29 ± 4.21 |
| mattcl-py | input-chancalan | 14.4 ± 0.6 | 13.4 | 18.1 | 18.16 ± 4.43 |
| mattcl-py | input-lanjian | 14.5 ± 0.6 | 13.5 | 17.3 | 18.20 ± 4.43 |
| pting | input-mattcl | 14.5 ± 0.5 | 13.5 | 16.2 | 18.27 ± 4.42 |
| mattcl-py | input-kcen | 14.5 ± 0.7 | 13.4 | 17.9 | 18.27 ± 4.46 |
| kcen | input-chancalan | 14.5 ± 0.6 | 13.6 | 18.0 | 18.29 ± 4.45 |
| pting | input-chancalan | 14.5 ± 0.6 | 13.6 | 18.3 | 18.29 ± 4.45 |
| mattcl-py | input-mattcl | 14.6 ± 0.7 | 13.4 | 18.2 | 18.33 ± 4.49 |
| mattcl-py | input-pting | 14.6 ± 0.5 | 13.7 | 17.4 | 18.34 ± 4.45 |
| pting | input-lanjian | 14.6 ± 0.6 | 13.7 | 17.7 | 18.35 ± 4.46 |
| kcen | input-lanjian | 14.6 ± 0.6 | 13.5 | 17.7 | 18.38 ± 4.47 |
| kcen | input-kcen | 14.7 ± 0.6 | 13.7 | 18.1 | 18.44 ± 4.49 |
| kcen | input-mattcl | 14.7 ± 0.7 | 13.8 | 17.9 | 18.48 ± 4.51 |
| kcen | input-pting | 14.7 ± 0.7 | 14.0 | 18.0 | 18.53 ± 4.52 |
| pting | input-pting | 14.8 ± 0.6 | 13.7 | 17.9 | 18.62 ± 4.54 |
| chancalan | input-chancalan | 14.8 ± 0.5 | 13.9 | 17.4 | 18.64 ± 4.52 |
| chancalan | input-mattcl | 14.9 ± 0.6 | 13.9 | 18.1 | 18.76 ± 4.55 |
| chancalan | input-kcen | 15.0 ± 0.6 | 13.9 | 18.2 | 18.82 ± 4.57 |
| pting | input-kcen | 15.0 ± 4.3 | 13.5 | 58.5 | 18.85 ± 7.09 |
| chancalan | input-pting | 15.0 ± 0.7 | 14.0 | 18.4 | 18.91 ± 4.61 |
| chancalan | input-lanjian | 15.1 ± 2.7 | 13.8 | 51.5 | 19.02 ± 5.66 |
| mikofo | input-chancalan | 32.4 ± 0.5 | 31.4 | 34.4 | 40.71 ± 9.79 |
| mikofo | input-kcen | 32.4 ± 0.4 | 31.4 | 34.0 | 40.72 ± 9.78 |
| mikofo | input-mattcl | 32.5 ± 0.6 | 31.3 | 34.1 | 40.82 ± 9.82 |
| mikofo | input-lanjian | 32.5 ± 0.5 | 31.4 | 33.7 | 40.83 ± 9.81 |
| mikofo | input-pting | 32.7 ± 0.5 | 31.7 | 35.4 | 41.09 ± 9.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|