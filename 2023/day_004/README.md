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
| mattcl | input-mikofo | 0.8 ± 2.2 | 0.1 | 30.7 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.21 ± 3.34 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.4 | 1.24 ± 3.40 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.6 | 1.25 ± 3.44 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.2 | 1.7 | 1.26 ± 3.47 |
| lanjian | input-mikofo | 1.2 ± 0.2 | 0.4 | 1.5 | 1.50 ± 4.14 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.51 ± 4.15 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.6 | 1.4 | 1.51 ± 4.16 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.5 | 1.4 | 1.52 ± 4.17 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.6 | 1.7 | 1.54 ± 4.22 |
| mattcl-ts | input-kcen | 11.9 ± 0.3 | 11.1 | 12.9 | 15.21 ± 41.77 |
| mattcl-ts | input-chancalan | 11.9 ± 0.4 | 10.8 | 13.2 | 15.22 ± 41.80 |
| mattcl-ts | input-mattcl | 12.0 ± 0.4 | 11.0 | 13.1 | 15.31 ± 42.04 |
| mattcl-ts | input-lanjian | 12.0 ± 0.4 | 11.0 | 13.6 | 15.33 ± 42.10 |
| mattcl-ts | input-mikofo | 12.1 ± 0.4 | 10.9 | 12.9 | 15.45 ± 42.43 |
| mikofo | input-mattcl | 14.1 ± 0.4 | 13.1 | 15.7 | 18.00 ± 49.44 |
| mikofo | input-kcen | 14.1 ± 0.4 | 13.3 | 16.2 | 18.03 ± 49.51 |
| mikofo | input-chancalan | 14.1 ± 0.3 | 13.4 | 15.4 | 18.03 ± 49.53 |
| mikofo | input-lanjian | 14.1 ± 0.4 | 13.3 | 15.3 | 18.04 ± 49.55 |
| mikofo | input-mikofo | 14.4 ± 0.3 | 13.5 | 15.2 | 18.33 ± 50.33 |
| kcen | input-chancalan | 14.7 ± 0.6 | 13.6 | 18.4 | 18.74 ± 51.48 |
| mattcl-py | input-lanjian | 14.7 ± 0.5 | 13.7 | 17.6 | 18.77 ± 51.54 |
| kcen | input-kcen | 14.7 ± 0.5 | 13.7 | 17.0 | 18.81 ± 51.64 |
| pting | input-mattcl | 14.7 ± 0.6 | 13.8 | 18.0 | 18.81 ± 51.65 |
| mattcl-py | input-mattcl | 14.7 ± 0.6 | 13.8 | 17.6 | 18.82 ± 51.67 |
| mattcl-py | input-kcen | 14.7 ± 0.6 | 13.6 | 17.6 | 18.84 ± 51.73 |
| kcen | input-mattcl | 14.8 ± 0.6 | 13.4 | 17.6 | 18.85 ± 51.77 |
| mattcl-py | input-chancalan | 14.8 ± 0.7 | 13.8 | 17.8 | 18.85 ± 51.77 |
| kcen | input-lanjian | 14.8 ± 0.7 | 13.5 | 17.8 | 18.89 ± 51.87 |
| pting | input-kcen | 14.8 ± 0.7 | 13.5 | 18.1 | 18.91 ± 51.93 |
| pting | input-lanjian | 14.8 ± 0.7 | 13.6 | 18.3 | 18.91 ± 51.93 |
| pting | input-chancalan | 14.9 ± 0.7 | 13.7 | 18.1 | 18.97 ± 52.10 |
| kcen | input-mikofo | 14.9 ± 0.6 | 14.0 | 18.2 | 19.02 ± 52.24 |
| pting | input-mikofo | 14.9 ± 0.9 | 13.6 | 18.2 | 19.06 ± 52.34 |
| chancalan | input-mattcl | 15.1 ± 0.5 | 14.1 | 18.5 | 19.22 ± 52.80 |
| chancalan | input-chancalan | 15.1 ± 0.6 | 13.9 | 17.9 | 19.24 ± 52.85 |
| mattcl-py | input-mikofo | 15.1 ± 3.8 | 13.5 | 53.8 | 19.25 ± 53.09 |
| chancalan | input-kcen | 15.1 ± 0.6 | 13.9 | 18.4 | 19.33 ± 53.08 |
| chancalan | input-lanjian | 15.2 ± 0.6 | 14.1 | 18.2 | 19.36 ± 53.17 |
| chancalan | input-mikofo | 15.2 ± 0.6 | 14.2 | 17.9 | 19.40 ± 53.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>15205</pre>|<pre>6189740</pre>|
|input-kcen|<pre>21558</pre>|<pre>10425665</pre>|
|input-lanjian|<pre>17803</pre>|<pre>5554894</pre>|
|input-mattcl|<pre>15268</pre>|<pre>6283755</pre>|
|input-mikofo|<pre>21088</pre>|<pre>6874754</pre>|
|input-pting|<pre>25651</pre>|<pre>19499881</pre>|