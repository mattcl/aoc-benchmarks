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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.33 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.33 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.33 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.4 | 1.0 | 1.10 ± 0.31 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.7 | 1.26 ± 0.41 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.2 | 1.31 ± 0.38 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.31 ± 0.40 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.3 | 2.7 | 1.34 ± 0.43 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.35 ± 0.40 |
| mattcl-ts | input-chancalan | 11.1 ± 0.4 | 10.1 | 12.1 | 13.87 ± 3.43 |
| mattcl-ts | input-kcen | 11.1 ± 0.4 | 10.0 | 12.3 | 13.94 ± 3.45 |
| mattcl-ts | input-mattcl | 11.2 ± 0.4 | 10.0 | 12.1 | 14.01 ± 3.46 |
| mattcl-ts | input-lanjian | 11.2 ± 0.4 | 10.1 | 12.2 | 14.03 ± 3.47 |
| mattcl-ts | input-pting | 11.2 ± 0.4 | 10.1 | 12.7 | 14.04 ± 3.48 |
| mattcl-py | input-chancalan | 14.3 ± 0.5 | 13.6 | 17.0 | 17.88 ± 4.42 |
| mattcl-py | input-kcen | 14.4 ± 0.5 | 13.5 | 17.5 | 17.99 ± 4.46 |
| pting | input-kcen | 14.4 ± 0.6 | 13.4 | 17.5 | 18.06 ± 4.49 |
| pting | input-chancalan | 14.4 ± 0.6 | 13.5 | 17.8 | 18.07 ± 4.49 |
| mattcl-py | input-mattcl | 14.5 ± 0.6 | 13.4 | 17.0 | 18.09 ± 4.48 |
| pting | input-mattcl | 14.5 ± 0.4 | 13.6 | 17.0 | 18.09 ± 4.47 |
| pting | input-lanjian | 14.5 ± 0.5 | 13.5 | 16.8 | 18.16 ± 4.49 |
| kcen | input-kcen | 14.5 ± 0.6 | 13.7 | 17.7 | 18.19 ± 4.53 |
| pting | input-pting | 14.6 ± 0.6 | 13.7 | 18.1 | 18.22 ± 4.52 |
| kcen | input-chancalan | 14.6 ± 0.8 | 13.7 | 18.1 | 18.23 ± 4.57 |
| mattcl-py | input-pting | 14.6 ± 0.7 | 13.8 | 17.6 | 18.24 ± 4.55 |
| kcen | input-mattcl | 14.6 ± 0.5 | 13.7 | 17.7 | 18.24 ± 4.52 |
| kcen | input-pting | 14.6 ± 0.6 | 13.7 | 17.8 | 18.29 ± 4.53 |
| kcen | input-lanjian | 14.6 ± 0.5 | 13.6 | 17.3 | 18.29 ± 4.53 |
| mattcl-py | input-lanjian | 14.7 ± 2.4 | 13.5 | 47.6 | 18.37 ± 5.44 |
| chancalan | input-chancalan | 14.7 ± 0.5 | 13.7 | 17.6 | 18.42 ± 4.56 |
| chancalan | input-kcen | 14.8 ± 0.6 | 14.0 | 18.2 | 18.55 ± 4.62 |
| chancalan | input-mattcl | 14.9 ± 0.5 | 13.9 | 17.7 | 18.59 ± 4.59 |
| chancalan | input-pting | 14.9 ± 0.5 | 13.9 | 17.5 | 18.69 ± 4.62 |
| chancalan | input-lanjian | 14.9 ± 0.7 | 13.9 | 18.6 | 18.69 ± 4.66 |
| mikofo | input-chancalan | 32.2 ± 0.5 | 31.3 | 34.1 | 40.23 ± 9.87 |
| mikofo | input-kcen | 32.2 ± 0.4 | 31.2 | 33.4 | 40.25 ± 9.88 |
| mikofo | input-lanjian | 32.3 ± 0.4 | 31.4 | 33.2 | 40.39 ± 9.91 |
| mikofo | input-pting | 32.5 ± 0.6 | 31.4 | 34.9 | 40.61 ± 9.97 |
| mikofo | input-mattcl | 32.5 ± 1.0 | 31.4 | 39.6 | 40.67 ± 10.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|