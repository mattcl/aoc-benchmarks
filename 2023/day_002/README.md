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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.29 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.3 | 1.2 | 1.04 ± 0.27 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 1.05 ± 0.30 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.4 | 1.05 ± 0.29 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.3 | 1.2 | 1.05 ± 0.27 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.2 | 2.5 | 1.06 ± 0.32 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.2 | 1.07 ± 0.29 |
| lanjian | input-chancalan | 1.0 ± 0.1 | 0.2 | 1.5 | 1.07 ± 0.27 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.5 | 1.08 ± 0.30 |
| mattcl-ts | input-mattcl | 11.1 ± 0.4 | 9.9 | 11.9 | 12.11 ± 2.60 |
| mattcl-ts | input-aspidites | 11.1 ± 0.4 | 10.0 | 12.2 | 12.12 ± 2.60 |
| mattcl-ts | input-chancalan | 11.2 ± 0.4 | 10.2 | 11.9 | 12.15 ± 2.60 |
| mattcl-ts | input-lanjian | 11.2 ± 0.4 | 9.9 | 12.2 | 12.16 ± 2.61 |
| mattcl-ts | input-kcen | 11.2 ± 0.4 | 10.0 | 12.0 | 12.17 ± 2.61 |
| mikofo | input-aspidites | 11.3 ± 0.3 | 10.2 | 12.6 | 12.31 ± 2.63 |
| mikofo | input-kcen | 11.3 ± 0.3 | 10.1 | 12.3 | 12.34 ± 2.64 |
| mikofo | input-lanjian | 11.4 ± 0.3 | 10.6 | 12.0 | 12.38 ± 2.64 |
| mikofo | input-mattcl | 11.4 ± 0.3 | 10.3 | 12.5 | 12.41 ± 2.65 |
| mikofo | input-chancalan | 11.4 ± 0.3 | 10.4 | 12.7 | 12.42 ± 2.65 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.7 | 14.4 | 13.85 ± 2.98 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.3 | 14.2 | 13.89 ± 2.99 |
| aspidites | input-chancalan | 12.9 ± 0.5 | 11.9 | 15.3 | 13.98 ± 3.01 |
| aspidites | input-mattcl | 12.9 ± 0.5 | 11.7 | 14.2 | 13.99 ± 3.01 |
| aspidites | input-kcen | 13.0 ± 2.7 | 11.1 | 41.1 | 14.15 ± 4.23 |
| pting | input-lanjian | 14.6 ± 0.6 | 13.5 | 17.9 | 15.83 ± 3.41 |
| pting | input-chancalan | 14.6 ± 0.5 | 13.7 | 17.6 | 15.86 ± 3.40 |
| mattcl-py | input-kcen | 14.6 ± 0.7 | 13.6 | 18.4 | 15.91 ± 3.44 |
| pting | input-mattcl | 14.6 ± 0.6 | 13.6 | 17.7 | 15.91 ± 3.43 |
| mattcl-py | input-lanjian | 14.7 ± 0.5 | 13.6 | 17.4 | 15.95 ± 3.43 |
| pting | input-aspidites | 14.7 ± 0.7 | 13.4 | 18.3 | 15.96 ± 3.46 |
| mattcl-py | input-chancalan | 14.7 ± 0.7 | 13.6 | 18.3 | 15.96 ± 3.47 |
| mattcl-py | input-aspidites | 14.7 ± 0.6 | 13.6 | 17.6 | 15.97 ± 3.45 |
| mattcl-py | input-mattcl | 14.7 ± 0.7 | 13.7 | 18.5 | 16.02 ± 3.48 |
| pting | input-kcen | 14.7 ± 0.7 | 13.7 | 17.9 | 16.03 ± 3.48 |
| chancalan | input-chancalan | 15.2 ± 0.5 | 14.1 | 18.5 | 16.49 ± 3.54 |
| chancalan | input-lanjian | 15.2 ± 0.6 | 14.3 | 18.4 | 16.49 ± 3.55 |
| chancalan | input-mattcl | 15.2 ± 0.6 | 14.4 | 18.1 | 16.57 ± 3.57 |
| chancalan | input-aspidites | 15.3 ± 0.6 | 14.3 | 18.1 | 16.59 ± 3.58 |
| chancalan | input-kcen | 15.3 ± 2.1 | 14.1 | 43.0 | 16.65 ± 4.18 |
| kcen | input-chancalan | 15.5 ± 0.6 | 14.5 | 18.4 | 16.83 ± 3.63 |
| kcen | input-lanjian | 15.5 ± 0.7 | 14.4 | 18.8 | 16.86 ± 3.65 |
| kcen | input-aspidites | 15.5 ± 0.6 | 14.7 | 18.3 | 16.90 ± 3.64 |
| kcen | input-mattcl | 15.6 ± 0.7 | 14.6 | 19.1 | 16.93 ± 3.67 |
| kcen | input-kcen | 15.6 ± 0.9 | 14.2 | 19.2 | 16.96 ± 3.72 |


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