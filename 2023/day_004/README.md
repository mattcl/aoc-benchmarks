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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.3 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.5 | 1.00 ± 0.25 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.22 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.23 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.3 | 1.2 | 1.04 ± 0.21 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.8 | 1.21 ± 0.26 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.6 | 1.8 | 1.21 ± 0.27 |
| lanjian | input-chancalan | 1.3 ± 0.1 | 0.7 | 1.8 | 1.24 ± 0.24 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.1 | 1.27 ± 0.27 |
| lanjian | input-mikofo | 1.3 ± 0.1 | 0.8 | 2.0 | 1.28 ± 0.25 |
| mattcl-ts | input-chancalan | 11.8 ± 0.3 | 10.9 | 12.7 | 11.30 ± 1.85 |
| mattcl-ts | input-mattcl | 11.8 ± 0.4 | 10.7 | 12.8 | 11.32 ± 1.86 |
| mattcl-ts | input-lanjian | 11.8 ± 0.4 | 10.7 | 13.2 | 11.35 ± 1.87 |
| mattcl-ts | input-mikofo | 12.0 ± 0.4 | 11.0 | 13.0 | 11.50 ± 1.89 |
| mattcl-ts | input-kcen | 12.0 ± 2.7 | 10.9 | 50.0 | 11.53 ± 3.22 |
| mikofo | input-chancalan | 14.0 ± 0.4 | 12.8 | 15.7 | 13.43 ± 2.20 |
| mikofo | input-lanjian | 14.0 ± 0.3 | 13.2 | 14.9 | 13.46 ± 2.20 |
| mikofo | input-mattcl | 14.0 ± 0.3 | 13.1 | 14.8 | 13.46 ± 2.20 |
| mikofo | input-mikofo | 14.3 ± 0.3 | 13.3 | 15.1 | 13.70 ± 2.24 |
| mikofo | input-kcen | 14.5 ± 4.1 | 13.2 | 58.5 | 13.89 ± 4.52 |
| kcen | input-chancalan | 14.6 ± 0.7 | 13.5 | 18.2 | 14.02 ± 2.35 |
| kcen | input-kcen | 14.6 ± 0.6 | 13.5 | 17.7 | 14.05 ± 2.34 |
| mattcl-py | input-chancalan | 14.6 ± 0.7 | 13.8 | 18.3 | 14.07 ± 2.36 |
| mattcl-py | input-lanjian | 14.7 ± 0.6 | 13.6 | 17.5 | 14.09 ± 2.36 |
| kcen | input-lanjian | 14.7 ± 0.6 | 13.6 | 18.1 | 14.09 ± 2.36 |
| pting | input-lanjian | 14.7 ± 0.6 | 13.7 | 18.0 | 14.12 ± 2.36 |
| pting | input-chancalan | 14.7 ± 0.7 | 13.7 | 17.7 | 14.13 ± 2.38 |
| mattcl-py | input-mikofo | 14.7 ± 0.6 | 13.7 | 17.8 | 14.13 ± 2.35 |
| pting | input-mattcl | 14.7 ± 0.5 | 13.8 | 17.4 | 14.13 ± 2.33 |
| kcen | input-mikofo | 14.7 ± 0.6 | 13.6 | 17.6 | 14.16 ± 2.37 |
| mattcl-py | input-mattcl | 14.7 ± 0.6 | 13.7 | 17.7 | 14.17 ± 2.36 |
| pting | input-mikofo | 14.7 ± 0.6 | 13.5 | 17.9 | 14.17 ± 2.37 |
| kcen | input-mattcl | 14.8 ± 0.7 | 13.6 | 17.7 | 14.18 ± 2.40 |
| pting | input-kcen | 14.8 ± 0.7 | 13.9 | 18.2 | 14.19 ± 2.38 |
| mattcl-py | input-kcen | 15.0 ± 3.8 | 13.5 | 67.2 | 14.42 ± 4.34 |
| chancalan | input-lanjian | 15.0 ± 0.5 | 13.9 | 17.6 | 14.43 ± 2.38 |
| chancalan | input-chancalan | 15.0 ± 0.5 | 14.3 | 18.3 | 14.44 ± 2.39 |
| chancalan | input-mattcl | 15.0 ± 0.5 | 14.0 | 17.8 | 14.46 ± 2.39 |
| chancalan | input-kcen | 15.1 ± 0.5 | 14.2 | 17.6 | 14.48 ± 2.39 |
| chancalan | input-mikofo | 15.1 ± 0.5 | 14.0 | 17.8 | 14.55 ± 2.40 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|