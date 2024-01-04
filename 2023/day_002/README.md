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
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 ± 0.31 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.29 |
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.2 | 1.03 ± 0.28 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.3 | 1.4 | 1.04 ± 0.29 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 2.4 | 1.07 ± 0.30 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.2 | 1.2 | 1.07 ± 0.28 |
| lanjian | input-chancalan | 1.0 ± 2.9 | 0.2 | 41.9 | 1.07 ± 3.26 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.6 | 1.08 ± 0.29 |
| mattcl-ts | input-lanjian | 10.9 ± 0.4 | 9.9 | 11.8 | 12.16 ± 2.61 |
| mattcl-ts | input-aspidites | 11.0 ± 0.4 | 9.5 | 12.0 | 12.17 ± 2.62 |
| mattcl-ts | input-chancalan | 11.0 ± 0.4 | 9.8 | 11.8 | 12.17 ± 2.61 |
| mattcl-ts | input-kcen | 11.0 ± 0.4 | 9.9 | 11.9 | 12.18 ± 2.62 |
| mattcl-ts | input-mattcl | 11.0 ± 0.4 | 9.9 | 11.8 | 12.22 ± 2.62 |
| mikofo | input-mattcl | 11.2 ± 0.4 | 10.3 | 12.2 | 12.47 ± 2.67 |
| mikofo | input-kcen | 11.3 ± 0.3 | 10.4 | 12.1 | 12.52 ± 2.68 |
| mikofo | input-lanjian | 11.3 ± 0.4 | 10.2 | 12.5 | 12.53 ± 2.69 |
| mikofo | input-chancalan | 11.3 ± 0.4 | 10.1 | 12.8 | 12.53 ± 2.69 |
| mikofo | input-aspidites | 11.3 ± 0.3 | 10.3 | 12.1 | 12.59 ± 2.69 |
| aspidites | input-aspidites | 12.7 ± 0.5 | 11.1 | 14.2 | 14.06 ± 3.03 |
| aspidites | input-mattcl | 12.7 ± 0.4 | 11.7 | 14.0 | 14.10 ± 3.03 |
| aspidites | input-kcen | 12.7 ± 0.5 | 11.8 | 14.2 | 14.13 ± 3.05 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.6 | 14.4 | 14.19 ± 3.05 |
| aspidites | input-chancalan | 12.8 ± 0.4 | 11.7 | 14.3 | 14.27 ± 3.06 |
| pting | input-chancalan | 14.2 ± 0.6 | 13.3 | 17.7 | 15.79 ± 3.41 |
| pting | input-lanjian | 14.2 ± 0.5 | 13.3 | 16.8 | 15.82 ± 3.40 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.4 | 17.8 | 15.83 ± 3.42 |
| mattcl-py | input-lanjian | 14.3 ± 0.6 | 13.5 | 17.4 | 15.89 ± 3.42 |
| pting | input-aspidites | 14.3 ± 0.6 | 13.4 | 18.2 | 15.89 ± 3.44 |
| pting | input-kcen | 14.3 ± 0.8 | 13.4 | 18.0 | 15.91 ± 3.48 |
| mattcl-py | input-mattcl | 14.4 ± 0.6 | 13.4 | 18.1 | 15.97 ± 3.44 |
| mattcl-py | input-aspidites | 14.4 ± 0.7 | 13.5 | 18.2 | 15.98 ± 3.47 |
| mattcl-py | input-chancalan | 14.4 ± 0.6 | 13.5 | 17.6 | 16.02 ± 3.46 |
| mattcl-py | input-kcen | 14.5 ± 0.7 | 13.7 | 18.2 | 16.06 ± 3.48 |
| chancalan | input-aspidites | 14.9 ± 0.4 | 14.0 | 17.7 | 16.52 ± 3.53 |
| chancalan | input-chancalan | 14.9 ± 0.6 | 13.8 | 18.2 | 16.57 ± 3.58 |
| chancalan | input-kcen | 14.9 ± 0.6 | 14.0 | 17.9 | 16.58 ± 3.58 |
| chancalan | input-lanjian | 14.9 ± 0.7 | 13.8 | 18.3 | 16.60 ± 3.59 |
| chancalan | input-mattcl | 15.0 ± 0.6 | 14.0 | 17.9 | 16.64 ± 3.60 |
| kcen | input-kcen | 15.2 ± 0.5 | 14.1 | 18.5 | 16.83 ± 3.62 |
| kcen | input-lanjian | 15.2 ± 0.6 | 14.2 | 17.7 | 16.88 ± 3.64 |
| kcen | input-aspidites | 15.2 ± 0.5 | 14.1 | 18.4 | 16.89 ± 3.63 |
| kcen | input-mattcl | 15.3 ± 0.7 | 14.2 | 18.4 | 16.94 ± 3.66 |
| kcen | input-chancalan | 15.7 ± 4.6 | 13.9 | 66.2 | 17.42 ± 6.31 |


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