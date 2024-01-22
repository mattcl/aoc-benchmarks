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
| mattcl | input-aspidites | 0.8 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.1 | 1.4 | 1.02 ± 0.33 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.3 | 1.03 ± 0.32 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.32 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.30 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.30 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.32 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.6 | 1.08 ± 0.32 |
| mattcl-ts | input-mattcl | 11.0 ± 0.4 | 10.1 | 11.8 | 13.09 ± 2.86 |
| mattcl-ts | input-aspidites | 11.0 ± 0.4 | 9.9 | 12.0 | 13.11 ± 2.87 |
| mattcl-ts | input-chancalan | 11.0 ± 0.4 | 10.0 | 12.0 | 13.16 ± 2.87 |
| mattcl-ts | input-kcen | 11.1 ± 0.4 | 10.0 | 11.9 | 13.17 ± 2.88 |
| mattcl-ts | input-lanjian | 11.1 ± 0.4 | 9.9 | 11.9 | 13.17 ± 2.88 |
| mikofo | input-kcen | 11.2 ± 0.3 | 10.3 | 12.4 | 13.35 ± 2.91 |
| mikofo | input-chancalan | 11.2 ± 0.4 | 10.1 | 12.9 | 13.37 ± 2.92 |
| mikofo | input-aspidites | 11.2 ± 0.4 | 10.1 | 12.6 | 13.39 ± 2.93 |
| mikofo | input-mattcl | 11.3 ± 0.3 | 10.3 | 12.3 | 13.42 ± 2.92 |
| mikofo | input-lanjian | 11.3 ± 0.3 | 10.5 | 12.3 | 13.45 ± 2.93 |
| aspidites | input-lanjian | 12.6 ± 0.5 | 11.7 | 14.0 | 15.01 ± 3.29 |
| aspidites | input-aspidites | 12.6 ± 0.5 | 11.8 | 14.0 | 15.07 ± 3.30 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.5 | 14.5 | 15.13 ± 3.32 |
| aspidites | input-kcen | 12.7 ± 0.5 | 11.6 | 14.9 | 15.18 ± 3.34 |
| aspidites | input-mattcl | 12.8 ± 0.4 | 11.7 | 14.1 | 15.26 ± 3.33 |
| pting | input-kcen | 14.4 ± 0.5 | 13.4 | 17.3 | 17.20 ± 3.76 |
| pting | input-aspidites | 14.5 ± 0.6 | 13.2 | 18.2 | 17.24 ± 3.78 |
| mattcl-py | input-mattcl | 14.5 ± 0.7 | 13.3 | 17.4 | 17.32 ± 3.82 |
| pting | input-lanjian | 14.5 ± 0.5 | 13.6 | 18.2 | 17.32 ± 3.79 |
| mattcl-py | input-chancalan | 14.6 ± 0.6 | 13.7 | 17.4 | 17.34 ± 3.81 |
| pting | input-chancalan | 14.6 ± 0.6 | 13.7 | 17.6 | 17.35 ± 3.81 |
| mattcl-py | input-kcen | 14.6 ± 0.7 | 13.6 | 18.0 | 17.38 ± 3.84 |
| pting | input-mattcl | 14.6 ± 0.7 | 13.6 | 17.7 | 17.38 ± 3.84 |
| mattcl-py | input-aspidites | 14.6 ± 0.6 | 13.4 | 17.3 | 17.41 ± 3.83 |
| mattcl-py | input-lanjian | 14.6 ± 0.7 | 13.6 | 18.2 | 17.45 ± 3.85 |
| chancalan | input-chancalan | 15.1 ± 0.6 | 14.0 | 18.3 | 17.94 ± 3.93 |
| chancalan | input-mattcl | 15.1 ± 0.6 | 13.8 | 18.1 | 18.01 ± 3.96 |
| chancalan | input-kcen | 15.1 ± 0.6 | 14.1 | 17.7 | 18.01 ± 3.94 |
| chancalan | input-aspidites | 15.2 ± 0.7 | 14.0 | 18.6 | 18.08 ± 4.00 |
| chancalan | input-lanjian | 15.2 ± 0.7 | 14.3 | 18.5 | 18.09 ± 3.99 |
| kcen | input-lanjian | 15.3 ± 0.7 | 14.5 | 18.5 | 18.23 ± 4.01 |
| kcen | input-mattcl | 15.3 ± 0.7 | 14.1 | 18.2 | 18.28 ± 4.03 |
| kcen | input-aspidites | 15.4 ± 0.6 | 14.5 | 18.0 | 18.31 ± 4.01 |
| kcen | input-chancalan | 15.4 ± 0.7 | 14.2 | 18.8 | 18.31 ± 4.04 |
| kcen | input-kcen | 15.5 ± 0.7 | 14.3 | 18.5 | 18.43 ± 4.07 |


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