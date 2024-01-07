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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.6 | 1.00 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.1 | 1.03 ± 0.27 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.5 | 1.5 | 1.03 ± 0.26 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.5 | 1.6 | 1.06 ± 0.27 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.3 | 1.4 | 1.26 ± 0.31 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.7 | 1.8 | 1.27 ± 0.31 |
| lanjian | input-mikofo | 1.2 ± 0.1 | 0.8 | 1.6 | 1.28 ± 0.31 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.8 | 1.9 | 1.28 ± 0.31 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.30 ± 0.34 |
| mattcl-ts | input-chancalan | 11.8 ± 0.3 | 11.1 | 13.0 | 12.84 ± 2.74 |
| mattcl-ts | input-kcen | 11.9 ± 0.4 | 10.9 | 13.5 | 12.86 ± 2.75 |
| mattcl-ts | input-lanjian | 12.0 ± 0.4 | 11.0 | 12.8 | 12.95 ± 2.77 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 11.0 | 13.3 | 12.96 ± 2.77 |
| mattcl-ts | input-mikofo | 12.2 ± 2.7 | 10.9 | 49.5 | 13.22 ± 4.03 |
| mikofo | input-lanjian | 14.1 ± 0.4 | 13.3 | 15.1 | 15.29 ± 3.26 |
| mikofo | input-chancalan | 14.1 ± 0.4 | 13.1 | 15.0 | 15.29 ± 3.26 |
| mikofo | input-mattcl | 14.1 ± 0.3 | 13.1 | 14.9 | 15.29 ± 3.26 |
| mikofo | input-kcen | 14.1 ± 0.4 | 13.3 | 15.1 | 15.29 ± 3.26 |
| mikofo | input-mikofo | 14.3 ± 0.4 | 13.4 | 16.3 | 15.50 ± 3.31 |
| mattcl-py | input-kcen | 14.7 ± 0.7 | 13.6 | 18.2 | 15.91 ± 3.45 |
| mattcl-py | input-lanjian | 14.7 ± 0.6 | 13.8 | 17.7 | 15.92 ± 3.43 |
| kcen | input-kcen | 14.7 ± 0.6 | 13.5 | 17.4 | 15.92 ± 3.43 |
| kcen | input-lanjian | 14.7 ± 0.6 | 13.5 | 17.7 | 15.92 ± 3.43 |
| mattcl-py | input-chancalan | 14.7 ± 0.6 | 13.7 | 17.7 | 15.93 ± 3.43 |
| pting | input-chancalan | 14.7 ± 0.7 | 13.7 | 17.9 | 15.98 ± 3.46 |
| pting | input-lanjian | 14.8 ± 0.5 | 13.9 | 17.3 | 15.99 ± 3.43 |
| mattcl-py | input-mattcl | 14.8 ± 0.7 | 13.8 | 18.0 | 16.00 ± 3.46 |
| pting | input-kcen | 14.8 ± 0.7 | 13.7 | 17.8 | 16.00 ± 3.47 |
| pting | input-mattcl | 14.8 ± 0.6 | 13.7 | 17.4 | 16.01 ± 3.44 |
| pting | input-mikofo | 14.8 ± 0.6 | 13.6 | 17.5 | 16.02 ± 3.44 |
| kcen | input-mattcl | 14.8 ± 0.8 | 13.4 | 18.1 | 16.04 ± 3.49 |
| mattcl-py | input-mikofo | 14.8 ± 0.7 | 13.6 | 18.1 | 16.08 ± 3.49 |
| kcen | input-mikofo | 14.8 ± 0.7 | 13.9 | 18.1 | 16.08 ± 3.48 |
| kcen | input-chancalan | 15.0 ± 3.1 | 13.4 | 57.5 | 16.21 ± 4.80 |
| chancalan | input-chancalan | 15.1 ± 0.5 | 14.0 | 17.7 | 16.32 ± 3.49 |
| chancalan | input-kcen | 15.1 ± 0.5 | 13.8 | 17.7 | 16.32 ± 3.50 |
| chancalan | input-mattcl | 15.1 ± 0.6 | 14.0 | 17.8 | 16.33 ± 3.52 |
| chancalan | input-lanjian | 15.1 ± 0.6 | 13.9 | 18.5 | 16.35 ± 3.52 |
| chancalan | input-mikofo | 15.2 ± 0.6 | 14.3 | 18.4 | 16.50 ± 3.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|