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
| mattcl | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.31 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.34 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.1 | 1.0 | 1.02 ± 0.31 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.32 |
| lanjian | input-aspidites | 0.8 ± 0.2 | 0.2 | 1.3 | 1.03 ± 0.33 |
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.1 | 1.3 | 1.03 ± 0.32 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.1 | 1.1 | 1.04 ± 0.31 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.05 ± 0.35 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.33 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.1 | 1.06 ± 0.33 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.34 |
| lanjian | input-pting | 0.8 ± 0.1 | 0.2 | 1.1 | 1.06 ± 0.32 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.1 | 1.0 | 1.07 ± 0.31 |
| mattcl-ts | input-lanjian | 10.4 ± 0.4 | 9.3 | 11.8 | 13.00 ± 3.19 |
| mattcl-ts | input-aspidites | 10.4 ± 0.4 | 9.3 | 11.4 | 13.00 ± 3.19 |
| mattcl-ts | input-mikofo | 10.4 ± 0.4 | 9.2 | 11.3 | 13.02 ± 3.19 |
| mattcl-ts | input-kcen | 10.4 ± 0.4 | 9.4 | 11.3 | 13.04 ± 3.19 |
| mattcl-ts | input-mattcl | 10.4 ± 0.4 | 9.3 | 11.7 | 13.07 ± 3.20 |
| mattcl-ts | input-pting | 10.5 ± 0.3 | 9.6 | 11.3 | 13.08 ± 3.20 |
| mattcl-ts | input-chancalan | 11.2 ± 6.8 | 9.6 | 86.8 | 13.98 ± 9.17 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.6 | 13.9 | 15.84 ± 3.89 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.8 | 14.2 | 15.89 ± 3.90 |
| aspidites | input-mikofo | 12.7 ± 0.5 | 11.7 | 14.2 | 15.91 ± 3.90 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.5 | 14.2 | 15.91 ± 3.91 |
| aspidites | input-aspidites | 12.7 ± 0.4 | 11.7 | 14.1 | 15.93 ± 3.90 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.8 | 13.9 | 15.96 ± 3.92 |
| aspidites | input-pting | 12.8 ± 0.5 | 11.8 | 14.4 | 16.01 ± 3.93 |
| pting | input-aspidites | 14.3 ± 0.5 | 13.1 | 17.6 | 17.85 ± 4.38 |
| pting | input-kcen | 14.3 ± 0.6 | 13.6 | 17.5 | 17.86 ± 4.40 |
| mattcl-py | input-kcen | 14.3 ± 0.6 | 13.4 | 17.6 | 17.86 ± 4.39 |
| mattcl-py | input-mattcl | 14.3 ± 0.6 | 13.4 | 17.6 | 17.88 ± 4.39 |
| pting | input-chancalan | 14.3 ± 0.7 | 13.4 | 17.2 | 17.89 ± 4.42 |
| mattcl-py | input-lanjian | 14.3 ± 0.5 | 13.4 | 17.7 | 17.90 ± 4.39 |
| pting | input-lanjian | 14.3 ± 0.6 | 13.5 | 17.6 | 17.91 ± 4.41 |
| mattcl-py | input-pting | 14.3 ± 0.6 | 13.3 | 17.7 | 17.92 ± 4.42 |
| mattcl-py | input-aspidites | 14.3 ± 0.7 | 13.3 | 17.9 | 17.92 ± 4.43 |
| pting | input-pting | 14.3 ± 0.7 | 13.4 | 18.3 | 17.95 ± 4.43 |
| mattcl-py | input-mikofo | 14.4 ± 0.6 | 13.4 | 17.4 | 18.02 ± 4.44 |
| pting | input-mattcl | 14.4 ± 1.6 | 13.3 | 33.8 | 18.03 ± 4.80 |
| mattcl-py | input-chancalan | 14.4 ± 1.5 | 13.3 | 34.5 | 18.04 ± 4.78 |
| pting | input-mikofo | 14.8 ± 4.2 | 13.2 | 52.7 | 18.51 ± 6.89 |
| chancalan | input-kcen | 14.8 ± 0.5 | 13.8 | 17.2 | 18.55 ± 4.54 |
| chancalan | input-chancalan | 14.9 ± 0.6 | 13.8 | 17.6 | 18.62 ± 4.57 |
| chancalan | input-aspidites | 14.9 ± 0.5 | 14.1 | 17.9 | 18.62 ± 4.55 |
| chancalan | input-mikofo | 14.9 ± 0.5 | 13.9 | 18.2 | 18.63 ± 4.57 |
| chancalan | input-mattcl | 14.9 ± 0.6 | 13.9 | 18.2 | 18.69 ± 4.60 |
| chancalan | input-lanjian | 15.0 ± 0.6 | 13.9 | 17.8 | 18.71 ± 4.60 |
| chancalan | input-pting | 15.0 ± 0.6 | 13.8 | 17.7 | 18.74 ± 4.61 |
| kcen | input-pting | 15.1 ± 0.5 | 14.1 | 18.2 | 18.92 ± 4.63 |
| kcen | input-lanjian | 15.2 ± 0.5 | 14.4 | 18.1 | 18.95 ± 4.64 |
| kcen | input-mikofo | 15.2 ± 0.6 | 14.1 | 18.2 | 18.99 ± 4.66 |
| kcen | input-mattcl | 15.2 ± 0.6 | 14.2 | 18.2 | 19.00 ± 4.66 |
| kcen | input-aspidites | 15.2 ± 0.5 | 14.4 | 17.9 | 19.04 ± 4.67 |
| kcen | input-chancalan | 15.2 ± 0.6 | 14.2 | 18.2 | 19.04 ± 4.68 |
| kcen | input-kcen | 15.3 ± 0.7 | 14.3 | 18.0 | 19.12 ± 4.71 |
| mikofo | input-aspidites | 30.0 ± 0.5 | 29.0 | 31.4 | 37.51 ± 9.12 |
| mikofo | input-chancalan | 30.0 ± 0.5 | 29.0 | 31.1 | 37.57 ± 9.13 |
| mikofo | input-mattcl | 30.0 ± 0.4 | 29.2 | 31.4 | 37.58 ± 9.13 |
| mikofo | input-mikofo | 30.0 ± 0.4 | 29.2 | 31.2 | 37.59 ± 9.13 |
| mikofo | input-lanjian | 30.1 ± 0.5 | 28.8 | 31.3 | 37.64 ± 9.15 |
| mikofo | input-kcen | 30.1 ± 0.4 | 29.4 | 31.7 | 37.66 ± 9.15 |
| mikofo | input-pting | 30.1 ± 0.4 | 29.2 | 31.4 | 37.67 ± 9.15 |


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