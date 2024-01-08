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
| mattcl | input-mikofo | 0.9 ± 0.3 | 0.2 | 1.4 | 1.00 |
| lanjian | input-mikofo | 1.0 ± 3.6 | 0.3 | 51.2 | 1.10 ± 4.05 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.2 | 1.10 ± 0.37 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.2 | 1.11 ± 0.37 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.5 | 1.7 | 1.15 ± 0.37 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.4 | 1.2 | 1.15 ± 0.36 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.9 | 1.39 ± 0.45 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.7 | 1.9 | 1.40 ± 0.44 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.7 | 1.7 | 1.41 ± 0.44 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.6 | 1.8 | 1.42 ± 0.45 |
| mattcl-ts | input-chancalan | 11.7 ± 0.4 | 10.6 | 12.6 | 13.14 ± 3.80 |
| mattcl-ts | input-lanjian | 11.7 ± 0.3 | 11.0 | 12.6 | 13.21 ± 3.82 |
| mattcl-ts | input-kcen | 11.7 ± 0.4 | 10.7 | 13.4 | 13.22 ± 3.83 |
| mattcl-ts | input-mattcl | 11.8 ± 0.4 | 10.6 | 12.8 | 13.27 ± 3.84 |
| mattcl-ts | input-mikofo | 12.1 ± 2.6 | 10.9 | 48.6 | 13.67 ± 4.92 |
| mikofo | input-mattcl | 13.9 ± 0.3 | 13.1 | 14.9 | 15.73 ± 4.54 |
| mikofo | input-lanjian | 14.0 ± 0.3 | 13.0 | 15.1 | 15.78 ± 4.56 |
| mikofo | input-kcen | 14.0 ± 0.3 | 13.0 | 14.9 | 15.79 ± 4.56 |
| mikofo | input-chancalan | 14.2 ± 2.9 | 12.7 | 54.4 | 15.98 ± 5.63 |
| mikofo | input-mikofo | 14.2 ± 0.4 | 13.2 | 15.3 | 16.03 ± 4.63 |
| mattcl-py | input-kcen | 14.6 ± 0.6 | 13.8 | 18.3 | 16.43 ± 4.77 |
| pting | input-kcen | 14.6 ± 0.5 | 13.7 | 18.1 | 16.45 ± 4.77 |
| kcen | input-chancalan | 14.6 ± 0.6 | 13.6 | 17.5 | 16.48 ± 4.79 |
| pting | input-chancalan | 14.6 ± 0.6 | 13.8 | 17.4 | 16.49 ± 4.78 |
| pting | input-lanjian | 14.6 ± 0.5 | 13.8 | 16.9 | 16.49 ± 4.78 |
| kcen | input-kcen | 14.6 ± 0.6 | 13.5 | 17.6 | 16.49 ± 4.79 |
| mattcl-py | input-lanjian | 14.6 ± 0.7 | 13.6 | 18.4 | 16.50 ± 4.81 |
| kcen | input-lanjian | 14.6 ± 0.7 | 13.7 | 17.8 | 16.51 ± 4.81 |
| pting | input-mattcl | 14.7 ± 0.7 | 13.7 | 18.4 | 16.53 ± 4.82 |
| mattcl-py | input-mattcl | 14.7 ± 0.7 | 13.5 | 17.6 | 16.54 ± 4.82 |
| mattcl-py | input-mikofo | 14.7 ± 0.7 | 13.6 | 17.9 | 16.56 ± 4.82 |
| kcen | input-mattcl | 14.7 ± 0.8 | 13.6 | 18.2 | 16.59 ± 4.86 |
| kcen | input-mikofo | 14.7 ± 0.6 | 13.5 | 17.4 | 16.61 ± 4.83 |
| pting | input-mikofo | 14.8 ± 0.7 | 13.9 | 17.8 | 16.72 ± 4.87 |
| mattcl-py | input-chancalan | 15.0 ± 3.3 | 13.5 | 49.0 | 16.94 ± 6.16 |
| chancalan | input-chancalan | 15.0 ± 0.7 | 13.9 | 18.1 | 16.95 ± 4.94 |
| chancalan | input-lanjian | 15.0 ± 0.5 | 14.0 | 17.6 | 16.96 ± 4.92 |
| chancalan | input-kcen | 15.1 ± 0.6 | 13.7 | 18.0 | 16.98 ± 4.94 |
| chancalan | input-mattcl | 15.1 ± 0.6 | 14.0 | 17.6 | 16.99 ± 4.93 |
| chancalan | input-mikofo | 15.1 ± 0.4 | 14.0 | 17.4 | 17.04 ± 4.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|