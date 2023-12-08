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
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.35 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.04 ± 0.34 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.3 | 1.05 ± 0.33 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.6 | 1.06 ± 0.37 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.2 | 1.06 ± 0.32 |
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.35 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.06 ± 0.34 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.07 ± 0.34 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.09 ± 0.34 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.09 ± 0.33 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.10 ± 0.34 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.2 | 1.3 | 1.10 ± 0.32 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.3 | 1.1 | 1.11 ± 0.33 |
| mattcl-ts | input-aspidites | 10.5 ± 0.4 | 9.5 | 11.4 | 12.50 ± 3.17 |
| mattcl-ts | input-lanjian | 10.5 ± 0.4 | 9.6 | 11.4 | 12.53 ± 3.17 |
| mattcl-ts | input-kcen | 10.5 ± 0.3 | 9.4 | 11.5 | 12.57 ± 3.18 |
| mattcl-ts | input-mikofo | 10.5 ± 0.4 | 9.5 | 11.6 | 12.57 ± 3.18 |
| mattcl-ts | input-chancalan | 10.5 ± 0.4 | 9.2 | 11.7 | 12.58 ± 3.18 |
| mattcl-ts | input-mattcl | 10.5 ± 0.3 | 9.6 | 11.4 | 12.59 ± 3.18 |
| mattcl-ts | input-pting | 10.6 ± 0.3 | 9.4 | 11.6 | 12.63 ± 3.19 |
| mikofo | input-mattcl | 11.2 ± 0.4 | 10.2 | 12.0 | 13.39 ± 3.39 |
| mikofo | input-chancalan | 11.3 ± 0.4 | 10.4 | 12.4 | 13.46 ± 3.40 |
| mikofo | input-mikofo | 11.3 ± 0.4 | 10.3 | 12.3 | 13.47 ± 3.40 |
| mikofo | input-aspidites | 11.3 ± 0.3 | 10.4 | 12.2 | 13.49 ± 3.41 |
| mikofo | input-pting | 11.3 ± 0.4 | 10.2 | 12.4 | 13.51 ± 3.42 |
| mikofo | input-lanjian | 11.3 ± 0.4 | 10.4 | 12.4 | 13.53 ± 3.42 |
| mikofo | input-kcen | 12.1 ± 5.9 | 10.4 | 66.1 | 14.41 ± 7.90 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.8 | 14.2 | 15.17 ± 3.84 |
| aspidites | input-mikofo | 12.8 ± 0.4 | 11.7 | 14.0 | 15.28 ± 3.87 |
| aspidites | input-pting | 12.8 ± 0.4 | 12.0 | 13.9 | 15.30 ± 3.87 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.8 | 14.1 | 15.35 ± 3.89 |
| aspidites | input-mattcl | 12.9 ± 0.5 | 11.6 | 14.5 | 15.37 ± 3.89 |
| aspidites | input-chancalan | 12.9 ± 0.5 | 11.9 | 14.2 | 15.38 ± 3.90 |
| aspidites | input-kcen | 12.9 ± 0.5 | 11.8 | 14.5 | 15.38 ± 3.90 |
| mattcl-py | input-mattcl | 14.3 ± 0.5 | 13.4 | 16.9 | 17.15 ± 4.34 |
| pting | input-mattcl | 14.4 ± 0.6 | 13.6 | 18.1 | 17.17 ± 4.36 |
| pting | input-lanjian | 14.4 ± 0.7 | 13.4 | 17.7 | 17.18 ± 4.39 |
| mattcl-py | input-aspidites | 14.4 ± 0.4 | 13.5 | 17.0 | 17.21 ± 4.34 |
| mattcl-py | input-lanjian | 14.4 ± 0.6 | 13.6 | 17.6 | 17.22 ± 4.37 |
| pting | input-pting | 14.4 ± 0.6 | 13.4 | 18.0 | 17.22 ± 4.38 |
| mattcl-py | input-kcen | 14.4 ± 0.6 | 13.3 | 17.7 | 17.22 ± 4.37 |
| pting | input-mikofo | 14.4 ± 0.7 | 13.2 | 17.6 | 17.22 ± 4.39 |
| mattcl-py | input-pting | 14.4 ± 0.5 | 13.3 | 17.2 | 17.23 ± 4.36 |
| mattcl-py | input-chancalan | 14.4 ± 0.6 | 13.5 | 18.0 | 17.24 ± 4.38 |
| pting | input-aspidites | 14.4 ± 0.7 | 13.5 | 17.5 | 17.25 ± 4.40 |
| mattcl-py | input-mikofo | 14.4 ± 0.6 | 13.7 | 17.6 | 17.28 ± 4.40 |
| pting | input-chancalan | 14.5 ± 0.7 | 13.2 | 18.0 | 17.29 ± 4.42 |
| pting | input-kcen | 14.6 ± 2.5 | 13.5 | 48.3 | 17.48 ± 5.29 |
| chancalan | input-mikofo | 15.0 ± 0.6 | 14.0 | 18.4 | 17.92 ± 4.54 |
| chancalan | input-chancalan | 15.0 ± 0.7 | 14.1 | 18.5 | 17.93 ± 4.56 |
| chancalan | input-lanjian | 15.0 ± 0.6 | 13.9 | 18.5 | 17.94 ± 4.56 |
| chancalan | input-mattcl | 15.0 ± 0.5 | 14.0 | 18.1 | 17.94 ± 4.54 |
| chancalan | input-aspidites | 15.0 ± 0.6 | 14.0 | 18.2 | 17.99 ± 4.58 |
| chancalan | input-pting | 15.2 ± 1.9 | 13.9 | 41.1 | 18.15 ± 5.10 |
| chancalan | input-kcen | 15.2 ± 2.7 | 14.0 | 52.7 | 18.19 ± 5.61 |
| kcen | input-kcen | 15.2 ± 0.5 | 14.3 | 18.2 | 18.21 ± 4.61 |
| kcen | input-pting | 15.3 ± 0.5 | 14.5 | 18.3 | 18.25 ± 4.62 |
| kcen | input-aspidites | 15.3 ± 0.6 | 14.3 | 18.9 | 18.27 ± 4.64 |
| kcen | input-mattcl | 15.3 ± 0.6 | 14.2 | 18.3 | 18.27 ± 4.64 |
| kcen | input-lanjian | 15.3 ± 0.7 | 14.2 | 18.2 | 18.28 ± 4.66 |
| kcen | input-chancalan | 15.3 ± 0.6 | 14.3 | 18.7 | 18.30 ± 4.65 |
| kcen | input-mikofo | 15.3 ± 0.7 | 14.2 | 18.8 | 18.32 ± 4.67 |


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