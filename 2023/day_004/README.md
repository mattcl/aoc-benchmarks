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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.4 | 1.5 | 1.00 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.2 | 1.3 | 1.00 ± 0.22 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.2 | 1.00 ± 0.22 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.7 | 1.01 ± 0.21 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.4 | 1.7 | 1.04 ± 0.23 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.7 | 2.6 | 1.21 ± 0.27 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.7 | 1.21 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.22 ± 0.26 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.9 | 1.24 ± 0.26 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.4 | 1.7 | 1.25 ± 0.25 |
| mattcl-ts | input-lanjian | 11.9 ± 0.4 | 10.9 | 12.7 | 12.11 ± 1.90 |
| mattcl-ts | input-kcen | 11.9 ± 0.4 | 10.8 | 12.9 | 12.13 ± 1.90 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 11.0 | 12.8 | 12.18 ± 1.91 |
| mattcl-ts | input-mikofo | 12.1 ± 0.4 | 11.2 | 13.0 | 12.33 ± 1.92 |
| mikofo | input-chancalan | 14.1 ± 0.4 | 13.2 | 15.4 | 14.34 ± 2.23 |
| mikofo | input-lanjian | 14.2 ± 0.4 | 13.1 | 15.1 | 14.42 ± 2.24 |
| mattcl-ts | input-chancalan | 14.2 ± 10.3 | 10.9 | 69.9 | 14.42 ± 10.65 |
| mikofo | input-kcen | 14.2 ± 0.4 | 13.5 | 15.2 | 14.43 ± 2.24 |
| mikofo | input-mattcl | 14.3 ± 0.4 | 13.5 | 15.1 | 14.48 ± 2.25 |
| mattcl-py | input-mattcl | 14.7 ± 0.5 | 13.6 | 17.6 | 14.92 ± 2.34 |
| pting | input-chancalan | 14.8 ± 0.5 | 13.5 | 17.4 | 15.02 ± 2.36 |
| kcen | input-lanjian | 14.8 ± 0.6 | 13.8 | 18.0 | 15.03 ± 2.38 |
| pting | input-lanjian | 14.8 ± 0.6 | 13.6 | 17.5 | 15.04 ± 2.37 |
| mattcl-py | input-mikofo | 14.8 ± 0.6 | 13.6 | 18.3 | 15.05 ± 2.38 |
| kcen | input-mattcl | 14.8 ± 0.6 | 13.5 | 17.4 | 15.06 ± 2.38 |
| mikofo | input-mikofo | 14.8 ± 4.1 | 13.3 | 64.5 | 15.07 ± 4.80 |
| mattcl-py | input-kcen | 14.8 ± 0.6 | 13.8 | 17.4 | 15.07 ± 2.39 |
| kcen | input-chancalan | 14.9 ± 0.7 | 13.7 | 18.5 | 15.10 ± 2.42 |
| kcen | input-kcen | 14.9 ± 0.7 | 13.5 | 18.5 | 15.10 ± 2.41 |
| kcen | input-mikofo | 14.9 ± 0.6 | 13.8 | 18.1 | 15.11 ± 2.39 |
| pting | input-mattcl | 14.9 ± 0.6 | 13.8 | 18.1 | 15.11 ± 2.40 |
| mattcl-py | input-lanjian | 14.9 ± 0.7 | 13.8 | 17.8 | 15.12 ± 2.42 |
| pting | input-kcen | 14.9 ± 0.7 | 13.8 | 18.2 | 15.14 ± 2.41 |
| pting | input-mikofo | 15.0 ± 0.6 | 13.8 | 18.1 | 15.20 ± 2.40 |
| mattcl-py | input-chancalan | 15.0 ± 3.2 | 13.4 | 58.8 | 15.25 ± 3.99 |
| chancalan | input-lanjian | 15.1 ± 0.6 | 13.8 | 18.2 | 15.37 ± 2.44 |
| chancalan | input-mattcl | 15.2 ± 0.6 | 14.2 | 18.6 | 15.39 ± 2.43 |
| chancalan | input-kcen | 15.2 ± 0.6 | 14.0 | 18.3 | 15.41 ± 2.44 |
| chancalan | input-chancalan | 15.2 ± 0.6 | 14.0 | 18.4 | 15.45 ± 2.45 |
| chancalan | input-mikofo | 15.6 ± 2.8 | 14.2 | 44.1 | 15.80 ± 3.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|