# Day 2 benchmarks

[link to problem](https://adventofcode.com/2023/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [aspidites](https://github.com/aspidites/aoc2023) (haskell)
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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.1 | 1.2 | 1.05 ± 0.35 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.35 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.08 ± 0.36 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.08 ± 0.38 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.09 ± 0.36 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.4 | 1.10 ± 0.34 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.5 | 1.12 ± 0.35 |
| lanjian | input-aspidites | 0.9 ± 0.1 | 0.2 | 1.6 | 1.14 ± 0.34 |
| lanjian | input-kcen | 1.0 ± 0.1 | 0.5 | 1.6 | 1.15 ± 0.34 |
| mattcl-ts | input-chancalan | 10.6 ± 0.4 | 9.7 | 11.8 | 12.74 ± 3.40 |
| mattcl-ts | input-lanjian | 10.7 ± 0.4 | 9.5 | 11.7 | 12.76 ± 3.41 |
| mattcl-ts | input-aspidites | 10.7 ± 0.4 | 9.5 | 12.1 | 12.76 ± 3.41 |
| mattcl-ts | input-mattcl | 10.7 ± 0.4 | 9.6 | 11.8 | 12.79 ± 3.41 |
| mattcl-ts | input-kcen | 10.7 ± 0.4 | 9.5 | 11.8 | 12.83 ± 3.42 |
| mikofo | input-aspidites | 10.9 ± 0.4 | 9.8 | 12.0 | 13.01 ± 3.47 |
| mikofo | input-chancalan | 10.9 ± 0.4 | 9.9 | 11.8 | 13.02 ± 3.48 |
| mikofo | input-lanjian | 10.9 ± 0.4 | 9.8 | 11.8 | 13.04 ± 3.48 |
| mikofo | input-mattcl | 10.9 ± 0.4 | 10.0 | 12.1 | 13.07 ± 3.49 |
| mikofo | input-kcen | 11.0 ± 0.4 | 10.1 | 12.0 | 13.16 ± 3.51 |
| aspidites | input-chancalan | 12.6 ± 0.5 | 11.1 | 14.1 | 15.04 ± 4.03 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.8 | 14.2 | 15.15 ± 4.03 |
| aspidites | input-aspidites | 12.7 ± 0.5 | 11.8 | 14.2 | 15.17 ± 4.05 |
| aspidites | input-kcen | 12.7 ± 0.5 | 11.8 | 15.0 | 15.20 ± 4.06 |
| aspidites | input-mattcl | 12.8 ± 0.5 | 11.8 | 14.4 | 15.29 ± 4.08 |
| pting | input-aspidites | 14.3 ± 0.6 | 13.3 | 17.6 | 17.12 ± 4.58 |
| pting | input-mattcl | 14.3 ± 0.6 | 13.4 | 17.7 | 17.12 ± 4.58 |
| mattcl-py | input-lanjian | 14.3 ± 0.6 | 13.5 | 18.1 | 17.18 ± 4.59 |
| pting | input-chancalan | 14.3 ± 0.6 | 13.4 | 17.4 | 17.18 ± 4.59 |
| pting | input-kcen | 14.4 ± 0.6 | 13.4 | 16.9 | 17.21 ± 4.60 |
| mattcl-py | input-aspidites | 14.4 ± 0.5 | 13.6 | 17.5 | 17.22 ± 4.60 |
| pting | input-lanjian | 14.4 ± 0.7 | 13.2 | 18.5 | 17.26 ± 4.63 |
| mattcl-py | input-mattcl | 14.4 ± 0.6 | 13.3 | 17.5 | 17.28 ± 4.63 |
| mattcl-py | input-chancalan | 14.5 ± 0.7 | 13.3 | 17.4 | 17.34 ± 4.66 |
| mattcl-py | input-kcen | 14.5 ± 0.7 | 13.4 | 17.7 | 17.38 ± 4.67 |
| chancalan | input-chancalan | 14.9 ± 0.5 | 13.9 | 18.3 | 17.86 ± 4.75 |
| chancalan | input-kcen | 15.0 ± 0.6 | 14.0 | 18.3 | 17.92 ± 4.78 |
| chancalan | input-aspidites | 15.0 ± 0.6 | 14.0 | 17.9 | 17.92 ± 4.78 |
| chancalan | input-mattcl | 15.0 ± 0.5 | 14.0 | 18.3 | 17.96 ± 4.79 |
| chancalan | input-lanjian | 15.0 ± 0.6 | 14.0 | 18.8 | 18.00 ± 4.82 |
| kcen | input-chancalan | 15.2 ± 0.6 | 14.3 | 18.3 | 18.19 ± 4.86 |
| kcen | input-aspidites | 15.2 ± 0.6 | 14.4 | 17.8 | 18.21 ± 4.86 |
| kcen | input-lanjian | 15.2 ± 0.6 | 14.2 | 18.4 | 18.22 ± 4.87 |
| kcen | input-mattcl | 15.3 ± 0.6 | 14.2 | 18.4 | 18.29 ± 4.89 |
| kcen | input-kcen | 15.3 ± 0.6 | 14.2 | 18.3 | 18.31 ± 4.89 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-mikofo|<pre>2162</pre>|<pre>72513</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|