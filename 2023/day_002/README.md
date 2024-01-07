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
| lanjian | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.5 | 1.01 ± 0.30 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.3 | 1.4 | 1.02 ± 0.29 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.4 | 1.03 ± 0.29 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.30 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.2 | 1.05 ± 0.29 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.4 | 1.2 | 1.06 ± 0.27 |
| lanjian | input-mattcl | 1.0 ± 0.1 | 0.5 | 1.3 | 1.07 ± 0.27 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.3 | 1.2 | 1.08 ± 0.27 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.4 | 1.2 | 1.09 ± 0.26 |
| mattcl-ts | input-mattcl | 10.8 ± 0.4 | 9.8 | 11.6 | 11.76 ± 2.58 |
| mattcl-ts | input-lanjian | 10.8 ± 0.4 | 9.7 | 11.7 | 11.79 ± 2.60 |
| mattcl-ts | input-kcen | 10.8 ± 0.4 | 9.9 | 11.6 | 11.83 ± 2.60 |
| mattcl-ts | input-chancalan | 10.8 ± 0.4 | 9.6 | 11.7 | 11.83 ± 2.60 |
| mattcl-ts | input-aspidites | 10.9 ± 0.4 | 9.7 | 11.8 | 11.85 ± 2.61 |
| mikofo | input-mattcl | 11.0 ± 0.4 | 10.1 | 11.9 | 11.99 ± 2.64 |
| mikofo | input-kcen | 11.1 ± 0.4 | 10.0 | 11.8 | 12.08 ± 2.65 |
| mikofo | input-chancalan | 11.1 ± 0.4 | 10.1 | 12.1 | 12.10 ± 2.66 |
| mikofo | input-aspidites | 11.7 ± 6.5 | 9.9 | 82.9 | 12.78 ± 7.66 |
| mikofo | input-lanjian | 12.4 ± 8.4 | 9.9 | 90.4 | 13.55 ± 9.58 |
| aspidites | input-chancalan | 12.7 ± 0.4 | 11.8 | 14.6 | 13.82 ± 3.04 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.8 | 14.1 | 13.88 ± 3.06 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.9 | 14.7 | 13.95 ± 3.07 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.7 | 14.3 | 13.96 ± 3.07 |
| aspidites | input-mattcl | 13.2 ± 6.0 | 11.0 | 79.8 | 14.46 ± 7.30 |
| pting | input-lanjian | 14.3 ± 0.5 | 13.3 | 17.4 | 15.65 ± 3.43 |
| mattcl-py | input-lanjian | 14.4 ± 0.5 | 13.5 | 17.5 | 15.70 ± 3.46 |
| pting | input-kcen | 14.4 ± 0.6 | 13.4 | 17.9 | 15.70 ± 3.47 |
| mattcl-py | input-kcen | 14.4 ± 0.5 | 13.5 | 17.6 | 15.72 ± 3.46 |
| mattcl-py | input-mattcl | 14.4 ± 0.5 | 13.5 | 17.1 | 15.73 ± 3.46 |
| pting | input-chancalan | 14.4 ± 0.6 | 13.7 | 17.4 | 15.74 ± 3.48 |
| pting | input-mattcl | 14.4 ± 0.7 | 13.4 | 17.5 | 15.76 ± 3.50 |
| pting | input-aspidites | 14.5 ± 0.7 | 13.8 | 17.8 | 15.80 ± 3.51 |
| mattcl-py | input-chancalan | 14.5 ± 0.8 | 13.5 | 18.2 | 15.84 ± 3.55 |
| chancalan | input-lanjian | 14.9 ± 0.5 | 14.1 | 18.6 | 16.30 ± 3.59 |
| chancalan | input-chancalan | 15.0 ± 0.6 | 14.0 | 18.0 | 16.35 ± 3.60 |
| chancalan | input-mattcl | 15.0 ± 0.6 | 14.2 | 18.4 | 16.40 ± 3.62 |
| chancalan | input-aspidites | 15.0 ± 0.5 | 14.1 | 18.0 | 16.41 ± 3.61 |
| chancalan | input-kcen | 15.1 ± 0.6 | 13.8 | 17.9 | 16.46 ± 3.64 |
| kcen | input-lanjian | 15.2 ± 0.5 | 14.2 | 18.1 | 16.58 ± 3.65 |
| mattcl-py | input-aspidites | 15.2 ± 6.0 | 13.1 | 67.1 | 16.64 ± 7.48 |
| kcen | input-mattcl | 15.3 ± 0.6 | 14.3 | 18.4 | 16.68 ± 3.68 |
| kcen | input-chancalan | 15.3 ± 0.7 | 14.1 | 18.2 | 16.69 ± 3.70 |
| kcen | input-kcen | 15.3 ± 0.7 | 14.7 | 18.6 | 16.73 ± 3.71 |
| kcen | input-aspidites | 16.0 ± 4.5 | 14.3 | 56.4 | 17.50 ± 6.19 |


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