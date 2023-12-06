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
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.2 | 1.01 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.03 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.3 | 1.05 ± 0.30 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.2 | 1.1 | 1.08 ± 0.28 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.8 | 1.30 ± 0.36 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.8 | 1.34 ± 0.37 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.36 ± 0.35 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.39 ± 0.35 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.8 | 1.44 ± 0.37 |
| mattcl-ts | input-chancalan | 11.2 ± 0.4 | 10.0 | 12.2 | 13.10 ± 2.76 |
| mattcl-ts | input-lanjian | 11.2 ± 0.3 | 10.2 | 12.3 | 13.20 ± 2.76 |
| mattcl-ts | input-mattcl | 11.3 ± 0.6 | 10.3 | 16.9 | 13.24 ± 2.82 |
| mattcl-ts | input-kcen | 11.4 ± 2.4 | 10.1 | 45.1 | 13.33 ± 3.97 |
| mattcl-ts | input-pting | 11.4 ± 0.3 | 10.4 | 12.2 | 13.34 ± 2.79 |
| mattcl-py | input-chancalan | 14.4 ± 0.7 | 13.7 | 17.7 | 16.91 ± 3.60 |
| pting | input-chancalan | 14.5 ± 0.7 | 13.2 | 18.2 | 16.96 ± 3.60 |
| mattcl-py | input-mattcl | 14.5 ± 0.5 | 13.5 | 17.7 | 16.99 ± 3.58 |
| mattcl-py | input-kcen | 14.5 ± 0.6 | 13.5 | 17.5 | 17.01 ± 3.59 |
| mattcl-py | input-lanjian | 14.5 ± 0.7 | 13.4 | 18.2 | 17.01 ± 3.61 |
| pting | input-mattcl | 14.5 ± 0.6 | 13.6 | 17.7 | 17.06 ± 3.60 |
| mattcl-py | input-pting | 14.5 ± 0.6 | 13.6 | 18.4 | 17.06 ± 3.60 |
| pting | input-lanjian | 14.6 ± 0.6 | 13.6 | 17.7 | 17.09 ± 3.62 |
| pting | input-kcen | 14.6 ± 0.6 | 13.6 | 17.7 | 17.12 ± 3.61 |
| kcen | input-chancalan | 14.6 ± 0.6 | 13.6 | 17.6 | 17.12 ± 3.63 |
| pting | input-pting | 14.6 ± 0.5 | 13.6 | 17.5 | 17.13 ± 3.60 |
| kcen | input-mattcl | 14.6 ± 0.5 | 13.8 | 17.2 | 17.17 ± 3.60 |
| kcen | input-lanjian | 14.7 ± 0.7 | 13.6 | 18.5 | 17.22 ± 3.67 |
| chancalan | input-chancalan | 14.7 ± 0.5 | 13.6 | 17.5 | 17.25 ± 3.62 |
| kcen | input-pting | 14.7 ± 0.6 | 13.8 | 17.8 | 17.30 ± 3.65 |
| kcen | input-kcen | 14.7 ± 2.5 | 13.4 | 48.7 | 17.30 ± 4.63 |
| chancalan | input-kcen | 14.8 ± 0.4 | 14.0 | 17.6 | 17.38 ± 3.63 |
| chancalan | input-lanjian | 14.9 ± 0.6 | 13.7 | 18.1 | 17.52 ± 3.70 |
| chancalan | input-mattcl | 14.9 ± 0.6 | 13.7 | 17.9 | 17.52 ± 3.70 |
| chancalan | input-pting | 15.1 ± 0.7 | 14.1 | 18.6 | 17.73 ± 3.76 |
| mikofo | input-kcen | 32.2 ± 0.4 | 31.3 | 33.3 | 37.78 ± 7.85 |
| mikofo | input-chancalan | 32.2 ± 0.5 | 31.0 | 33.3 | 37.80 ± 7.85 |
| mikofo | input-mattcl | 32.3 ± 0.4 | 31.5 | 33.5 | 37.90 ± 7.87 |
| mikofo | input-lanjian | 32.3 ± 0.5 | 31.1 | 34.0 | 37.92 ± 7.88 |
| mikofo | input-pting | 32.5 ± 0.4 | 31.2 | 33.8 | 38.09 ± 7.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|