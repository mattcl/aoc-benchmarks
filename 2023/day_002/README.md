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
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 ± 0.29 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.29 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.3 | 1.03 ± 0.29 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.1 | 1.03 ± 0.28 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.6 | 1.03 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.29 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.7 | 1.05 ± 0.30 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.4 | 1.1 | 1.05 ± 0.26 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.2 | 1.1 | 1.06 ± 0.27 |
| lanjian | input-aspidites | 0.9 ± 0.1 | 0.2 | 1.3 | 1.07 ± 0.27 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.6 | 1.07 ± 0.29 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.4 | 1.1 | 1.08 ± 0.26 |
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.5 | 1.5 | 1.08 ± 0.29 |
| mattcl-ts | input-mattcl | 11.1 ± 0.4 | 10.0 | 12.2 | 12.94 ± 2.74 |
| mattcl-ts | input-chancalan | 11.1 ± 0.4 | 9.9 | 11.8 | 12.95 ± 2.74 |
| mattcl-ts | input-aspidites | 11.1 ± 0.4 | 10.0 | 12.7 | 12.97 ± 2.75 |
| mattcl-ts | input-lanjian | 11.1 ± 0.4 | 10.0 | 12.3 | 12.97 ± 2.74 |
| mattcl-ts | input-mikofo | 11.1 ± 0.4 | 9.9 | 11.8 | 12.99 ± 2.75 |
| mattcl-ts | input-kcen | 11.1 ± 0.4 | 10.0 | 11.9 | 13.01 ± 2.75 |
| mattcl-ts | input-pting | 11.2 ± 0.4 | 9.7 | 12.3 | 13.04 ± 2.76 |
| mikofo | input-mikofo | 11.3 ± 0.3 | 10.3 | 12.3 | 13.19 ± 2.78 |
| mikofo | input-pting | 11.3 ± 0.3 | 10.3 | 12.5 | 13.21 ± 2.79 |
| mikofo | input-mattcl | 11.3 ± 0.3 | 10.3 | 12.4 | 13.21 ± 2.78 |
| mikofo | input-aspidites | 11.3 ± 0.3 | 10.3 | 12.3 | 13.24 ± 2.79 |
| mikofo | input-lanjian | 11.3 ± 0.3 | 10.4 | 12.7 | 13.25 ± 2.79 |
| mikofo | input-chancalan | 11.4 ± 0.3 | 10.6 | 12.2 | 13.27 ± 2.79 |
| mikofo | input-kcen | 11.4 ± 0.3 | 10.4 | 12.7 | 13.28 ± 2.80 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.5 | 14.8 | 14.84 ± 3.15 |
| aspidites | input-pting | 12.7 ± 0.5 | 11.6 | 14.8 | 14.84 ± 3.16 |
| aspidites | input-mikofo | 12.7 ± 0.5 | 11.4 | 14.3 | 14.88 ± 3.16 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.6 | 14.3 | 14.92 ± 3.17 |
| aspidites | input-lanjian | 12.8 ± 0.4 | 11.8 | 14.1 | 14.95 ± 3.17 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.9 | 14.2 | 14.96 ± 3.17 |
| aspidites | input-mattcl | 12.9 ± 3.2 | 11.1 | 47.3 | 15.07 ± 4.86 |
| pting | input-chancalan | 14.5 ± 0.6 | 13.6 | 17.6 | 16.94 ± 3.60 |
| pting | input-pting | 14.5 ± 0.7 | 13.2 | 17.9 | 16.94 ± 3.63 |
| pting | input-lanjian | 14.5 ± 0.5 | 13.5 | 17.6 | 16.96 ± 3.60 |
| mattcl-py | input-mikofo | 14.5 ± 0.6 | 13.3 | 17.3 | 16.97 ± 3.60 |
| pting | input-mattcl | 14.5 ± 0.7 | 13.5 | 18.1 | 16.98 ± 3.63 |
| pting | input-kcen | 14.6 ± 0.6 | 13.2 | 17.2 | 17.02 ± 3.62 |
| mattcl-py | input-lanjian | 14.6 ± 0.5 | 13.3 | 17.3 | 17.03 ± 3.61 |
| mattcl-py | input-mattcl | 14.6 ± 0.6 | 13.4 | 17.8 | 17.04 ± 3.62 |
| mattcl-py | input-chancalan | 14.6 ± 0.7 | 13.4 | 18.3 | 17.06 ± 3.65 |
| mattcl-py | input-pting | 14.6 ± 0.6 | 13.7 | 17.3 | 17.07 ± 3.63 |
| pting | input-aspidites | 14.6 ± 0.7 | 13.7 | 17.4 | 17.08 ± 3.66 |
| mattcl-py | input-aspidites | 14.6 ± 0.7 | 13.6 | 18.3 | 17.09 ± 3.65 |
| mattcl-py | input-kcen | 14.7 ± 1.4 | 13.7 | 33.6 | 17.22 ± 3.96 |
| pting | input-mikofo | 15.0 ± 3.8 | 13.5 | 57.7 | 17.48 ± 5.78 |
| chancalan | input-lanjian | 15.1 ± 0.6 | 13.8 | 17.9 | 17.59 ± 3.73 |
| chancalan | input-mikofo | 15.1 ± 0.5 | 14.0 | 18.1 | 17.60 ± 3.72 |
| chancalan | input-kcen | 15.1 ± 0.6 | 13.9 | 18.9 | 17.63 ± 3.74 |
| chancalan | input-chancalan | 15.1 ± 0.7 | 14.0 | 18.2 | 17.66 ± 3.77 |
| chancalan | input-mattcl | 15.1 ± 0.6 | 14.1 | 18.9 | 17.68 ± 3.76 |
| chancalan | input-pting | 15.2 ± 0.6 | 14.2 | 18.3 | 17.70 ± 3.77 |
| kcen | input-lanjian | 15.3 ± 0.6 | 14.3 | 18.3 | 17.81 ± 3.78 |
| chancalan | input-aspidites | 15.4 ± 2.4 | 14.2 | 47.1 | 17.96 ± 4.67 |
| kcen | input-aspidites | 15.4 ± 0.6 | 14.1 | 18.2 | 17.99 ± 3.83 |
| kcen | input-mattcl | 15.4 ± 0.7 | 14.4 | 18.8 | 18.01 ± 3.84 |
| kcen | input-mikofo | 15.4 ± 0.6 | 14.4 | 18.0 | 18.02 ± 3.83 |
| kcen | input-pting | 15.5 ± 0.6 | 14.1 | 18.3 | 18.06 ± 3.85 |
| kcen | input-kcen | 15.5 ± 1.6 | 14.6 | 36.5 | 18.10 ± 4.23 |
| kcen | input-chancalan | 15.5 ± 0.7 | 14.6 | 19.0 | 18.12 ± 3.88 |


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