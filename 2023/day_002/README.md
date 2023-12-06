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
| mattcl | input-lanjian | 0.6 ± 0.2 | 0.0 | 0.8 | 1.00 |
| lanjian | input-chancalan | 0.6 ± 0.3 | 0.0 | 3.3 | 1.01 ± 0.60 |
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.0 | 0.8 | 1.02 ± 0.46 |
| mattcl | input-pting | 0.6 ± 0.2 | 0.0 | 0.8 | 1.03 ± 0.45 |
| mattcl | input-chancalan | 0.6 ± 0.2 | 0.0 | 0.8 | 1.05 ± 0.44 |
| mattcl | input-kcen | 0.6 ± 0.2 | 0.0 | 1.2 | 1.06 ± 0.44 |
| mattcl | input-aspidites | 0.6 ± 0.1 | 0.0 | 1.1 | 1.07 ± 0.41 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.2 | 1.10 ± 0.47 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.0 | 1.0 | 1.12 ± 0.45 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.1 | 1.12 ± 0.45 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 0.8 | 1.13 ± 0.44 |
| lanjian | input-aspidites | 0.7 ± 0.1 | 0.2 | 1.2 | 1.19 ± 0.43 |
| mattcl-ts | input-mattcl | 10.0 ± 0.4 | 8.8 | 10.8 | 16.83 ± 5.34 |
| mattcl-ts | input-chancalan | 10.0 ± 0.4 | 9.0 | 11.2 | 16.89 ± 5.37 |
| mattcl-ts | input-pting | 10.1 ± 0.4 | 9.0 | 11.4 | 16.90 ± 5.37 |
| mattcl-ts | input-lanjian | 10.1 ± 0.4 | 9.0 | 11.6 | 16.94 ± 5.38 |
| mattcl-ts | input-aspidites | 10.1 ± 0.3 | 9.1 | 10.8 | 16.95 ± 5.37 |
| mattcl-ts | input-kcen | 10.1 ± 0.4 | 9.1 | 11.4 | 16.96 ± 5.38 |
| aspidites | input-lanjian | 12.6 ± 0.5 | 11.6 | 13.7 | 21.14 ± 6.71 |
| aspidites | input-chancalan | 12.6 ± 0.4 | 11.6 | 14.3 | 21.19 ± 6.72 |
| aspidites | input-pting | 12.6 ± 0.5 | 11.7 | 14.2 | 21.25 ± 6.75 |
| aspidites | input-aspidites | 12.7 ± 0.5 | 11.8 | 14.9 | 21.34 ± 6.78 |
| aspidites | input-kcen | 12.7 ± 0.4 | 11.8 | 13.9 | 21.35 ± 6.77 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.7 | 14.9 | 21.41 ± 6.80 |
| pting | input-aspidites | 14.0 ± 0.6 | 13.3 | 17.2 | 23.62 ± 7.51 |
| pting | input-pting | 14.1 ± 0.4 | 13.2 | 17.6 | 23.64 ± 7.49 |
| pting | input-lanjian | 14.1 ± 0.6 | 13.2 | 17.9 | 23.71 ± 7.55 |
| mattcl-py | input-lanjian | 14.1 ± 0.6 | 13.3 | 18.0 | 23.74 ± 7.54 |
| mattcl-py | input-mattcl | 14.1 ± 0.4 | 13.4 | 17.3 | 23.79 ± 7.54 |
| pting | input-chancalan | 14.2 ± 0.6 | 13.0 | 17.2 | 23.80 ± 7.58 |
| mattcl-py | input-aspidites | 14.2 ± 0.4 | 13.3 | 17.0 | 23.81 ± 7.54 |
| pting | input-kcen | 14.2 ± 0.5 | 13.3 | 17.0 | 23.85 ± 7.56 |
| mattcl-py | input-kcen | 14.3 ± 0.7 | 13.1 | 17.4 | 23.97 ± 7.65 |
| pting | input-mattcl | 14.3 ± 2.1 | 13.2 | 41.9 | 24.00 ± 8.33 |
| mattcl-py | input-pting | 14.3 ± 0.7 | 13.3 | 18.1 | 24.05 ± 7.67 |
| mattcl-py | input-chancalan | 14.6 ± 4.0 | 13.1 | 61.8 | 24.54 ± 10.29 |
| chancalan | input-mattcl | 14.8 ± 0.5 | 13.9 | 17.6 | 24.82 ± 7.87 |
| chancalan | input-chancalan | 14.8 ± 0.7 | 13.7 | 17.9 | 24.87 ± 7.93 |
| chancalan | input-pting | 14.8 ± 0.5 | 14.2 | 18.2 | 24.94 ± 7.90 |
| chancalan | input-lanjian | 14.8 ± 0.7 | 13.6 | 18.0 | 24.96 ± 7.96 |
| chancalan | input-kcen | 14.9 ± 0.6 | 13.7 | 17.9 | 24.98 ± 7.95 |
| chancalan | input-aspidites | 14.9 ± 0.8 | 13.8 | 18.3 | 25.07 ± 8.01 |
| kcen | input-lanjian | 15.0 ± 0.4 | 14.0 | 17.1 | 25.23 ± 7.98 |
| kcen | input-mattcl | 15.0 ± 0.6 | 14.0 | 18.3 | 25.27 ± 8.03 |
| kcen | input-chancalan | 15.0 ± 0.7 | 14.0 | 18.3 | 25.28 ± 8.05 |
| kcen | input-pting | 15.1 ± 0.6 | 13.9 | 18.2 | 25.33 ± 8.05 |
| kcen | input-kcen | 15.1 ± 0.5 | 14.3 | 18.1 | 25.39 ± 8.06 |
| kcen | input-aspidites | 15.1 ± 0.6 | 14.3 | 18.4 | 25.42 ± 8.08 |
| mikofo | input-chancalan | 29.8 ± 0.5 | 28.9 | 31.4 | 50.16 ± 15.84 |
| mikofo | input-pting | 29.9 ± 0.4 | 28.7 | 31.2 | 50.22 ± 15.85 |
| mikofo | input-lanjian | 29.9 ± 0.4 | 29.1 | 31.1 | 50.27 ± 15.87 |
| mikofo | input-kcen | 29.9 ± 0.5 | 28.8 | 31.6 | 50.30 ± 15.89 |
| mikofo | input-aspidites | 29.9 ± 0.5 | 28.8 | 31.6 | 50.32 ± 15.89 |
| mikofo | input-mattcl | 30.3 ± 3.7 | 28.9 | 66.7 | 50.94 ± 17.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|