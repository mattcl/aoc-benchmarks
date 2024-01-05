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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.3 | 1.06 ± 0.32 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.8 | 1.08 ± 0.33 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.4 | 1.09 ± 0.32 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.3 | 1.8 | 1.13 ± 0.33 |
| lanjian | input-kcen | 1.2 ± 1.6 | 0.3 | 23.1 | 1.26 ± 1.66 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.7 | 1.31 ± 0.36 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.5 | 1.7 | 1.31 ± 0.36 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.33 ± 0.38 |
| lanjian | input-mikofo | 1.3 ± 0.1 | 0.5 | 1.5 | 1.34 ± 0.36 |
| mattcl-ts | input-chancalan | 11.9 ± 0.4 | 10.8 | 12.9 | 12.25 ± 3.00 |
| mattcl-ts | input-kcen | 12.0 ± 0.4 | 11.2 | 13.3 | 12.37 ± 3.03 |
| mattcl-ts | input-lanjian | 12.0 ± 0.4 | 11.0 | 13.3 | 12.37 ± 3.03 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 10.9 | 13.1 | 12.38 ± 3.03 |
| mattcl-ts | input-mikofo | 12.2 ± 0.3 | 11.4 | 13.3 | 12.54 ± 3.07 |
| mikofo | input-chancalan | 14.2 ± 0.4 | 13.1 | 15.3 | 14.60 ± 3.57 |
| mikofo | input-mattcl | 14.2 ± 0.4 | 13.3 | 16.1 | 14.63 ± 3.57 |
| mikofo | input-lanjian | 14.2 ± 0.3 | 13.5 | 15.7 | 14.64 ± 3.57 |
| mikofo | input-kcen | 14.2 ± 0.4 | 13.1 | 15.5 | 14.66 ± 3.58 |
| mikofo | input-mikofo | 14.6 ± 2.4 | 13.6 | 48.1 | 15.07 ± 4.42 |
| kcen | input-lanjian | 14.8 ± 0.6 | 13.6 | 17.8 | 15.23 ± 3.75 |
| mattcl-py | input-lanjian | 14.8 ± 0.5 | 13.8 | 17.6 | 15.24 ± 3.73 |
| kcen | input-chancalan | 14.8 ± 0.6 | 13.5 | 17.8 | 15.26 ± 3.76 |
| mattcl-py | input-mattcl | 14.8 ± 0.6 | 13.6 | 18.2 | 15.28 ± 3.76 |
| kcen | input-kcen | 14.9 ± 0.6 | 13.9 | 17.8 | 15.33 ± 3.77 |
| pting | input-kcen | 14.9 ± 0.6 | 13.9 | 18.3 | 15.35 ± 3.78 |
| pting | input-mattcl | 14.9 ± 0.7 | 13.7 | 18.4 | 15.36 ± 3.80 |
| mattcl-py | input-kcen | 14.9 ± 0.7 | 13.9 | 18.2 | 15.37 ± 3.80 |
| mattcl-py | input-mikofo | 15.0 ± 0.7 | 14.0 | 17.7 | 15.40 ± 3.80 |
| pting | input-mikofo | 15.0 ± 0.6 | 13.8 | 17.8 | 15.41 ± 3.79 |
| kcen | input-mattcl | 15.0 ± 0.6 | 14.0 | 17.8 | 15.41 ± 3.79 |
| pting | input-lanjian | 15.0 ± 0.6 | 13.8 | 18.3 | 15.42 ± 3.80 |
| pting | input-chancalan | 15.0 ± 0.7 | 13.9 | 18.0 | 15.43 ± 3.82 |
| kcen | input-mikofo | 15.0 ± 0.7 | 13.9 | 18.5 | 15.45 ± 3.82 |
| mattcl-py | input-chancalan | 15.1 ± 2.2 | 13.7 | 45.6 | 15.52 ± 4.42 |
| chancalan | input-lanjian | 15.2 ± 0.5 | 14.1 | 17.4 | 15.60 ± 3.82 |
| chancalan | input-chancalan | 15.2 ± 0.5 | 14.4 | 18.0 | 15.63 ± 3.84 |
| chancalan | input-kcen | 15.2 ± 0.5 | 14.2 | 18.0 | 15.69 ± 3.85 |
| chancalan | input-mikofo | 15.2 ± 0.6 | 14.1 | 18.5 | 15.69 ± 3.85 |
| chancalan | input-mattcl | 15.3 ± 0.8 | 14.4 | 18.7 | 15.78 ± 3.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|