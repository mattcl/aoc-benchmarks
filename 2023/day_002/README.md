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
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.7 | 1.00 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.4 | 1.00 ± 0.28 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.28 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.2 | 1.01 ± 0.26 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.2 | 1.01 ± 0.28 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.2 | 1.01 ± 0.27 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.5 | 1.02 ± 0.28 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.5 | 1.2 | 1.03 ± 0.26 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.8 | 1.05 ± 0.30 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.7 | 1.06 ± 0.27 |
| mattcl-ts | input-kcen | 11.2 ± 0.4 | 10.0 | 11.9 | 11.46 ± 2.34 |
| mattcl-ts | input-mattcl | 11.2 ± 0.4 | 9.9 | 12.1 | 11.46 ± 2.35 |
| mattcl-ts | input-chancalan | 11.2 ± 0.4 | 10.0 | 12.7 | 11.49 ± 2.35 |
| mattcl-ts | input-lanjian | 11.2 ± 0.4 | 10.1 | 12.0 | 11.49 ± 2.35 |
| mattcl-ts | input-aspidites | 11.3 ± 0.4 | 10.2 | 12.2 | 11.56 ± 2.36 |
| mikofo | input-kcen | 11.4 ± 0.3 | 10.4 | 12.6 | 11.72 ± 2.39 |
| mikofo | input-aspidites | 11.4 ± 0.3 | 10.5 | 12.4 | 11.72 ± 2.39 |
| mikofo | input-lanjian | 11.4 ± 0.3 | 10.4 | 13.0 | 11.73 ± 2.39 |
| mikofo | input-chancalan | 11.5 ± 0.4 | 10.6 | 13.2 | 11.79 ± 2.40 |
| mikofo | input-mattcl | 11.9 ± 4.3 | 10.5 | 66.0 | 12.17 ± 5.09 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.9 | 14.0 | 13.13 ± 2.70 |
| aspidites | input-mattcl | 12.8 ± 0.5 | 11.6 | 14.1 | 13.15 ± 2.70 |
| aspidites | input-kcen | 12.9 ± 0.5 | 11.7 | 14.2 | 13.19 ± 2.70 |
| aspidites | input-aspidites | 12.9 ± 0.5 | 11.8 | 15.3 | 13.24 ± 2.73 |
| aspidites | input-chancalan | 12.9 ± 3.0 | 11.1 | 54.0 | 13.24 ± 4.05 |
| mattcl-py | input-mattcl | 14.6 ± 0.6 | 13.7 | 18.0 | 15.00 ± 3.08 |
| pting | input-aspidites | 14.6 ± 0.5 | 13.6 | 17.5 | 15.01 ± 3.08 |
| pting | input-lanjian | 14.6 ± 0.5 | 13.7 | 17.3 | 15.02 ± 3.07 |
| mattcl-py | input-lanjian | 14.7 ± 0.6 | 13.5 | 18.4 | 15.03 ± 3.10 |
| mattcl-py | input-chancalan | 14.7 ± 0.5 | 13.8 | 18.2 | 15.03 ± 3.08 |
| pting | input-kcen | 14.7 ± 0.6 | 13.9 | 17.6 | 15.05 ± 3.09 |
| pting | input-mattcl | 14.7 ± 0.7 | 13.4 | 17.8 | 15.10 ± 3.12 |
| mattcl-py | input-aspidites | 14.7 ± 0.6 | 13.7 | 18.0 | 15.10 ± 3.11 |
| pting | input-chancalan | 14.8 ± 0.6 | 13.8 | 18.3 | 15.15 ± 3.13 |
| mattcl-py | input-kcen | 14.9 ± 1.6 | 13.7 | 35.7 | 15.27 ± 3.49 |
| chancalan | input-lanjian | 15.2 ± 0.5 | 14.0 | 17.8 | 15.63 ± 3.20 |
| chancalan | input-mattcl | 15.3 ± 0.6 | 14.2 | 17.8 | 15.66 ± 3.22 |
| chancalan | input-kcen | 15.3 ± 0.7 | 14.0 | 18.3 | 15.67 ± 3.23 |
| chancalan | input-aspidites | 15.3 ± 0.6 | 14.2 | 18.2 | 15.67 ± 3.22 |
| kcen | input-mattcl | 15.5 ± 0.5 | 14.7 | 18.5 | 15.87 ± 3.25 |
| kcen | input-chancalan | 15.5 ± 0.6 | 14.2 | 19.0 | 15.89 ± 3.26 |
| kcen | input-lanjian | 15.5 ± 0.6 | 14.3 | 19.0 | 15.92 ± 3.26 |
| kcen | input-aspidites | 15.7 ± 0.7 | 14.3 | 18.4 | 16.05 ± 3.32 |
| chancalan | input-chancalan | 15.7 ± 5.1 | 13.8 | 82.4 | 16.05 ± 6.11 |
| kcen | input-kcen | 15.7 ± 0.6 | 14.9 | 18.6 | 16.08 ± 3.31 |


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