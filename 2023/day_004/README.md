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
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 0.9 | 1.04 ± 0.40 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.1 | 0.9 | 1.06 ± 0.37 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 0.9 | 1.09 ± 0.38 |
| mattcl | input-pting | 0.8 ± 3.6 | 0.0 | 50.8 | 1.18 ± 4.98 |
| lanjian | input-pting | 1.0 ± 0.3 | 0.2 | 1.6 | 1.41 ± 0.53 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.5 | 1.45 ± 0.48 |
| lanjian | input-lanjian | 1.1 ± 0.1 | 0.4 | 1.2 | 1.47 ± 0.47 |
| lanjian | input-chancalan | 1.1 ± 0.1 | 0.5 | 1.7 | 1.49 ± 0.47 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.49 ± 0.50 |
| mattcl-ts | input-mattcl | 11.2 ± 0.4 | 10.1 | 12.1 | 15.56 ± 4.50 |
| mattcl-ts | input-kcen | 11.2 ± 0.4 | 10.2 | 12.1 | 15.57 ± 4.49 |
| mattcl-ts | input-lanjian | 11.2 ± 0.4 | 10.1 | 12.1 | 15.64 ± 4.52 |
| mattcl-ts | input-pting | 11.2 ± 0.3 | 10.3 | 12.1 | 15.69 ± 4.53 |
| mattcl-ts | input-chancalan | 11.7 ± 5.4 | 9.8 | 71.1 | 16.31 ± 8.90 |
| mattcl-py | input-kcen | 14.4 ± 0.6 | 13.7 | 18.1 | 20.15 ± 5.83 |
| mattcl-py | input-lanjian | 14.4 ± 0.6 | 13.4 | 17.7 | 20.16 ± 5.85 |
| mattcl-py | input-mattcl | 14.4 ± 0.6 | 13.7 | 18.3 | 20.16 ± 5.84 |
| pting | input-mattcl | 14.5 ± 0.6 | 13.4 | 18.0 | 20.19 ± 5.85 |
| pting | input-chancalan | 14.5 ± 0.4 | 13.4 | 16.5 | 20.19 ± 5.83 |
| pting | input-lanjian | 14.5 ± 0.6 | 13.5 | 17.7 | 20.21 ± 5.86 |
| pting | input-kcen | 14.5 ± 0.7 | 13.6 | 19.4 | 20.25 ± 5.88 |
| pting | input-pting | 14.5 ± 0.5 | 13.6 | 18.2 | 20.26 ± 5.86 |
| mattcl-py | input-pting | 14.5 ± 0.6 | 13.6 | 18.2 | 20.26 ± 5.87 |
| kcen | input-kcen | 14.5 ± 0.6 | 13.5 | 17.8 | 20.28 ± 5.87 |
| kcen | input-mattcl | 14.6 ± 0.6 | 13.6 | 17.3 | 20.32 ± 5.89 |
| kcen | input-lanjian | 14.7 ± 0.6 | 13.6 | 17.9 | 20.49 ± 5.94 |
| chancalan | input-chancalan | 14.8 ± 0.5 | 13.8 | 17.7 | 20.65 ± 5.96 |
| chancalan | input-lanjian | 14.9 ± 0.6 | 13.8 | 18.0 | 20.76 ± 6.02 |
| chancalan | input-mattcl | 14.9 ± 0.4 | 14.1 | 17.2 | 20.78 ± 5.99 |
| chancalan | input-kcen | 15.0 ± 0.7 | 13.6 | 17.4 | 20.88 ± 6.07 |
| kcen | input-pting | 15.0 ± 4.2 | 13.8 | 63.6 | 20.99 ± 8.37 |
| mattcl-py | input-chancalan | 15.1 ± 5.2 | 13.4 | 59.5 | 21.06 ± 9.45 |
| kcen | input-chancalan | 15.3 ± 5.2 | 13.4 | 73.6 | 21.37 ± 9.55 |
| chancalan | input-pting | 15.3 ± 2.9 | 14.0 | 54.5 | 21.40 ± 7.36 |
| mikofo | input-chancalan | 32.3 ± 0.4 | 31.4 | 33.3 | 45.14 ± 12.96 |
| mikofo | input-lanjian | 32.3 ± 0.4 | 31.3 | 33.5 | 45.15 ± 12.97 |
| mikofo | input-mattcl | 32.4 ± 0.4 | 31.6 | 33.6 | 45.22 ± 12.99 |
| mikofo | input-kcen | 32.4 ± 0.4 | 31.8 | 33.4 | 45.24 ± 12.99 |
| mikofo | input-pting | 32.5 ± 0.4 | 31.5 | 33.7 | 45.34 ± 13.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|