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
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.6 | 1.00 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 ± 0.31 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.30 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.29 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.02 ± 0.30 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.29 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.5 | 1.03 ± 0.29 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.29 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.29 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.3 | 1.2 | 1.05 ± 0.28 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.6 | 1.05 ± 0.30 |
| mattcl | input-aspidites | 1.0 ± 0.1 | 0.3 | 1.2 | 1.05 ± 0.28 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.5 | 1.08 ± 0.29 |
| mattcl-ts | input-kcen | 11.1 ± 0.4 | 9.8 | 12.3 | 12.09 ± 2.73 |
| mattcl-ts | input-mattcl | 11.1 ± 0.4 | 10.0 | 12.1 | 12.15 ± 2.74 |
| mattcl-ts | input-aspidites | 11.1 ± 0.4 | 10.0 | 12.0 | 12.15 ± 2.74 |
| mattcl-ts | input-pting | 11.2 ± 0.4 | 10.1 | 12.1 | 12.25 ± 2.75 |
| mikofo | input-chancalan | 11.3 ± 0.3 | 10.3 | 12.4 | 12.37 ± 2.78 |
| mikofo | input-kcen | 11.4 ± 0.3 | 10.4 | 12.6 | 12.41 ± 2.79 |
| mikofo | input-pting | 11.4 ± 0.3 | 10.4 | 12.8 | 12.41 ± 2.78 |
| mikofo | input-aspidites | 11.4 ± 0.3 | 10.3 | 12.0 | 12.43 ± 2.78 |
| mikofo | input-mattcl | 11.4 ± 0.3 | 10.4 | 12.5 | 12.44 ± 2.79 |
| mikofo | input-lanjian | 11.4 ± 0.3 | 10.5 | 12.3 | 12.45 ± 2.79 |
| mikofo | input-mikofo | 11.4 ± 0.4 | 10.4 | 13.5 | 12.45 ± 2.80 |
| mattcl-ts | input-chancalan | 11.5 ± 3.0 | 9.7 | 53.7 | 12.50 ± 4.32 |
| mattcl-ts | input-lanjian | 11.5 ± 3.4 | 10.2 | 46.2 | 12.55 ± 4.62 |
| mattcl-ts | input-mikofo | 11.5 ± 3.4 | 10.3 | 58.8 | 12.55 ± 4.63 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.7 | 14.1 | 13.91 ± 3.14 |
| aspidites | input-pting | 12.7 ± 0.5 | 11.7 | 14.2 | 13.92 ± 3.14 |
| aspidites | input-mikofo | 12.8 ± 0.5 | 11.4 | 14.5 | 13.93 ± 3.15 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.8 | 14.3 | 13.95 ± 3.15 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.5 | 14.3 | 13.96 ± 3.15 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.8 | 14.2 | 13.97 ± 3.15 |
| aspidites | input-mattcl | 12.9 ± 0.5 | 11.9 | 14.4 | 14.04 ± 3.17 |
| pting | input-kcen | 14.5 ± 0.4 | 13.4 | 17.3 | 15.80 ± 3.54 |
| pting | input-chancalan | 14.6 ± 0.7 | 13.2 | 18.3 | 15.89 ± 3.61 |
| pting | input-mattcl | 14.6 ± 0.5 | 13.6 | 17.5 | 15.91 ± 3.58 |
| pting | input-lanjian | 14.6 ± 0.6 | 13.6 | 18.6 | 15.95 ± 3.61 |
| mattcl-py | input-pting | 14.6 ± 0.5 | 13.3 | 16.7 | 15.97 ± 3.59 |
| mattcl-py | input-mikofo | 14.6 ± 0.7 | 13.4 | 18.0 | 15.99 ± 3.63 |
| pting | input-pting | 14.6 ± 0.7 | 13.5 | 18.1 | 15.99 ± 3.63 |
| mattcl-py | input-chancalan | 14.7 ± 0.6 | 13.5 | 17.4 | 16.01 ± 3.62 |
| mattcl-py | input-mattcl | 14.7 ± 0.6 | 13.6 | 17.4 | 16.01 ± 3.62 |
| pting | input-mikofo | 14.7 ± 0.6 | 13.3 | 17.6 | 16.03 ± 3.63 |
| pting | input-aspidites | 14.7 ± 0.7 | 13.5 | 17.7 | 16.04 ± 3.64 |
| mattcl-py | input-aspidites | 14.7 ± 0.6 | 13.9 | 17.7 | 16.04 ± 3.63 |
| mattcl-py | input-lanjian | 14.7 ± 0.6 | 13.4 | 17.8 | 16.05 ± 3.64 |
| mattcl-py | input-kcen | 14.7 ± 0.7 | 13.4 | 18.1 | 16.06 ± 3.64 |
| chancalan | input-mattcl | 15.1 ± 0.7 | 13.9 | 18.1 | 16.51 ± 3.75 |
| chancalan | input-mikofo | 15.1 ± 0.6 | 13.9 | 17.9 | 16.53 ± 3.74 |
| chancalan | input-chancalan | 15.2 ± 0.5 | 14.3 | 17.7 | 16.55 ± 3.72 |
| chancalan | input-kcen | 15.2 ± 0.6 | 14.1 | 18.5 | 16.56 ± 3.75 |
| chancalan | input-aspidites | 15.2 ± 0.6 | 14.2 | 18.2 | 16.59 ± 3.74 |
| chancalan | input-pting | 15.3 ± 0.7 | 14.5 | 18.5 | 16.67 ± 3.78 |
| chancalan | input-lanjian | 15.3 ± 0.7 | 13.8 | 18.2 | 16.68 ± 3.79 |
| kcen | input-kcen | 15.4 ± 0.6 | 14.2 | 18.3 | 16.84 ± 3.79 |
| kcen | input-lanjian | 15.5 ± 0.6 | 14.3 | 18.5 | 16.87 ± 3.81 |
| kcen | input-pting | 15.5 ± 0.7 | 14.3 | 18.9 | 16.88 ± 3.82 |
| kcen | input-chancalan | 15.5 ± 0.5 | 14.6 | 18.3 | 16.88 ± 3.80 |
| kcen | input-mattcl | 15.5 ± 0.6 | 14.5 | 18.4 | 16.95 ± 3.83 |
| kcen | input-aspidites | 15.6 ± 0.8 | 14.3 | 18.9 | 16.99 ± 3.87 |
| kcen | input-mikofo | 15.6 ± 0.7 | 14.6 | 18.5 | 17.02 ± 3.86 |


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