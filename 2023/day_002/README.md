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
| mattcl | input-aspidites | 0.6 ± 0.2 | 0.0 | 1.0 | 1.00 |
| mattcl | input-pting | 0.6 ± 0.2 | 0.0 | 1.3 | 1.03 ± 0.47 |
| mattcl | input-mattcl | 0.6 ± 0.2 | 0.0 | 1.5 | 1.04 ± 0.47 |
| mattcl | input-chancalan | 0.7 ± 0.1 | 0.0 | 0.9 | 1.07 ± 0.43 |
| mattcl | input-kcen | 0.7 ± 0.1 | 0.0 | 1.0 | 1.08 ± 0.43 |
| lanjian | input-aspidites | 0.7 ± 0.2 | 0.0 | 1.1 | 1.09 ± 0.49 |
| mattcl | input-lanjian | 0.7 ± 0.1 | 0.0 | 1.0 | 1.11 ± 0.44 |
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.1 | 0.9 | 1.12 ± 0.45 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.1 | 1.14 ± 0.46 |
| lanjian | input-pting | 0.7 ± 0.1 | 0.3 | 0.9 | 1.18 ± 0.44 |
| lanjian | input-mattcl | 0.7 ± 0.1 | 0.4 | 0.9 | 1.19 ± 0.43 |
| lanjian | input-kcen | 0.7 ± 0.1 | 0.4 | 0.9 | 1.21 ± 0.43 |
| mattcl-ts | input-mattcl | 10.1 ± 0.3 | 9.0 | 10.9 | 16.25 ± 5.48 |
| mattcl-ts | input-aspidites | 10.1 ± 0.4 | 9.0 | 11.3 | 16.30 ± 5.51 |
| mattcl-ts | input-pting | 10.1 ± 0.4 | 9.1 | 11.5 | 16.34 ± 5.52 |
| mattcl-ts | input-kcen | 10.1 ± 0.3 | 8.8 | 11.0 | 16.35 ± 5.52 |
| mattcl-ts | input-chancalan | 10.1 ± 0.3 | 8.9 | 10.9 | 16.38 ± 5.53 |
| mattcl-ts | input-lanjian | 10.1 ± 0.3 | 9.1 | 11.4 | 16.38 ± 5.53 |
| aspidites | input-lanjian | 12.5 ± 0.5 | 11.7 | 14.4 | 20.26 ± 6.84 |
| aspidites | input-aspidites | 12.6 ± 0.4 | 11.6 | 13.9 | 20.36 ± 6.88 |
| aspidites | input-pting | 12.7 ± 0.5 | 11.5 | 14.0 | 20.45 ± 6.92 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.7 | 14.5 | 20.47 ± 6.92 |
| aspidites | input-kcen | 12.7 ± 0.4 | 11.7 | 14.1 | 20.48 ± 6.91 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.7 | 13.9 | 20.51 ± 6.93 |
| pting | input-aspidites | 14.1 ± 0.5 | 13.2 | 17.1 | 22.78 ± 7.69 |
| mattcl-py | input-chancalan | 14.1 ± 0.4 | 13.3 | 17.0 | 22.85 ± 7.71 |
| pting | input-mattcl | 14.1 ± 0.6 | 13.1 | 17.0 | 22.86 ± 7.73 |
| mattcl-py | input-mattcl | 14.1 ± 0.6 | 13.5 | 18.3 | 22.86 ± 7.73 |
| pting | input-kcen | 14.1 ± 0.6 | 13.3 | 17.6 | 22.87 ± 7.74 |
| mattcl-py | input-aspidites | 14.2 ± 0.6 | 13.2 | 17.8 | 22.89 ± 7.75 |
| pting | input-pting | 14.2 ± 0.6 | 13.1 | 17.7 | 22.89 ± 7.75 |
| pting | input-chancalan | 14.2 ± 0.6 | 13.2 | 17.1 | 22.89 ± 7.75 |
| pting | input-lanjian | 14.2 ± 0.7 | 13.3 | 17.6 | 22.98 ± 7.81 |
| mattcl-py | input-pting | 14.2 ± 0.6 | 13.2 | 17.2 | 22.99 ± 7.79 |
| mattcl-py | input-kcen | 14.2 ± 0.7 | 13.3 | 17.5 | 22.99 ± 7.80 |
| mattcl-py | input-lanjian | 14.3 ± 0.7 | 13.2 | 17.8 | 23.05 ± 7.83 |
| chancalan | input-aspidites | 14.7 ± 0.6 | 13.8 | 17.8 | 23.81 ± 8.05 |
| chancalan | input-kcen | 14.8 ± 0.5 | 13.8 | 18.4 | 23.85 ± 8.05 |
| chancalan | input-mattcl | 14.8 ± 0.6 | 13.8 | 18.2 | 23.85 ± 8.07 |
| chancalan | input-chancalan | 14.8 ± 0.7 | 13.6 | 18.0 | 23.95 ± 8.13 |
| chancalan | input-pting | 14.8 ± 0.6 | 13.8 | 17.6 | 23.98 ± 8.11 |
| kcen | input-mattcl | 15.0 ± 0.4 | 14.0 | 17.5 | 24.31 ± 8.20 |
| kcen | input-kcen | 15.1 ± 0.5 | 14.4 | 18.3 | 24.38 ± 8.23 |
| kcen | input-aspidites | 15.1 ± 0.5 | 14.0 | 18.0 | 24.40 ± 8.24 |
| kcen | input-pting | 15.1 ± 0.6 | 14.2 | 18.3 | 24.41 ± 8.26 |
| kcen | input-chancalan | 15.1 ± 0.6 | 14.0 | 17.9 | 24.43 ± 8.26 |
| kcen | input-lanjian | 15.3 ± 2.6 | 14.2 | 50.8 | 24.68 ± 9.30 |
| chancalan | input-lanjian | 15.4 ± 5.6 | 13.7 | 70.5 | 24.86 ± 12.27 |
| mikofo | input-aspidites | 29.8 ± 0.5 | 29.0 | 31.3 | 48.23 ± 16.22 |
| mikofo | input-mattcl | 30.0 ± 0.4 | 28.9 | 31.3 | 48.44 ± 16.29 |
| mikofo | input-pting | 30.0 ± 0.4 | 28.8 | 31.3 | 48.46 ± 16.29 |
| mikofo | input-lanjian | 30.0 ± 0.5 | 28.9 | 31.5 | 48.48 ± 16.30 |
| mikofo | input-chancalan | 30.0 ± 0.4 | 29.0 | 31.1 | 48.50 ± 16.30 |
| mikofo | input-kcen | 30.1 ± 0.5 | 29.1 | 32.1 | 48.65 ± 16.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>2593</pre>|<pre>54699</pre>|
|input-chancalan|<pre>2617</pre>|<pre>59795</pre>|
|input-kcen|<pre>3099</pre>|<pre>72970</pre>|
|input-lanjian|<pre>2256</pre>|<pre>74229</pre>|
|input-mattcl|<pre>2476</pre>|<pre>54911</pre>|
|input-pting|<pre>2551</pre>|<pre>62811</pre>|