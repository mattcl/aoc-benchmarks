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
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.31 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.30 |
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.3 | 1.2 | 1.03 ± 0.30 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.1 | 1.4 | 1.03 ± 0.30 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.5 | 1.1 | 1.04 ± 0.29 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.31 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.7 | 1.06 ± 0.34 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.06 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.1 | 1.08 ± 0.28 |
| mattcl-ts | input-mattcl | 11.0 ± 0.4 | 9.7 | 11.8 | 12.69 ± 2.92 |
| mattcl-ts | input-lanjian | 11.0 ± 0.5 | 9.8 | 12.7 | 12.70 ± 2.93 |
| mattcl-ts | input-chancalan | 11.1 ± 0.4 | 10.1 | 12.1 | 12.73 ± 2.93 |
| mattcl-ts | input-aspidites | 11.1 ± 0.4 | 9.7 | 12.4 | 12.79 ± 2.94 |
| mattcl-ts | input-kcen | 11.1 ± 0.4 | 10.0 | 12.1 | 12.80 ± 2.94 |
| mikofo | input-lanjian | 11.3 ± 0.4 | 10.2 | 12.5 | 12.99 ± 2.98 |
| mikofo | input-mattcl | 11.3 ± 0.3 | 10.3 | 12.1 | 13.00 ± 2.98 |
| mikofo | input-chancalan | 11.3 ± 0.3 | 10.3 | 12.9 | 13.02 ± 2.98 |
| mikofo | input-kcen | 11.4 ± 0.5 | 10.2 | 15.7 | 13.06 ± 3.02 |
| mikofo | input-aspidites | 11.4 ± 0.3 | 10.7 | 12.3 | 13.10 ± 2.99 |
| aspidites | input-chancalan | 12.6 ± 0.5 | 11.3 | 14.6 | 14.47 ± 3.34 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.6 | 14.0 | 14.63 ± 3.38 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.7 | 14.0 | 14.68 ± 3.38 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.8 | 14.2 | 14.68 ± 3.39 |
| aspidites | input-mattcl | 13.0 ± 4.1 | 11.0 | 45.6 | 14.95 ± 5.84 |
| pting | input-chancalan | 14.5 ± 0.6 | 13.2 | 17.6 | 16.66 ± 3.84 |
| pting | input-lanjian | 14.6 ± 0.6 | 13.2 | 17.3 | 16.74 ± 3.86 |
| pting | input-aspidites | 14.6 ± 0.5 | 13.6 | 17.0 | 16.77 ± 3.85 |
| mattcl-py | input-chancalan | 14.6 ± 0.7 | 13.3 | 18.1 | 16.79 ± 3.89 |
| mattcl-py | input-mattcl | 14.6 ± 0.7 | 13.3 | 18.2 | 16.81 ± 3.90 |
| pting | input-mattcl | 14.7 ± 0.8 | 13.6 | 18.3 | 16.86 ± 3.93 |
| mattcl-py | input-aspidites | 14.7 ± 0.7 | 13.6 | 18.2 | 16.87 ± 3.91 |
| mattcl-py | input-kcen | 14.7 ± 0.8 | 13.4 | 18.1 | 16.89 ± 3.93 |
| mattcl-py | input-lanjian | 14.7 ± 0.7 | 13.7 | 18.4 | 16.92 ± 3.92 |
| pting | input-kcen | 14.8 ± 2.4 | 13.5 | 47.6 | 17.01 ± 4.76 |
| chancalan | input-lanjian | 15.1 ± 0.5 | 13.9 | 18.2 | 17.41 ± 4.01 |
| chancalan | input-mattcl | 15.2 ± 0.6 | 14.1 | 18.6 | 17.46 ± 4.03 |
| chancalan | input-aspidites | 15.2 ± 0.7 | 13.9 | 18.6 | 17.47 ± 4.05 |
| chancalan | input-kcen | 15.2 ± 0.7 | 14.0 | 18.2 | 17.51 ± 4.06 |
| chancalan | input-chancalan | 15.3 ± 0.8 | 14.0 | 19.0 | 17.55 ± 4.10 |
| kcen | input-mattcl | 15.4 ± 0.6 | 14.5 | 18.6 | 17.67 ± 4.07 |
| kcen | input-chancalan | 15.4 ± 0.6 | 14.2 | 18.9 | 17.71 ± 4.09 |
| kcen | input-lanjian | 15.4 ± 0.6 | 14.1 | 18.4 | 17.73 ± 4.10 |
| kcen | input-aspidites | 15.5 ± 0.7 | 14.6 | 18.6 | 17.85 ± 4.13 |
| kcen | input-kcen | 15.5 ± 0.7 | 14.6 | 18.5 | 17.88 ± 4.14 |


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