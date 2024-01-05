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
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.29 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.28 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.28 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.28 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.4 | 1.04 ± 0.28 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.1 | 1.04 ± 0.28 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.2 | 1.05 ± 0.27 |
| lanjian | input-kcen | 1.0 ± 0.1 | 0.6 | 1.2 | 1.06 ± 0.26 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.4 | 1.06 ± 0.28 |
| mattcl-ts | input-mattcl | 11.0 ± 0.4 | 9.7 | 11.7 | 11.75 ± 2.46 |
| mattcl-ts | input-kcen | 11.0 ± 0.4 | 10.0 | 11.9 | 11.77 ± 2.47 |
| mattcl-ts | input-chancalan | 11.0 ± 0.4 | 9.7 | 12.8 | 11.81 ± 2.48 |
| mattcl-ts | input-lanjian | 11.1 ± 0.4 | 9.9 | 11.8 | 11.86 ± 2.49 |
| mattcl-ts | input-aspidites | 11.1 ± 0.4 | 9.9 | 11.9 | 11.87 ± 2.48 |
| mikofo | input-chancalan | 11.3 ± 0.4 | 10.3 | 12.3 | 12.11 ± 2.53 |
| mikofo | input-aspidites | 11.3 ± 0.3 | 10.2 | 12.1 | 12.12 ± 2.53 |
| mikofo | input-kcen | 11.3 ± 0.4 | 10.2 | 12.7 | 12.13 ± 2.53 |
| mikofo | input-lanjian | 11.3 ± 0.4 | 10.3 | 12.5 | 12.13 ± 2.54 |
| mikofo | input-mattcl | 11.3 ± 0.4 | 10.4 | 12.4 | 12.15 ± 2.54 |
| aspidites | input-lanjian | 12.6 ± 2.4 | 11.0 | 44.5 | 13.53 ± 3.77 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.8 | 14.5 | 13.66 ± 2.86 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.7 | 14.6 | 13.72 ± 2.89 |
| aspidites | input-aspidites | 13.0 ± 3.9 | 11.0 | 49.3 | 13.93 ± 5.11 |
| aspidites | input-mattcl | 13.0 ± 3.2 | 11.2 | 46.3 | 13.95 ± 4.51 |
| mattcl-py | input-aspidites | 14.3 ± 0.5 | 13.5 | 18.5 | 15.31 ± 3.21 |
| pting | input-chancalan | 14.3 ± 0.5 | 13.6 | 17.4 | 15.32 ± 3.22 |
| pting | input-kcen | 14.4 ± 0.7 | 13.3 | 17.4 | 15.37 ± 3.27 |
| pting | input-aspidites | 14.4 ± 0.7 | 13.3 | 18.4 | 15.37 ± 3.27 |
| pting | input-mattcl | 14.4 ± 0.6 | 13.3 | 17.8 | 15.40 ± 3.25 |
| mattcl-py | input-mattcl | 14.4 ± 0.5 | 13.5 | 17.5 | 15.41 ± 3.23 |
| mattcl-py | input-lanjian | 14.4 ± 0.6 | 13.5 | 17.3 | 15.46 ± 3.26 |
| mattcl-py | input-kcen | 14.4 ± 0.6 | 13.3 | 17.5 | 15.47 ± 3.27 |
| mattcl-py | input-chancalan | 14.4 ± 0.6 | 13.4 | 17.8 | 15.47 ± 3.26 |
| pting | input-lanjian | 14.5 ± 2.1 | 13.5 | 42.8 | 15.54 ± 3.92 |
| chancalan | input-lanjian | 15.0 ± 0.7 | 13.8 | 18.0 | 16.08 ± 3.40 |
| chancalan | input-mattcl | 15.0 ± 0.6 | 13.9 | 18.0 | 16.09 ± 3.39 |
| chancalan | input-chancalan | 15.0 ± 0.7 | 14.0 | 18.4 | 16.09 ± 3.40 |
| chancalan | input-kcen | 15.0 ± 0.6 | 14.2 | 18.1 | 16.10 ± 3.39 |
| chancalan | input-aspidites | 15.0 ± 0.7 | 14.0 | 17.9 | 16.10 ± 3.40 |
| kcen | input-chancalan | 15.2 ± 0.5 | 14.2 | 18.3 | 16.25 ± 3.39 |
| kcen | input-mattcl | 15.2 ± 0.6 | 14.1 | 18.6 | 16.32 ± 3.43 |
| kcen | input-aspidites | 15.3 ± 0.6 | 14.3 | 18.0 | 16.33 ± 3.43 |
| kcen | input-kcen | 15.3 ± 0.6 | 14.4 | 18.0 | 16.34 ± 3.44 |
| kcen | input-lanjian | 15.3 ± 0.7 | 14.3 | 19.5 | 16.41 ± 3.48 |


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